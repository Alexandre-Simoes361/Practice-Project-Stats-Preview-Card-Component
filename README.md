# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

<img src="Images/Screens/Screenshot Desktop.png" alt="Desktop Screenshot" />
<img src="Images/Screens/Screenshot Mobile.png" alt="Mobile Screenshot" />

### Links

- Solution URL: [Github Repo](https://github.com/Alexandre-Simoes361/Practice-Project-Stats-Preview-Card-Component)
- Live Site URL: [Live Site](https://resilient-elf-8cb33b.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I took this project on because I thought it would be a nice way to both work on getting acquainted with the CSS blend mode and because it was the perfect opportunity to try out using the html <picture> element that I wasn't able to get to work on my first project for dynamically changing pictures according to the screen size. I learned a great deal about it, learned why the element is useful and I also learned that its use instead of using various <img> elements to be handled by CSS media queries later carries the disadvantage of having the images be much harder to manipulate, which was what gave me the most trouble in this project, I couldn't get the picture to act how I wished it to act. It was a good learning experience in this case, because I learned some of the various reasons why an image might refuse to fill a parent <div> while working on debugging it. As for the blend mode, I learned some of the various approaches one can have while employing it, and I'd say I settled on the one that seemed more intuitive to me, which in this case involved using a parent <div> as a mask to give the picture the desired color. This was also the first project I ever completed where I used relative units only.

### Continued development

I got some very good advice by Grace Snow regarding kinks to hammer out in the way I write both my CSS and HTML, and I incorporated it into my final solution, which actually allowed me to delete a good chunk of my code which became unnecessary, and in the future this is what I intend to keep working on, writing the shortest and best thought out code I possibly can.

## Author

- Linkedin - [Alexandre Simões](https://www.linkedin.com/in/alexandre-sim%C3%B5es-21198a223/)
- Frontend Mentor - [@Alexandre-Simoes361](https://www.frontendmentor.io/profile/Alexandre-Simoes361)

## Acknowledgments

Thank you to Grace Snow for giving me some very good pointers regarding my HTML and CSS, the part about just redefining the root inside my media query to switch font sizes especially was gold. Another thank you to Chamu for all the help with the misbehaving image, and finally a big thank you to Alex K Marshall for all the help with switching over to relative units.