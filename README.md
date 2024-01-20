# Dynamic Multi Filter Input
Vanilla javascript Dynamic Multi Filter Input
This project implements a dynamic multi-filter input field using HTML, CSS, and JavaScript. It allows users to select multiple options from a dropdown list. The selected options are displayed as styled blocks within the input field.

## Features

- Dynamically create multi-filter input fields.
- Add options to the filter input programmatically.
- Display selected options as styled blocks.
- Use of modern JavaScript (ES6) for class-based encapsulation.

## Usage

To use this component:

1. Include the `style.css` and `script.js` files in your HTML file.
2. Create a container element in your HTML with a unique ID.
3. Instantiate the `MultiFilterInput` class with the ID of the container element.
4. Use the `addItem` method to add options to the filter input.

Example:

```html
<div id="filterContainer"></div>
