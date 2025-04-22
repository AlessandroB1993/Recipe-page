- [Overview](#overview)
  - [The challenge](#the-challenge)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

I tried to use semantic HTML and diveded some part of the page content with <article> and <section>. I used the BEM approach for CSS. The difficult part for me was to get the image at the top to work properly, especially for the desktop design. To make it work I figure as the container, gave it max-height: from 160px to "fit-content", and to the image itself: object-fit: cover. This way the image takes the height it needs to be displayed properly while being always displayed totally as the screen size increases.
