# Ahinora Goranova — Personal Portfolio Website

## About the Project

This project is a personal portfolio website created by me Ahinora Goranova as part of my web development learning and assessment.

The purpose of the website is to introduce myself, present the skills I am learning, and provide a simple way for visitors to interact with my portfolio.

The website is built using HTML, CSS and JavaScript.

## Technologies Used

- **HTML5:** Creates the structure and content of the website.
- **CSS3:** Controls the visual design, colours, spacing, typography and responsive layout.
- **JavaScript:** Adds interactivity to the website, including a working button that displays a message when clicked.

## Project Structure

```text
AhinoraWebsite/
├── index.html
├── style.css
├── script.js
└── README.md
```

### 1. `index.html` — Website Structure

The HTML file contains the main content and structure of the website.

It includes:

- **Header:** Displays my name, Ahinora Goranova, and a welcome message.
- **Navigation:** Provides links to the About Me, My Skills and Contact sections.
- **About Me section:** Introduces me and my website.
- **My Skills section:** Describes the web development skills I am learning.
- **Contact section:** Contains a button that visitors can click.
- **Footer:** Displays the website creator's name.

The HTML also links the CSS stylesheet and JavaScript file so that the design and interactive functionality work together.

### 2. `style.css` — Website Design

The CSS file controls how the website looks.

The main styling features include:

- A light purple page background.
- A dark purple navigation bar and footer.
- A purple header with white text.
- White content sections with rounded corners.
- Consistent fonts, spacing and colours.
- Hover effects for navigation links and the button.
- A responsive design using a CSS media query for smaller screens.

The `@media (max-width: 600px)` rule adjusts the layout for smaller screens, helping the website remain usable on mobile devices.

### 3. `script.js` — Website Interactivity

The JavaScript file makes the Contact section interactive.

It uses `document.getElementById()` to select the button and the paragraph where the response will appear.

The `addEventListener("click", ...)` method listens for a click on the button. When the button is clicked, the `textContent` property changes the paragraph to display the message:

"Hello Ahinora! Thanks for visiting my website."

This demonstrates how JavaScript can respond to user actions and dynamically update HTML content.

## Features

- Personal introduction.
- Navigation links to different page sections.
- Consistent purple-themed design.
- Interactive "Say Hello" button.
- Hover effects.
- Responsive styling for smaller screens.

## How to Run the Project

1. Download or clone this repository to your computer.
2. Open the project folder in Visual Studio Code or another code editor.
3. Open `index.html` in a web browser.
4. Navigate through the website and click the "Say Hello" button to test the JavaScript functionality.

No additional software packages or installations are required to run this basic website.

## What I Learned

Through this project, I practised:

- Writing HTML to structure a webpage.
- Using CSS selectors and properties to style webpage elements.
- Linking external CSS and JavaScript files to HTML.
- Using JavaScript variables and DOM methods.
- Responding to button clicks using event listeners.
- Creating navigation links with HTML IDs.
- Applying responsive CSS techniques.
- Organising a web development project into separate files.

## Future Improvements

Possible improvements for future versions include:

- Adding a profile photograph.
- Expanding the About Me section.
- Displaying completed projects in a portfolio gallery.
- Adding a contact form with input validation.
- Improving accessibility and mobile navigation.
- Publishing the website using GitHub Pages.

## Author

**Ahinora Goranova**

Created as a personal portfolio and web development learning project.
