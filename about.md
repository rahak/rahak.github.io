---
layout: main
title: about
---
****
<h1 class="name" style="margin-top:0px;"></h1>

<div class="col-12 col-md-3 col-lg-6 intro">
<span class="penname">Hi, I'm Rahak.</span><span class="name"></span> A designer and a creative generalist. My current interests are narratives, digital publising and systems. I am currently based in Tallinn, Estonia.
<span class="penname">This is my blog/portfolio/digitalspace. I wish to share my thoughts and articulate them here. ⌘(ctrl) + P to download my CV!</span>
<p></p>
</div>

→ {{ site.email }}  
→ {{ site.phone }}  
→ https://rahak.net 

![self](img/Cross-Ventilation.png)
## Work
 {% for item in site.data.cv.work %}
 <div class="row">
    <div class="col-3 col-lg-3 col-md-3 col-sm-3" style="border-top:4px solid black;">
         <p style="padding:10px 0px 0px 0px;">{{ item.year }}</p>
    </div>
    <div class="col-9 col-lg-9 col-md-9 col-sm-9">
        <p><b>{{ item.title }}</b><br>
        {{ item.firm }} <a href="{{ item.url }}">{{ item.url }}</a></p>
        <p>{{ item.description }}</p>
     </div>
</div>
{% endfor %}

## Education
{% for item in site.data.cv.Education %}
 <div class="row">
    <div class="col-3 col-lg-3 col-md-3 col-sm-3" style="border-top:4px solid black;">
         <p style="padding:10px 0px 0px 0px;">{{ item.year }}</p>
    </div>
    <div class="col-9 col-lg-9 col-md-9 col-sm-9">
        <p><b>{{ item.title }}</b><br>{% if item.url %}<a href="{{ item.url }}">Link</a>{% endif %}</p>
        <p>{{ item.firm }}</p>
        <p>{{ item.description }}</p>
    </div>
</div>
{% endfor %}

## Film Festivals and Collaborations
{% for item in site.data.cv.Film-Festivals %}
 <div class="row">
    <div class="col-3 col-lg-3 col-md-3 col-sm-3" style="border-top:4px solid black;">
         <p style="padding:10px 0px 0px 0px;">{{ item.year }}</p>
    </div>
    <div class="col-9 col-lg-9 col-ms-9 col-sm-9">
        <p><b>{{ item.title }}</b><br><a href="{{ item.url }}">Link</a></p>
    <p>{{ item.firm }}</p>
        <p>{{ item.description }}</p>
    </div>
</div>
{% endfor %}

## Skills
{% for item in site.data.cv.Skills %}
 <div class="row">
    <div class="col-9 col-lg-3 col-md-3 col-sm-3" style="border-top:4px solid black;">
    </div>
    <div class="col-9 col-lg-9 col-md-9 col-sm-9">
        <p style="padding:10px 0px 0px 0px;"><b>{{ item.title }}</b><br>
        {{ item.firm }}
        {{ item.description }}</p>
    </div>
</div>
{% endfor %}

## Extra Curriculars and Hobbies
{% for item in site.data.cv.extra %}
 <div class="row">
    <div class="col-9 col-lg-3 col-md-3 col-sm-3" style="border-top:4px solid black;">
         <p style="padding:10px 0px 0px 0px;">{{ item.year }}</p>
    </div>
    <div class="col-9 col-lg-9 col-md-9 col-sm-9 d-flex">
        <p>{{ item.title }}<br>
        {{ item.firm }}
        {{ item.description }}</p>
    </div>
</div>
{% endfor %}

## Languages
{% for item in site.data.cv.Languages %}
 <div class="row">
    <div class="col-9 col-lg-3 col-md-3 col-sm-3" style="border-top:4px solid black;">
         <p style="padding:10px 0px 0px 0px;">{{ item.year }}</p>
    </div>
    <div class="col-9 col-lg-9 col-md-9 col-sm-9 d-flex">
        <p><b>{{ item.title }}</b><br>
        {{ item.firm }}
        {{ item.description }}</p>
    </div>
</div>
{% endfor %}




