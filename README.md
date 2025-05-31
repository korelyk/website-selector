
Built by https://www.blackbox.ai

---

# 网站选择器 (Website Selector)

## Project Overview
网站选择器是一个简单的网页应用，旨在提供多个热门网站的快速访问。用户可以通过点击卡片直接在应用内查看网站内容，或者在安全限制无法显示的情况下，在新标签页中打开网站。

## Installation
To run the website on your local machine, follow these steps:

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd <repository-directory>
   ```

2. **Open the `index.html` file**
   You can open the `index.html` file directly in your web browser. No additional server setup is needed.

## Usage
1. Open the `index.html` file in your web browser.
2. Click on any of the website cards (e.g., Google, Baidu, etc.) to load the website in a modal window.
3. If the website cannot be loaded due to security restrictions, click the button to open it in a new tab.

## Features
- Grid layout for easy access to websites.
- Smooth animations and hover effects for an engaging user experience.
- Responsive design that adapts to different screen sizes.
- Modal for displaying websites with fallback to opening in new tabs if needed.

## Dependencies
This project uses [Tailwind CSS](https://tailwindcss.com) for styling. The CDN link is included in the `index.html` file. No additional dependencies are required.

## Project Structure
```
.
├── index.html         # Main HTML file for the website selector
```

### CSS & Styling
- Using Tailwind CSS for utility-first styling.
- Custom CSS styles defined within the `<style>` tag in the HTML for specific layout needs, such as grid display and hover effects.

### JavaScript
- Inline JavaScript functions for loading websites and handling modals:
  - `loadWebsite(url)` – loads the selected website into an iframe.
  - `showErrorMessage(url)` – displays an error message if the website cannot be loaded.
  - `closeWebsite()` – closes the modal and resets the iframe.

## Contributing
If you would like to contribute to this project, feel free to fork the repository and submit a pull request.

## License
This project is licensed under the MIT License.