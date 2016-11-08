# Website Optimization portfolio project

Project aims at Optimizing this online portfolio for speed and getting a score above 90 for both mobile & desktop!

## Getting started

* Download this Project or clone repository through Git.
* Open Index.html in a Web Browser.
* Use options in Dev tools to measure the web performance.
* Use PageSpeed Insights to get scores for the webpage.

## Optimizations done

### On index.html to get score above 90

* Inlined style.css
* Added media = "print" attribute to `link` of print.css
* Added async attribute to js files
* compressed profilepic & Pizzeria (resized too)
* Used optimie CSS delivery trick to load openSans font delivered by google

### Optimizations on views/js/main.js

* UpdatePositions()

 Declared new variables to do calculations outside the for-loop. Declared an array to store the repeating values. Replaced document.querySelector with document.getElementsByClassName. Used style.transform instead of style.left
