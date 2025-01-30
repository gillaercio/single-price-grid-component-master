# single-price-grid-component-master
 single-price-grid-component-master

This is a solution to the [Single-price-grid-component-master challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### Screenshot

These are my screenshots showing how the project turned out.

- For desktop version:

![design](./assets/images/screenshot-desktop.png)

- For mobile version:

![design](./assets/images/screenshot-mobile.png)

### Links

- Solution URL: [My Solution](https://gillaercio.github.io/single-price-grid-component-master/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Grid Layout
- Mobile-first workflow

### What I learned

I took advantage of this project to practice the use of **Grid Layout**:

Grid-area in large screens

```css
@media (width > 1023px) {
  #content {
    min-width: 1024px;
    display: grid;
    grid-template-areas: 
    "feature feature"
    "budget footer";
  }

  .feature-content {
    grid-area: feature;
  }

  .budget-content {
    grid-area: budget;
    border-bottom-left-radius: 8px;
    width: 522px;
  }

  .footer-content {
    grid-area: footer;
    border-bottom-left-radius: 0px;
    border-bottom-right-radius: 8px;
    width: 522px;
  }
}
```

### Continued development

I would like to improve the use of **Grid layout** in conjunction with media queries.

## Author

- Frontend Mentor - [@gillaercio](https://www.frontendmentor.io/profile/gillaercio)
- Github - [My Github](https://github.com/gillaercio)
- LinkedIn - [My LinkedIn](https://www.linkedin.com/in/gildman-la%C3%A9rcio/)