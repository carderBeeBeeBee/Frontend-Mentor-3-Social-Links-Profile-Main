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
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

[Desktop](./screenshots/desktop-screenshot.png)
[Mobile](./screenshots/mobile-screenshot.png)

### Links

- Solution URL: [Add solution URL here](https://carderbeebeebee.github.io/frontend-mentor-3-social-links-profile-main)
- Live Site URL: [Add live site URL here](https://carderbeebeebee.github.io/frontend-mentor-3-social-links-profile-main)

## My process

This clearly required a mobile-first approach and didn't even need media queries to work correctly. Overall very straightforward! I focusd on getting the CSS correct first, then just went back and added some JS for the buttons.

### Built with

- Semantic HTML5 markup
- Custom font face
- Mobile-first workflow

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned
```html - the <q> tag, and its limitations
<q>"Front-end developer and avid reader."</q>
```
```css - making the main card dynamically resize correctly using both width and max-width
.container {
  width: 90%;
  max-width: 400px;
}
```
```js - a neat function that sends a dynamic alert based on whichever button was clicked
function buttonClick(btnId) {
    console.log(btnId);
    alert("This would open a link to Jessica's " + document.getElementById(btnId).innerHTML + " profile.");
}
```

### Continued development

This was a good opportunity to practice some basics, and also let me use a bit of JavaScript. It would be great to have an opportunity to use some more complex JS in a challenge like this.

### Useful resources

- [W3 Schools](https://www.w3schools.com/) - Always helpful for reference!

## Author

- Website - [carderBee](https://carderbeebeebee.github.io)
- Frontend Mentor - [@carderBee](https://www.frontendmentor.io/profile/carderBee)

## Acknowledgments

[Stack Overflow](https://stackoverflow.com/questions/10291017/how-to-get-id-of-button-user-just-clicked) User GeckoTang on Stack Overflow for demonstrating the use of this.id!
