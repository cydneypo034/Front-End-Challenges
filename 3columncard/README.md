# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The Challenge](#The-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My Process](#my-process)
  - [Built With](#built-with)
  - [What I Learned](#what-i-learned)
  - [Continued Development](#continued-development)
  - [Useful Resources](#useful-resources)
  - [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot


- [Screenshot Plan for Desktop via Sketch](./planningstage/3cardcolumnplan.png)
- [Screenshot Plan for Mobile via Sketch](./planningstage/3cardcolumnmobile.png)

### Links

- Live Site URL: [3ColumnCards Live Site via Netlify](https://3columncards.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [Bulma](https://bulma.io/) - For styles

### What I learned

I learned many things while coding this project and it challenged me to research deeper into the workings of CSS since I chose to work with Bulma as my framework. One of those things I learned was boxes and columns are completely different and one required more steps than the other to get the result I was looking for. Midway through, I found myself changing the boxes to columns since it was a lot to try and make boxes do what columns can do naturally. 

```html
<div class="container">

        <div class="columns is-centered isgapless mb-0">
```

I also learned the importance of structuring out your code before beginning a project. It took me until a few commits in that I needed to wrap the entire columns area into a container. 

Inline styling has also been a big help for me in terms of styling elements individually since many of my classes were able to be styled together. For elements that couldn't be styled together and would save the eyes from scrolling through so much code, I used my stylesheet to create other elements for the classes I had.

```html
<h1 style="color: hsl(0, 0%, 95%); font-size: 65px; text-align: left;">
```

```css
.button-1 {
    color: hsl(31, 77%, 52%);
}

.button-2 {
    color: hsl(184, 100%, 22%);
}

.button-3 {
    color: hsl(179, 100%, 13%);
}
```
Focusing on mobile responsiveness first has been a big lesson I've learned and part of why I am beginning to love front-end development. To implement this into the code was a hasstle for me since I never worked with adjusting web applications for multiple screens before.

```css
@media only screen and (max-width: 1440px) {
    body {
        width: 100%;
    }
}
```
### Continued development

I want to in the future try using other frameworks aside from bulma to help me with the styling. I'd also like to try this project in a JavaScript framework like React, Vue, or Angular. 

### Useful resources

- [CSS Media Queries](https://www.w3schools.com/css/css_rwd_mediaqueries.asp) - This helped me in learning to use sizing of the screen a bit better. I really liked how using @media is like a javascript statement where if x is 600px, then y will turn blue. Funny example, but nonetheless great help.

- [For Bulma Columns to Fix The Gaps In Between](https://bulma.io/documentation/columns/gap/) - This helped me in learning how to utilize the features in Bulma for their columns. Knowing you can fix the gap that's in between each item is good since it responds well when a screen is minimized.

## Author

- Website - [Cydney Pollard](https://cydneypo034.github.io/cyddesport/#/)
- Frontend Mentor - [@cydneypo034](https://www.frontendmentor.io/profile/yourusername)