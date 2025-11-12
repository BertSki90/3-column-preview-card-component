# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

Estimated Time: 10hrs

Actual Time: 6:13 hrs

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./screenshot.jpg)

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it.

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

### Links

- Solution URL: [Github @BertSki90](https://github.com/BertSki90/3-column-preview-card-component)
- Live Site URL: [Github Pages @BertSki90](https://bertski90.github.io/3-column-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

When rounding the corners of the the .car-model-preview-card class using the border-radius property it does not apply to the children elements. The children elements will spill over the rounded edge of .car-model-preview-card giving it a pointed edge. By applying the overflow:hidden; property/value this prevents the children elements form overflowing the parent element. See below:

```html
<body>
    <header>
      <h1 class="sr-only">3 Column Preview Card Component</h1>
    </header>
    <main>
      <!-- CARD -->
      <article class="car-model-preview-card">
        <!-- SEDAN -->
        <section class="car-model-sedan" aria-labelledby="sedan-title">
          <!-- REST OF CODE -->
      </article>
    </main>
```

```css
.car-model-preview-card {
  border-radius: 0.6em;
  margin-block-start: 2em;
  /* v Prevents children elements from overflowing v */
  overflow: hidden;
  max-width: 21.8em;
}
```

### Continued development

To keep building upon my HTML and CSS skills by continuing my studies and applying the advice I get from the community.

### Useful resources

N/A

## Author

- Github Profile - [@BertSki90](https://github.com/BertSki90)
- Frontend Mentor - [@BertSki90](https://www.frontendmentor.io/profile/BertSki90)
- X - [@BertSki90](https://x.com/BertSki90)

## Acknowledgments

Thank you to Frontend Mentor, FreeCodeCamp, and the coding communities. I am a skilled trades worker that is learning to code. Without these supports I would have never been able to find out and learn about coding. My experience has been magnificient!
