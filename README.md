# Frontend Wizards — Stage 0 & Stage 1 (Profile, Contact & About)

This repository contains my Stage 0 Profile Card and Stage 1 pages (Contact & About) for the Frontend Wizards / HNG Internship tasks.

## Live Demo
https://kodesomi.github.io/frontend-stage0-profile-card/
<!-- Replace above link with your Netlify or GitHub Pages URL if different -->

## Files
- `index.html` — Profile Card (Stage 0)
- `contact.html` — Contact form with validation (Stage 1)
- `about.html` — About Me / reflections (Stage 1)

## How to run locally
1. Clone or download the repository.
2. Open any file (`index.html`, `contact.html`, `about.html`) in your browser (double-click the file or right-click → Open with → Browser).

## Requirements implemented
- All required `data-testid` attributes are present:
  - Profile: `test-profile-card`, `test-user-name`, `test-user-bio`, `test-user-time`, `test-user-avatar`, `test-user-social-links`, `test-user-hobbies`, `test-user-dislikes`
  - Contact: `test-contact-name`, `test-contact-email`, `test-contact-subject`, `test-contact-message`, `test-contact-submit`, `test-contact-error-<field>`, `test-contact-success`
  - About: `test-about-page`, `test-about-bio`, `test-about-goals`, `test-about-confidence`, `test-about-future-note`, `test-about-extra`
- `test-user-time` displays `Date.now()` and updates.
- Contact form validates inputs and prevents invalid submissions.
- Semantic HTML (article, main, section, nav, figure, headings) and ARIA associations for accessibility.
- Responsive layout for mobile, tablet, and desktop.
- Keyboard navigable controls and visible focus styles.

## Notes
- Avatar upload preview available on the Profile Card (index.html).
- If Pages shows a 404, ensure `index.html` is in the repository root and GitHub Pages is set to the `main` branch and root folder.

## Contact
Kamorudeen Adeleke Odesomi — (add your email here if you want)
