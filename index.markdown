---
title: Home | Understanding Transgender Identity
layout: index
---

<div class="heading">
    <h1> Understanding Transgender Identity</h1>
</div>

<hr>

<div class="paracontainer">
    <div class="subheading">
        <h2> What is Transgender? </h2>
        <p>"Transgender is an umbrella term for people whose gender identity and/or gender expression differs from the sex they were assigned at birth <a class="citation" href="https://www.glaad.org/reference/transgender"><u>(Gay and Lesbian Alliance Against Defamation [GLAAD], 2007)</u></a>.”  “Transgender individuals should be identified with the pronoun that correspond with the gender with which they identify. It is appropriate to respectfully ask their name and what pronoun they prefer that you use <a class="citation" href="https://books.google.com/books?hl=en&lr=&id=XS3XJL_RGIgC&oi=fnd&pg=PP1&dq=Altilio,+Terry%3B+Otis-Green,+Shirley+(2011).+Oxford+Textbook+of+Palliative+Social+Work.+Oxford+University+Press.+p.+380.&ots=ak946C8Tcx&sig=ZK8zOWrvE99ZOQB2ZUVTUdUf1MM"><u>(Altilio and Otis-Green, 2011, p. 380)</u></a>."</p>
    </div>
     <div class="subheading">
        <h2> Our Aim </h2>
        <p>This is a Transgender website covering the most emergent issues around transgender group. It aims at establishing a fundamental understanding to the public about this minority group, creating a sense of inclusion for transgender group, and providing researchers with controversial dilemmas and debates for research purposes.</p>
     </div>
</div>
<br>
<hr>

<div class="subheading1">
    <h2> Latest News </h2>
</div>

<div id = "news-container">
  {% assign sorted_news = site.exhibits %}
  {% for news in sorted_news %}
    <div class = "news-cell">
      <a class="news-image" href = "{{ news.news-url }}"><img src="{{ news.image-url }}" class="news-picture"></a>
      <br>
      <p><a class="citation" href = "{{ news.news-url }}">{{ news.title }}</a></p>
      <p><a href="{{ news.licence-url }}">{{ news.licence }}</a></p>
    </div>
  {% endfor %}
</div>
<br>
<hr>

<div class="subheading1">
    <h3> <i>"I am transgender and this doesn't mean that I am unlovable."</i> </h3>
    <p> — Lana Wachowski, HRC Visibility Award Acceptance Speech </p>
</div>
<hr>


<div class="subheading1">
    <h2> Recommended Films </h2>
</div>

<div class="defaultcontainer">
    {% for film in site.data.films %}
    <p><a href="{{ film.homepage }}">{{ film.name }}, {{ film.year }}</a></p>
    {% endfor %}
</div>

