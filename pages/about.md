
title: About
layout: about
permalink: /about.html
# include CollectionBuilder info at bottom
credits: true
# Edit the markdown on in this file to describe your collection
# Look in _includes/feature for options to easily add features to the page
---

{% include feature/jumbotron.html objectid="https://cdil.lib.uidaho.edu/images/palouse_sm.jpg" %}

{% include feature/nav-menu.html sections="About the Collection;About the About Page" %}

{% assign imagesample = site.data[site.metadata] | where_exp: 'item','item.format contains "image"' | first %}
{% capture imagesampleid %}{{imagesample.objectid | default: "https://www.lib.uidaho.edu/collectionbuilder/demo-objects/mg101_b6_photographs_01.jpg"}}{% endcapture %}
{% assign pdfsample = site.data[site.metadata] | where_exp: 'item','item.format contains "pdf"' | first %}
{% capture pdfsampleid %}{{pdfsample.objectid | default: "https://www.lib.uidaho.edu/collectionbuilder/demo-objects/uiext21768.pdf"}}{% endcapture %}
{% assign videosample = site.data[site.metadata] | where_exp: 'item','item.format contains "video"' | first %}
{% capture videosampleid %}{{videosample.objectid | default: "https://cdil.lib.uidaho.edu/storying-extinction/objects/trailcams/videos/ballcreek-cedarrub-birdonpath.mp4"}}{% endcapture %}
{% assign audiosample = site.data[site.metadata] | where_exp: 'item','item.format contains "audio"' | first %}
{% capture audiosampleid %}{{audiosample.objectid | default: "https://www.lib.uidaho.edu/digital/mp3s/Clouds.mp3"}}{% endcapture %}

## What's A World’s Fair Anyways??
<P> During the prime of the international World's Fair, the expositions were hubs for international connectivity, cultural revolution, industrialization, and entertainment. What was introduced at a World’s Fair would become news around the world and Americans were fascinated by new ideas and technologies that would become a part of everyday life. Some expositions were thematically based upon technology and industrialization in fields such as agriculture and environmentalism. Others were commemorating a celebration such as the fairs held in Jamestown in 1907 and St. Louis in 1904. </p>


### Comics and the World's Fair?? What's the connection?
Comics and the World’s Fair Connection
<P> While it may not be obvious, the history of comics is directly tied to the American World’s Fair. At the 1893 Colombian Exposition, the world was introduced to four-color pressed newspaper cartoons. The Chicago Inter-Ocean wanted to show off its new color printing press and used cartoons to impress the fairgrounds’ visitors. After this new breakthrough in innovation, cartoonist Charles Saalburg debuted the first color newspaper comic strip characters, the Ting-Lings. This was years before The Yellow Kid ever debuted in the Hearst newspapers. </p>
<p> Following the fair of 1893, cartoonists took note and used the fair to promote their newest and greatest projects. In 1904, R.F. Outcault took his Buster Brown character to the St. Louis fair and told his character to tons of licensees, creating the greatest wave of cartoon character licensing up to that point. At the Century of Progress, Popeye, Mickey Mouse, and Moon Mullins were all used to promote the event. Other world fairs between 1900 and 1934 also featured editorial and newspaper cartoons that showcased the events that took place. </p>
<p> However, the accumulation and biggest moment for comics and the World’s Fair was when Superman Day at the World’s Fair occurred at the 1939 World’s Fair. Five years prior, Siegel and Shuster’s idea for Superman was rejected by every newspaper syndicate and magazine publisher in America. But at that moment, their creation was the leading star of an international exposition. Because of this event, a wave of merchandise and comic book storylines related to the World’s Fair emerged. The comic book industry was in New York and artists were reflecting on what was happening in their own America. This is why more than half of the objects in this collection are mapped in Flushing Park in New York City. Comics are a representation of the times they were produced, and the World’s Fair defined New York City life during the 1939-1940 period in which it ran. </p>
<iframe width="560" height="315" src="https://www.youtube.com/embed/A27ii9cIPGw?si=AXln-L1sSKYzk-2n" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<p>Like the World’s Fair in 1939, other world’s fairs would be portrayed in comics as relevant to American or world society. Back in New York again, the World’s Fair in 1964 would also have many comics based on its events. Set in New York City, the Marvel Universe would continue to use its remnants well after the fair had ended. </p>
<p> The World’s Fair is a very important factor in understanding the history of comics. This CollectionBuilder digital library allows researchers to see how important the World’s Fair was in comic history, and it will allow fair enthusiasts to see the history of the fair from a different perspective. </p>



#### Who is this Collection for and How Can it Be Used?
<p>The collection on this website is a selection of nearly a hundred years of cartoons and comics centralizing on the World’s Fair. Each of the cartoons and comics selected was set at a World’s Fair and was produced while that fair was relevant and was being held. Forty different examples were selected from a variety of different cartooning genres and venues. Each of these objects holds a particular significance, which is explained in the notes provided on each object’s page. There is also a page to search and browse based on keywords in provided notes, comic titles, creators, and subject matter. The subject matter of each object is the creators, features, and fair attractions central to the stories or gags in each magazine, strip, or editorial work. </p>
<p> The purpose of this collection is to showcase the history of comics through the various World’s Fairs that have been featured in them. Some comics feature fairs that took place worldwide, but more than half of them are from the fairs in New York City, where much of the comic book industry was home. This collection will be a good tool for pop culture scholars, researchers, comic book historians, and the world’s fair aficionados. </p>


{% include feature/image.html objectid=imagesampleid width="75" %}

#### Thanks to---

### Bill Cotter
For his incredible world's fair knowledge and notes on World's Fair attractions.
### Alberto Becattini
For helping with the selection process

### Alan Holtz
For his help on additional notes to early comic strip connections to the fair and for allowing the usage of his comic strip history blog.

