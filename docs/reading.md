---
title: Četba na jednotlivé semináře
layout: page
menuItem: Termíny a&nbsp;četba
menuPosition: 2
---
<img src="{{ site.baseurl }}/style/klee.jpg" width="100%">

Veškerá povinná literatura je dostupná ve složce [Učební materiály v ISu](https://is.muni.cz/el/1421/podzim2016/VIKBB55/um/) (včetně materiálů publikovaných online). Níže najdete přesné specifikace rozsahů stránek, které jsou určeny k přípravě na semináře.

Pokud neznáte nějaké pojmy, události či osoby, které jsou v textech zmíněny, doporučuji dohledávat vše na Wikipedii (nejlépe na její anglickojazyčné verzi).

<ol>
{% assign syllabus = site.syllabus | sort: "week" %}
{% for week in syllabus %}
  <li>
  	<a href="{{ site.baseurl }}{{ week.url }}">{{ week.title }}</a> 
  	{% for tag in week.tags %}
  		<b>#{{ tag }}</b>
  	{% endfor %}
  	({{ week.day }})</li>
{% endfor %}
</ol>

## Základní literatura

Adorno, T. W., Horkheimer M. (2009). _Dialektika osvícenství._ Oikoymenh.

Adorno, T. W. (1992). _The Schema of Mass Culture._ In: Adorno, T. W. (1992). _Culture Industry._ Sage, pp. 53- 84.

Benjamin, W. (2009). _Umělecké dílo ve věku své technické reprodukovatelnosti._ In: _Literárněvědné studie._ Oikoymenh.

Foucault, M. (2010). _Zrození kliniky._ Pavel Mervart.

Godin, B. (2008). _Innovation: The History of a Category._ Working Paper no. 1\. In: _Project on the Intellectual History of Innovation. INRS._

Godin, B. (2009). _The making of science, technology and innovation policy: conceptual frameworks as narratives, 1945–2005._ Centre Urbanisation Culture Société.

Godin, B. (2010). _“Meddle Not With Them That Are Given to Change”: Innovation as Evil_, Working Paper no. 6\. In: Project on the Intellectual History of Innovation. INRS.

Honneth, A. (2011). _Patologie rozumu._ Filosofia.

Horkheimer, M. (2001). _Tradiční a kritická teorie._ In: _Aluze_, 4/2001, s. 74–106.

Košturiak, J., Chaľ, J. (2008). _Inovace – Vaše konkurenční výhoda!_ CPress.

Merton, R. K. (1936). _The Unanticipated Consequences of Purposive Social Action._ In: _American Sociological Review_, Vol 1 Issue 6, Dec 1936, pp. 894–904

McLuhan, M. (2000). _Člověk, média a elektronická kultura._ Jota.

Mills, Ch. W. (2008). _Sociologická imaginace._ Sociologické nakladatelství.

Morozov, Evgeny. _The Net Delusion: The Dark Side of Internet Freedom._ New York, NY: PublicAffairs, 2011.

Nietzsche, F. (1992). _Radostná věda „la gaya scienza”._ Československý spisovatel.

Stöckelová, T., Ghosh Y. A., eds. (2013). _Etnografie. Improvizace v teorii a terénní praxi._ SLON.
