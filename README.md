# Project 3: Around The U.S.

### Overview

- Intro
- technologies and techniques used
- GitHub Pages Link

**Intro**

This project is made so all the elements are displayed correctly on popular screen sizes.

**Technologies and techniques**

This project was made to address the problem of webpages looking different depending on the screen size the webpage is being displayed. To address this problem responsive design techniques were implemented for different screen resolutions. Specifically media queries were implemented to change styles under specific sets of conditions. Also the CSS declarations, dipslay: flex and display: grid with relative unit property values were used to make the webpage responsive. example code below

```css
.gallery__cards {
  display: grid;
  justify-content: center;
  grid-template-columns: repeat(auto-fit, 282px);
  gap: 20px 17px;
  padding: 0;
  margin: 0;
  list-style-type: none;
}

.page__content {
  display: flex;
  flex-direction: column;
  min-height: 100vh;
}
```

**GitHub Pages Link**

The way you'll do this at work is by exporting images directly from Figma — we recommend doing that to practice more. Don't forget to optimize them [here](https://tinypng.com/), so your project loads faster.

Good luck and have fun!

```

```
