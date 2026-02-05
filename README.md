# Portfolio Project

A modern, responsive portfolio website built with HTML5, CSS3, and Vanilla JavaScript.

## Features
- **Dark Theme**: Sleek, eye-friendly dark mode with ambient glowing gradients.
- **Glassmorphism**: Modern frosted glass effects on UI elements.
- **Animations**: Smooth scroll reveal animations and text glitch effects.
- **Responsive**: Fully optimized for mobile, tablet, and desktop.
- **No Dependencies**: Runs directly in the browser without any build steps.

## How to Run
Since this project uses pure HTML/CSS/JS, no installation is required!

1.  Navigate to the `portfolio` directory.
2.  Double-click `index.html` to open it in your web browser.

## Customization
- **Content**: Edit `index.html` to change text, links, and project details.
- **Styles**: Modify `styles.css` to tweak colors or layout. The `:root` variables at the top make it easy to change the color scheme.
- **Interactivity**: Adjust `script.js` to change animation speeds or behavior.

## ✍️ How to Customize Content
To make this portfolio yours, open `index.html` in a text editor (like VS Code or Notepad) and change the following:

1.  **Name & Title**:
    *   Look for `<h1 class="glitch" data-text="Woody Borgella">` and change both the text inside and the `data-text` attribute.
    *   Update `<p class="subtitle">` with your actual role.
2.  **About Section**:
    *   Find the `<div class="about-text">` section and replace the paragraph with your bio.
    *   Update the `<div class="skill-tag">` lines with your actual skills (e.g., Python, SQL, Tableau).
3.  **Projects**:
    *   Update the `<h3>` and `<p>` tags inside `<div class="project-card">` with your project names and descriptions.
    *   Change the `href="#"` in the "View Details" buttons to point to your actual GitHub repos or live demos.
4.  **Contact**:
    *   Update the `mailto:` link and the social media links (`href="#"`) at the bottom.

## 🚀 How to Make it Public (Deployment)
The easiest way to host this for free is **GitHub Pages**.

1.  **Create a GitHub Repository**:
    *   Go to GitHub.com and create a new public repository (e.g., `my-portfolio`).
2.  **Upload Files**:
    *   Upload `index.html`, `styles.css`, and `script.js` to this repository.
3.  **Activate Pages**:
    *   Go to the repository **Settings**.
    *   Click on **Pages** in the left sidebar.
    *   Under **Source**, select `Deploy from a branch`.
    *   Select `main` (or `master`) branch and `/ (root)` folder, then click **Save**.
4.  **Done!**:
    *   GitHub will give you a link (e.g., `yourusername.github.io/my-portfolio`). Share this link with the world!

