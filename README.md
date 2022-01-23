# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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
- See hover states for interactive elements

### Screenshot

![](images/Desktop_view.png)


### Links

- Solution URL: (https://github.com/jleegunn/3-column-card)
- Live Site URL: (https://jleegunn.github.io/3-column-card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I learned more about flexbox and how to manipulate the design, along with getting more comfortable with the Chrome developer tools when I have issues.


```css
@media (max-width: 975px){
  body {
    margin: 0;
  }
  .flex-container {
    flex-direction: column;
    align-items: center;
    width: 375px;
  }
  .container1 {
    border-top-right-radius: 10px;
    border-bottom-left-radius: 0;
  }

  .container3 {
    border-top-right-radius: 0;
    border-bottom-left-radius: 10px;
  }
}
}
```

### Useful resources

- [Example resource 1](https://css-tricks.com/almanac/properties/f/flex-flow/) - This helped me learn all the properties that flexbox offers.


## Author

- Website - [Jamie Counsellor](TBD)
