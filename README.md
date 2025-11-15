# Frontend Mentor – Browser Extensions Manager UI Solution

This is my solution to the **Browser Extensions Manager UI** challenge on [Frontend Mentor](https://www.frontendmentor.io/).  
The challenge helped me improve my HTML, CSS and JavaScript skills by building an interactive interface inspired by a browser extensions manager layout.

## Table of Contents
- [Overview](#overview)  
- [The Challenge](#the-challenge)  
- [Design](#design)  
- [Links](#links)  
- [My Process](#my-process)  
- [Built With](#built-with)  
- [What I Learned](#what-i-learned)

## Overview
This project is an **interactive browser extensions manager UI** that displays multiple sections including an overview panel and cards representing installed extensions.  
It features a clean and responsive layout that adapts to different screen sizes, and includes interactive buttons to simulate installation and management actions.  
The interface also includes **dark mode**, hover and focus states, and persistent storage using the browser's memory.

## The Challenge
Users should be able to:

- Browse the extension cards and interact with the buttons.  
- View the UI layout depending on their device’s screen width.  
- Experience hover and focus states on interactive elements.  
- Switch between **light and dark mode**, with the selected mode stored in the browser memory.  
- Select installed extensions and store that selection in the browser memory as well.  
- Read dynamic extension data obtained from a **JSON file**.  
- Read the information clearly thanks to a structured and semantic layout.

## Design
### Desktop Design  
![Desktop Design](./design/desktop-design-light.jpg)

### Desktop Design Hover
![Desktop Design](./design/desktop-design-light-hover.jpg)

### Desktop Design Focus
![Desktop Design](./design/desktop-design-light-focus.jpg)

### Desktop Design Active
![Desktop Design](./design/desktop-design-light-active.jpg)

### Desktop Design Inactive
![Desktop Design](./design/desktop-design-light-inactive.jpg)

### Mobile Design 
<img src="./design/mobile-design-light.jpg" width="200px" alt="Desktop design in dark mode with hover state">

### Desktop Design Dark
![Desktop Design](./design/desktop-design-dark.jpg)

### Desktop Design Dark Hover
![Desktop Design](./design/desktop-design-dark-hover.jpg)

### Desktop Design Dark Focus
![Desktop Design](./design/desktop-design-dark-focus.jpg)

### Desktop Design Dark Active
![Desktop Design](./design/desktop-design-dark-active.jpg)

### Desktop Design Dark Inactive
![Desktop Design](./design/desktop-design-dark-inactive.jpg)

### Mobile Design 
<img src="./design/mobile-design-dark.jpg" width="200px" alt="Desktop design in dark mode with hover state">


## Links
- **Solution URL:** [GitHub Repository](https://github.com/mlopezl/my-version-of-browser-extensions-manager-ui-main-challenge)  
- **Live Site URL:** [Live Demo](https://mlopezl.github.io/my-version-of-browser-extensions-manager-ui-main-challenge/)

## My Process
1. Structured the UI with semantic HTML sections.  
2. Used **Flexbox** and **CSS Grid** to align and organize all components.  
3. Applied hover and focus states for a more polished and interactive interface.  
4. Implemented **dark mode** and stored user preference using `localStorage`.  
5. Saved extension selections in the browser memory for persistent user experience.  
6. Loaded dynamic content from a **JSON file** to populate the extension cards.  
7. Implemented responsiveness using relative units, scaling and breakpoint adjustments.  
8. Organized files to keep HTML, CSS and assets clean and modular.

## Built With
- HTML5  
- CSS3  
- Flexbox  
- CSS Grid  
- JavaScript  
- JSON

## What I Learned
- How to structure a multi-section UI cleanly using HTML and CSS.  
- How to combine **Flexbox + Grid** for flexible and scalable layouts.  
- How to add hover and focus effects to improve UX.  
- How to implement and persist **dark mode** using localStorage.  
- How to store UI selections in browser memory for persistent state.  
- How to import and render extension data dynamically from a JSON file.  
- How to adapt the interface to mobile without sacrificing readability and spacing.
