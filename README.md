# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![Webpage screenshot](images/screenshot.jpeg)

### Links

- Solution URL: (https://github.com/antonio-barrera/stats-preview-card-component-main.git)
- Live Site URL: (https://antonio-barrera.github.io/stats-preview-card-component-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

The Media Query declaration must always be after (below) all the selectors that we are using within it, because the generation of styles starts from the top and ends at the bottom of the stylesheet.

```css
html {
    font-size: 62.5%;
}

@media (max-width: 375px) {
    html {
        font-size: 50%;
    }
}
```

### Useful resources

- [Background size adjustment](https://www.smashingmagazine.com/2021/10/object-fit-background-size-css/) - This is the blog I watched to get a better understanding about the different ways to adjust the background size in order to make it look better.
- [How to use Media Query](https://www.youtube.com/watch?v=yU7jJ3NbPdA&pp=ugMICgJlcxABGAE%3D) - Here we have a short video tutorial about how to start using Media Query to make a page responsive and to make it work in very different screen sizes.

## Author

- Frontend Mentor - [@antonio-barrera](https://www.frontendmentor.io/profile/antonio-barrera)
- Twitter - [@soyantoniob](https://www.twitter.com/soyantoniob)