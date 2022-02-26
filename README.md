# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![desktop-design](https://github.com/najmeh-najafi/testimonials-grid-section/blob/master/images/desktop-design.jpg)
### Links

- Solution URL: [https://github.com/najmeh-najafi/testimonials-grid-section](https://github.com/najmeh-najafi/testimonials-grid-section)
- Live Site URL: [https://najmeh-najafi.github.io/testimonials-grid-section](https://najmeh-najafi.github.io/testimonials-grid-section)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid


### What I learned

While doing this project, I became familiar with css gride and used it to create an entirely responsive design. css Grid is one of the best technologies for creating project layering and the design can be easily responsive.


```html
<section class="testimonials-container">
   <article class="testimonial"></article>
   <article class="testimonial"></article>
   <article class="testimonial"></article>
   <article class="testimonial"></article>
</section>
```
```css
.testimonials-container{
  display:grid;
  grid-template-columns: repeat(4,1fr);
  grid-template-rows: auto auto;
  grid-auto-rows: auto;
}
```

### Useful resources

- [developer.mozilla.org](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Grids)

## Author

- telegram - [najmeh najafi](@nojom27)
- Frontend Mentor - [erfan atarzadeh](https://devedoping.ir/)

