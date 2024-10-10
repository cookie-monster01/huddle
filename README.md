# Frontend Mentor - Huddle landing page with curved sections solution

This is a solution to the [Huddle landing page with curved sections challenge on Frontend Mentor]

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)



## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Links

- Solution Live URL: https://huddle-mauve-rho.vercel.app/

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

1. HTML Semantics, adding html resets. I also, learnt that to break two words I could use <br>. I also learnt that i could put desktop and mobile background on html, and hide or display them as required via CSS.

```html 
<p>Messages<br/> Sent</p>
```

2. I learnt CSS properties such as: 

      1. gap: to create space between elements without using margins. 
      2. clamp(): I used for responsive font-sizes. 
      3. calc(): I used it for width and also on padding and margins combining it with either min() or max(). 

```css
.intro {
    gap: 1.25em 0;
}

p {
    font-size: clamp(0.85rem, 0.78rem + 0.25vw, 1rem);
}

.subscribe p {
    width: calc(100% - 4vw);
}

form button {
    padding-inline: min(1.5em + 4%);
}

.start-free {
    margin-top: calc(max(6em, 2vh) + 6%); 
}
```

### Continued development

1. I did not understand css properties min() and max() well, also while combining them with calc(). 

2. At 1200px, footer element .subscribe{} shifts to the right edge, but is spaced correctly as I increase the screen size. 

3. Also, there is a horizontal scroll on the webpage, I cannot figure out what is causing it. 

4. I would like to practice Bootstrap. 

## Author
- Frontend Mentor - [@cookie-monster01]