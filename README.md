# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Frontend Mentor - QR code component solution](#frontend-mentor---qr-code-component-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
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

Here you will find what i learnt throughout my first challenge from frontend-mentor, what tools i used in accomplishing the project and some useful articles that can help anyone achieve his journey in becoming a better developer.

### Screenshot

<img src="./Screenshot/Desktop Preview.png">
<img src="./Screenshot/Mobile Preview.png">

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties

### What I learned

Before completing this project i had some difficulties with CSS positioning which was my major problem but after this project i have gotten an increase in knowledge on how to do CSS positioning in a slightly better way and am sure by the end of completing all the projects given by frontendmentor.io i'll be much better with CSS in total.

```html
<div class="card">
  <img src="/images/image-qr-code.png" />
  <div class="container">
    <h1>Improve your front-end skills by building projects</h1>
    <p>
      Scan the QR code to visit Frontend Mentor and take your coding skills to
      the next level
    </p>
  </div>
</div>
```

```css
.main-container {
  background-color: #dae1ef;
  width: 50%;
  z-index: 1;
  padding: 5%;
  margin-top: 30px;
  margin-left: 200px;
  box-shadow: 4px 8px 8px hsla(0, 2%, 75%, 0.38);
  resize: none;
}
.card {
  height: 270px;
  width: 181px;
  z-index: 2;
  border-radius: 5px;
  background-color: white;
  margin-left: 170px;
  box-shadow: 4px 8px 8px #d9ede26f;
  resize: none;
}
img {
  height: auto;
  max-width: 100%;
  border-radius: 5px 5px 5px 5px;
  width: 90%;
  margin-top: 4%;
  margin-left: 9px;
}
```

### Continued development

I will need to continue forcusing on CSS(Especially on the positioning section) and on how to position parent and child elements accurately in HTML.

### Useful resources

- [MDN](https://developer.mozilla.org/en-US/) - This helped me for any issue am facing in both HTML and CSS. I really liked this pattern and will use it going forward.
- [W3schools](https://www.w3schools.com/) - This is an amazing article which helped me finally understand HTML and CSS. I'd recommend it to anyone still learning this concept.

NB. Both resources also helps in problems regarding JavaScript and more of other programming languages.

## Author

- Frontend Mentor - [@ElWise237](https://www.frontendmentor.io/profile/@ElWise237)
- Twitter - [@ElAdams237](https://www.twitter.com/@ElAdams237)

## Acknowledgments

I would like to express my deepest appreciation to my MENTOR (NGWA SEDRICK MEH) which am deeply indebted to for all the help and guidance he has been providing me with throughout my learnig process. You can check him out on his personal website at https://www.nsedrickm.com/.
