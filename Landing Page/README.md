# Landing Page Project

This project is a simple landing page built with HTML and CSS. It is based on a task from The Odin Project. The goal of this project is to practice and reinforce basic web development skills, including working with HTML structure and CSS styling.

![brave_1IpRsqMGVl](https://github.com/user-attachments/assets/9bd9d122-333f-46c8-b90a-c60cf69ca9f0)

## Project Overview

The landing page consists of a header that includes the title of the page and a button that links to the shopping cart. The header is styled with a white background, centered text, and a button that changes slightly when hovered over.

## Development

### First Step

The first step was adding a header that includes the title of the page and a button that links to the shopping cart (no link included). The header is styled with a white background, centered text, and a button that changes slightly when hovered over.

**Main Issue**:

- **Button Stretching in Flex Container:** When adding the button inside the flex container, the button stretched to the height of the div, which wasn't the desired outcome. To fix this issue, specific CSS properties were applied to ensure that the button maintained its size while staying aligned with the header content.

### Second Step

The next step was to add an image to the landing page. The image serves as a visual focal point and contains some information.

**Main Issue**:

- **Adding Text and Button Over the Image:** The main challenge here was positioning text and a button over the image. To achieve this, CSS techniques like `position: relative` for the image container and `position: absolute` for the text and button were used. This allowed for precise placement of the elements over the image while maintaining responsiveness.

### Third Step

The Final Step was adding some cards at the bottom of the page the indicate some information of our shop page.

**Main Issue**:

- **Creating cards:** The main issue was creating cards in a specific style.

### Prerequisites

To view and edit this project, you'll need:

- A code editor (e.g., Visual Studio Code, Sublime Text)
- A web browser (e.g., Chrome, Firefox)

### Project Structure

Here's the structure of the project:

```bash
├── index.html
└── style.css
```
