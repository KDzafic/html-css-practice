# Grid Layout Project

## Project Overview
This project demonstrates the use of CSS Grid to create a simple and responsive web layout. The layout consists of five distinct sections: Header, Menu, Nav, Article, and Footer. The CSS Grid is used to define the structure and positioning of these sections within the webpage.

![image](https://github.com/user-attachments/assets/f3120219-7307-40be-9b7e-9c87e9c6f04a)

## File Structure
- `index.html`: The HTML file that defines the structure of the webpage using a grid container.
- `style.css`: The CSS file that styles the grid layout and its elements.

## HTML Explanation (`index.html`)
The HTML file creates a grid layout with five main sections, each represented by a `div` element inside a container.

### Key Elements:
- `<div class="grid-container">`: This is the container that holds all the grid items. It is styled with CSS Grid properties to create the layout.
- `<div class="item1">`, `<div class="item2">`, etc.: These are the individual grid items that correspond to different sections of the layout (Header, Menu, Nav, Article, and Footer).

## CSS Explanation (`style.css`)
The CSS file is responsible for defining the grid layout and styling the individual grid items.

### Key Styles:

#### `.grid-container`
- **Purpose**: Defines the grid layout for the container.
- **Properties**:
  - `display: grid;`: Enables CSS Grid on the container, allowing the child elements to be placed according to grid rules.
  - `grid-template-areas`: Defines named grid areas, making it easy to place grid items in specific locations. The template is arranged in a 3x6 grid pattern:
    - The first row has the header spanning all six columns.
    - The second row has the menu on the left, the main content in the center (spanning three columns), and the right section on the right.
    - The third row has the menu on the left and the footer spanning the remaining five columns.
  - `gap: 10px;`: Adds spacing between grid items.
  - `background-color: #2196F3;`: Sets the background color of the grid container to a blue shade.
  - `padding: 10px;`: Adds padding inside the grid container.

#### `.item1`, `.item2`, `.item3`, `.item4`, `.item5`
- **Purpose**: Assigns each grid item to a specific area within the grid layout.
- **Properties**:
  - `grid-area`: Associates each item with a named grid area defined in the `grid-template-areas` property. For example, `.item1` is placed in the `header` area, `.item2` in the `menu`, and so on.

#### `.grid-container > div`
- **Purpose**: Applies a common style to all grid items within the container.
- **Properties**:
  - `background-color: rgba(255, 255, 255, 0.8);`: Sets a semi-transparent white background for each grid item.
  - `text-align: center;`: Centers the text within each grid item.
  - `padding: 20px 0;`: Adds vertical padding inside each grid item to create space around the text.
  - `font-size: 30px;`: Sets the font size for the text inside each grid item.

## Additional Notes
This project provides a basic example of how CSS Grid can be used to create complex layouts with simple and readable code. The use of `grid-template-areas` makes it easy to visualize and control the placement of elements within the grid. This layout is responsive and can be easily modified to adapt to different screen sizes by adjusting the grid properties.
