# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

### Screenshot

![](./design/screenshot.PNG)

### Links

- Solution URL: [Add solution URL here](https://github.com/impuranjayp/Stat-Card-Preview-Component)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- HTML5 markup
- CSS custom properties
- Flexbox
- Desktop-first workflow

### What I learned

In this section I want to recap over some of the major code areas of the project that were hurdles to cross through this project. 
Here are some code samples of areas I want to highlight as a great way to reinforce knowledge.

The image and the overlay was a challenge especially in arranging the divs
```html
<div class="container">
  <img src="./images/image-header-desktop.jpg" alt="">
  <div class="img-overlay"></div>
</div>
```
```css
.container{
  position: relative;
  height: auto;
}

.container img{
  width: 100%;
  height: auto;
  border-radius: 10px 10px 0 0;
}

.img-overlay{
  position: absolute;
  background-color: hsl(278, 87%, 33%);
  opacity: 0.5;
  height: 98.7%;
  width: 100%;
  top: 0;
  left: 0px;
  border-radius: 10px 10px 0 0;
}
```
## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)



