# Frontend Mentor - Minimalist portfolio website solution

This is a solution to the [Minimalist portfolio website challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/minimalist-portfolio-website-LMy-ZRyiE). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for each page depending on their device's screen size
- See hover states for all interactive elements throughout the site
- Click the "About Me" call-to-action on the homepage and have the screen scroll down to the next section
- Receive an error message when the contact form is submitted if:
  - The `Name`, `Email Address` or `Message` fields are empty should show "This field is required"
  - The `Email Address` is not formatted correctly should show "Please use a valid email address"

### Links

- Solution URL: [https://www.frontendmentor.io/solutions/minimalist-portfolio-page-with-sass-and-bootstrap-no-js-needed-b57IL3fLO
- Live Site URL: https://dev-tron.github.io/Minamalist-portfolio-website/

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [Styled Components](https://styled-components.com/) - For styles
- SASS
- Bootstrap

### What I learned

In this code snippet, learned how to properly use the picture tags to display images according to screen sizes.

To see how you can add code snippets, see below:

```html
<picture>
          <source srcset="/images/homepage/desktop/image-homepage-profile.jpg" media="(min-width:1440px)">
          <source srcset="/images/homepage/tablet/             image-homepage-profile.jpg" media="(min-width:768px)">
          <img src="/images/homepage/mobile/  image-homepage-profile.jpg" alt="man-side-face" class="mb-4">
</picture>
```

In this example below, I learned how to order my flex-items and make them appear at different screen sizes.

```css
.left-align {
    @media #{$brk-tab} {
    padding: 5% 10% 5% 0;
    order: -1;
    }
}
```

### Continued development

Overall, this project was very insightful. I think I learned mostly everything I know about grid, flex-box, and bootstrap just from this one project. Only thing I feel I need to do differently in the future is to create my own navbars without using bootstraps. then I wont have to add a new navbar that displays the text at tablet screens and up.

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - (https://www.frontendmentor.io/profile/Dev-Tron)
- Twitter - (https://www.twitter.com/@BrownKeytron)# Minamalist-portfolio-website
