# Parallax Scrolling Page

This is a simple HTML and CSS project demonstrating the parallax scrolling effect. The page contains three parallax sections with fixed background images that create a dynamic scrolling experience.

![brave_yj3zrvoaEl](https://github.com/user-attachments/assets/ff04cbb3-6e6f-4d64-9bc3-9b839659bdeb)

## Project Structure

The project consists of the following files:

- `index.html`: The main HTML file that contains the structure of the parallax page.
- `style.css`: The CSS file that provides the styling for the parallax effects and the content sections.

## Features

### Parallax Sections

The page includes three parallax sections:

1. **First Parallax Section (`parallax-1`)**
   - Displays a background image with the title "Kenan Dzafic."
   - The background image remains fixed while the user scrolls, creating a parallax effect.

2. **Second Parallax Section (`parallax-2`)**
   - Displays a different background image with the title "Scrolling."
   - This section also uses a fixed background to maintain the parallax effect during scrolling.

3. **Third Parallax Section (`parallax-3`)**
   - Displays another background image with the title "COOL!"
   - Similar to the previous sections, the background remains fixed while scrolling.

### Content Sections

Between the parallax sections, there are content sections (`para-1` and `para-2`) with text that provides additional information about parallax scrolling.

- **First Content Section (`para-1`)**
  - Explains what parallax scrolling is and how it works.
  - The background color is white, and the text color is black.

- **Second Content Section (`para-2`)**
  - Encourages the user to scroll up and down to experience the parallax effect.
  - The background color is black, and the text color is white.

## Known Issues

### Understanding Parallax Properties

The key CSS properties that enable the parallax effect include:

- `background-size: 100% 100%`: Ensures that the background image covers the entire section, scaling to fit.
- `background-attachment: fixed`: Keeps the background image fixed in place while the content scrolls, creating the parallax effect.
- `position: relative`: Positions the content within each parallax section relative to its normal position.

These properties are crucial for achieving the desired parallax scrolling effect.

## How to Run

1. Clone the repository or download the project files.
2. Open `index.html` in your preferred web browser to view the parallax page.
