# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ).

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


## Overview

### The challenge

- Build out the project to the designs provided
  - [Desktop Design](challenge/desktop-design.jpg)
  - [Mobile Design](challenge/mobile-design.jpg)

### Screenshot

- [Desktop Preview of my solution](solution-screenshots/desktop-preview.png)
- [Mobile Preview of my solution](solution-screenshots/mobile-preview.png)

### Links

- Solution URL: [FrontEnd Mentor: My Solution](https://www.frontendmentor.io/solutions/profile-card-component-using-flexbox-TSRY-NyU1)
- Live Site URL: [GitHub Page: Profile Card Component](https://anoshaahmed.github.io/fem05-profile-card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

It took me some trial and error to achieve the right results when it came to:

- the background; but I learned more about the background-position property
  ```css
  body {
      background-color: var(--cyan);
      background-image: url(images/bg-pattern-top.svg), url(images/bg-pattern-bottom.svg);
      background-repeat: no-repeat;
      background-position: right 52vw bottom 35vh, left 48vw top 52vh;
  }
  ```

- the header of the profile card; but using the following properties worked:
  ```css
  main {
      background-image: url(images/bg-pattern-card.svg);
      background-repeat: no-repeat;
      background-position: contain;
  }
  ```

- shadow of the profile card
  ```css
  main {
      box-shadow: 0px 40px 100px hsla(229, 23%, 23%, 0.3);
  }
  ```

### Continued development

I want to work on

- Fluidity
- Responsiveness
- Mobile-first Workflow

## Author

- Website - [Anosha Ahmed](https://www.anoshaahmed.com) - Not up at the moment, but will be soon.
- Frontend Mentor - [@anoshaahmed](https://www.frontendmentor.io/profile/anoshaahmed)
- Twitter - [@anosha1ahmed](https://www.twitter.com/anosha1ahmed)
