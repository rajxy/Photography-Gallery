# Photography Gallery

## Overview

Photography Gallery is a simple responsive image gallery created using HTML and CSS. The project is designed for a photography blog where multiple photographs can be displayed in a clean and organized layout.

The gallery automatically adjusts the number of columns according to the available screen size, making it suitable for desktops, tablets, and mobile devices.

## Features

* Responsive image gallery layout
* Six photography images
* CSS Grid for arranging images
* Simple and clean page design
* Rounded corners for images
* Smooth image zoom effect on hover
* Separate CSS file for styling

## Technologies Used

* HTML5
* CSS3
* CSS Grid

## Project Structure

```text
Photography-Gallery/
│
├── index.html
├── style.css
│
└── images/
    ├── p1.jpg
    ├── p2.jpg
    ├── p3.jpg
    ├── p4.jpg
    ├── p5.jpg
    └── p6.jpg
```

## Description

The `index.html` file contains the structure of the photography gallery. It includes a heading and a gallery section containing six images.

The `style.css` file is used to control the appearance and layout of the page. CSS Grid is used to create a responsive gallery that changes according to the screen width.

The images also have a hover effect. When the cursor is placed over an image, it slightly increases in size using a CSS transformation.

## Responsive Layout

The gallery uses the following CSS Grid property:

```css
grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
```

This allows the browser to automatically determine the number of columns that can fit on the screen.

## How to Run

1. Download or clone the project.
2. Keep the `images` folder in the same directory as `index.html`.
3. Make sure all six image files are present in the `images` folder.
4. Open `index.html` in a web browser.
5. The photography gallery will be displayed.

## Purpose

The purpose of this project is to demonstrate how HTML and CSS can be used to create a responsive photography gallery. It also demonstrates the use of CSS Grid, responsive layouts, image styling, and hover effects.

## Author

Rajarshi Debbarma

## License

This project is created for educational purposes.
