# Kenan's Old Recipes

This is a simple HTML and CSS project for showcasing traditional recipes. The website includes a main page that links to individual recipe pages, with images and detailed instructions for preparing the dishes.

## Project Structure

The project consists of the following files:

- `index.html`: The main HTML file that contains the homepage with links to various recipes.
- `caesar.html`: A recipe page for Caesar Salad.
- `english.html`: A recipe page for English Breakfast.
- `teriyaki.html`: A recipe page for Teriyaki Chicken.
- `style.css`: The CSS file that provides the styling for the entire website.

## Features

### Homepage

- The homepage (`index.html`) displays the title "Kenan's Old Recipes" and provides links to individual recipe pages:
  - Caesar Salad
  - English Breakfast
  - Teriyaki Chicken

### Recipe Pages

Each recipe page (`caesar.html`, `english.html`, `teriyaki.html`) includes:
- A title with the name of the dish.
- An image of the dish centered on the page.
- A detailed list of ingredients and step-by-step instructions for preparing the dish.

### Styling

- The website uses a custom cursive font, "Great Vibes," from Google Fonts.
- A repeating background image (`restaurant.webp`) is applied across the site.
- The `.wrapper` and `.wrapper-receipe` classes ensure that the content is centered both vertically and horizontally.
- Recipe lists and instructions are displayed in a two-column format with some margin adjustments to prevent stretching issues.

## Known Issues

### Image Stretching Problem

When adding text below the image on recipe pages, the image was stretching undesirably. This issue was addressed by properly structuring the HTML and CSS, specifically by ensuring that the image is wrapped and centered within a `div` and that text elements are managed in separate `div` containers with controlled padding and margins.

## How to Run

1. Clone the repository or download the project files.
2. Open `index.html` in your preferred web browser to access the homepage.
3. Click on any recipe link to view the individual recipe pages.

