---
layout: default-de
---
[Startseite]({{ site.url }}/de/) - [So funktioniert's]({{ site.url }}/de/about.html) - [Warum Wegwerf-eMails?]({{ site.url }}/de/why.html) - [FAQ]({{ site.url }}/de/FAQ.html) - [News]({{ site.url }}/de/news.html) 

---

# Newsfeed 

<h1>{{ page.title }}</h1> <ul class="posts"> {% for post in site.categories.de %} <li><span>{{ post.date | date_to_string }}</span> » <a href="{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a></li> {% endfor %} </ul>
