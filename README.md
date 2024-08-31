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

## Overview

### The challenge

Users should be able to:

- View the optimal layout for each page depending on their device's screen size
- See hover states for all interactive elements throughout the site

### Screenshot

![](./preview.jpg)

### Links

- Solution URL: [Frontendmentor](https://www.frontendmentor.io/solutions/modern-art-gallery-znLhOJBrCk)
- Live Site URL: [Vercel](https://art-gallery-pink.vercel.app)

## My process

I decided to focus on a mobile-first design approach, ensuring that all the semantic HTML5 markup was correct before styling anything else. All went well, but I quickly realized that I should not ignore the tablet and desktop designs as they provide information about what I will need on larger viewports (additional HTML markup and grid). This is why, when I started the design for tablet and desktop, I had to add additional markup to manage the increased complexity.

On the tablet version, for a reason that I still cannot explain, the images on the grid overflow their container. However, I realized that there is no point in getting stuck on one project when I could always come back to it later and try to fix it. Instead, I could continue learning from other projects.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

The first thing I learned was to look at all the designs to understand what I will need and to make sure all the HTML markup is there to avoid issues with CSS later on.

Next, I learned how to display an image based on viewport size and resolution (both directly in the HTML using `picture` and `source`, and in the CSS document using `max-width` and `min-resolution`). This was something new to me, and although I need to investigate more to fully understand how it works (rather than relying on examples found online and copying snippets of code), I am happy with the result.

Regarding the image for the map, I decided to use `background-image`. That said, I am pretty sure there is a better way to achieve this result.

I also learned how to create the color effect in the `h1` for the desktop design (thanks to my good old friend ChatGPT), and how to change the color of an SVG file. However, although unknown to me, I am sure there is a different way to change to a specific color on `:hover` other than using `filter: invert(55%) sepia(100%) saturate(626%) brightness(100%)`, but I did not want to spend any more time on this project.

### Continued development

As I mentioned before, I want to make sure that I learn from my previous mistakes. I made a list of different things that I did not know or that went wrong to avoid repeating them in future projects. For example, ignoring the designs for larger viewports because I was focusing on mobile-first, or how to display an image based on screen resolution (among others), are things I need to remember and further investigate to tackle these obstacles in the future.

One of the reasons I did not want to spend too much time on this project is because I want to focus on learning CSS Grid on a deeper level. I paid for [Grid Critters](https://mastery.games/gridcritters/) and having learned Flexbox by playing Flexbox Zombies (from the same site), I know it needs some updates as some of the properties have changed. However, it is an incredible way to learn and remember how it works.

### Useful resources

- [Dash](https://www.kapeli.com/dash) - This is my go-to when I need to find or learn something by reading the official documentation
- [ChatGPT](https://chatgpt.com/) - This is what I use when I am stuck :joy:
- [Grid Critters](https://mastery.games/gridcritters/) - Although it is not free and the content needs to be updated, it is an excellent way to learn CSS and Flexbox

## Author

- GitHub - [Ivan Aguilar](https://github.com/Stigmavlc)
- Frontend Mentor - [@Stigmavlc](https://www.frontendmentor.io/profile/Stigmavlc)
