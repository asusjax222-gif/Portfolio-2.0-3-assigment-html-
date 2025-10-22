Personal Portfolio Webpage Lab
Description
This lab assignment involves creating a personal portfolio webpage using HTML and an external CSS stylesheet. The project demonstrates the application of CSS selectors, color themes, typography, the box model, positioning techniques, and styling for navigation, tables, buttons, and visual separators. The goal is to build a polished, professional-looking webpage that showcases skills, projects, and contact information.

The webpage includes sections such as a header, navigation, about, projects, skills table, contact form, and interactive elements like a back-to-top button or sticky header. All styling is done via an external CSS file to ensure clean, maintainable code.

Learning Outcomes
Upon completion of this assignment, the student will be able to:

1.Apply an external CSS stylesheet to structure and manage webpage design effectively.
2.Use element, class, and ID selectors to style different sections of a webpage in a systematic way.
3.Implement a consistent color theme and custom typography.
4.Utilize the CSS box model to create proper spacing, borders, and layout adjustments.
5.Design and style navigation bars, tables, buttons, and separators for a professional webpage appearance.
6.Apply CSS positioning techniques to create interactive elements such as sticky headers or back-to-top buttons.
Requirements
...A text editor (e.g., VS Code, Sublime Text) for writing HTML and CSS.
...A web browser (e.g., Chrome, Firefox) for viewing and testing the webpage.
...Basic knowledge of HTML and CSS.
...Access to Google Fonts for custom typography (optional, but recommended).
Setup Instructions
Create a Project Folder: Create a new folder named portfolio-project (or similar, using lowercase and no spaces).
File Structure:
1.Inside the folder, create the following files and subfolders:
.index.html (main HTML file)
.style.css (external CSS stylesheet)
.images/ (folder for images, e.g., profile photo)
.README.md (this file)
2.Link External CSS: In index.html, add the following inside the <head> tag:
html

Run

<link rel="stylesheet" href="style.css">
Import Google Fonts: In style.css, add an import statement at the top, e.g.:
css


@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap');
Build the HTML Structure: Create a basic HTML5 structure in index.html with sections like <header>, <nav>, <section> for About, Projects, Skills, Contact, etc. Include a <table> for skills, <button> elements, and an <hr> for separators.
Apply Styling: Follow the detailed instructions below to style the webpage in style.css.
Add Images: Place at least one image (e.g., profile photo) in the images/ folder and reference it in index.html with proper alt text.
Detailed Instructions
Link External CSS: Ensure style.css is linked as described.
Color Theme & Fonts: Choose 2–3 colors (HEX or RGB) for backgrounds, text, and headings. Import a Google Font (e.g., Poppins or Roboto) and apply it consistently.
Navigation Styling: Style the <nav> with a background color. Format <a> links with padding, remove underlines, and add hover effects (e.g., color change).
Box Model (Spacing): Use margins, padding, and borders to space out sections. Add shadows or borders for separation.
Skills Table Styling: Style the <table> with borders, alternating row colors (e.g., via :nth-child(even)), and cell padding.
Buttons: Customize <button> elements with background colors, padding, border-radius, and hover effects.
Positioning: Use position: fixed; for a back-to-top button or position: sticky; for the navigation bar.
Visual Elements: Style <hr> with borders for separators. Add box shadows to images.
Consistency & Clean Code: Use comments in CSS (e.g., /* Navigation Styles */). Ensure fonts, colors, and spacing are uniform.
How to View the Webpage
Open index.html in a web browser.
Test navigation links, form submission (if applicable), and interactive elements like buttons.
Resize the browser window to check responsiveness (though full responsiveness isn't required, ensure it looks good on standard screens).
Features
Consistent Theme: Color scheme and fonts applied throughout.
Navigation Bar: Styled with background and hover effects on links.
Sections: Clearly separated with spacing, borders, and <hr> elements.
Skills Table: Displays technical skills with borders and alternating colors.
Buttons: Customized with rounded corners, colors, and hover effects.
Interactive Elements: Back-to-top button or sticky header using CSS positioning.
Images: At least one image with shadows and proper alt text.
Form: Contact form with labels, placeholders, and validation.
Improvements/Adjustments
Ensure proper color contrast for readability.
Maintain consistent font usage (Google Fonts recommended).
Check layout on different screen sizes.
Align the Skills Table with bold headers and uniform spacing.
Use margins and padding to center elements.
Add hover effects on buttons.
Use visual separators for sections.
Ensure correct form structure.
Include at least one image with correct size and alt text.
Write clean, indented code.
Expected Output
The final webpage should resemble a professional portfolio with a header, navigation, about section (with image), projects, skills table, contact form, and styled buttons. Navigation should work, the table should be readable, and sections should be visually separated. Test for functionality in a browser.

Author:-
Jayesh Shrivastava - Completed as part of Btech cse data science  Lab Assignment 3.