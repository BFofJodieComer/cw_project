---
title: Home | Understanding Transgender Identity
layout: index
---
<!-- page heading -->
<div class="heading">
    <h1><span style='font-size: 80px ;'>&#127752;</span>Understanding Transgender Identity<span class="mirror" style='font-size: 80px;'>&#127752;</span></h1>
    <h2> <i>Proud To Be Me</i> </h2>
</div>

<hr>

<!-- definition and aim -->
<div class="paracontainer">
    <div class="subheading">
        {% for line in site.data.home-definition %}
        <h2> {{ line.definition}} </h2>
        <p>{{ line.definition-content }}</p>
        {% endfor %}
    </div>
     <div class="subheading">
        {% for line in site.data.home-definition %}    
        <h2> {{ line.aim }} </h2>
        <p>{{ line.aim-content }}</p>
        {% endfor %}
     </div>
</div>
<br>
<hr>

<!-- latest news -->
<div class="subheading2">
    <h2><span class="mirror" style='font-size:30px;'>&#128226;</span> Latest News <span style='font-size:30px;'>&#128226;</span> </h2>
</div>
<div id = "news-container">
  {% assign sorted_news = site.exhibits %}
  {% for news in sorted_news %}
    <div class = "news-cell">
      <p><a class="citation" href = "{{ news.news-url }}"><b>{{ news.title }}</b></a></p>
    </div>
  {% endfor %}
</div>
<br>
<hr>

<!-- quotation catch phrase -->
<div class="subheading2">
    <h3> <i>"I am transgender and this doesn't mean that I am unlovable." — Lana Wachowski, HRC Visibility Award Acceptance Speech</i> </h3>
</div>
<hr>

<!-- recommended films -->
<div class="subheading2">
    <h2> <span class="mirror" style='font-size:30px;'>&#127916;</span> Recommended Films <span style='font-size:30px;'>&#127916;</span> </h2>
</div>

<div class="defaultcontainer">
    {% for film in site.data.films %}
    <p><a href="{{ film.homepage }}">{{ film.name }}, {{ film.year }}</a></p>
    {% endfor %}
</div>

