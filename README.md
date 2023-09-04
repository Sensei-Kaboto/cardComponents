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
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![1693829088487](image/README/1693829088487.png)![1693828992291](image/README/1693828992291.png)

### Links

- Solution URL: https://github.com/Sensei-Kaboto/cardComponents/settings/pages
- Live Site URL: https://sensei-kaboto.github.io/cardComponents/

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

in this project I've learn some concept that I was lacking knowledge on and learn also new things. here what i learnt:

1. `<picture> properties: The <picture> HTML element contains zero or more <source> elements and one <img> element to offer alternative versions of an image for different display/device scenarios. `

```html
<picture>
          <source srcset="images/image-product-desktop.jpg" media="(min-width:23.5em)">
          <img src="images/image-product-mobile.jpg"  alt="image product ">
</picture>
```

2. Overflow property:

   sets the desired behavior when content does not fit in the parent element box (overflows) in the horizontal and/or vertical direction.															`.image__card{ height: 350px; overflow: hidden; }`

### Useful resources

- [An Interactive Guide to Flexbox in CSS](https://www.joshwcomeau.com/css/interactive-guide-to-flexbox/)- This helped me for a more understanding of how flexbox work.

## Author

- Website - Daniel Kaboto
- Frontend Mentor - @Sensei-kn
- Twitter - [@](https://www.twitter.com/yourusername)Sensei_kn
- LinkendIN : @Danielkaboto
