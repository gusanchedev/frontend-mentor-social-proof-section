# Frontend Mentor - Social proof section solution

This is a solution to the [Social proof section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-proof-section-6e0qTv_bA). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout for the section depending on their device's screen size

### Screenshot

![]("/design/desktop-preview.jpg")

### Links

- Solution URL: [@Github](https://github.com/gustavosanchezgalarza/frontend-mentor-social-proof-section)
- Live Site URL: [@Vercel](https://frontend-mentor-social-proof-section-five-delta.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

1. Using multiple background images

```css
body {
  font-size: 15px;
  font-family: "Spartan", sans-serif;
  margin: 0 auto;
  background-image: url('../images/bg-pattern-top-mobile.svg'), url('../images/bg-pattern-bottom-mobile.svg');
  background-repeat: no-repeat;
  background-position: top 0px right 0px, bottom 0px right 0px;
}
```
2. Using media queries for adjusting content to several screen types
```html
    <link rel="stylesheet" href="./css/mobile.css" />
    <link
      rel="stylesheet"
      media="screen and (min-width:768px and max-width:1024px)"
      href="./css/tablet.css"
    />
    <link
      rel="stylesheet"
      media="screen and (min-width:1025px)"
      href="./css/laptop.css"
    />
```

### Continued development

Next challenges will include Javascript to provide animation and interaction to user.

### Useful resources

- [Flexbox in CSS-Tricks](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) 
- [Grid in CSS-Tricks](https://css-tricks.com/snippets/css/complete-guide-grid/)

## Author

- Website - [www.gusanche.dev](https://www.gusanche.dev)
- Frontend Mentor - [@gustavosanchezgalarza](https://www.frontendmentor.io/profile/gustavosanchezgalarza)
- Twitter - [@gusanchedev](https://www.twitter.com/gusanchedev)

## Acknowledgments

**Thanks for reading me** 👍

**Gustavo**