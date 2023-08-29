# Frontend Mentor - Sunnyside agency landing page solution

This is a solution to the [Sunnyside agency landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/sunnyside-agency-landing-page-7yVs3B6ef). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![](./screenshot/screenshot.jpeg)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- sass
- Mobile-first workflow

### What I learned

```css (sass)
//tail effect for mobile menu
.main-nav::before
    content: ""
    position: absolute
    top: -5px
    left: 100%
    transform: rotate(90deg) scale(2, 2) translate(1px, 9.5px)
    border-style: solid
    border-width: 10px 10px 0 10px
    border-color: #fff transparent transparent transparent
    @media (min-width: 850px)
        display: none
```

### Continued development

making sits more responsive
keeping code DRY as much as possible

## Author

- Frontend Mentor - [@DagimTizazu](https://www.frontendmentor.io/profile/DagimTizazu)
- Email address - dagimtizazu4444@gmail.com
- Telegram - @dag400
