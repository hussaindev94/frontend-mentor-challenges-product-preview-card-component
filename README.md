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

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./assets/screenshot/screenshot.svg)


### Links

- Solution URL: [Solution URL](https://github.com/hussaindev94/frontend-mentor-challenges-product-preview-card-component)
- Live Site URL: [Live site URL](https://hussaindev94.github.io/frontend-mentor-challenges-product-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow


### What I learned

1. The format() in the src of the @font-face will make or break the font.
  * What do I mean by this? If you provide format wrong type the fonr will not work.
    ```css
    /*Worng*/
    /*Assume the font file extension is .otf*/
    @font-face{
      font-family: "font-family-name";
      src: url("../assets/font/fonfile.otf") format("otf"); /*or*/
      src: url("../assets/font/fonfile.otf") format("font/otf");/*or*/
      src: url("../assets/font/fonfile.otf") format(otf);
    }
    /*The correct way*/
        font-family: "font-family-name";
      src: url("../assets/font/fonfile.otf") format("opentype");
    ```
2.The background images: ust provide dimensions for them to show up on the screen.
  * If you just put them inside an element or wrapper they will not show up.

### Continued development


### Useful resources

- [resource 1](https://web.dev/learn/design) - This helped me in media query features, fluid typography , styling media such as images vedios, and pictuers, and exploring other style concepts.

## Author

- Website - [Hussain Al-shaer](https://hussaindev94.github.io/Portfolio/)
- Frontend Mentor - [@hussaindev94](https://www.frontendmentor.io/profile/hussaindev94)
- Twitter - [@hussaindev94](https://x.com/hussaindev94)
