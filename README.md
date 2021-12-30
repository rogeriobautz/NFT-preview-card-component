# Frontend Mentor - NFT preview card component solution

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
- Mobile-first workflow

### What I learned

I learned more about flexbox, overlay, media queries and inherit of some css properties.

I need a different opacity from eye icon on the overlay and i found a good solution using rgba on the parent-element. In this case, the child element does not inherit the opacity:

```css
.parent-element { rgba(13, 228, 221, 0) }
.child-element { opacity:0; }

/* The project requires a higher opacity for the child element */
.parent-element:hover { rgba(13, 228, 221, 0.4) }
.child-element:hover { opacity:.9; }
```

### Continued development

I will continue to study about CSS display and responsiveness and building web projects to practice and start a JavaScript Course

### Useful resources

- [Web Dev Simplified](https://www.youtube.com/c/WebDevSimplified) - A really good channel to new web developers

- [Google](https://www.google.com/) - Just put your problem along with the stack there like "overlay opacity css" and you be in good hands.

- [StackOverFlow](https://stackoverflow.com/) - Very helpfull but you need to be careful because you will see a lot of responses that are outdated and you have to dig the best answer to your problem.

## Author

- [Rogério Bautz](https://github.com/rogeriobautz)
- Frontend Mentor - [@rogeriobautz](https://www.frontendmentor.io/profile/rogeriobautz)
- Instagram - [@rogerio.bautz](https://www.instagram.com/rogerio.bautz)
