---
layout: page
title: Startside
---

- [Ada](/ada/)

### Søg

- [WebCrawler](https://www.webcrawler.com)
- [Google](https://www.google.com/)

### Blog posts

#### By URL
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

#### By tag

{% for tag in site.tags %}
##### {{ tag[0] }}
  <ul>
    {% for post in tag[1] %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% endfor %}

### Kirke

- [CityKirken](https://www.ckirken.dk/da/)
- [Effatha](http://effatha.dk)
- [BibelZoom](https://www.bibelzoom.dk)
- [Frikirken Randers](https://frikirkenranders.dk)
- [Ancent Hebrew](https://www.ancient-hebrew.org/)
- [Tagryggen](https://tagryggen.dk)


### Ada

- [Ada Planet](https://www.laeran.pl/adaplanet/i/)
- [comp.lang.ada](https://groups.google.com/g/comp.lang.ada)
- [Gitter](https://gitter.im/ada-lang/)
- [Ada Resources](https://jquorning.github.io/ada/)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/ada)
- [Rosetta Code](http://www.rosettacode.org/wiki/Category:Ada)
- [Reddit](https://www.reddit.com/r/ada/)
