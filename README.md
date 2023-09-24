# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
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
My first project on Frontend Mentor. The card of QR code is the same size on a mobile then I don't code the responsive part of code. Just use only the HTML and the CSS.

### Screenshot

![Desktop](./screenshot/screenshot-desktop.png)
![Mobile](./screenshot/screenshot-mobile.png)

### Links

- Live Site URL: [femt-qr-code-component](https://mpluggie7.github.io/femt-qr-code-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- [Styled Components](./style.css) - For styles

### What I learned

The new topic learning that I have just learned is the variable of the css. By decare the parameter as root: { --name_of_param : value; }
then, When be used I will call as style="some_style: var(--name_of_param);" 

```css
:root {
  --White: hsl(0, 0%, 100%);
}

.card {
  background-color: var(--White);
}
```

### Continued development

I will continue to practice in the other projects.

### Useful resources

- [variable-css](https://www.w3schools.com/css/css3_variables.asp) - This helped me to understand the variable in css.

## Author

- Website - [megamaxo-app](https://www.megamaxo-app.com)
- Frontend Mentor - [@Mpluggie7](https://www.frontendmentor.io/profile/Mpluggie7)

## Acknowledgments

n/a
