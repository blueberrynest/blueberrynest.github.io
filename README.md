# Ayishath Rusaina — Portfolio

Personal portfolio website for **Ayishath Rusaina**, Civil Engineer and M.Tech student in Water Resources Engineering at NIT Calicut.

This repository contains the source code for the GitHub Pages site.

---

## Live Website

[blueberrynest.github.io](https://blueberrynest.github.io)

---

## Structure

```
/
├── index.html          # About / Home
├── skills.html         # Skills & Tools
├── education.html      # Education
├── experience.html     # Professional Experience
├── projects.html       # Projects
├── contact.html        # Contact
├── assets/
│   ├── css/style.css   # Shared styles
│   ├── js/main.js      # Active nav state
│   └── resume/         # Place resume.pdf here
│       └── Ayishath_Rusaina_Resume.pdf 
└── README.md
```

---

## Deployment Workflow

This repository follows a simple branching model:

```
main        → production (live GitHub Pages site)
devel       → development branch
feature/*   → feature development
refactor/*  → code refactoring
docs/*      → documentation updates
fix/*       → bug fixes
```

Development happens in the `devel` branch. 
Once the site is stable, `devel` is merged into main. 

---

## Deployment

The site is deployed automatically via **GitHub Pages**.

- Source: `main` branch
- Directory: repository root

Any commit merged into `main` will update the live site.

---

## Updating the Website

### Update page content

Edit the corresponding HTML file:

- `index.html`
- `skills.html`
- `education.html`
- `experience.html`
- `projects.html`
- `contact.html`

### Update resume

Replace the file inside:

```
assets/resume/Ayishath_Rusaina_Resume.pdf
```

### Add a project

Copy an existing `.project-card` block inside:

```
projects.html
```

and update its details.

---

## License

This repository contains personal portfolio code and content.

---
