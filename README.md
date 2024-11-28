# Donut Animation

This project demonstrates a 3D rotating donut rendered in both ASCII art and on an HTML5 canvas using JavaScript.

## Files

- `index.html`: The main HTML file that includes the canvas and ASCII art elements.
- `style.css`: The CSS file for styling the page.
- `donut.js`: The JavaScript file that contains the logic for rendering the donut and handling animations.

## Usage

1. Open `index.html` in a web browser.
2. Click the "Toggle ASCII Animation" button to start or stop the ASCII art animation.
3. Click the "Toggle Canvas Animation" button to start or stop the canvas animation.

## Description

The project uses trigonometric functions to calculate the 3D coordinates of points on a torus (donut shape) and projects them onto a 2D plane. The ASCII art version updates the content of a `<pre>` tag, while the canvas version draws directly onto an HTML5 canvas element.

## Customization

You can adjust the following parameters in `donut.js` to change the appearance and behavior of the animations:

- `R1` and `R2`: Radii of the torus.
- `K1` and `K2`: Constants used for scaling and positioning.
- `A` and `B`: Angles that control the rotation of the donut.

## Author

This project is based on the work by [a1k0n](https://www.a1k0n.net/2021/01/13/optimizing-donut.html).

## License

This project is open source and available under the MIT License.