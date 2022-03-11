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

![](/images/Screenshot%20FrontendMentor%20NFT%20preview%20card%20component.png)

### Links

- Solution URL: [Solution code on Github](https://github.com/Irving2797/nft-preview-card-component-main)
- Live Site URL: [Live Site](https://irving2797.github.io/nft-preview-card-component-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

So I was so confused because the div I used for the overlay was not inside of the container, therefore the hover was not working. I just needed to put it inside the container, rookie mistake but glad I made it.

```html
<div class="container">
    <img id="main_img" src="images/image-equilibrium.jpg" alt="Equilibrium">
        <div class="viewoverlay"><img src="images/icon-view.svg"></div>
</div>
```

I always forget that I can group classes and elements this way
```css
.container:hover .viewoverlay,
.container:hover .viewoverlay img {
    display: unset;
}
```

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

### Useful resources

- [W3Schools - How TO - Image Hover Overlay](https://www.w3schools.com/howto/howto_css_image_overlay.asp) - I was clueless about the hover on the image part so this was very helpful
- [Image Hover Text Overlay Effect with HTML & CSS - Web Design Tutorial](https://www.youtube.com/watch?v=exb2ab72Xhs&ab_channel=dcode) - This video was huge on helping me with the hover part

## Author

- Github - [Irving De León](https://github.com/Irving2797)
- Frontend Mentor - [@Irving2797](https://www.frontendmentor.io/profile/Irving2797)