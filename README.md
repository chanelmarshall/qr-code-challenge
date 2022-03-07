# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

My goal with this challenge was to test my foundational knowledge in HTML5 and CSS. I know and have used Bootstrap and have heard of Materialize, but I wanted to avoid using them to see how well I could replicate the example using my own knowledge. I feel my replica is pretty close to the original and am proud of my result.

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

My process with this challenge was to take it step by step, starting with what I knew would be easiest to replicate (colors, fonts, etc) and finish with the harder parts to replicate (position, margin, padding, etc).

I also worked down the structure of the page to give some kind of order to putting it together.

### Built with

- HTML5 markup
- CSS custom properties
- Media query for mobile responsiveness

### What I learned

I learned how to properly add a media query to fit what I was wanting to happen for the responsiveness of the design. I knew the width for mobile I was wanting to meet (375px), but I had to figure out how to meet that width while having everything bigger than it be the original CSS code.

The other thing I learned is how to use and manipulate box-shadow. It was definitely confusing, but thanks to MDN, I was able to figure out how to set it to be similar to how the example looked.

See code snippets below:

```css
.qr-scan {
  box-shadow: -10px 10px 6px hsl(212, 45%, 88%);
}

@media (max-width: 375px) {}
```

### Continued development

I know I could use more development in working with CSS layout as far as margins and padding. I'm sure I could have used flexbox, grid, or both for this challenge, but because I'm not as confident in using those, I skipped it this go around.

Even though this challenge didn't have as many components that caused need for different class selectors, I know in the future I won't be able to rely on tag selectors as much.

### Useful resources

- [CSS Tricks](https://www.css-tricks.com/almanac/properties/b/box-shadow/) - This helped me for finding exactly how I wanted to make the box shadow.
- [MDN Docs](https://www.https://developer.mozilla.org/en-US/) - This also helped with understanding the values for the box-shadow. It also helped me understand the values for hsl as I have never used that for colors before.

## Author

- Chanel Marshall
- Frontend Mentor - [@chanelmarshall](https://www.frontendmentor.io/profile/chanelmarshall)
