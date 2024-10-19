# Codesapeins_Project-1_webpage-tab-creation
# Simple Tab Functionality with HTML, CSS, and JavaScript
## Overview
This project demonstrates how to create a simple tabbed interface using HTML, CSS, and JavaScript. 
The tab system allows users to switch between different content sections by clicking on the respective tab.
Each tab displays its associated content, while the content of the other tabs is hidden. The first tab is active by default when the page loads.

## Features
- Four different tabs. 
- Simple, responsive design using HTML and CSS.
- Dynamic tab content switching using JavaScript.
- Active tab highlighted with an underline.


## Project Structure
The project contains the following files:

- index.html: The main HTML file that contains the structure for the tabs and content sections.
- style.css: Contains the styling for the tabs and content sections.
  -script.js: JavaScript functionality for switching between tabs.
- README.md: Documentation for the project.


## Code Explanation

### HTML
The tabs are implemented using buttons for each tab and corresponding content sections. Each content section has an `id` attribute for easy reference by JavaScript.

```html
<div class="tabs">
    <button class="tab-link active" onclick="openTab(event, 'first')">First Tab</button>
    <button class="tab-link" onclick="openTab(event, 'second')">Second Tab</button>
    <button class="tab-link" onclick="openTab(event, 'third')">Third Tab</button>
    <button class="tab-link" onclick="openTab(event, 'fourth')">Fourth Tab</button>
</div>

## Project URL
https://roadmap.sh/projects/simple-tabs
