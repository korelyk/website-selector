
Built by https://www.blackbox.ai

---

# 网站选择器 (Website Selector)

## Project Overview
网站选择器 (Website Selector) is a web application that allows users to easily navigate to popular websites. Built using HTML, CSS, and JavaScript, this project features a card-based interface where users can click on website cards to load them in a modal iframe. The selected website is displayed within the app, enhancing user experience by keeping them within the application while accessing content from popular web sources.

## Installation
To get started with the 网站选择器 project, you need to clone the repository to your local machine:

```bash
git clone [REPOSITORY_URL]
```

Then, navigate to the project directory:

```bash
cd website-selector
```

After cloning, open the `index.html` file in your preferred web browser to view and interact with the application.

## Usage
1. Launch the application by opening `index.html` in a web browser.
2. Click on any of the displayed website cards to load the respective website in a modal.
3. If the website doesn't load due to security restrictions, an option to open it in a new tab will be provided.

## Features
- Responsive design with a modern card interface.
- Clickable cards that load websites in an overlay modal.
- Error handling for inaccessible websites, providing users with an alternative link.
- Smooth animations for hover effects to enhance user interaction.

## Dependencies
This project utilizes Tailwind CSS for styling. The CSS framework is linked via CDN in the HTML file.

```html
<script src="https://cdn.tailwindcss.com"></script>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
```

## Project Structure
The project is structured as follows:

```
/website-selector
|-- index.html       # Main HTML file containing application structure and logic
```

### File Descriptions
- **index.html**: Contains the HTML structure of the application, along with CSS styling and JavaScript functionality. The file defines the layout of the site selector and implements the logic for loading external websites into a modal.

## Conclusion
The 网站选择器 project is a sleek, user-friendly web application that simplifies access to popular websites through a card-based interface. With minimal setup, users can explore multiple online resources efficiently. Feel free to contribute or customize the project as you see fit!