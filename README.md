jsfest.berlin
=============

The schedule page for jsfest.berlin 2014

SVG Berlin Skyline by wasat on http://www.openclipart.org/detail/27938

Setup
=====

The site uses [jekyll](jekyllrb.com), to run the site do the following in your
terminal:

* `git clone git@github.com:rmehner/jsfest.berlin.git`
* `cd jsfest.berlin`
* `gem install jekyll`
* `jekyll serve --watch`

The site should then be available on http://localhost:4000

Compile CSS
===========

* `sass --watch scss/style.scss:css/style.css`

Create an event
===============

To create an event you just have to add a new markdown file to the _posts folder:

year-month-day-nameOfTheEvent.md

The following points are necessary:

* layout: post
* title: "name of the event"
* date: year-month-day
* venue: "name of the venue"
* ticket: "ticket status - RSVP, Register, Sold out, etc."
* time: "hours:minutesam/pm"
* href: "link to the page of the event host"

The href is crucial as long as the detail pages on jsfest.berlin aren't finished.

