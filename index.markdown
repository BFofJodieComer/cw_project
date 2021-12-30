---
title: Home | Understanding Transgender Identity
layout: index
---

<div class="heading">
    <h1> Understanding Transgender Identity</h1>
    {% assign description = 'How to display the "desciption" content here in markdown using liquid?' %}
</div>

<hr>

<div class="paracontainer">
    <div class="subheading">
        {% assign exhibits = site.exhibits %}
        {% for information in exhibits %}
        <h2> {{ information.definition-title }}</h2>
        {% endfor %}
        <p>"Transgender is an umbrella term for people whose gender identity and/or gender expression differs from the sex they were assigned at birth <a class="citation" href="https://www.glaad.org/reference/transgender">(Gay and Lesbian Alliance Against Defamation [GLAAD], 2007)</a>.”  “Transgender individuals should be identified with the pronoun that correspond with the gender with which they identify. It is appropriate to respectfully ask their name and what pronoun they prefer that you use <a class="citation" href="https://books.google.com/books?hl=en&lr=&id=XS3XJL_RGIgC&oi=fnd&pg=PP1&dq=Altilio,+Terry%3B+Otis-Green,+Shirley+(2011).+Oxford+Textbook+of+Palliative+Social+Work.+Oxford+University+Press.+p.+380.&ots=ak946C8Tcx&sig=ZK8zOWrvE99ZOQB2ZUVTUdUf1MM">(Altilio and Otis-Green, 2011, p. 380)</a>."</p>
    </div>
     <div class="subheading">
        <h2> Our Aim </h2>
        <p>This is a Transgender website covering the most emergent issues around transgender group. It aims at establishing a fundamental understanding to the public about this minority group, creating a sense of inclusion for transgender group, and providing researchers with controversial dilemmas and debates for research purposes. </p>
     </div>
</div>
<br>
<hr>

<div class="subheading1">
    <h2> Latest News </h2>
</div>
<div class="gridcontainer">
    <div class="news">
        <a class="ex1" href="https://www.bbc.co.uk/news/uk-59667786?utm_campaign=later-linkinbio-bbcnews&utm_content=later-23140797&utm_medium=social&utm_source=linkin.bio">
        <img src="https://ichef.bbci.co.uk/news/976/cpsprodpb/ED0A/production/_122228606_gettyimages-860167584.jpg" width="300"> 
        </a>
    </div>
    <div class="news">
        <a class="ex1" href="https://www.bbc.co.uk/news/world-us-canada-58974627">
        <img src="https://ichef.bbci.co.uk/news/976/cpsprodpb/5CC0/production/_121144732_levine.jpg" width="300">
        </a >
    </div>
    <div class="news"> 
        <a class="ex1" href= "https://www.bbc.co.uk/news/newsbeat-53692435">
        <img src= "https://images.immediate.co.uk/production/volatile/sites/3/2021/09/Screenshot-2021-11-22-at-12.36.45-090106e.png?webp=true&quality=45&resize=1240%2C826" width="300">
        </a>
    </div>
    <div class="news">
        <p>Gender-neutral passports: Campaigner Christie Elan-Cane loses Supreme Court case</p>
    </div>
    <div class="news">
        <p>Rachel Levine: Transgender official sworn in as four-star admiral</p>
    </div>
    <div class="news">
        <p>The Wachowski Sisters: Transgender directors of Matrix series</p>
    </div>
</div>
<br>
<hr>

<div class="subheading1">
    <h3> <i>"I am transgender and this doesn't mean that I am unlovable."</i> </h3>
    <p> — Lana Wachowski, HRC Visibility Award Acceptance Speech </p>
</div>
<hr>


<div class="subheading1">
    <h2> Recomended Films </h2>
</div>

<div class="defaultcontainer">
    {% for film in site.data.films %}
    <p><a href="{{ film.homepage }}">{{ film.name }}, {{ film.year }}</a></p>
    {% endfor %}
    {{ test.description }}
</div>

