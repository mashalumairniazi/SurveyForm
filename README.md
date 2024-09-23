# Certification Project 1 - Survey Form - Responsive Web Design (FCC)

##### This repository contains the completed code for Project 1.5 *(Certification Project)* in the FreeCodeCamp "Responsive Web Design" course.

The project is a survey form that follows the provided instructions and meets the outlined user stories, with a personalized theme based on Minecraft.

## Project Overview

The **Survey Form - Minecraft** project collects user information through a form that includes fields for name, email, age, preferences, and additional comments. The form is styled with a unique color scheme and layout. It implements basic HTML5 validation for email and number fields and allows users to select various options through dropdowns, radio buttons, and checkboxes.

### Key Features

- **User Stories**: The project fulfills the required user stories, including an `<h1>` title with an id of `title`, a description in a `<p>` element with an id of `description`, and a form with various input fields.
- **Form Fields**: The form includes inputs for text, email, number, dropdowns, radio buttons, checkboxes, and a textarea.
- **HTML5 Validation**: The form uses built-in HTML5 validation for email formatting and numeric ranges.
- **Custom Styling**: The project is styled using external CSS, featuring a Minecraft-themed design with bold colors and a simple, clean layout.

## Code Details

### HTML Structure:

- **Form Inputs**:
  - Text input for name (with a placeholder) and corresponding label with an id of `name-label`.
  - Email input with a validation pattern and a corresponding label with an id of `email-label`.
  - Number input with a range of 12 to 120, along with a label with an id of `number-label`.
  - Dropdown menu to select a favorite mob from Minecraft.
  - Radio buttons to select a favorite block.
  - Checkboxes for final selections.
  - Textarea for additional comments.

- **Form Organization**:
  - The form is organized using `<fieldset>` elements to group related fields for better readability and accessibility.

### CSS Styling:

- **Typography**: The page uses the Tahoma font for a bold and professional look.
- **Layout**: The form is styled to be centered on the page with clear margins and padding.
- **Color Scheme**: A Minecraft-inspired color palette with shades of green, brown, and black to reflect the theme.
- **Form Element Styling**: Inputs, textareas, and labels are styled with consistent padding, margins, and background colors to enhance user experience.
  
## How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/survey-form-minecraft.git
2. Ensure that both the index.html and styles.css files are in the same directory.
3. Open the index.html file in a web browser to view the project.

## Learning Objectives

This project helps learners:
- Build a functional HTML form that collects user input through various form elements.
- Implement built-in HTML5 validation for email and number fields.
- Style a form using CSS to create a visually appealing and accessible user interface.
- Use HTML attributes like `required`, `placeholder`, and `pattern` to enhance user experience.

## FreeCodeCamp Curriculum

This project is a part of the [Responsive Web Design Certification](https://www.freecodecamp.org/learn/2022/responsive-web-design/) on FreeCodeCamp.

## License

This project is licensed under the MIT License.
