# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![Mobile](./images/Screenshot1%203-column%20preview%20card%20component.png)
![Desktop](./images/Screenshot2%203-column%20preview%20card%20component.png)

### Links

- Live Site URL: [3-column preview component](https://magical-crumble-6b03a0.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid

### What I learned

I learned more grid display and Im proud to learned make more organized classes in css
```css
.sedans{
    grid-area: sedans;
    grid-column-start: sedans;
    grid-column-end: sedans;
    background-color: hsl(31, 77%, 52%);
    border-radius: 10px 0 0 10px;
}
.suvs{
    grid-area: suvs;
    grid-column-start: suvs;
    grid-column-end: suvs;
    display: grid;
    background-color: hsl(184, 100%, 22%);
}
.luxury{
    grid-area: suvs;
    grid-column-start: luxury;
    grid-column-end: luxury;
    display: grid;
    background-color: hsl(179, 100%, 13%);
    border-radius: 0 10px 10px 0;
}
.img{
    justify-self: left;
    align-self: self-start;
    margin-top: 3rem;
}
.sedans, .suvs, .luxury{
    max-width: 300px;
    max-height: 500px;
    place-items: center;
    padding-left: 3rem;
    display: grid;
    grid-template-rows: 20% 60% 20%;
}
```

### Continued development

I'm going to continued development in grid display and more organized classes in css

### Useful resources

- [wh3schools](https://www.w3schools.com/) - A great place.

## Author

- Frontend Mentor - [@R3ptarGreen](https://www.frontendmentor.io/profile/yourusername)

## Acknowledgments

I'm studying by myself in FreeCodeCamp and I'm improving my skills with Frontend Mentor
