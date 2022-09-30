# Frontend Mentor - Order summary card solution

![](./design/desktop-preview.jpg)

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

<h2 align="center">Links</h2>

- Solution URL: [Order Summary Component (SASS + Mobile first + BEM) | Frontend Mentor](https://www.frontendmentor.io/solutions/order-summary-component-sass-mobile-first-bem-BlfUdr5oBv)
- Live Site URL: [https://order-summary-component-melvinhdz.vercel.app/](https://order-summary-component-melvinhdz.vercel.app/)

<br>

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
- [My process](#my-process)
  - [Built with](#built-with)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- See hover states for interactive elements

## My process

### Built with

- Semantic HTML5 markup
- Mobile-first approach
- Flex Layout
- BEM naming convention
- [SASS](https://sass-lang.com/documentation/modules) - Sass modules


### Useful resources

- [Mobile-first approach](https://www.freecodecamp.org/news/taking-the-right-approach-to-responsive-web-design/)
- [CSS Guidelines](https://cssguidelin.es/#bem-like-naming)
- [BEM naming convention](https://css-tricks.com/bem-101/)
- [BEM naming examples](https://getbem.com/naming/)

- [Material Design Box Shadows](https://codepen.io/sdthornton/pen/wBZdXq)
- [CSS background Property](https://www.w3schools.com/cssref/css3_pr_background.asp)

- [Solving Sticky Hover States with @media (hover: hover)](https://css-tricks.com/solving-sticky-hover-states-with-media-hover-hover/)

## Author

- Frontend Mentor - [@melvinaguilar](https://www.frontendmentor.io/profile/melvinaguilar)

## Acknowledgments

When using `sass` in order to build this solution

- Install `sass` if not yet installed:

```bash
npm install -g sass
```

- Run build command from command line:

```bash
sass assets/sass/main.scss assets/css/style.css
```

- If you want to edit the code and test, in the root folder of this repository, run this command from the command line:

```bash
sass --watch assets/sass/main.scss assets/css/style.css
```

## File structure

```
.
├── assets
│   ├── css
│   │   ├── style.css
│   │   └── style.css.map
│   ├── images
│   │   ├── favicon-32x32.png
│   │   ├── icon-music.svg
│   │   ├── illustration-hero.svg
│   │   ├── pattern-background-desktop.svg
│   │   └── pattern-background-mobile.svg
│   └── sass
│       ├── abstracts
│       │   ├── _mixins.scss
│       │   └── _variables.scss
│       ├── base
│       │   ├── _page.scss
│       │   └── _reset.scss
│       ├── component
│       │   ├── _attribution.scss
│       │   ├── _buttons.scss
│       │   ├── _heading.scss
│       │   └── _screen-reader.scss
│       ├── layout
│       │   └── _order-card.scss
│       └── main.scss
├── design
│   ├── active-states.jpg
│   ├── desktop-design.jpg
│   ├── desktop-preview.jpg
│   ├── mobile-design.jpg
│   └── screenshot.png
├── index.html
└── README.md
```
