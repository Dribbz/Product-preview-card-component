# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Frontend Mentor - Product preview card component solution](#frontend-mentor---product-preview-card-component-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [The challenge](#the-challenge)
    - [Screenshot](#screenshot)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
  - [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./sc-desktop.png)
![](./sc-mobile.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

```html
<button class="button" data-icon="shopping-cart">Add to Cart</button>

<picture>
  <source
    srcset="./images/image-product-desktop.jpg"
    media="(min-width:600px)"
  />
  <img
    src="./images/image-product-mobile.jpg"
    alt="perfume on a table sorrounded by leaves"
  />
</picture>

<p class="product__original-price"><s>$169.99</s></p>

using the <s> to add a stroke</s>
```

```css
using data attributes .button[data-icon="shopping-cart"]::before {
  content: "";
  width: 15px;
  height: 16px;
  background-image: url("./images/icon-cart.svg");
}
```

## Acknowledgments

Kevin Powell on Youtube i followed his tutorials and i learned a lot about variables and keeping my code clean and non repetitive
