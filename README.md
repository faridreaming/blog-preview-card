# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Frontend Mentor - Blog preview card solution](#frontend-mentor---blog-preview-card-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [The challenge](#the-challenge)
    - [Screenshot](#screenshot)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
  - [Author](#author)

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![](./screenshot.png)

### Links

- Solution URL: [https://github.com/faridreaming/blog-preview-card](https://github.com/faridreaming/blog-preview-card)
- Live Site URL: [https://faridreaming.github.io/blog-preview-card/](https://faridreaming.github.io/blog-preview-card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS Flexbox
- Modern CSS


### What I learned

Understanding deeper use of semantic html, and use of the clamp() function on width and font size.

```css
& > time {
  font-size: clamp(0.75rem, 0.7rem + 0.2vw, 0.875rem);
}
& > h1 {
  font-size: clamp(1.25rem, 1rem + 1vw, 1.5rem);
  font-weight: 800;
}
& > p {
  font-size: clamp(0.875rem, 0.8rem + 0.25vw, 1rem);
  color: var(--color-gray-500);
}
```

## Author

- Website - [https://faridreaming.my.id/](https://faridreaming.my.id/)
- Frontend Mentor - [@faridreaming](https://www.frontendmentor.io/profile/faridreaming)
- X - [@faridreaming](https://x.com/faridreaming)
- Instagram - [@frddev](https://www.instagram.com/frddev)