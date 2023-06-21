# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-).

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

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](screenshot.png)

### Links

- Live Site URL: [https://lucasepk.github.io/3-column-preview-card-component/](https://lucasepk.github.io/3-column-preview-card-component/)

## My process

### Built with

- HTML
- CSS
- CSS Grid

### What I learned

In this project I learnt CSS grid, and that line-height exists.

```css
#container {
    /*makes container a grid with 1 row and 3 columns*/
    display: grid;
    grid-template-rows: 500px;
    grid-template-columns: 310px 310px 310px;
}

p{/*sets paragraphs parameters*/
    line-height: 1.6; /*makes text line more separated*/
}
```

### Continued development

I would like to understand better how to center a div, because the way I did it broke when i changed to mobile view and I don't really get it. It has to do with vh but idk. 

### Useful resources

- [https://youtu.be/EiNiSFIPIQE](https://youtu.be/EiNiSFIPIQE) - Very helpful video to understand CSS grid
- [https://youtu.be/9zBsdzdE4sM](https://youtu.be/9zBsdzdE4sM) - Another very helpful video to understand CSS grid
- [https://www.w3schools.com/cssref/pr_dim_line-height.php](https://www.w3schools.com/cssref/pr_dim_line-height.php) - Helped me understand and discover line-height

## Author

- Frontend Mentor - [@LucasEPK](https://www.frontendmentor.io/profile/LucasEPK)