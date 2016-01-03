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