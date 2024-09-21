# Jianan Ni - Professional Portfolio and Resume

This project mainly consists of two HTML files (`index.html` and `resume.html`) and a CSS file (`styles.css`) to present a professional portfolio and resume. Below is an overview of the main HTML tags and CSS classes used in the project.

## HTML Tags

### Structural Elements
- `<html>`: Root element of the HTML document.
- `<head>`: Contains metadata, title, and links to stylesheets.
- `<body>`: Main content of the web page.
- `<header>`: Defines the header section, including the navigation menu and page title.
- `<main>`: Wraps the main content of the page.
- `<footer>`: Defines the footer section with contact information.
- `<section>`: Groups related content, such as the "About", "Skills", "Certifications", and "Contact" sections.
- `<nav>`: Contains the navigation links.
- `<ul>`: Unordered list, used for lists like the navigation menu.
- `<li>`: List item within a list.
- `<table>`: Displays tabular data such as skills and education.
- `<tr>`, `<td>`, `<th>`: Represent rows and cells in tables.
- `<form>`: Collects user input (e.g., contact form).
- `<video>`: Embeds a video file with controls.
- `<audio>`: Embeds an audio file with autoplay and loop functionalities.
- `<img>`: Embeds images, such as certifications and profile pictures.
- `<details>`: Provides a collapsible section for additional information.
- `<summary>`: A summary or title for the collapsible details element.

### Meta Elements
- `<meta charset="UTF-8">`: Defines the character encoding for the document.
- `<meta name="viewport" content="width=device-width, initial-scale=1.0">`: Ensures responsive design for mobile devices.
- `<meta name="description" content="...">`: Describes the content of the page for SEO purposes.

### Links and Hyperlink
- `<link rel="stylesheet" href="...">`: Links to the external CSS file.
- `<a href="#section-id">`: Anchor tags are used within the navigation `menu` block to link to specific sections,such as "**About Me**", "**Skills**", "**Certifications**", and "**Contact**".
- `<a href="mailto:...">`: Creates email links.
- `<a href="#section-id">`: Creates navigation links within the page.

## CSS Classes and IDs

### General Layout
- `body`: Sets general styles for the webpage, including font, margin, and background color.
- `header`, `footer`: Styles the header and footer sections with background color, text color, and padding.
- `menu`: Defines the navigation menu layout, with flexbox for horizontal alignment.
- `about-layout`: Used for the "About Me" section to control the layout of the content and images.

### Tables and Lists
- `table`: Defines the style for the table element, including border collapse and padding.
- `ul`, `li`: Styles unordered lists, such as the navigation menu or skill list.

### Media (Images, Video, and Audio)
- `img`: Styles images, particularly in the gallery and about sections, with hover effects. In the "About Me" section, the image uses the `float: left;` property to wrap text around the image, providing a more visually appealing layout.
- `gallery`: Flexbox layout for displaying certification images.
- `video`, `audio`: Sets styles and behavior for multimedia elements.

### Forms
- `form`: Defines the layout for the contact form, including input and textarea elements.
- `input`, `textarea`, `button`: Styles the form elements for user interaction.

### Responsiveness
- Media queries: Used to adjust the layout for different screen sizes (e.g.,  **iPad(768px)** and **Smart phones (350–365px)**).
- `flex`, `grid`: Applied to various sections (**About me** and **Certifications**) to ensure responsive layouts across screen sizes.

## JavaScript
- Simple script to toggle background music play/pause on user interaction with the music control button.

## Project Structure
- `index.html`: The main portfolio page, showcasing skills, certifications, and contact information.
- `resume.html`: The detailed professional resume.
- `styles.css`: Defines the visual styles for both HTML files.
