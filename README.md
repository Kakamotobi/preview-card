# preview-card

## Table of Contents
- [Overview](#overview)
  - [The Challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built With](#built-with)
  - [What I Learned](#what-i-learned)
- [Author](#author)

## Overview
### The Challenge
Users should be able to:
- View the optimal layout depending on their device's screen size.
- See hover states for interactive elements.
### Links
- Live Site URL: https://preview-card.vercel.app/

## My Process
### Built With
- HTML
- CSS
### What I Learned
- Margin Collapse
  - Only occurs vertically.
  - To avoid this, `display: inline-block` can be set on the element below.
    - Top and bottom margins/paddings are now respected.
- Hovering on element A to animate element B.
  - Element A has to be before element B (HTML-wise).
  - Ex: `section:first-child:hover > img { transform: translateX(150px);}`

## Author
- GitHub - [Kakamotobi](https://github.com/Kakamotobi)
- Frontend Mentor - [@Kakamotobi](https://www.frontendmentor.io/profile/Kakamotobi)
