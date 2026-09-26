# Thandeka's Kitchen

A five-page website for Thandeka's Kitchen, a home-style South African eatery in Germiston, Gauteng — built for the WEDE5020w Web Development module (IIE).

## Pages
- `index.html` — Home
- `menu.html` — Menu
- `about.html` — About
- `gallery.html` — Gallery
- `contact.html` — Contact

## Structure
- `style.css` — single external stylesheet, linked from every page
- `images/` — site photography: hero.jpg, kitchen.jpg, dish1.webp–dish4.webp, dish5.jpg

## Changelog

### v2.0 — Part 2 submission (CSS Styling and Responsive Design)
- Added a single external stylesheet (`style.css`) and linked it from every page, replacing the previous unstyled markup.
- Applied a base style/reset, a typographic scale, and a warm South African colour palette.
- Built the desktop layout using Flexbox for the header/navigation and CSS Grid for the Menu, Contact, and Gallery sections, relying on the cascade to keep selector use minimal (mostly element selectors, no added classes).
- Added responsive breakpoints at 1024px (tablet) and 600px (mobile) using media queries, with relative units (rem, %) for spacing and font sizes.
- Navigation, menu list, and gallery grid all reflow to single columns on mobile.
- Fixed carried-over Part 1 issues:
  - `about.html`: corrected a broken Home link (index.hmtl -> index.html).
  - `about.html`: fixed spelling ("misson" -> "mission") and footer capitalisation.
  - `menu.html`: corrected the stylesheet link (stle.css -> style.css) and a missing closing `</li>` tag.
  - `gallery.html` / `contact.html`: fixed a malformed viewport meta tag.
  - `gallery.html`: corrected inconsistent image folder references and alt-text typos.
- Added final site photography to `images/`.

### v1.0 — Part 1 submission
- Initial five-page HTML structure and content for Thandeka's Kitchen (Home, Menu, About, Gallery, Contact).

## References
Github (2026) *Github*. Available at: https://docs.github.com (Accessed: 12 August 2026).

Pexels (2026) *Free stock photos*. Available at: https://www.pexels.com (Accessed: 12 August 2026).

The Independent Institute of Education (2026) *WEDE5020w Module Manual*. Johannesburg: The IIE.

W3Schools (2026) *HTML, CSS and JavaScript reference*. Available at: https://www.w3schools.com (Accessed: 13 August 2026).

Mozilla Developer Network (2026) *CSS: Cascading Style Sheets*. Available at: https://developer.mozilla.org/en-US/docs/Web/CSS (Accessed: 25 September 2026).

W3C (2026) *Media Queries Level 4*. Available at: https://www.w3.org/TR/mediaqueries-4/ (Accessed: 25 September 2026).