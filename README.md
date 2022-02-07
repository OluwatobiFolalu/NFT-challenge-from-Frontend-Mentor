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
- 

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![images/Sceenshot9).png](./screenshot.jpg)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox


### What I learned

I got a better grasp of how to use the flexbox, as well as how to change text and image properties of linked items

```css
.cube{
    width: 320px;
    margin: 20px 20px 0 20px;
    border-radius: 10px;
    opacity: 1;
    transition: .5s ease;
    backface-visibility: hidden;
    background-color: hsl(178, 100%, 50%);
}

.view{
    transition: .5s ease;
    opacity: 0;
    position: absolute;
    top:50%;
    left: 50%;
    transform: translate(-50%, -50%);
    -ms-transform: translate(-50%, -50%);
    background-color: rgba(0, 255, 247, .3);
    padding: 36.5%;
    border-radius: 10px;
}

.image:hover .cube {
    opacity: 0.3;
}

.image:hover .view{
}
```

### Continued development

I need to put more effort into mastering the flexbox property as well as how to create an overlay effect on images

### Useful resources

- [https://www.w3schools.com/howto/tryit.asp?filename=tryhow_css_image_overlay_opacity]- This helped me to create theoverlay effective for the image's active state. I'm still trying to get a good grasp of this pattern but I will continue to use it going forward.


## Author

- Website - [Folalu!]
- Frontend Mentor - [@Folalu!](https://www.frontendmentor.io/profile/Folalu!)
- Twitter - [@McphilzT](https://www.twitter.com/McphilzT)


