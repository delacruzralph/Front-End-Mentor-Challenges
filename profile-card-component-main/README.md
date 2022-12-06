# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Frontend Mentor - Profile card component solution](#frontend-mentor---profile-card-component-solution)
  - [Table of contents](#table-of-contents)
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
## Overview

### The challenge

- Build out the project to the designs provided

### Screenshot

![](./solution.png)

### Links

- Solution URL: [https://github.com/delacruzralph/Front-End-Mentor-Challenges/tree/master/profile-card-component-main](https://github.com/delacruzralph/Front-End-Mentor-Challenges/tree/master/profile-card-component-main)
- Live Site URL: [https://delacruzralph.github.io/Front-End-Mentor-Challenges/profile-card-component-main/](https://delacruzralph.github.io/Front-End-Mentor-Challenges/profile-card-component-main/)

## My process

For this component, I took some time figuring out a good way to set up the html and body for spacing and centering the card. Then, as usual I organized the HTML and then styled each piece one at a time. 

### Built with

- HTML/CSS
- CSS Grid
- Mobile-first workflow

### What I learned

I made use of the position and transform CSS properties to properly lay out the images on the page and inside the card. 


```css
.top-bg {
  position: fixed;
  transform: translate(-50%, -50%);
  z-index: -100;
}

.profile-pic {
  border: 5px solid hsl(0, 0%, 100%);
  border-radius: 50%;
  position: absolute;
  left: 50%;
  bottom: 0;
  transform: translate(-50%, 50%)
}
```

### Continued development

I was able to use position to organize some elements on the page which I am happy about and would like to continue practicing with. Overall, this page feels clean and I am proud of it.

### Useful resources

- [Box Shadows](https://getcssscan.com/css-box-shadow-examples) - This helped me for finding a good box shadow setting and will be helpful for the future.

## Author

- Github - [Ralph Dela Cruz](https://github.com/delacruzralph/)
- Frontend Mentor - [@delacruzralph](https://www.frontendmentor.io/profile/delacruzralph)