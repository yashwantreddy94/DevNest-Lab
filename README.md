# DevNest Lab

A clean multi-page portfolio website for a freelance web studio focused on business websites, dashboards, service pages, and digital support. The project is built with plain HTML, CSS, and JavaScript, which makes it lightweight, easy to edit, and simple to deploy on static hosting platforms.

## Overview

DevNest Lab is a static studio website designed to present services, featured work, studio information, and contact details in a clear and professional format. The structure uses separate HTML pages for content, shared include files for common layout sections, and centralized CSS and JavaScript assets for styling and interactivity.

## Pages

- `index.html` — Homepage with the main studio introduction.
- `services.html` — Overview of studio services.
- `work.html` — Selected projects and portfolio showcase.
- `about.html` — Studio background, process, and identity.
- `contact.html` — Contact and enquiry page.

## Project Structure

```text
devnest-lab/
│
├── index.html
├── services.html
├── work.html
├── about.html
├── contact.html
│
├── include/
│   ├── header.html
│   └── footer.html
│
├── sample-projects/
│   └── (some files)
│
└── assets/
    ├── css/
    │   └── style.css
    └── js/
        └── script.js
```

This structure follows a common static-site pattern where HTML handles page content, CSS controls presentation, and JavaScript manages shared front-end behavior.

## Features

- Multi-page portfolio website.
- Separate pages for services, work, about, and contact.
- Reusable header and footer includes.
- Shared styles through `assets/css/style.css`.
- Shared interactions through `assets/js/script.js`.
- Easy-to-edit static architecture.
- Suitable for GitHub Pages, Netlify, and other static hosting options.

## Built With

- HTML5
- CSS3
- JavaScript
- Google Fonts
- Font Awesome

## Getting Started

### Clone the repository

```bash
git clone https://github.com/your-username/devnest-lab.git
cd devnest-lab
```

### Run locally

Because this is a static project, it can be opened directly in the browser through `index.html`, or served locally with a lightweight development server for better testing. Static portfolio projects are commonly run this way during development.

Example using Python:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Customization

To customize this project for another portfolio or studio site:

- Update text content inside the HTML files.
- Replace or expand project items in `work.html`.
- Edit colors, spacing, layout, and responsive styles in `assets/css/style.css`.
- Update shared behavior in `assets/js/script.js`.
- Modify `include/header.html` and `include/footer.html` for navigation and footer content.
- Add or replace files inside `sample-projects/` as needed.

## Deployment

This project can be deployed on any static hosting platform, including:

- GitHub Pages
- Netlify
- Vercel for static sites
- Apache or Nginx-based hosting

## Suggested Improvements

- Add real screenshots for featured projects.
- Add Open Graph and Twitter meta tags.
- Add favicon and app icons.
- Connect the contact form to an email or backend handler.
- Expand `sample-projects/` with actual case studies or live demos.
- Improve SEO with page-specific meta descriptions and titles.

## License

This project is available for personal and commercial customization unless a separate license file is added to the repository.

## Author

**B Yashwant Reddy**  
Guwahati, Assam, India  
yashwantreddy94@gmail.com

