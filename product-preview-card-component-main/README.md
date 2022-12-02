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
    - [Continued development](#continued-development)
  - [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./mobile.png)
![](./desktop.png)

### Links

- Solution URL: [https://github.com/delacruzralph/Front-End-Mentor-Challenges/blob/master/product-preview-card-component-main/index.html](https://github.com/delacruzralph/Front-End-Mentor-Challenges/blob/master/product-preview-card-component-main/index.html)
- Live Site URL: [https://delacruzralph.github.io/Front-End-Mentor-Challenges/product-preview-card-component-main/](https://delacruzralph.github.io/Front-End-Mentor-Challenges/product-preview-card-component-main/)

## My process

I mistakenly started off with the desktop solution to the challenge, which I realized made things more difficult when implementing the mobile version, specifically with the layout. I started with the HTML and organizing all the information and worked on styling each small piece. Then I worked on the layout using flexbox and made sure the sizing of the image and text matched the design. I then moved on to the mobile design, making sure I did not mess up the desktop design while doing so.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

I learned the importance of mobile-first workflows and how it is valuable for scaling up designs for screen sizes. However, I also got a better sense of translating between mobile and desktop for styles and how one small change in one size can affect the other size drastically. Fortunately, the mobile and desktop versions were not too different and fixing the code to accomodate was manageable.

To see how you can add code snippets, see below:

I am proud of this code because I was having problems with changing the height of the product information part of the card in which the mobile and desktop versions were not cooperating. I was able to find a solution that accomodated both.
```css
.product-info {
  padding: 28px;
  height: 90%;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
}
```

I am also proud of this code because I found an easy way to center elements horizontally and vertically on the whole page without any guessing.
```css
html {
    margin: 0;
    height: 100%;
  }

  body {
    background-color: hsl(30, 38%, 92%);
    margin: 0;
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
  }
```

### Continued development

I would like to continue practice with responsive design and mobile-first workflows and get a better sense of ways to accomodate multiple screens. I also want to learn more about responsively setting the heights and widths of elements instead of hardcoding pixel sizes.

## Author

- Website - [Ralph Dela Cruz](https://www.your-site.com)
- Frontend Mentor - [@delacruzralph](https://www.frontendmentor.io/profile/delacruzralph)
