# Frontend Mentor - Easybank landing page solution

This is a solution to the [Easybank landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/easybank-landing-page-WaUhkoDN). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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
- See hover states for all interactive elements on the page

### Screenshot

![](./images/Screenshot.jpg)

### Links

I'm really sorry for not providing links. Built the project before initializing on github.

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Desktop-first workflow
- Vanilla JavaScript

### What I learned

Using the 'auto-fit' was the best thing for me while writng the css... It helps me to write less media queries... Making the site very responsive across different width/devices. I finally got to use the checkbox hack for the mobile navigation. It was good remembering how to use it cause I last used it while following Jonas' Schmedtmann's udemy course on advanced css and sass.
Finally, I got to use some of the things i learnt from Jonas' complete JavaScipt course for page-navigation and revealing elements on scroll. This was definitely a challenging project and I'm happy I got to finish it.

```html
<aside>...</aside>
```

```css
grid-template-columns: repeat(auto-fit, minmax(12rem, 1fr));
```

```js
document.querySelector('.nav__links').addEventListener('click', function (e) {
  e.preventDefault();

  if (e.target.classList.contains('nav__link')) {
    const id = e.target.getAttribute('href');
    document.querySelector(id).scrollIntoView({ behavior: 'smooth' });
  }
});
```

### Continued development

I'm not completely comfortable with building navigation bars. It was great using flexbox. Moving forward, I would love to perfect it.

### Useful resources

## Author

- Frontend Mentor - [@Kl3va](https://www.frontendmentor.io/profile/Kl3va)
- Twitter - [@_Kl3va_](https://www.twitter.com/_Kl3va_)

## Acknowledgments

I would like to give a shout out to Jonas Schmedtmann. His udemy courses have been very helpful in my journey to become a professional FrontEnd Developer. Much love.
