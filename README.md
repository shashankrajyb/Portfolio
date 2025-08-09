# YB Shashank Raj – Portfolio

A clean, fast, and mobile‑friendly portfolio for a Python Full Stack Developer. It’s intentionally minimal: just HTML + CSS for speed and simplicity.

## What’s inside
- Sticky header with smooth in‑page navigation (Home, Skills, Projects, Resume)
- Hero section with name, role, intro, and profile photo
- Skills grid and project cards
- Resume section with a download button
- Accessible, responsive layout (mobile‑first)

## Tech & Style
- HTML5 + modern CSS (no JavaScript)
- Font: Inter (with system fallbacks)
- Color palette (professional + minimal):
  - Background: `#F9FAFB`
  - Primary text: `#111827`
  - Accent: `#2563EB`
  - Secondary text: `#6B7280`
  - Header/Footer: `#1F2937`
  - Cards/White base: `#FFFFFF`

## Quick start
1. Open `index.html` in your browser.
2. That’s it. It’s a static site.

## Personalize
- Profile photo
  - Replace the file named `passport photo.jpg` in the project root with your own image (keep the same name for zero changes), or update the `src` in `index.html`:
    ```html
    <img src="passport photo.jpg" alt="YB Shashank Raj" class="profile-img">
    ```
- Resume download
  - Replace `resume.docx` with your latest resume (keep the same name), or point the button to a different file:
    ```html
    <a href="resume.docx" class="btn-primary" download>Download Resume</a>
    ```
- Colors & fonts
  - Tweak colors and spacing in `styles.css`. Stick to the accent blue for highlights and use grays for everything else for a clean, consistent look.

## Structure
```
Porfolio/
├── index.html      # Page markup
├── styles.css      # Styling and layout
├── resume.docx     # Downloaded from Resume section
└── passport photo.jpg  # Profile image
```

## Notes
- Smooth scrolling is handled natively via CSS and anchor links.
- Sections are offset correctly under the sticky header using `scroll-margin-top`.
- The code is intentionally small and readable so you can quickly tailor it to your needs.

## Deploy
- Drag‑and‑drop to any static host (GitHub Pages, Netlify, Vercel, your server). No build step required.

