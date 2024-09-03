# Flex-Layout Website

This project demonstrates the use of Flexbox in creating a responsive web layout with a header, sidebar, main content area, and footer.

![image](https://github.com/user-attachments/assets/b0488768-8603-4e79-ba69-d97d683fe1c3)

## Project Structure

The project consists of the following files:

- `index.html`: The main HTML file that contains the structure of the webpage.
- `style.css`: The CSS file that provides the styling for the layout using Flexbox.

## Features

### Layout Structure

The webpage is divided into several sections:

1. **Header**
   - Contains the title of the website, "MY AWESOME WEBSITE."
   - Styled using Flexbox to center the content vertically.

2. **Sidebar**
   - A vertical navigation bar on the left side with links.
   - Styled with a fixed width, and the Flexbox property `flex-direction: column` is used to align the links vertically.
   - The `box-sizing: border-box` property ensures that padding is included in the element's total width, and `flex-shrink: 0` prevents the sidebar from shrinking when the window is resized.

3. **Main Content Area**
   - Contains three "cards" with text content.
   - The cards are centered within the container using Flexbox.

4. **Footer**
   - Displays a footer with the text "My Flex Project ❤️."
   - The footer is centered horizontally and vertically using Flexbox.

### Flexbox Properties

Key Flexbox properties used in this project include:

- **`display: flex;`**: Used to define a flex container, enabling Flexbox layout for its children.
- **`align-items: center;`**: Vertically aligns items within the flex container.
- **`justify-content: center;`**: Horizontally centers items within the flex container.
- **`flex-direction: column;`**: Stacks child elements vertically within the flex container.
- **`box-sizing: border-box;`**: Ensures padding and border are included in the element's total width and height.
- **`flex-shrink: 0;`**: Prevents the flex item from shrinking when there isn't enough space in the flex container.

## Known Issues

### Sidebar and Flexbox Properties

Understanding the following Flexbox properties was crucial for creating the sidebar:

- **`box-sizing: border-box;`**: This property is essential to ensure that padding is included within the width of the sidebar, preventing overflow issues.
- **`flex-shrink: 0;`**: This property was used to prevent the sidebar from shrinking when the content in the main container expands or when the window is resized.

## How to Run

1. Clone the repository or download the project files.
2. Open `index.html` in your preferred web browser to view the Flexbox layout.

