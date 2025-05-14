# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- See hover and focus states for all interactive elements on the page

### Screenshot

![](.\assets\images\FireShot Capture 002 - Frontend Mentor - Social links profile - [127.0.0.1].png)
![](.\assets\images\FireShot Capture 001 - Frontend Mentor - Social links profile - [127.0.0.1].png)

the fireshots are in the assets/images/ path.

### Links

- Solution URL: [Add solution URL here](https://github.com/nachar99/social-links-profile-main)
- Live Site URL: [Add live site URL here](https://social-links-profile-main-livid.vercel.app/)

## My process

### Built with

- **Semantic HTML5** for meaningful structure
- **CSS custom properties** for centralized theming (colors, font sizes)
- **Flexbox** for vertical and horizontal centering of card contents
- **Mobile-first workflow** with responsive sizing and spacing
- **CSS pseudo-classes** (`:hover`, `:focus`, `:active`) for interactive states

### What I learned

This project reinforced several front-end fundamentals:

- **Semantic structure:** I used `<header>`, heading tags, and `<p>` elements to give the profile card clear document hierarchy.

  ```html
  <h1 id="name">Jessica Randall</h1>
  <p id="bio">"Front-end developer and avid reader."</p>
  ```

- **Flexbox centering:** I applied Flexbox on the card container to vertically and horizontally center its contents.

  ```css
  .box {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
  }
  ```

- **CSS custom properties:** I defined a set of CSS variables for colors and fonts to keep the theme consistent and easy to update.

  ```css
  :root {
    --clr-bg: hsl(0, 0%, 8%);
    --clr-card: hsl(0, 0%, 12%);
    --clr-accent: hsl(75, 94%, 57%);
    --clr-text: hsl(0, 0%, 100%);
  }
  ```

- **Interactive states:** I implemented `:hover`, `:focus`, and `:active` pseudo-classes on the social buttons to give clear visual feedback and improve accessibility.

  ```css
  .buttons:hover,
  .buttons:focus {
    background-color: var(--clr-accent);
    color: var(--clr-bg);
    outline: none;
  }
  .buttons:active {
    transform: scale(0.98);
  }
  ```

### Continued development

Explore CSS Grid for more complex two-dimensional layouts.

Improve accessibility by adding ARIA labels and keyboard navigation hints.

Add theming toggles (light/dark mode) using JavaScript to swap CSS custom-property values.

## Author

- Website - [Abdulrahman Al-Nachar](https://github.com/nachar99)
- Frontend Mentor - [@nachar99](https://www.frontendmentor.io/profile/nachar99)
