---
layout: page
title: "WebDev & Research for Doomscroll"
image: "/img/Newsmap-2.gif"
year: 2022
---
<p></p>
Link to the web app developed: [doomscroll.news](http://doomscroll.news/)  

Creator [Andre Otis](https://andrewotis.com/)  
Developed by [Navanudi](https://navanudi.in)  
I was part of the Digital Design and leading the team at Navanudi.

The proposed project aims to create a web-based platform that displays news stories from around the world on an interactive map. The platform uses various open-source tools and algorithms to extract geolocation data from news stories, plot them on a map, and provide users with a way to preview related stories.

The first step in building the platform is obtaining a base map. Mapbox is used to build the because it is free for development. Once a base map is obtained, the next step is to retrieve news stories using an API.  NewsAPI, but an alternate open-source news API could be used as well.

 A natural language processing (NLP) algorithm is used. Since geolocation data is usually found in the first sentence or headline of a news story, the algorithm only processes the first sentence. If a story is reported from multiple locations, the algorithm selects one location to geolocate it to. If a story cannot be geolocated, it is ignored.

Once the geolocation data is extracted, the platform places a visual representation of each news story on the map. These visual representations are in the form of story cards containing a representative image (if available), headline, source, and timestamp. To reduce visual clutter on the screen, an algorithm is used to determine which stories to display on the map.

When a user clicks on a story card, the platform shows a preview of the article along with a feed of previews of similar stories. An algorithm is used to select these similar stories, similar to how social media feeds work. The platform also features advertisements to cover costs and generate revenue. The creator suggests using Google Adsense and placing the ads on the feed.

In conclusion, the platform has the potential to be a valuable tool for anyone interested in keeping up with news stories from around the world. The creator suggests using a combination of open-source tools and algorithms to extract geolocation data from news stories, plot them on a map, and provide users with a way to preview related stories. Other options may be available for each step of the process. Overall, the project aims to create a useful and informative platform for those interested in global news.