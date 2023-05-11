# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
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

![](./screenshot.png)

### Links

- Solution URL: [Add solution URL here](https://github.com/apah-dev/four-card-feature-section-master.git)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

Learn how to properly use the align-self property and how to use it for self-aligning contents withing a flexbox div.

To see how you can add code snippets, see below:

```css
.middle-set {
  justify-content: center;
  align-items: center;
}

.tools {
  width: 80%;
}

.tools:nth-of-type(1) {
  align-self: flex-center;
}

.tools:nth-of-type(4) {
  align-self: center;
}
```

### Useful resources

- [HTML & CSS Udemy Course](https://www.udemy.com/course/the-web-developer-bootcamp/learn/lecture/22380972#notes) - This helped with properly understanding the align-self property and how to use it for self-aligning contents withing a flexbox div.

## Author

- Frontend Mentor - [@apah-dev](https://www.frontendmentor.io/profile/apah-dev)
- Twitter - [@benson_apah](https://www.twitter.com/benson_apah)

## Acknowledgments

Thanks to Colt for the udemy course https://www.udemy.com/course/the-web-developer-bootcamp/learn/lecture/22380972#notes
