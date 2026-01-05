# Recipe Page - Chocolate Cake Recipe

A beautifully designed recipe webpage featuring a delicious chocolate cake recipe with custom typography and clean layout.

## Overview

This project showcases a fully responsive recipe page with semantic HTML structure, custom font integration, and modern CSS styling. The page presents a complete chocolate cake recipe with ingredients, step-by-step directions, and a finished product photo.

## Features

- **Custom Typography:** Geometria font family with 8 different weights (Thin to Heavy)
- **Semantic HTML:** Proper use of header, main, sections, and footer elements
- **Responsive Design:** Adapts to different screen sizes
- **Clean Layout:** Centered content with card-style design
- **Professional Styling:** Subtle shadows, rounded corners, and consistent spacing
- **Organized Structure:** Separated ingredients and directions sections

## File Structure

```
RecipePage/
├── index.html
├── css/
│   └── style.css
├── fonts/
│   ├── Geometria.ttf
│   ├── Geometria-Thin.ttf
│   ├── Geometria-ExtraLight.ttf
│   ├── Geometria-Light.ttf
│   ├── Geometria-Medium.ttf
│   ├── Geometria-Bold.ttf
│   ├── Geometria-ExtraBold.ttf
│   ├── Geometria-Heavy.ttf
│   └── (Italic variants)
└── images/
    └── chocolate_cake.jpg
```

## Technical Implementation

**Technologies:** HTML5, CSS3, Custom Web Fonts

**Key Concepts Demonstrated:**

- @font-face declarations for custom fonts
- Font-weight property for typography hierarchy
- Semantic HTML5 elements
- CSS box model and layout
- Responsive images
- CSS3 styling (border-radius, box-shadow)

**Typography Hierarchy:**

```css
Header (h1):     Geometria Heavy (900)
Subheaders (h2): Geometria Bold (700)
Body text:       Geometria Light (300)
Footer:          Geometria Thin (100)
```

## Recipe Content

**Delicious Chocolate Cake**

- 11 ingredients for rich chocolate flavor
- 6 easy-to-follow steps
- Bake time: 30-35 minutes
- Serves: 8-10 people

## How to Run

Simply open `index.html` in any modern web browser. No server required!

**Or use a local server:**

```bash
# Python
python3 -m http.server 8000

# VS Code Live Server
# Right-click index.html → Open with Live Server
```

## Design Features

- **Color Scheme:** Clean white content on light gray background
- **Layout:** Max-width 800px centered container
- **Typography:** Multiple font weights for visual hierarchy
- **Spacing:** Consistent padding and margins throughout
- **Visual Interest:** Card design with subtle shadow effects

## Browser Compatibility

Works in all modern browsers:

- Chrome/Edge
- Firefox
- Safari
- Opera

**Note:** Custom fonts require browser support for @font-face (all modern browsers)

## Educational Value

This project demonstrates:

- Custom web font integration with @font-face
- Proper semantic HTML structure
- CSS typography hierarchy
- Responsive design principles
- Clean, maintainable code organization
- Professional web page layout

## Future Enhancements

Potential additions:

- Nutrition information section
- Print-friendly stylesheet
- Recipe rating system
- Cooking timer functionality
- Additional recipe variations
- Video tutorial section

## Development Information

**Developer:** Ana McCullagh  
**Course:** CS 300 - Client Side Web Development  
**Project Type:** Recipe webpage with custom typography

## Credits

**Fonts:** Geometria font family  
**Photo:** Chocolate cake image

## License

Educational project - free to use and modify for learning purposes.
