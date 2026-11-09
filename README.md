# -Au-feu-de-bois-
A French barbecue recipe website built with PHP, Bootstrap 5 and custom CSS.
Developed as a school project at ESGI. It was planned as a group project of three, and I completed it entirely on my own.

## Overview

*Au feu de bois* gathers simple, generous barbecue recipes designed to be shared with friends.
The site includes a home page, a recipe index, three detailed recipes and an "About" page with a project postmortem.

## Pages

| Page | Description |
|------|-------------|
| `index.php` | Home page with a hero image and a link to the recipes |
| `recettes.php` | Recipe index displayed as clickable circular cards |
| `poulet.php` | Honey chicken skewers |
| `hamburger.php` | Barbecue hamburger |
| `mais.php` | Grilled corn |
| `a_propos.php` | Story of the project, values, and postmortem |

Each recipe page contains a photo carousel, an ingredients list (for 4 people), a utensils list, step-by-step instructions, and a short review with a rating.

## Features

- **Modular PHP structure**: shared header and footer (`top.php`, `bottom.php`) included on every page to avoid code duplication
- **Responsive design** built with Bootstrap 5: collapsible navbar, adaptive grid, flexible layouts
- **Image carousels** on each recipe page, each with its own unique ID
- **Custom CSS**: Flexbox layouts, hover animations (zoom on carousels, rotating recipe images), custom font (DynaPuff)
- **Accessibility**: descriptive `alt` text on images, ARIA labels on navigation and carousel controls, semantic HTML (`header`, `main`, `footer`)
- **Icons** from Font Awesome

## Tech stack

- PHP
- HTML5 / CSS3
- Bootstrap 5.3.3 (via CDN)
- Font Awesome 6.7.2 and Google Fonts (via CDN)
- Local environment: MAMP

## Project structure

```
.
├── index.php
├── recettes.php
├── poulet.php
├── hamburger.php
├── mais.php
├── a_propos.php
├── top.php        # shared header and navigation
├── bottom.php     # shared footer and scripts
├── style.css
└── images/
```

## Lessons learned

- Carousels must have unique IDs when several are used in a project, otherwise they conflict.
- Images need to be resized and optimized before being added to the site.
- Managing a whole project alone taught me to plan, prioritize, and see a project through from start to finish.

## Possible improvements

- Improve the layout for tablets and small screens
- Add a comment system for visitors
- Connect the site to a MySQL database

## Author

**Mélissa Gomes**: [Portfolio](https://melissagomes22.github.io/Portfolio/)
