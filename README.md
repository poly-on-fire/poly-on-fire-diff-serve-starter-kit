# poly-on-fire-diff-serve-starter-kit

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





