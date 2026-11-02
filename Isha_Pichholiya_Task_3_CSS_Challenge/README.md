# CSS Lab - Flexbox, Grid and Animation Challenge

**Author:** Isha Pichholiya  
**Organisation:** WeIntern Pvt Ltd  
**Assignment:** Week 1 - Task 3

## Project description

CSS Lab brings together three layout and animation exercises in a single page. The first uses Flexbox to arrange three sample testimonial cards. The second uses CSS Grid for six visual tiles. The third explores button transitions, a spinning loader and a fading element. The original dark background, purple accents and interactive examples are preserved.

## Technologies used

- Semantic HTML5
- CSS3, custom properties and media queries
- Flexbox and CSS Grid
- CSS transitions, transforms and keyframe animations
- Vanilla JavaScript for button feedback
- Google Fonts: DM Sans and Space Grotesk, with browser fallback fonts

## Features

### Responsive Flexbox cards

Three equal-width cards sit side by side on larger screens and stack vertically at widths of 780 pixels or less. Hovering lifts a card and highlights its border. Names and quotes are sample content for the layout exercise.

### Six-item CSS Grid

Six tiles use `repeat(3, minmax(0, 1fr))` on larger screens, two columns at 780 pixels or less and one column at 480 pixels or less. Hovering gently scales a tile.

### CSS animation

- A button demonstrates hover transitions with translation, scaling and a shadow.
- A spinner rotates using the `spin` keyframes.
- A separate element fades and moves using the `fadeUp` keyframes.
- Clicking the button updates a status message through JavaScript.
- A reduced-motion media query shortens animations and transitions for visitors who request less motion.

The page also includes section navigation and visible keyboard focus styles.

## Folder structure

```text
index.html
README.md
css/
    style.css
js/
    script.js
```

All decorative visuals use HTML and CSS. No separate image assets were present in the original project. This ZIP contains only Task 3.

## Instructions to run locally

1. Extract the ZIP into a folder.
2. Open `index.html` in a modern browser such as Chrome, Edge or Firefox.
3. Use the Flexbox, Grid and Animation navigation links to visit each exercise.
4. Resize the browser to see the card and grid layouts change.
5. Hover over the cards, tiles and demo button; click the button to see its feedback message.

No installation, build step or configuration is needed. An internet connection loads the optional Google Fonts; browser fallback fonts are used otherwise.

## Screenshots

No screenshots were supplied in the original project, and none are included in this ZIP. The visual tiles are part of the exercise, not screenshots. Suggested views for later documentation are desktop and mobile Flexbox layouts, the six-item grid and the animation section.

## GitHub repository link

Placeholder: pending publication under `isha-pichholiya-css-challenge` using the author's GitHub account. No repository URL has been invented.

## Live deployment link

Placeholder: pending GitHub Pages deployment. No live URL has been created yet.

## Assignment review

The source contains a responsive Flexbox layout with three cards, a CSS Grid layout with six items, and CSS transitions, transforms and keyframe animations, matching the Task 3 requirements supplied with the request. The official handbook PDF was not available with the supplied files, so any additional handbook requirements remain unverified.