# Task 3 – CSS Units, Box Model & Fonts

## Description

This project creates a simple webpage containing an **image and a button**. The main purpose of the task is to practice CSS **Units, Box Models, and Font Styling**.

## Features

* Displays an image inside a container.
* Adds a **Click Me** button below the image.
* Uses **25vw** spacing from the left and right.
* Uses **10vh** spacing from the top and bottom.
* Uses viewport units (`vw` and `vh`) for sizing.
* Uses `box-sizing: border-box`.
* Button has a **linear gradient background**.
* Button font and text colour are customized.
* Page is designed to fit within the viewport without unnecessary scrolling.

## Technologies Used

* HTML5
* CSS3

## Project Structure

```text
Task3/
│
├── index.html
├── style.css
├── image.jpg
└── README.md
```

### Viewport Units

`vw` is based on the width of the browser viewport.

```css
margin-left: 25vw;
margin-right: 25vw;
```

`vh` is based on the height of the browser viewport.

```css
margin-top: 10vh;
margin-bottom: 10vh;
```

### Box Sizing

```css
box-sizing: border-box;
```

This makes width and height calculations easier by including padding and border within the specified dimensions.

### Gradient

A linear gradient is used to create the multicolour background of the **Click Me** button.

## Restrictions Followed

* No Flexbox used.
* No `overflow: hidden` used.
* No `position: relative` used.
* No `position: absolute` used.