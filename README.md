# Website Performance Optimization portfolio project #perfmatters

## Synopsis

This project aims at optimizing a portfolio website by analyzing the critical rendering path and other browser optimizations. This project is part of the coursework at Udacity - FEND program

## Optimizations performed
1. Compress images
2. async request javascript
3. minify inline css
4. Change Pizza sizes modified to use percatage values to avoid expensive calculations
5. Update Postions uses getElementsByClassName instead of querySelectorAll as it is faster
6. Update Positions queries the DOM for the Node 'mover' once outside the for loop instead of querying each time
7. A constant array with all possible position values created to avoid calculating on each scroll

## Instructions
1. Website URL - http://91sanjay.github.io/website-optimization/index.html
2. Click on each link to visit the projects completed as part of Udacity FEND
3. Click on Cam's Pizzeria to visit the site in which the frame rate improvements were made
4. Visit https://developers.google.com/speed/pagespeed/insights/ to test the page speed of this site