*poly-on-fire* is a collection of proof-of-concept projects using [Polymer](https://www.polymer-project.org/) and [Firebase](https://firebase.google.com/)

|[**_Pete Carapetyan_**](http://appwriter.com)|  [TL;DR? blog](https://betterologist.net/2018/04/poly-on-fire-polymer-on-firebase/) |[TL;DR? _video:_](https://youtu.be/P9DwkqqUxNs)|
| --- | --- | --- |
|<a href="http://appwriter.com"><img class="style-svg" src="https://betterologist.net/wp-content/uploads/2016/05/pete-300x297.jpg" alt="pete" width="116" height="115" /></a>|<a href="https://betterologist.net/2018/04/poly-on-fire-polymer-on-firebase/" ><img class="style-svg" src="http://docs.datafundamentals.com/txt.png" alt="jammazwanPhotoSmall" width="200" height="116" /></a>|<a href="https://youtu.be/P9DwkqqUxNs"><img class="style-svg" src="https://betterologist.net/wp-content/uploads/2016/05/jamzVid1.png" alt="about" width="115" height="115" /></a>|


##### A project for learning an aspect of developing a Polymer app, deployed on Firebase hosting.

The idea is to prove out an approach or component in the simplest project first, before combining it with other code in a real project.

----

# \<poly-on-fire-diff-serve-starter-kit\>

## What it does:

Implementation of differential serve per capabilities of browser, per scarygami blog

## Motive ##

While debugging a problem with deploying a vaadin element on firebase hosting, was advised of this project at this time.

Still learning about the needs for same, but wanted to incorporate these capabilities as I became aware of them.

## What is this project? ##

Direct implementation of the work on this blog, per this codebase

* https://medium.com/@scarygami/differential-serving-on-firebase-hosting-f83c33b83a8e
* https://github.com/Scarygami/polymer-starter-kit-firebase-hosting/

## Steps completed to do this #

* created this project from standard init.sh at https://github.com/poly-on-fire/poly-on-fire-init
* copied these 3 files from scarygami to new project
    * polymer.json
    * firebase.json
    * index.js
* hand modified firebase.json
    * changed public to public/build
* followed build instructions on scarygami blog

## To build ##

`polymer build`

## Status ##

* built OK
* did not `firebase deploy` successfully due to apparent error in index.js
* did not try to fix error, saved this task for another day
