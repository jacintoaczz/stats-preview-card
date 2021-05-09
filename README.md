# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](./assets/finished.png)

### Links

- Solution URL: [Here!](https://github.com/jacintoaczz/stats-preview-card)
- Live Site URL: [Here!](https://jacintoaczz.github.io/stats-preview-card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

One thing i found interesting an very useful when coding the card was the color overlay on the image.
Initially, I was taking the approach of creating a div and use the absolute position + z-index for it to be on the front of the image, but, using the ::before pseudo-element worked pretty well.
I'll take that approach into consideration for future projects.

```css
.card__img::before {
  content: "";
  display: block;
  position: absolute;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
  width: 100%;
  height: 100%;
  background-color: hsla(276.4, 91%, 26.3%, 0.53);
}
```

I also tried to use as much semantic elements as I could, but it probably can be improved quite a bit.

### Continued development

It's very likely that the overlay color and some margins/paddings aren't exactly the same as the design. I need to keep improving on those kind of things.
I'll also keep learning about creating semantic layouts.

**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

## Author

- Frontend Mentor - [@jacintoaczz](https://www.frontendmentor.io/profile/jacintoaczz)
- Twitter - [@jacintoaczz](https://www.twitter.com/jacintoaczz)
