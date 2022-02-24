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

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

### Useful resources

- [Example resource 1](https://www.example.com) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
- [Example resource 2](https://www.example.com) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.

**Note: Delete this note and replace the list above with resources that helped you during the challenge. These could come in handy for anyone viewing your solution or for yourself when you look back on this project in the future.**

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.

**Note: Delete this note and edit this section's content as necessary. If you completed this challenge by yourself, feel free to delete this section entirely.**
