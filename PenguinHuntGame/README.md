# Penguin Hunt Game

An interactive browser-based game where players click on snow mounds to find hidden penguins. Be careful not to click on the yeti!

## Overview

This is a simple yet engaging click-and-reveal game built with pure HTML and CSS (no JavaScript required). Players click on mysterious snow mounds to reveal what's hiding underneath - cute penguins or a scary yeti. The game uses CSS checkbox hacks for interactivity and features smooth hover effects.

## Features

- **Pure CSS Interactivity:** No JavaScript required - uses CSS checkbox technique
- **9 Interactive Mounds:** 8 penguins and 1 yeti to discover in a 3×3 grid
- **Hover Effects:** Visual feedback when hovering over mounds
- **Unique Mounds:** Each mound has a different snow pattern
- **Cute Graphics:** Hand-drawn style penguin and yeti characters

## How to Play

1. Open `index.html` in any web browser
2. Hover over snow mounds to see them change
3. Click on mounds to reveal what's hiding
4. Try to find all 8 penguins!
5. Watch out for the yeti!

## Technical Implementation

**Technologies:** HTML5, CSS3  
**Technique:** CSS checkbox hack for click interactivity

**Key Concepts Demonstrated:**

- CSS pseudo-classes (`:checked`, `:hover`)
- Adjacent sibling selector (`+`)
- Background image manipulation
- Float-based grid layout
- Interactive UI without JavaScript

**File Structure:**

```
PenguinHuntGame/
├── index.html
├── css/
│   └── style.css
└── media/
    ├── penguin_title.png
    ├── penguin_1.png through penguin_8.png
    ├── mound_1.png through mound_9.png
    ├── mound_1_hover.png through mound_9_hover.png
    └── yeti.png
```

## Game Mechanics

The game uses hidden checkboxes paired with labels:

- Checkboxes are hidden with `display: none`
- Labels act as clickable mound images (3×3 grid)
- When checkbox is checked, CSS changes the background image to reveal the character
- Hover states provide visual feedback

## CSS Checkbox Hack Explanation

```css
/* Hide checkbox */
input[type="checkbox"] {
  display: none;
}

/* When checkbox is checked, change the label's background */
#penguin1:checked + label[for="penguin1"] {
  background-image: url(../media/penguin_1.png);
}
```

## How to Run

Simply open `index.html` in any modern web browser. No server required!

**Or use a local server:**

```bash
# Python
python3 -m http.server 8000

# VS Code Live Server
# Right-click index.html → Open with Live Server
```

## Browser Compatibility

Works in all modern browsers:

- Chrome/Edge
- Firefox
- Safari
- Opera

## Educational Value

This project demonstrates:

- Creative CSS-only interactivity
- Proper HTML semantics with labels and inputs
- Image asset management
- Hover and click state handling
- Grid layout with floats
- Game design with pure CSS

## Development Information

**Developer:** Ana McCullagh  
**Project Type:** Web Development coursework  
**Technologies:** HTML5, CSS3

## License

Educational project - free to use and modify for learning purposes.
