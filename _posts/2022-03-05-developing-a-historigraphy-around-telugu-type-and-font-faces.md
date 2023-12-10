---
layout: post
title: "Developing a historiography around telugu type"
date: 2022-03-05 15:37:37 +0530
tags: type experiments
---
There were many times when I wanted to know more about the typefaces and anatomy script of my native language. I feel a little handicaped when typesetting telugu text or trying to manipulate the letterforms for certain visual excersises. Although elements such as stems, counters and spacing remain same as roman script, the extra glyphs sitting around the letterform make me feel anxious. It's as if I am about to commit something horrible. So I just stop thinking about manual kerning and leading resorting to the default parameters. Many such problems about typefaces of regional languages emerge due to dearth in necessary literature surrounding a script and font.

I don't knwo much about people who designed the first movable type for Telugu. What were they thinking when making? How did they transfer the knowledge? What were their limitations? and how did these letter forms found themselves onto screens? Questions worthy of answers and answers to raise more questions.

Although the idea needs strong foundations of the regional script, with a fair knowledge of typography and the technology surrounding it can give a kickstart into data visualisation project.

To make 
* Download all the free fonts availbale on the internet
* Clear Duplicates
* extract metadata into .csv (the hard part for me!)
    * Extracting ```lang``` tags and ```script``` tags from GSUB and GPOS
* Look for proprietory Telugu fonts available online(Data collection by contacting source)
* Interviewing designers and writers, newspapers and archival material can shed some light

Still trying to find a method to extract script and language fields.
[Fonttools](https://pypi.org/project/fonttools/) is library to manipulate font files is a handy tool to extract metadata.

## Onamaalu ఓనమాలు
telugu alphabet. 

|telugu vowels|
|---|
|-|అ|ఆ|ఇ|ఈ|ఉ|ఊ|ఋ|ౠ|ఌ|ౡ|ఎ|ఏ|ఐ|ఒ|ఓ|ఔ|  

consonant + vowel → syllable
ex:
1. ఖ + ఈ (ీ) → ఖీ
2. జ + ఉ (ు) → జు



## References and reading list
1. http://anufonts.com/
2. https://en.wikipedia.org/wiki/Telugu_script
3. https://keyaar.in/exif/waterfountain-pdf-drift
4. https://keyaar.in/exif/fonts-typefaces-etcetera
5. https://www.unicode.org/charts/PDF/U0C00.pdf
6. https://docs.microsoft.com/en-gb/typography/script-development/telugu
7. https://scriptsource.org/cms/scripts/page.php?item_id=script_detail&key=Telu
8. https://www.typoday.in/2011/papers/Shashi_On-Screen-Font-In-Telugu.pdf
9. https://www.unicode.org/charts/PDF/U0C00.pdf
10. https://omniglot.com/writing/telugu.htm
11. https://pypi.org/project/fontmeta/