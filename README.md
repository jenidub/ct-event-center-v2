
# JeniDub Event Center (JDEC)
A fictional event venue website built as my Coding Temple capstone project, showcasing semantic HTML, CSS layout techniques, and fully responsive design across desktop, tablet, and mobile.

🔗 **Live Site:** _https://jenidub.github.io/ct-event-center-v2/_ 
📂 **Repo:** https://github.com/jenidub/ct-event-center-v2

## Overview
JDEC is a five-page marketing site for a Northern California event venue, covering everything a prospective client would want to see: what the venue offers, who runs it, what's coming up, ticket pricing, and how to get in touch or find directions.

## Features
-   **Semantic structure** — `header`, `footer`, and `section` elements organize content on every page; `main` wraps the primary content region on the Contact, Events, and Services pages, and `article` is used on the Home page for the About and Next Event feature sections; heading levels (`h1`–`h5`) build a logical content hierarchy
-   **Site-wide navigation** — a shared nav menu (built as an unordered list) links every page together, plus a mobile hamburger menu toggle
-   **Event schedule table** — a dedicated `<table>` on the Events page lists upcoming shows, with a card-based alternate layout for mobile screens
-   **Contact forms** — text, email, and message (textarea) fields with a styled submit button, on both the Home and Contact pages, with a JS-driven confirmation message on submit
-   **Embedded venue map** — Google Maps iframe embed on the Contact page, with a "View in Maps" link for mobile users
-   **Fully responsive layout** — every stylesheet includes breakpoints at 1024px (tablet) and 768px (mobile), built with Flexbox
-   **Back to Top button** — appears after scrolling and smoothly returns the user to the top of the page
-   **Custom favicon** — an SVG ticket icon in the browser tab

## Built With
-   HTML5
-   CSS3 (Flexbox, media queries, custom properties via class/ID selectors)
-   Vanilla JavaScript (mobile nav toggle, back-to-top visibility, form confirmation message)
-   [Font Awesome](https://fontawesome.com/) for icons
-   [Google Fonts](https://fonts.google.com/) for typography
-   Google Maps embed API

## Project Structure
```
ct-event-center-v2/
├── index.html
├── about.html
├── services.html
├── events.html
├── contact.html
├── css/
│   ├── styles.css      # shared/global styles
│   ├── index.css
│   ├── about.css
│   ├── services.css
│   ├── events.css
│   └── contact.css
└── assets/              # images and favicon

```

Each page loads `styles.css` for shared styling plus its own page-specific stylesheet.

## Author
**Jeni Williams** ([@jenidub](https://github.com/jenidub)) 
Built as part of the Coding Temple Fullstack Certification program.
