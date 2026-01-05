# Mondrian Art Recreation

A CSS Grid-based recreation of Piet Mondrian's iconic "Composition II in Red, Blue, and Yellow" using pure HTML and CSS.

## Overview

This project recreates the famous 1930 modernist artwork by Piet Mondrian using CSS Grid layout. The webpage displays both the original artwork for comparison and a pixel-perfect CSS recreation, demonstrating the power of modern CSS layout techniques for creating geometric art.

## Features

- **Pure CSS Art:** No images used for the grid - entirely CSS-based
- **CSS Grid Layout:** Demonstrates advanced grid positioning
- **Comparison View:** Original artwork displayed alongside CSS recreation
- **Responsive Design:** Centered layout with clean presentation
- **Geometric Precision:** Accurate proportions and color matching

## Art Details

**Original Artwork:**

- Title: Composition II in Red, Blue, and Yellow
- Artist: Piet Mondrian
- Year: 1930
- Location: Kunsthaus Zürich
- Style: De Stijl, Neo-Plasticism

**Color Palette:**

- Primary Red (#FF0000)
- Primary Blue (#0000FF)
- Primary Yellow (#FFFF00)
- White (#FFFFFF)
- Black borders

## File Structure

```
MondrianArtRecreation/
├── index.html
└── Piet_Mondriaan_Composition.jpg
```

## Technical Implementation

**Technologies:** HTML5, CSS3 Grid

**Key Concepts Demonstrated:**

- CSS Grid layout with custom positioning
- Grid-column and grid-row properties
- Box-sizing for precise borders
- Flexbox for page centering
- Background colors for geometric shapes

**Grid Structure:**

```css
.container {
  display: grid;
  grid-template-columns: repeat(4, 100px);
  grid-template-rows: repeat(4, 100px);
  gap: 0;
  border: 10px solid black;
}
```

**Grid Positioning Example:**

```css
.box2 {
  grid-column: 3 / 5; /* Spans 2 columns */
  grid-row: 1 / 3; /* Spans 2 rows */
  background-color: red;
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

## Design Breakdown

**Grid Composition (4×4):**

- 9 boxes with varying sizes
- Each box positioned using grid-column and grid-row
- Black borders create the iconic Mondrian grid lines
- Primary colors (red, blue, yellow) with white spaces

**Box Distribution:**

- 4 white boxes
- 2 red boxes
- 2 blue boxes
- 1 yellow box

## Browser Compatibility

Works in all modern browsers with CSS Grid support:

- Chrome/Edge (57+)
- Firefox (52+)
- Safari (10.1+)
- Opera (44+)

## Educational Value

This project demonstrates:

- Advanced CSS Grid techniques
- Precise geometric layout without JavaScript
- Art recreation through code
- Understanding of grid positioning
- Modern CSS layout capabilities

## About the Artist

Piet Mondrian (1872-1944) was a Dutch painter who pioneered abstract art and co-founded the De Stijl art movement. His compositions using only primary colors, black, white, and geometric shapes became iconic symbols of modernism.

## Future Enhancements

Potential additions:

- Interactive color picker to customize colors
- Animation effects on hover
- Multiple Mondrian compositions
- Randomized Mondrian generator
- Mobile-responsive grid scaling
- Print-to-canvas functionality

## Development Information

**Developer:** Ana McCullagh  
**Project Type:** CSS Grid Art Recreation  
**Inspiration:** Piet Mondrian's De Stijl movement

## Credits

**Original Artwork:** Piet Mondrian, 1930  
**Image Source:** Kunsthaus Zürich

## License

Educational project - free to use and modify for learning purposes.
