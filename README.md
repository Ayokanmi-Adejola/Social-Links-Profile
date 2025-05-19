# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![](./preview.jpg)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- CSS transitions for hover effects

### What I learned

This project helped me improve my skills in creating responsive layouts using Flexbox. I learned how to effectively use CSS custom properties (variables) to maintain a consistent color scheme throughout the project.

I'm particularly proud of the hover and focus effects on the social links:

```css
.link-btn:hover, .link-btn:focus {
  background-color: var(--green);
  color: var(--grey-900);
}
```

I also improved my understanding of responsive design by implementing a mobile-first approach and adding media queries for smaller screens:

```css
@media (max-width: 375px) {
  .card {
    padding: 1.5rem;
  }
}
```

### Continued development

In future projects, I want to focus more on accessibility features and implementing more complex animations. I also plan to explore CSS Grid for more complex layouts.

## Author

- Frontend Mentor - [@Ayokanmi-Adejola](https://www.frontendmentor.io/profile/Ayokanmi-Adejola)
