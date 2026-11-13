# Rotaa – SaaS Landing Page

Front-end internship assignment for Sankar Group. Rotaa is an invented staff-scheduling SaaS for small teams (cafés, clinics, shops).

- **Live website:** https://vitianyash42.github.io/rotaa-landing-page/
- **Source code:** https://github.com/VITianYash42/rotaa-landing-page
- **Author:** VITianYash42

## Run locally
No install or build step.
1. Download or clone this repository (`git clone https://github.com/VITianYash42/rotaa-landing-page.git`).
2. Open `index.html` in any modern browser.

Fonts load from Google Fonts; the page falls back to system fonts when offline.

## Deployment
Hosted on GitHub Pages (Settings → Pages → Deploy from branch → `main` / `/ (root)`).

## Technologies
HTML5, CSS3 (custom properties, Grid, Flexbox, `color-mix`), vanilla JavaScript. No frameworks or libraries.

## Assignment checklist
- **Navigation bar:** logo, section links, "Get started" button, mobile hamburger menu.
- **Hero:** headline, description, two CTAs, and an interactive rota demo (click a shift to change it and see hours and cost update).
- **Features:** four cards with icons.
- **How it works:** three steps.
- **Pricing:** three plans (Starter, Team, Business).
- **Contact / footer:** demo request form plus contact details and footer.
- **Interactions:** smooth-scroll nav links, buttons open a sign-up modal or scroll to the contact form, both forms validate (name, email format, team size, password rule) and show a success message. No backend.
- **Responsive:** tested layouts at desktop, tablet and ~375px mobile widths. Also supports light/dark mode and reduced motion.

## Screenshots

**Desktop**

![Desktop layout](screenshots/desktop.png)

**Mobile**

![Mobile hero](screenshots/mobile-hero.png)
![Mobile menu](screenshots/mobile-menu.png)

## Design notes (for the 5–8 line explanation)
1. I chose a scheduling product because its main value can be shown, not just described, so the hero is a working mini-rota instead of a stock illustration.
2. A deep blue base with teal, amber and coral shift colours keeps the page calm, and the colour only appears where it carries meaning.
3. One heading font (Bricolage Grotesque) and one body font (DM Sans) with a consistent spacing scale give a clear hierarchy.
4. Layout uses CSS Grid with `auto-fit` so cards reflow without many media queries; the nav collapses to a menu under 820px.
5. Forms use custom validation with inline messages, focus moves to the first error, and a success message replaces the need for a backend.
6. Challenge solved: keeping the rota grid usable at 375px width by shrinking columns and labels rather than scrolling sideways.
