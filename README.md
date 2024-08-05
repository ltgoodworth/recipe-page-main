# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

This was my first Frontend Mentor challenge. Having just completed basic courses in html and CSS this project
was a good opportunity to test what I have learned so far.

### Links

- Solution URL: https://github.com/ltgoodworth/recipe-page-main
- Live Site URL: https://ltgoodworth.github.io/recipe-page-main/

## My process

### Built with

- HTML5
- CSS
- Flexbox
- Git
- Github

### What I learned

I was able to complete a lot of this project from memory, using everything I have learnt so far. There were a few things I had to look up. The main thing was how to style the bullets/numbers on a html list. The best solution that I found was to style the list elements in their entierty to style nthe bullets/numbers and then use a span tag to restyle the text:

```html
<li><span class="list-text"><strong>Beat the eggs:</strong> In a bowl, beat the eggs with a pinch of salt and pepper until they are well mixed.
    You can add a tablespoon of water or milk for a fluffier texture.</span></li>
```

```css
.list-text {
    color: hsl(24, 5%, 18%);
    font-weight: normal;
    padding-left: 15px;
}
```

### Continued development

I am now starting to learn JavaScript and it will be important for me to not lose sight of/forget what I have already learned with html and CSS. Sometimes simple solutions are the best option and overthinking some of the CSS styling leads me to repeat/write lengthy coding. I will aim to continue refiing this as I continue learning.

### Useful resources

- https://stackoverflow.com/questions/6457059/customize-list-item-bullets-using-css - This helped me figure out how to set my list styling.
- https://www.w3schools.com/html/html_tables.asp - This w3schools page helped me remember how to create a table in order to more closely match the Nutrients section styling.

## Author

- Github - ltgoodworth (https://github.com/ltgoodworth)
- Frontend Mentor - [@ltgoodworth](https://www.frontendmentor.io/profile/ltgoodworth)

## Acknowledgments

Shoutout to my coding mentor DennieCodes! He set this as my first coding challenge and provided suggestions to help optimize my styling syntax along with demonstrating how git works when multiple developers are working on separate branches of code.
