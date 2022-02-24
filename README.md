# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

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

### Screenshot

![img](https://github.com/IvanSerranoGit/QRCodeComponent/blob/main/images/Screenshot%202022-02-24%20at%2015-46-04%20QR%20Code%20Component.png)

### Links

- Solution URL: [solution URL](https://ivanserranogit.github.io/QRCodeComponent/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [React](https://reactjs.org/) - JS library (comingsoon)

### What I learned

In this section i learn use property place-items: center; a property  GRID align items at center

```html
    <main class="container">
        <section class="container_qr">
            <figure class="qr_container-img">
                <img class="qr_container-img-item" src="./images/image-qr-code.png" alt="qr-code">
            </figure>
            <div class="info_container">
                <h3 class="info_container-title">Improve your front-end
                    skills by building projects</h3>
                <p class="info_container-text">
                    Scan the QR code to visit Frontend
                    Mentor and take your coding skills to
                    the next level
                </p>
            </div>
        </section>
    </main>
```

```css
main {
  background-color: var(--Light-bg);
  width: 100%;
  height: 100vh;
  display: grid;
  place-items: center;
}
```



### Useful resources

- [Guide to FlexBox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - Our comprehensive guide to CSS flexbox layout. This complete guide explains everything about flexbox, focusing on all the different possible properties for the parent element (the flex container) and the child elements (the flex items). It also includes history, demos, patterns, and a browser support chart.

- [Guide to Grid](https://css-tricks.com/snippets/css/complete-guide-grid/) - Our comprehensive guide to CSS grid, focusing on all the settings both for the grid parent container and the grid child elements.

## Author

- Website - [Iván Serrano](https://ivan.serrano.opengala.xyz/)
- Frontend Mentor - [@IvanSerranoGit](https://www.frontendmentor.io/profile/IvanSerranoGit)
- Twitter - [@lvanSerrano](https://twitter.com/lvanSerrano)

