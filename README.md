# Frontend Mentor - Results summary component solution
![Design preview for the  Result Summary component coding challenge](/design/desktop-preview.jpg)

This is a solution to the [Results summary component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/results-summary-component-CE_K6s0maV). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Screenshot

Evidence for the completed project meeting the challenge requirements:

view the image of my solution following the directory below:

Desktop View - version 1<br>
<a>
  <image src="/assets/images/Desktop-img.png" width="600" height="400">
</a>

***

Mobile View - version 1<br>
<a>
  <image src="/assets/images/Mobile-img.png" width="300" height="600">
</a>

Check the code here:
<!-- Html -->
[Html code for this project](./index.html)
<!-- CSS -->
[CSS code for this project](./styles.css)


### Links

- Live Site URL: [Result Summary Component](https://result-summary-comp-main.netlify.app)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid


### What I learned

In this challenge I learned how useful the :root psuedo-class can be when implemented properly, as my styling consist of using it through out specially with the amount of different colour being used, this is important to keep organized early and as much as possible as this can grow and become un-maintainable if this was a normal project. Further more, I touch on a bit of gradient colour property on this project prompting me tp search on how to implement it properly.

> :root psuedo-class used to organised this project
``` css
:root{
    /* Color */
    --primary-c-red: hsl(0, 100%, 67%);
    --primary-c-yellow: hsl(39, 100%, 56%);
    --primary-c-green: hsl(166, 100%, 37%);
    --primary-c-blue: hsl(234, 85%, 45%);

    --primary-c-red-a: hsl(0, 100%, 67%, .1);
    --primary-c-yellow-a: hsl(39, 100%, 56%, .1);
    --primary-c-green-a: hsl(166, 100%, 37%, .1);
    --primary-c-blue-a: hsl(234, 85%, 45%, .1);

    /* Gradients */
    --gradient-b-slateblue: hsl(252, 100%, 67%);
    --gradient-b-royalblue: hsl(241, 81%, 54%);
    --gradient-b-violetblue: hsla(256, 72%, 46%, 1);
    --gradient-b-persianblue: hsla(241, 72%, 46%, 0);

    /* Neutral */
    --white-n-100: hsl(0, 0%, 100%);
    --white-n-100-a1: hsl(0, 0%, 100%, 0.6);
    --white-n-100-a2: hsl(0, 0%, 100%, 0.4);
    --paleblue-n-200: hsl(221, 100%, 96%);
    --lightlavender-300: hsl(241, 100%, 89%);
    --darkgrayblue-n-800: hsl(224, 30%, 27%);
    --darkgrayblue-n-800-a1: hsl(224, 30%, 27%, 0.6);
}
```

### Continued development

I can probably look in to naming my files clearer and to a more design standard so that when other developers looks at the code they can clearly read how they were implemented. 

I will also need to do some further reading regarding the gradient property amd box shadow as this can come handy in the future. 


### Useful resources

- [Further learning on gradients](https://developer.mozilla.org/en-US/docs/Web/CSS/gradient/linear-gradient) - this has helped with the basic on gradients and can be used for future reference.
- [Further learning on Box Shadows](https://css-tricks.com/almanac/properties/b/box-shadow/) 


## Author

- Frontend Mentor - [@timothy-joseph-collado](https://www.frontendmentor.io/profile/timothy-joseph-collado)

