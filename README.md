# custom-bootstrap-framework
# Custom CSS Framework

## Framework Name: **StylishScaffolding**

### Description
StylishScaffolding is a lightweight and customizable CSS framework built using Sass, designed to streamline your web development process. Combining the power of Bootstrap with our custom theme, StylishScaffolding provides a flexible and appealing design for standard HTML elements. With a focus on utility classes and easy customization, this framework allows developers to quickly create responsive and visually attractive web applications while ensuring a consistent look and feel across all components.

## Features
- **Custom Theme:** Tailored styles for headings, buttons, forms, lists, and tables that ensure visual harmony.
- **Utility Classes:** Quick and easy styling with predefined utility classes for spacing, colors, and typography.
- **Sass Variables:** Customize your design effortlessly with Sass variables for colors, fonts, and spacing.
- **Modular Structure:** Organized SCSS partials for easy maintenance and scalability.

## Installation
To use StylishScaffolding in your project, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/ZoeyHashemi/custom-bootstrap-framework.git
2.**Install the dependencies:**
Ensure you have Node.js installed, then run:
npm install

3.**Compile the SCSS:**
Turn the SCSS files into a CSS file by running this command:
sass src/custom-css-framework.scss dist/custom-css-framework.css

4.**Include in your project:**
Add the compiled CSS file to your HTML by including this line in the <head> section:
<link rel="stylesheet" href="dist/custom-css-framework.css">


## Usage
You can utilize StylishScaffolding by applying the provided classes to your HTML elements. Here are some examples:

**Headings**
```html
<h1 class="heading-primary">Supercharge Your CSS with Sass</h1>
<h2 class="heading-secondary">Are You Ready to Make Your Dreams a Reality?</h2>

 **Buttons**
<button class="btn btn-primary">Access the Framework</button>
<button class="btn btn-secondary">Subscribe</button>

 **Forms **
<form>
  <div class="form-group">
    <label for="name">Name:</label>
    <input type="text" class="form-control" id="name" placeholder="Enter your name">
  </div>
  <button type="submit" class="btn btn-primary">Submit</button>
</form>

## Customization
StylishScaffolding is highly customizable. You can easily adjust the look and feel of your site by overriding default Sass variables. Here’s how to customize the framework:

Open the _variables.scss file in the src folder.

Modify the values of the variables to fit your project’s design needs. Here are a few variables you can change:

Colors:
$primary-color: #CAD2C5;      // Primary theme color
$secondary-color: #84A98C;    // Secondary theme color- use for buttons
$background-color: #ecf0ed;  // Background color for the body
$accent-color: #52796F;      // Color for  hovering  buttons
$text-color: #354F52;        // Default text color
$footer-color: #2F3E46;  //Background color for the footnote

Typography:
$font-family-default: "Times New Roman", Times, serif;
$font-size-body: 1em;
$font-size-h1: 2em;
$font-size-h2: 1.5em;
$font-size-h3: 1.3em;
$font-weight-h1: 700;
$font-weight-h2: 600;
$font-weight-h3: 500;
$line-height-h1: 1.2;
$line-height-h2: 1.3;
$line-height-h3: 1.4;

Spacing:

$padding-base: 1rem;                 // Default padding
$margin-base: 1rem;                  // Default margin


Recompile the SCSS to generate customized CSS file: with Live Sass compiler

