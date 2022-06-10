# Frontend Mentor - NFT preview card component solution - Yet to update

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./screenshot.jpg)

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it. 

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [React](https://reactjs.org/) - JS library
- [Next.js](https://nextjs.org/) - React framework
- [Styled Components](https://styled-components.com/) - For styles

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

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

If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.

**Note: Delete this note and the content within this section and replace with your own learnings.**

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

### Useful resources

- [Example resource 1](https://www.example.com) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
- [Example resource 2](https://www.example.com) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.

**Note: Delete this note and replace the list above with resources that helped you during the challenge. These could come in handy for anyone viewing your solution or for yourself when you look back on this project in the future.**

## Author

- Website - [Ruban Gino Singh](https://www.rubangino.in)
- Frontend Mentor - [@Ruban2205](https://www.frontendmentor.io/profile/Ruban2205)
- Twitter - [@rubangino](https://www.twitter.com/rubangino)

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

## Acknowledgments

Credit: Frontendmentor.io
