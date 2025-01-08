# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![Desktop view](<Screenshot (86).png>)
![Mobile view](<Screenshot (85).png>)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Desktop-first workflow

### What I learned

To see how you can add code snippets, see below:

```html
<article class="item">
  <hgroup class="item-heading">
    <img
      src="images/image-jonathan.jpg"
      alt="Photo of Jonathan"
      class="item-img"
    />
    <div>
      <h6 class="name">Jonathan Walters</h6>
      <p class="title">Verified Graduate</p>
    </div>
  </hgroup>
  <p class="item-text">The team was very supportive and kept me motivated.</p>

  <blockquote class="item-quote">
    “ I started as a total newbie with virtually no coding skills. I now work as
    a mobile engineer for a big company. This was one of the best investments
    I’ve made in myself. ”
  </blockquote>
</article>
```

```css
.item:nth-child(1)::before {
  content: "\201d";
  font-size: 30rem;
  position: absolute;
  top: -9rem;
  right: 3.2rem;
  opacity: 0.2;
}
```

```js
const proudOfThisFunc = () => {
  console.log("🎉");
};
```

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

## Author

- Frontend Mentor - [@Abdul-ade](https://www.frontendmentor.io/profile/Abdul-ade)
- Twitter - [@AdeniyiAbdulsa3](https://www.twitter.com/AdeniyiAbdulsa3)
