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
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![](./screenshot.jpg)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- HTML5 
- Css
- flexbox

### What I learned
During this project, I learned to use CSS Flexbox to arrange and center elements on a page. I also learned how (min-height: 100vh) allows the (body) element to occupy at least the full height of the viewport, which helped me vertically center the profile card.

Additionally, I learned to use (padding) to create internal space within a container and (gap) to control the spacing between elements.

One of the most useful things I learned was how to approach responsive design. Instead of simply moving elements when they didn't fit, I learned to analyze the available space and determine whether the issue stemmed from the width, padding, or margins.

For example, I used a media query to reduce the card's internal spacing on smaller screens.

```
css
@media (max-width: 375px) {
  .container {
    padding: 30px;
  }
}
.links {
  width: 100%;
  max-width: 350px;
}
```
### Continued development

I want to continue improving my understanding of responsive design and CSS. I especially want to become better at analyzing a layout and understanding which CSS property is causing a problem instead of changing values randomly.


### Useful resources

Frontend Mentor - I used this platform to practice building a real frontend project from a design.


### AI Collaboration

i used ChatGPT as the only AI tool during this project.

I mainly used it to understand concepts that I found difficult, especially CSS layout, Flexbox, spacing, and responsive design.


## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**
