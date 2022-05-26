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

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](.implemented-imgs/1.png)
![](.implemented-imgs/2.png)
![](.implemented-imgs/3.png)
![](.implemented-imgs/4.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process
- I started by laying out the HTML structure 
- I gave the divs class names 
- I connected CSS to my HTML page 
- I gave basic styling to the HTML structure 
- I worked on aligning the divs to the center of my page 
- I added hover to some of the texts 
- I started by overlaying the card image with the view icon 
- I added background color to the image overlay 
- I positioned the overlay to fit the card image
- moved the view icon to the center of the image
- tested the card's responsiveness

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

With this project, I gained a better understanding of positioning, and it took some trial and error until I ultimately got it right. I also enjoyed the hover transition effect.

```css
.overlay {
    transition: 0.3s ease;
    position: absolute;
    opacity: 0;
    margin:auto;
    background-color: hsl(178, 100%, 50%);
    border-radius: 10px;
    width: 300px;
    height: auto;
```

### Continued development

I'd like to continue learning CSS because working on this project taught me that there's a lot you can do with just CSS, and I'd like to expand my knowledge. I'm curious about positioning, flexbox, transform, and transition (animation)

### Useful resources

- [Example resource 1](https://www.w3schools.com/howto/howto_css_image_overlay.asp) - This aided in the construction of the card picture overlay's background color and fading effect. I was still able to use some keynotes for the background color despite using this approach for overlaying text on an image.

- [Example resource 2](https://stackoverflow.com/questions/35131965/display-image-in-the-center-of-screen-when-hovering-on-a-link) - This code assisted in the understanding of hover image centering. In the active state, this helped in aligning the view icon in the image's center. Anyone still studying this topic would benefit from it, in my opinion.

## Author

- Website - [Dolapo Olayinka](https://github.com/DolapoOlayinka)
- Frontend Mentor - [@Dolapoolayinka](https://www.frontendmentor.io/profile/dolapoolayinka)
- Twitter - [@dedolap0r](https://www.twitter.com/dedolap0r)
