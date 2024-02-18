# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

  - [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [My process](#my-process)
  - [Built with](#built-with)
  - [Other tools used](#other-tools-used)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)


## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![<img src="images/screenshot1.png" alt="screenshot-Blog-preview-card-desktop-view">]
![<img src="images/screenshot2.png" alt="screenshot-Blog-preview-card-mobile-view">]


### Links

- Solution URL: [https://github.com/andr-ch/Blog-preview-card.git]
- Live Site URL: [https://andr-ch.github.io/Blog-preview-card/]

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow



### Other tools used:
- Pesticide extension -> this is perfect to outline eacth element to better see the placement on the page  
- Developer tools -> available on any browser and is ideal for experimenting with changes to your page without affecting your code


### What I learned


1.Adding Box Shadow Effect on Main Container Click:

```css
main:active {       
    color: rgb(5, 3, 0);
    opacity: 1;
    box-shadow: 15px 17px 0px 0px rgba(0,0,0,0.75);    
}
```

2.Implementing Responsive Behavior for Mobile Devices:
```css
@media (max-width: 767px) {
    main {}
}
```

3.Adjusting Main Container Size for Mobile Devices using calc() Function:
```css
width: calc(100% - 40px);
```

4.Utilizing box-sizing Property to Include Padding and Borders:
```css
@media (max-width: 767px) {
    main {}
}
	box-sizing: border-box; 
```

5.Constraining Image Size to Fit Container:
```css
.code-pic {
        max-width: 85.5%; 
        min-width: 301px;
}
```

6.Ensuring the image's responsiveness by allowing its height to adjust automatically:
```css
.code-pic {
height: auto;
}
```

7.Media Queries for Font Size Adjustment:
```css
.text-1, .date {
        font-size: 13.5px;
}
```

8.Aligning Text Near Profile Using Relative Positioning:
```css
.person-name {
    position: relative;
    left: 48px;
    bottom: 47px;
    margin-right: 76px;
}
```


### Useful resources

- [Example resource 1](https://developer.mozilla.org/en-US/) - This resource proved valuable to me when I had to search for specific HTML or CSS elements for my project. I highly recommend this site to anyone looking to initiate their learning journey in HTML and CSS. It also offers a comprehensive set of learning materials tailored for novice developers and students.

- [Example resource 2](https://www.w3schools.com/) - This is additionally valuable for refining coding skills, and the "try me" section is beneficial if you wish to observe the code in action.

- [Example resource 3](https://www.sitepoint.com/) - Good to find a range of resources including articles, tutorials, books, and online courses covering various topics such as HTML, CSS, JavaScript, PHP, UX/UI design, and more.

- [Example resource 4](https://www.cssmatic.com/box-shadow/) - Helpful for experimenting and generating CSS styles such as border radius, box shadow, and more.




