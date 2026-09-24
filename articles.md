---
title: "Articles"
order: 4
in_menu: true
blog_index: true
---
<aside>
  S'abonner via le <a href="{{ '/feed.xml' | relative_url }}">flux RSS</a>
  (<a href="https://flus.fr/carnet/a-quoi-servent-les-flux.html">c'est quoi ?</a>)
</aside>

{% for post in site.posts %}
<article class="blog-item">
  <h2>
    {{ post.title }}
  </h2>

  <a href="{{post.url | relative_url}}"> Lire l'article <span aria-hidden="true">➞</span></a>
</article>
<hr />
{% endfor %}


### Site amies
____
Voir aussi 
 [En savoir plus avec Hélène Jeanne Lévy Benseft]https://youtu.be/Vw9WXSrLCQA?si=SVhEebceRoTPpYWb.


Apprenez Markdown avec [le Guide Markdown](https://flus.fr/markdown). 