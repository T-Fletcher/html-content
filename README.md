# README

## Introduction

This project is simply a collection of HTML elements on a single page, designed to give developers and designers
a quick look at all the common HTML elements as a user will see them. It is particularly useful for creating 
CSS stylesheets that cover all elements, even if they may not be used in the forseeable future. 

This is not a new idea; this particular repo is a chop-up of an existing content page:

Original Author: [Jukka K. Korpela](http://www.cs.tut.fi/~jkorpela/personal.html)
Original project: [Test display of HTML content](http://www.cs.tut.fi/~jkorpela/www/testel.html)


## Purpose and caveats

The purpose of this version was to update the HTML to HTML5 standards, with a few caveats:

- The elements are not an exhaustive list. This content page doesn't include *all* elements in the HTML specification;
- Only non-experimental elements have been included. This is to ensure that content covered offers a relatively consistent experience to the end user.
- No CSS has been included, deliberately; Only your Broswer's user agent stylesheet and your styles will affect the elements. 

## Extra fruit

To speed up navigation and keep the HTML elements as clean as possible, I've added some dynamic extras using JavaScript and jQuery:

- A table of contents of all the `<h2>`s is also included. 
- A list of the first instance of every HTML element referenced inside a `<code>` tag is included. Click a tag to go to it.
  - Some tags will include others, which may not be explicity mentioned, e.g. a `<thead>` inside a `<table>`.
- Each element also includes a link to the matching Mozilla Developer Network page for detailed information about that element.

**If you don't want to see this stuff, simply comment out/delete the script at the bottom of the `html-content.htm` file**

## How to use it

The demo page can be used in several ways:

- A standalone HTML file - just open 'html-content.htm' in your browswer of choice.
- Elements for insertion into another page/CMS - copy everything in the `<main>` tag and paste it wherever you want to test.

For example, I like to paste the `<main>` contents into an unpublished test page on any website i build, so I can quickly preview
any CSS changes that might affect content.

## List of elements included

- a
- abbr
- address
- area
- aside
- audio
- blockquote
- br
- button
- canvas
- caption
- cat
- cite
- code
- data
- datalist
- dd
- del
- details
- dfn
- dialog
- div
- dl
- dt
- em
- fieldset
- figcaption
- figure
- form
- header
- hr
- i
- image
- img
- input
- ins
- kbd
- label
- legend
- li
- main
- map
- mark
- meter
- nav
- noscript
- object
- ol
- optgroup
- option
- p
- param
- pre
- q
- samp
- section
- select
- small
- source
- strong
- sub
- summary
- sup
- table
- td
- textarea
- tfoot
- th
- time
- tr
- u
- ul
- var
- video
