---
layout: post
title: On hybrid publishing craft
tags: publishing
date: 2022-09-30 21:49:00 +530
image: /img/banner-publishing.png
---
<p></p>
After a long journey into the world of static-site generators and spending relentless nights to achieve what I had in mind, I feel helpless and handicapped for unable to achieve what I have in mind. Time just flies and all I achieve is tufte style side notes, taking up 24 hours to find the right plugin and technique. 

Surprisingly going back into my bookmarks folders I came accross some secrets I wish I knew long back. I found out Hybrid Publishing Toolkit{% sidenote %}By https://networkcultures.org/ and this note is for showing off tufte notes ;).{% endsidenote %}This is a nice kickstart into modern publishing methods that come handy and you miss out in college. It talks about formal elements and building blocks of a epub and the tools availabe to produce them. But which is ready for print too! It mentions certain cli tools which I am still figuring out but it also talks about e-publishing on Indesign extensively. It was instructional and informative both for programmers and me.

This book took me into what I call the alchemists of the web who made opensource frameworks and repositories such as [Paged.js](https://pagedjs.org/), [HTML2Print](http://osp.kitchen/tools/html2print/) and [Bindery.js](https://bindery.info/). All of them have one thing in common, to extend publishing into both digital and analog worlds in a single workflow{% margin %}Still.. Indesign-Incopy duo win in many respects, but my infatuation with these experiments just grows. Couldn't stop finding an alternative to Adobe. Being at SFLC.in gave me enough space and time to venture into libre graphics{% endmargin %}. I have gone through documentations of all the three and more too. But I favoured paged.js for it's straight forward instructions and their predecessor project, Paged media(depricated now).

I started working with a telugu document for elami and found publication of paged media on browsers to be fun and found myself much closer to the content and design elements in terms of markup than a Complete GUI solution. But I am still stuck at figuring out a proper workflow. 

Write now my observations are as follows for Telugu text:  
1. If the text is in google doc, download docx file
2. Convert it to html using pandoc. There is significant bloat present. Need to figure out a way to filter using Pandoc.
3. Clean up the html and insert the classes for chapter breaks
4. Styling advanced styling of tables is a little tough, I found a small script which you can find in this repo, [github.com/rahak/internet-shutdowns-report](https://github.com/rahak/internet-shutdowns-report)
5. Justification! achieving it is nearly impossible. Browsers can not understand word break for other languages (at least telugu)
6. With some neat markup and custom scripts things are achievable.
7. With unicode and web as publishing methods, book is free from regional texta are freeof orthodoxy.

Too many things are possible! Decentalised printing and distribution on mini printing presses and print on demand by authors themselves.{%margin%}Need work on small system on this zine utopia.{%endmargin%}

A sample produced from Paged.js for a telugu document on technology.
<p></p>
{% pdf "/files/everyday-tech-sample.pdf" %}
<p></p>
The sample illustrations made for the book using balsamiq
<p></p>
![illustration-everyday-tech](/img/everyday-tech-illustration.png)
<p></p>

and a cover art(illustrator)..
<p></p>
![sketches-cover](/img/sketches-everyday-tech.png)  

<p></p>
![texture](/img/cover-art-everyday-tech.png)
<p></p>
I have also made a report by sflc.in using paged.js for the first time. Checkout the working directory of the book at [github.com/rahak/internet-shutdowns-report](https://github.com/rahak/internet-shutdowns-report) and the completed report here [https://sflc.in/internet-shutdowns-india-2022](https://sflc.in/internet-shutdowns-india-2022).

Here is my first succesfull hybrid publication, it's my [CV](/about). Press ⌘(ctrl) + P to have a look at it or print it. Made it using ```@media``` query for paged media in CSS.

I wish to comment more on this process. Will update.

P.S: Thanks Deep for being a partner in crime and listening to all my blabber and pulling all nighter.