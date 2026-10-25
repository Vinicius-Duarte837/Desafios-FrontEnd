# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- Build out the project to the designs provided

### Screenshot

![Screenshot](./images/Screenshot.png)

### Links

- Solution URL: [GitHub Pages](https://your-solution-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

This project was a little challenging because it required multiple uses of flexbox, first for the main itens within the main container, and then to the information inside these items. It may seen overwhelming at first, but after breaking and working on each item individually, it turned out to be pretty simple. The biggest problem that I had was the two spheres at the background, I had a lot of trouble trying to figure out how to properly position them and keep them in place for different screen sizes. I had to look it up some documentation in order to do it the right way, and ultimately, came across the use of view-height and view-width on the background position, which solved my problem.

```css
body {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: var(--blue);
  background-image: url('images/bg-pattern-top.svg'), url('images/bg-pattern-bottom.svg');
  background-position: right 50vw bottom 50vh, left 50vw top 50vh;
  background-repeat: no-repeat;
  overflow-x: hidden;
}
```

### Continued development

I need to keep up with these projects because they are helping me understand how to solve problems by myself without relying on chewed up code that someone else made. I have been studying CSS for a while but the lack of practice made me forget some simple stuff, mainly within the background selector. By training with these, I'll strengthen my understanding of CSS.

### Useful resources

- [W3Schools](https://www.w3schools.com/css/css3_backgrounds.asp) - This helped me remember about the background shorthand property, and I didn't know I could use multiple background images and set them differently
- [MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/Properties/background) - Same reasons as above, before settling with vw and vh, I tried using percentages on the positioning, which I learned by reading the documentation, despite not using it in the final version.

## Author

- Frontend Mentor - [@Vinicius-Duarte837](https://www.frontendmentor.io/profile/Vinicius-Duarte837)
