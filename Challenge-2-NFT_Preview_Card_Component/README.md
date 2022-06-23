# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

![image](https://user-images.githubusercontent.com/63004130/173112260-1d09eb06-aa20-4602-9ef9-4c7e92350cf4.png)

### Links

- Solution URL: [https://github.com/Ruban2205/FrontEndMentor-Solutions/tree/main/Challenge-2-NFT_Preview_Card_Component](https://github.com/Ruban2205/FrontEndMentor-Solutions/tree/main/Challenge-2-NFT_Preview_Card_Component)
- Live Site URL: [https://ruban2205.github.io/FrontEndMentor-Solutions/Challenge-2-NFT_Preview_Card_Component/NFT-Preview-card-component/index.html](https://ruban2205.github.io/FrontEndMentor-Solutions/Challenge-2-NFT_Preview_Card_Component/NFT-Preview-card-component/index.html)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

```html
<h1>Some HTML code I'm proud of</h1>

  <div class="title-container">
      <h1 class="card-title">Equilibrium #3429</h1>
      <p class="card-text">Our Equilibrium collection promotes balance and calm.</p>
    </div>

    <div class="card-body">
      <div>
        <div class="etherum-price">
          <img src="./images/icon-ethereum.svg" alt="ethereum">
        </div>
        <h4 class="coin-name">0.041 ETH</h4>
      </div>

      <div>
        <div class="etherum-days">
          <img src="./images/icon-clock.svg" alt="clock">
        </div>
        <h4 class="coin-day">3 days left</h4>
      </div>
    </div>

    <div class="line"></div>

    <div class="card-footer">
      <div class="footer-section">
        <img src="./images/image-avatar.png" alt="Jules-wyvern-Image">
      </div>
      <p class="footer-text">Creation of <a class="footer-name" href="#">Jules Wyvern</a></p>
    </div>
  </div>
```
```css
.card-title {
    font-size: 1.45em;
    margin: 25px 0 15px;
    color: var(--White);
}

.card-title:hover {
    color: var(--Cyan);
    cursor: pointer;
}

.card-text {
    font-size: .90em;
    color: var(--Soft-blue);

}

/* Card Body */
.card-body {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    margin: 1rem 0 .40rem 0;
}

.card-body div {
    display: flex;
    justify-content: space-between;
}

.coin-name {
    color: var(--Cyan);
}

.coin-day {
    color: var(--Soft-blue);
}

.etherum-price,
.etherum-days {
    margin-right: 1rem;
}

/* Card Horizantal Line */
.line {
    width: 100%;
    height: .5px;
    background-color: var(--Soft-blue);
    /* border: .5px solid; */
    margin: .20rem 0;
    display: inline-block;
}

/* Card Footer Section */
.card-footer {
    display: flex;
    flex-direction: row;
    justify-content: flex-start;
    margin: .50rem 0 0 0;
}

.footer-section img{
    width: 100%;
    border: 1px solid var(--White);
    border-radius: 50%;
}

.footer-section{
    width: 18%;
}

.footer-text {
    margin: auto 1rem;
    color: var(--Soft-blue);
    font-size: 18px;
}

.footer-name {
    color: var(--White);
}

.footer-name:hover {
    color: var(--Cyan);
}

```

## Author

- Website - [Ruban Gino Singh](https://www.rubangino.in)
- Frontend Mentor - [@Ruban2205](https://www.frontendmentor.io/profile/Ruban2205)
- Twitter - [@rubangino](https://www.twitter.com/rubangino)

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

## Acknowledgments

Credit: [Frontendmentor.io](https://frontendmentor.io/)
