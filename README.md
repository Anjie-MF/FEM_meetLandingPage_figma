# Frontend Mentor - Meet landing page solution

This is a solution to the [Meet landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/meet-landing-page-rbTDS6OUR). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
- See hover states for interactive elements

### Screenshot

![](/screenshots/mobile.png) ![](/screenshots/tablet.png)
![](/screenshots/desktop.png)

### Links

- Solution URL: [GitHub](https://github.com/Anjie-MF/FEM_meetLandingPage_figma)
- Live Site URL: [GitHub Pages](https://anjie-mf.github.io/FEM_meetLandingPage_figma/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Figma

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```html
      <div class="component-marker2">
        <div class="vertical-line"></div>
        <div class="circle">02</div>
      </div>

It was my first time "drawing" using HTML... 
```
```css
section .vertical-line {
    background-color: #d1d1d1;
    width: 1px;
    height: 80px;
    display: flex;
    justify-content: center;
    align-items: center;
    margin-left: 25px;
}

section .circle {
    width: 56px;
    height: 56px;
    background-color: #d1d1d1;
    border-radius: 50%;
    display: flex;
    justify-content: center;
    align-items: center;
    color: white;
    font-weight: bold;
}

... And using CSS  to visualize it. 
```
```
.footer-hero::before {
    content: "";
    background-color: #4d96a9;
    opacity: 0.5;
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    z-index: 1;
}

First really using z-index and pseudo-elements. 
```

### Continued development

I am looking forward to learning more about z-index, pseudo-elements, and CSS specificity. 


### Useful resources

- [CSS Specificity](https://css-tricks.com/specifics-on-css-specificity/)- CSS-Tricks
- [CSS Specificity](https://www.w3schools.com/css/css_specificity.asp) - w3schools
- [Pseudo-Elements](https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-elements) - MDN_web_docs
- [Pseudo-Elements](https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-elements) - MDN_web_docs


## Author

- Linkedin - [Anjelica May](www.linkedin.com/in/anjiemay23)
- Frontend Mentor - [Anjie-MF](https://www.frontendmentor.io/profile/Anjie-MF)
- Dev.to - [anjelica_mf](https://dev.to/anjie_mf)

## Acknowledgments

- Front End Mentor Discord - [chamu_k_m]- Thank you for pointing out that the media queries were wrtiten incorrectly. 
- Front End Mentor Discord - [itsdarkstar] - Thank you for pointing out horizontal scrollbar, the excessive amount of grid-columns, and instructions on how to layer the componenent marker. 
