# Frontend Mentor - QR code component solution

This is a solution to the QR code component challenge on Frontend Mentor (https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### Screenshot

![375 pixels wide screenshot](\screenshots\375dev.png)
![1440 pixels wide screenshot](\screenshots\1440dev.png)

### Links

- Solution URL: (https://github.com/Klonnister/HTML-Pruebas/tree/main/Exercises/qr-code-component-main)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Mobile-first workflow

### What I learned

In this exercise I first practiced using media queries, which I hadn't done before. 

```css
@media only screen and (max-width:375px) {

      .whitecontainer{
        width: 320px;
        height: 500px;
        margin-left: 17.5px;
        margin-top: 80px;
      }
```

The second thing I learned with this challenge, is to add google fonts to html documents. At the beginning I wasn't able to do it, as I was just copying the font link provided in the style-guide text document. So I had to navigate through the google font page and get some guidance from the w3schools page to correctly add the font. 

How did I add the google font to my page? 
First I compared the link provided in the style-guide text document to the examples shown at the w3schools page for adding google fonts; I realized they were somehow different. So I navigated through the google font page and looked for a way to get a similar link to the one in the style-guide doc. It was until I selected any of the options (the options are identified by weight. E.g. Regular 400) in the styles section that a canvas showed up with the links to add the font to your css. 

```html
 <link href="https://fonts.googleapis.com/css2?family=Outfit:wght@700&display=swap" rel="stylesheet">
```

### Useful resources

[W3Schools google font page](https://www.w3schools.com/css/css_font_google.asp)

## Author

- Github - [Klonnister](https://github.com/Klonnister)
- Frontend Mentor - [@Klonnister](https://www.frontendmentor.io/profile/Klonnister)
- Instagram - [dennis_herrera_f](https://www.instagram.com/dennis_herrera_f/)

## Acknowledgments

Gotta say thanks to [Cristian](https://github.com/CristianBlake), who's helped me a lot to learn web design, and also recommended me these front-end exercises :D.
