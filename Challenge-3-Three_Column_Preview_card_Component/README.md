# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![image](https://user-images.githubusercontent.com/63004130/173406363-92031ece-5a93-4c54-bbc7-79863499d5f2.png)

### Links

- Solution URL: [https://github.com/Ruban2205/FrontEndMentor-Solutions/tree/main/Challenge-3-Three_Column_Preview_card_Component](https://github.com/Ruban2205/FrontEndMentor-Solutions/tree/main/Challenge-3-Three_Column_Preview_card_Component)
- Live Site URL: [https://ruban2205.github.io/FrontEndMentor-Solutions/Challenge-3-Three_Column_Preview_card_Component/3-column-preview-card-component-main/index.html](https://ruban2205.github.io/FrontEndMentor-Solutions/Challenge-3-Three_Column_Preview_card_Component/3-column-preview-card-component-main/index.html)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

```html
<h1>Some HTML code I'm proud of</h1>


  <div class="container">
    <div class="container-left">
      <img src="assets/images/icon-sedans.svg" alt="">
      <h1 class="card-title">Sedans</h1>
      <p class="card-body">Choose a sedan for its affordability and excellent fuel economy. Ideal for cruising in the city
      or on your next road trip.</p>
      <button>Learn more</button>
    </div>

    <div class="container-middle">
      <img src="assets/images/icon-suvs.svg" alt="">
      <h1 class="card-title">SUVs</h1>
      <p class="card-body">Take an SUV for its spacious interior, power, and versatility. Perfect for your next family vacation
      and off-road adventures.</p>
      <button>Learn more</button>
    </div>

    <div class="container-right">
      <img src="assets/images/icon-luxury.svg" alt="">
      <h1 class="card-title">Luxury</h1>
      <p class="card-body">Cruise in the best car brands without the bloated prices. Enjoy the enhanced comfort of a luxury
      rental and arrive in style.</p>
      <button>Learn more</button>
    </div>
  </div>
```
```
CSS
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

.container {
    width: 100%;
    height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
    margin: auto;
}

.container-left{
    height: 70%;
    width: 22rem;
    background-color: var(--Bright-orange);
    padding: 3rem;
    border-radius: 8px 0 0 8px;
}

.container-middle{
    height: 70%;
    width: 22rem;
    background-color: var(--Dark-cyan);
    padding: 3rem;
}

.container-right{
    height: 70%;
    width: 22rem;
    background-color: var(--Very-dark-cyan);
    padding: 3rem;
    border-radius: 0 8px 8px 0;
}

.card-title{
    font-family: var(--font1);
    font-weight: 700;
    margin: 2rem 0;
    text-transform: uppercase;
    color: white;
}

.card-body{
    font-family: var(--font2);
    font-weight: 400;
    font-size: 15px;
    margin: 0 0 10rem 0;
    color: white;
}
```

## Author

- Website - [Ruban Gino Singh](https://www.rubangino.in)
- Frontend Mentor - [@Ruban2205](https://www.frontendmentor.io/profile/Ruban2205)
- Twitter - [@rubangino](https://www.twitter.com/rubangino)

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

## Acknowledgments

Credit: [Frontendmentor.io](https://frontendmentor.io/)

