{{ website.cell('6','') }}
#About
**develost.com** is one-man band. 

Open Space Technology is the approach I use to design and build better useful software. 

Php / python developer.
<br><br>

Purposes of my software:

- **dlMetro**: dress a website with liquid layout.
- **websu**: forget ftp updates and welcome dropbox/github/web publishing.
- **surfway**: generate A CRUD web application starting from an XML.
- **tython**: CMS capable to run python code.
- **dlCarousel**: the n-th dynamic carousel for posts, but this is mine.
- **KeyframesAnimationStudio**: creation of custom CSS3 Keyframes animation via web.
<br><br>

What is Open Space Technology?

- is the approach I use to design and build better useful software
- is an approach to purpose-driven leadership [more](http://en.wikipedia.org/wiki/Open_Space_Technology)
- is a simple way to run productive meetings  [more](http://openspaceworld.org/)



{{ website.endCell() }}


{{ website.link('keyframesanimationstudio','') }}
{{ website.cell('222662','') }}
#KeyframesAnimationStudio

Forget manually writing complex CSS3 codes for your custom keyframes animation. Focus on final result and use our web application. For free. 1 click to export/import to file (in development)

{{ website.endCell() }}
{{ website.endLink() }}





{{ website.link('dlMetro','') }}
{{ website.cell('222662','') }}
#dlMetro
The goal of dlMetro is to dress a site with an interface like Windows 8 Metro UI.
Two files make the solution:

- **dlMetro.css:** which contains all the stylesheets needed
- **dlMetro.js:** which eliminates scrollbar and makes blocks same size

No external dependency is required.
{{ website.endCell() }}
{{ website.endLink() }}

{{ website.link('tython','') }}
{{ website.cell('222662','') }}
#tython

### A Template engine written in python.

- Makes you capable to use vanilla **python code in page** genaration and markdown formatting for the content.
- Usage is free but registration is needed. Yust put your (vaild) email into the registration form.

Now on git hub, download the zip and follow the readme to start.
                
{{ website.endCell() }}
{{ website.endLink() }}

{{ website.link('websu','') }}
{{ website.cell('222662','') }}
#websu
Manage easily the process of updating of your website.

- user password protection
- works under apache httpd through http/https
- capable to encode sensible files using blowfish cipher
- keeps historical versions
- minimize offline time by switching rewrite rules only at the end of an update
- support both static and dynamic web sites

{{ website.endCell() }}
{{ website.endLink() }}


{{ website.link('surfway','') }}
{{ website.cell('222662','') }}
#surfway

From a db to a complete web application passig from an XML.
Now on github


{{ website.endCell() }}
{{ website.endLink() }}

{{ website.cell('222662','') }}
#dlCarousel
dynamic + infinite loop post carousel for facebook and twitter (in development)

{{ website.endCell() }}





{{ website.cell('6','last') }}
<div id="mainCarousel"></div>
<script src="./js/http.js"></script>
<script src="./js/dlCarousel.js"></script>
<script>
    dlCarousel.setCarouselNumItems(3);
    dlCarousel.build("mainCarousel");
    dlCarousel.setCarouselUrl("twitterPosts.php?s=at&v=develost_com");
    dlCarousel.setCssAnimation("magictime slideRightRetourn","fg");
    dlCarousel.setCssAnimation("magictime slideLeft","bg");
    dlCarousel.setCarouselTimeout(10000);
    dlCarousel.start();
    // slider left
</script>
Test dlCarousel by yourself mentioning @develost_com in a tweet with image. 
Your tweet will appear here after a while, without refreshing the page.
(tweet without images will not be shown)
{{ website.endCell() }}





