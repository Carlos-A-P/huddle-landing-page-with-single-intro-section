# 3-column preview card component

- Live website -(https://carlospwd-four-card-feature-section.netlify.app/)

## Table of contents

- [The challenge](#the-challenge)
- [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)

### The challenge

Users should be able to:

- View the optimal layout for the section depending on their device's screen size

## My process

### Screenshot

![result](https://user-images.githubusercontent.com/85038929/125175767-1c7f4400-e183-11eb-8fc9-0033ab8a2a56.JPG)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

I learned how to format the two cards on top of each other with the help of grid rows. I thought it would be more difficult but after some visualizing I was able to complete the project quickly

```css
.boxes {
	display: grid;
	grid-template-areas: "card-1 stacked-boxes card-4";
	grid-template-columns: repeat(3, 1fr);
	grid-gap: 30px;
	margin-top: 10px;
}

.card-1,
.card-4 {
	margin: auto 0;
}
```

### Questions

- Is there another easier way to complete this project?
- Is my method logical?

### Useful resources

- [Build a Responsive Grid CSS Website Layout From Scratch](https://www.youtube.com/watch?v=moBhzSC455o&ab_channel=TraversyMedia) - This helped me understand how to use grids and flexbox to organize my website. I also learned about some new vs code extentions such as prettier which helped make my code look neat and organised.

## Author

- Website - [Carlos Perez](https://www.site.com)
- Frontend Mentor - [@Carlos-A-P](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@WDCarlosP](https://www.twitter.com/WDCarlosP)
