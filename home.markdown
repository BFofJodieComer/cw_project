---
title: Home | Understanding Transgender Identity
layout: index
---

<div class="heading">
    <h1> Understanding Transgender Identity </h1>
</div>

<hr>

<div class="container">
    <div class="subheading">
        <h2> What is Transgender?</h2>
        <p>"Transgender is an umbrella term for people whose gender identity and/or gender expression differs from the sex they were assigned at birth" (Gay and Lesbian Alliance Against Defamation [GLAAD], 2007)." https://www.glaad.org/reference/transgender "Transgender individuals should be identified with the pronoun that correspond with the gender with which they identify. It is appropriate to respectfully ask their name and what pronoun they prefer that you use."</p>
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
<div class="news_container">
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
        <p>The Wachowski Sisters:  transgender directors of Matrix series</p>
    </div>
</div>

<div class="films">
    {% for name in collections.exhibits.name %}
     <p>{{ name.name }}</p>
    {% endfor %} 
</div>
