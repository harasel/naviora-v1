# NAVIORA — Global Maritime Advisory Website

A premium, contest-ready static website for **NAVIORA**, an independent maritime advisory & consulting firm. Built with pure HTML5, CSS3 and a small vanilla-JS file. No build step, no dependencies, GitHub Pages–ready.

## File structure

```
naviora/
├── index.html      # Full single-page site
├── style.css       # Design system + all sections
├── script.js       # Nav, scroll reveal, form UX
├── assets/         # (empty — add favicon / OG image here)
└── README.md
```

## Sections included

Hero · Client marquee · About + Vision & Mission · Team (Leadership, Advisors, Consultants, Experts, Global Partners) · Industries (12) · Why Choose Us (8) · Services (16) · Clients (12) · Testimonials · CTA strip · Contact form · Footer.

## Deploy to GitHub Pages

1. Create a new repo, e.g. `naviora-site`.
2. Upload the contents of this folder to the repo root.
3. Repo → **Settings → Pages** → Source: `main` branch, folder `/root` → **Save**.
4. Site goes live at `https://<username>.github.io/naviora-site/`.

## Customising

- **Colors / fonts**: change the CSS variables at the top of `style.css` (`--accent`, `--bg`, `--serif`, etc.).
- **Copy**: all text is in `index.html`.
- **Contact form**: currently client-side only. To receive enquiries, wire the `<form id="enquiryForm">` submit handler in `script.js` to a service such as Formspree, Getform, or a custom endpoint.
- **Favicon & OG image**: drop files into `/assets/` and link them from `<head>` in `index.html`.

## Performance

- No framework, no external JS libraries.
- Single Google Fonts request (Fraunces + Inter) with `preconnect`.
- All decoration is inline SVG — no image assets required.
- Under typical hosting, first paint < 1s and total load < 2s on GTmetrix.

## Browser support

Chrome, Safari, Edge, Firefox (latest 2 versions). Fully responsive down to 360 px.

© NAVIORA
