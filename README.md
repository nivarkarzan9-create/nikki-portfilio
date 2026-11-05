# Nikki — Portfolio

A responsive, accessible personal portfolio built with HTML5, CSS, and vanilla JavaScript. It has light and dark themes, remembers a visitor’s theme choice, and follows the device preference on a first visit. There are no framework or package dependencies and no build step.

## Project structure

```text
website2/
├── index.html
├── style.css
├── script.js
├── netlify.toml
├── README.md
├── .gitignore
└── assets/
    ├── icons/
    └── images/
```

Keep the three source files separate. Add local images under `assets/images/` and icons under `assets/icons/`, then reference them with relative paths such as `assets/images/project-name.png`.

## Run locally

1. Open this project folder in Visual Studio Code.
2. Install the Live Server extension if you do not already have it.
3. Right-click `index.html` and choose **Open with Live Server**.

You can also open `index.html` directly in a browser. Live Server is useful while editing because it refreshes the page when files change.

## Customize

- Update portfolio copy, project cards, and contact placeholders in `index.html`.
- Adjust the light and dark palettes in the CSS variables near the top of `style.css`.
- Keep menu and theme behavior in `script.js`.
- Replace project artwork with real images and descriptive `alt` text when available.

The skill, project, and contact entries are placeholders. Replace them with confirmed details before sharing the site publicly.

## Upload to GitHub

Create a repository, then add or push the contents of this folder to its root. `index.html` is already at the project root, and `.gitignore` excludes common local editor, operating system, dependency, and Netlify working files.

## Deploy with Netlify

Import the GitHub repository into Netlify and use the project root as the base directory. No build command is needed; `netlify.toml` sets the publish directory to `.`. Netlify will publish the static HTML, CSS, JavaScript, and assets directly.
