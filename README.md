# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62).

## Table of contents

- [Screenshots](#screenshots)

- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
 
## Screenshots
### Desktop Design
![](./screenshot.jpg)
### Mobile Design (executed with pure CSS media queries)
![](./mobile.jpg)


## My process

### Built with

- Pure HTML and CSS
- Mobile-first workflow

### What I learned
- Utilize flex-direction to stack images in a responsive media query, in the desired order.
- Overlaying the image by wrapping it in a div and utilizing a pseudo element.  When doing this it was helpful to use the browser dev tools to explicitly set the height of the wrapper and pseudo element.
- To get the desired color overlay hue it is important to work with both the opacity AND the color hue/saturation.
- Nested elements do not inherit the border radius...