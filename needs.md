# Needs

* As a user, I want to be able to work quickly without waiting for rebuilds all the time.
* As a user who only knows HTML/CSS, I want to be able to get going without a steep learning curve.
* As a user, I don't want to see all the code, just the important bit (inside <div class="wrapper") so that I can get some head space.
* As a user, I want to be able to update the stylesheets easily so that they stay up to date.

## Why not jekyll?

* The performance is bad. Every time you make a change, you have to rebuild the entire prototyping app. The current prototyping-v2 allows you to run sass from within your subfolder (or just use straight css).
* It's confusing for noobs. It's not foolproof to get working and it's confusing exactly what happens to your file (most of the time your <div class="wrapper"> just gets wrapped with everything else)

## As simple as possible

* We're going to need some kind of ruby/python/php app to wrap the prototypes with the rest of the HTML and create a local webserver.
* Whatever this is, it should be ultra simple to use (!= simple to code). For example, if it works on ruby 1.8.7 this is good, because that's the ruby that comes with vanilla macs.

## Success criteria

* An app which lets a designer who only knows HTML and CSS start prototyping without having to learn loads of technical stuff.