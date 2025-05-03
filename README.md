# Frontend Mentor - Calculator app solution

This is my solution to the [Calculator app challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/calculator-app-9lteq5N29). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- See the size of the elements adjust based on their device's screen size
- Perform mathmatical operations like addition, subtraction, multiplication, and division
- Adjust the color theme based on their preference
- **Bonus**: Have their initial theme preference checked using `prefers-color-scheme` and have any additional changes saved in the browser

### Screenshot

![](./screenshot.jpg)

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it. 

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

### Links

- Solution URL: [Link to Git repository](https://github.com/KaerailearS/FrontEndMentor-Calculator)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

Initially built this very early on using "onclick" attribute on each button.
Revisited a bit later, changed all buttons from "onclick" to having eventListeners on each.
Revisited again, changing eventListeners to be on the parent container instead, using event delegation to further reduce lines of code.


### Continued development

Error message functionality is something that I need to figure out better, current iteration only works with proper errors, but if the result is "undefined" it wont do the automatic reset.

### Useful resources

- [Google](https://www.google.com/) - Googling anything I had issues with, didn't understand or dealt with for the first time helped immensely.
- [ChatGPT](https://chatgpt.com/) - Asking ChatGPT for code optimizations, or having it explain some systems, methods or other JavaScript related stuff.
- [MDN Web Docs](https://developer.mozilla.org/en-US/) - MDN Web Docs popped up alot from Google searches, and has an immense amount of information for web development.
- [W3Schools](https://www.w3schools.com/) - Similar to MDN Web Docs, very common result from Google searches, and also hosts alot of relevant information.

## Author

- GitHub - [KaerailearS](https://github.com/KaerailearS)

## Acknowledgments

This was done 99.9% solo, but I had a few pointers from my colleagues at the workshop when it came to design colours.

