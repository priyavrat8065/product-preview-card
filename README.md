# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![Screenshot of the web page.](./screenshot.png)

### Links

- To check the Github source code of the project, click [here](https://github.com/priyavrat8065/product-preview-card)
- To check the live site URL, Click [here](https://priyavrat8065.github.io/product-preview-card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

In this project i learnt how to perfectly vertically align before pseudo element with respect to element it is applied on. This is why i managed to center the shopping cart icon inside the button and side by `Add to cart` text. Below is the code snipped of how i achieved that -

```css
.perfume__shopping-btn:any-link {
  display: flex;
  justify-content: center;
  align-items: center;
}
.perfume__shopping-btn::before {
  display: flex;
  align-items: center;
}
```

I also learnt how to make sure that image flex item stays 50% the total size of its parent container. I set achieved it by setting `min-width:50%` to figure flex item that contains the image.

```css
.container figure {
  min-width: 50%;
}
```

### Useful resources

- I took help of [this resource](https://www.bennadel.com/blog/3857-applying-css-flexbox-to-pseudo-elements.htm) to perfectly center the shopping cart icon vertically with respect to the `Add to Cart` text. You can also take a look at this resource. It was very helpful.

## Author

- My Github Dashboard: [Link](https://github.com/dashboard)
- My Frontend Mentor page: - [Link](https://www.frontendmentor.io/profile/priyavrat8065)
