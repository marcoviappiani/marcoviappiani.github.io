---
layout: post
title: BlocJams
thumbnail-path: "img/blocjams.png"
short-description: Bloc Jams is a simple player to listen to your favourite music online.

---

{:.center}
![]({{ site.baseurl }}/img/blocjams.png)

## Explanation

Bloc Jams is a web based music player. It's mobile responsive and built with Angular.js.

## Problem

Music Players nowadays are full of extra features and typically require subscription for a monthly fee or listening to ads. I wanted to make something that would go back to basics and show a nice simple interface to listen to my own music.

## Solution

Bloc Jams is mobile responsive and accessible from any browser. The design is beautiful and minimal while the functionality is kept to a minimum.
The advantage of using Angular.js is having a "single page app" with fast page load and solid architecture despite having three sections with different functionalities.

this is an example of the code I used to set up a router that would switch between the different views:

{% highlight javascript %}
$stateProvider
         .state('landing', {
             url: '/',
             controller: 'LandingCtrl as landing',
             templateUrl: '/templates/landing.html'
         })
        .state('album',{
            url: '/album',
            controller: 'AlbumCtrl as album',
            templateUrl: '/templates/album.html'
        })
        .state('collection',{
            url: '/collection',
            controller: 'CollectionCtrl as collection',
            templateUrl: '/templates/collection.html'
        });
    }
{% endhighlight %}

## Results

The interface is divided in three main parts. A "home" page, a "collection" page which lists all available albums, and an "album" view which also contains the player.

> Play, pause, volume controls are some of the available features


## Conclusion

Obviously this market is very saturated and there isn't a lot of space for new music players. Possible next steps would require adding the ability to import one's own music and sharing features.