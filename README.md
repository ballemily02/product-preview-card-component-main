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
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- HTML
- CSS 
- Flexbox

### What I learned

I found this challenge definetly the hardest yet as I had no idea where to start. I found that starting with the desktop design first was really helpful then researching how to make the design responsive. Specifically this code below:

@media (max-width: 600px) {
    #card {
        border-radius: 10px;
        display: flex;
        justify-content: center;
        align-items: center;
        overflow: hidden;
        max-width: 600px;
        margin: auto;
        flex-direction: column;
    }

    #photo {
        background-image: url(images/image-product-mobile.jpg);
        height: 350px;
        background-size: cover;
        width: 100%;
        background-position: center;
    }
}

Overall I am really pleased with everything I've learnt this challenge and am really excited to take these skills forward.

## Author

- Frontend Mentor - [@ballemily02](https://www.frontendmentor.io/profile/ballemily02)


