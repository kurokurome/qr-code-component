# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)

## Overview

### Links

- Solution URL: [Github Repo](https://https://github.com/kurokurome/qr-code-component/)
- Live Site URL: [Github Pages](https://kurokurome.github.io/qr-code-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

I learned how to center elements of page using flexbox

```css
.container {
  background-color: hsl(212, 45%, 89%);
  margin: auto;
  padding: 75px 0;
  display: flex;
  align-items: center;
  justify-content: center;
  box-shadow: 3px 5px 25px hsla(0, 0%, 50%, 0.418);
}

.qrbox {
  margin: auto;
  display: flex;
  flex-flow: column wrap;
  justify-content: center;
  align-items: center;
  text-align: center;
  max-width: 250px;
  background-color: hsl(0, 0%, 100%);
  padding: 10px;
  border-radius: 15px;
  box-shadow: 1px 15px 25px hsla(220, 15%, 55%, 0.2);
}
```

### Continued development

Understanding more and more about CSS Flexbox since it is still making me confused

### Useful resources

- [W3Schools](https://www.w3schools.com/cssref/css3_pr_mediaquery.asp) - This helped me setup CSS for certain size of screen
- [CSS Tricks](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - This is the most helpful article for learning and understanding how flexbox works
