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


## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![](/display.png)


### Links

- Solution URL: [GitHub](https://github.com/khome-j/Social-Links-Page.git)
- Live Site URL: [GitHub](https://khome-j.github.io/Social-Links-Page/)

## My process
I achieved a responsive layout for this webpage using CSS flexbox. The body element acts as the flex container, and I set its display property to flex. This allows me to arrange the child elements of the body in a flexible manner. To control the width of these child elements, I used the flex-basis property with a value of 30%. This ensures they will all take up 30% of the available space within the body container and adjust accordingly on various screen sizes.

```css
body {
    background-color: hsl(0, 0%, 8%);
    font-size: 1.4em;
    font-family: Inter;
    display: flex;
}

.container {
    background-color: hsl(0, 0%, 12%);
    flex-basis: 30%;
    margin: 10em auto;
}
```
To enhance the responsiveness of the layout, I've implemented a media query that targets screens with a minimum width of 500 pixels. Within this media query, I adjust the flexbox properties of the elements. By setting flex-grow: 0, I ensure they won't grow to fill any extra space available in the container. Additionally, I set flex-shrink: 1 to allow them to shrink proportionally if the screen size becomes smaller and there's not enough space to display them all at their full width.

Here's the code sample demonstrating the use of flexbox with media queries, based on the explanation you provided:

```css
@media screen and (min-width: 500px) {
    .container {
        flex: 0 1;
        /* max-width: max-content; */
        min-height: max-content;
        /* margin: 5em auto 10em auto; */
    }
}
```

 
### Built with
<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>

<img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"/>



### What I learned
Gearing up for a responsive webpage design! Flexbox is my weapon of choice for this project. I'm actively learning how to use it effectively for both containers and flex items to achieve a user-friendly layout that adapts to different screen sizes."

```css
body {
  display: flex;
}
```

### Continued development

On my journey to becoming a better web developer, I've been blown away by the power of flexbox. Now I'm focusing on mastering flexbox, grid layout, and building responsive webpages in general.


## Author

- Frontend Mentor - [@khome-j](https://www.frontendmentor.io/profile/khome-j)
- Twitter - [@khome-j](https://www.twitter.com/yourusername)



