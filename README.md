# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)


## Overview

### The challenge

Users should be able to:

- See hover states for interactive elements



### Links

- Solution URL: https://github.com/adeoyewole028/order-summary-component-main.git
- Live Site URL: https://capstone-group-62-project.netlify.app/

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

```css
.music-img {
  background-image: url(./images/illustration-hero.svg);
  background-repeat: no-repeat;
  width: 450px;
  height: 220px;
  border-top-left-radius: 10px;
  border-top-right-radius: 10px;
}

and

@import url("https://fonts.googleapis.com/css2?family=Red+Hat+Display&display=swap");

body {
  font-family: "Red Hat Display", sans-serif;
  font-weight: 500, 700, 900;
  font-size: 16px;
  justify-content: center;
  align-items: center;
  background-image: url(./images/pattern-background-desktop.svg);
  background-size: 100%;
}
```

## What I, Osazuwa-Ojo Victory have learnt:

```css
/* Learnt adjusting and formatting of text colour and font.*/
.cancel {
  padding: 20px;
  color: hsl(224, 23%, 55%) ;
  font-weight: 700;
}

.cancel:hover {
  font-weight: 800;
  cursor: pointer;
  color:  hsl(223, 47%, 23%); 
  
}


/* What I Adegboyega Have learnt */
/* Learnt the @media query and how to display background pictures and colour*/
@media(min-width: 376px) {
body {
  font-family: "Red Hat Display", sans-serif;
  font-weight: 500, 700, 900;
  font-size: 16px;
  justify-content: center;
  align-items: center;
  background-image: url("./images/pattern-background-desktop.svg");
  background-size: 100% ;
  background-color:  hsl(225, 100%, 94%);
  background-repeat: no-repeat;
}
}

@media(max-width: 375px){
body{
    background-image: url("../images/pattern-background-mobile.svg");
    background-color:  hsl(225, 100%, 94%);
    background-repeat: no-repeat;
}
}
```

## Authors

- Project Website - https://capstone-group-62-project.netlify.app/
- Side Hustle - Adegboyega SH-IT-0075304
- Side Hustle - Osazuwa-Ojo Victory SH-IT-0087734
- Side Hustle - Chukwu Joseph SH-IT-0107838
- Side Hustle - Afolabi Olanshile SH-IT-006681
- Side Hustle - Adama Ojochege John Jnr SH-IT-0029720
- Side Hustle - Kolapo Limah SH-IT-0056971
- Side Hustle - Blessing Umana Eno SH-IT-0097188
- Side Hustle - Onome Okosun SH-IT-0081806
- Side Hustle - Omolusi Ayobami SH-IT-0039919

