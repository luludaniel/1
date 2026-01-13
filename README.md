# Layout starter (HTML + CSS)

This repo is intentionally minimal: it shows **how to make a layout** with semantic HTML and modern CSS.

## What “layout” means

A layout is the page structure (not the content): typically

- `header`: top bar / branding / primary actions
- `nav` / `aside`: navigation or sidebar
- `main`: the primary content area
- `footer`: bottom area (links, legal, etc.)

## Run it

Open `index.html` in a browser.

## How it’s built

- **CSS Grid** sets the overall page regions (header/sidebar/main/footer)
- **Flexbox** handles small component alignment inside regions (header content, nav lists, etc.)
- A **media query** switches from a single-column mobile layout to a two-column desktop layout

Files:

- `index.html`: semantic structure with placeholder content
- `styles.css`: the layout rules (grid areas + responsive breakpoint)

