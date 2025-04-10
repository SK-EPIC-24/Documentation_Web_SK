# Documentation_Web_SK Website: https://sk-epic-24.github.io/Documentation_Web_SK/

📘 JavaScript Documentation Webpage
This project is a simple and elegant documentation-style webpage designed to explain the basics of JavaScript. It features a fixed sidebar navigation and a clean, responsive layout built using HTML5 and CSS3 — ideal for beginners looking to understand both JavaScript and how to present content effectively on the web.

🔍 Overview
The webpage mimics the structure of official documentation (like MDN or freeCodeCamp), offering a left-hand sidebar for navigation and a content panel with scrollable sections for each topic.

🛠️ Technologies Used
✅ HTML5 – for page structure

✅ CSS3 – for styling and layout

✅ Responsive Layout – sidebar with sticky navigation

✅ Vanilla JavaScript Example – included in the "Hello World" section

📑 Page Structure Breakdown
📌 Sidebar Navigation (<div class="sidebar">)
Contains navigation links (<ul> with <li><a href="#id">) pointing to specific documentation sections.

Fixed to the left using CSS position: fixed, ensuring it stays visible while scrolling.

Uses hover effect to highlight active items.

📌 Content Area (<div class="content">)
Each topic is placed within a semantic <section> tag, making the content accessible and structured.

Topics include:

Introduction

Prerequisites

JavaScript vs Java

Hello World (Code Example)

Variables (var, let, const)

📌 Code Highlights
In the "Hello World" and "Variables" sections, JavaScript code snippets are embedded directly inside paragraph tags for demonstration.

💡 Key CSS Features
Flexbox Layout: The entire page uses display: flex to place the sidebar and content next to each other.

Sticky Sidebar: The sidebar is fixed with position: fixed and takes up the full viewport height (height: 100vh).

Hover Effects: Sidebar links darken on hover to improve user interaction.

Spacing and Typography: Margins, padding, and fonts are customized for readability.

📷 Demo Screenshot (Optional)
Include a screenshot here if you want to show off the layout visually.

🧪 How to Use
Clone or download the repository.

Ensure style.css is in the same directory as index.html.

Open index.html in a web browser.

Click on sidebar links to navigate through the documentation sections.

🧠 Concepts Covered
This documentation explains basic JavaScript topics such as:

What JavaScript is used for

How it differs from Java

How to print "Hello, World!"

How to use var, let, and const to declare variables

📌 Folder Structure

bash

Copy

Edit

/project-root

│

├── index.html        # Main HTML file

├── style.css         # CSS styling

🚀 Future Improvements (Suggestions)
Add more JavaScript topics (e.g., functions, arrays, objects)

Include interactive code examples using embedded editors

Add syntax highlighting using a library like Prism.js or Highlight.js

Make sidebar collapsible for mobile view

Author:
Shyamsunder Kadam
