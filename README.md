# Aman Jirshad — Personal Website

A calm, responsive personal website built with plain HTML, CSS, and JavaScript. No build tools, external fonts, libraries, or network services are needed.

## Open it
1. Keep the `aman-jirshad-website` folder together with its subfolders.
2. Double-click `index.html` to open it in a browser. Core features work offline.
3. Optionally open the folder in Visual Studio Code and use the Live Server extension.

## Customize
- Edit page copy in `index.html`.
- Change colors, spacing, and responsive styles in `css/style.css`.
- Edit contact details, project cards, technologies, and learning areas in `js/script.js` in the `siteSettings` object. Blank project URLs are hidden.
- Theme follows system preference on first visit and saves your choice in local storage when available.

## Resume
Copy your real resume PDF to `assets/resume.pdf`. The buttons appear when the browser can detect the file. Change `resumePath` in `js/script.js` if it has another name. No resume is included because one was not provided. A local server may be needed if opening the page directly restricts the browser's file check.

## Contact links
The supplied email and GitHub, Instagram, and LinkedIn profiles are configured in `js/script.js`. Replace them there if they change. The Instagram URL omits the tracking query parameters.

## Troubleshooting
- If styles/scripts are missing, check the `css` and `js` folders are alongside `index.html`.
- If links do not appear, check their URL fields in `siteSettings`.
- If theme preference is not remembered, local storage may be disabled; the switch still works for the current visit.
