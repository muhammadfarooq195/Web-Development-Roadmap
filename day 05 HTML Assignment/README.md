# Barakode Digital Agency — Week 1 HTML Assignment

A pure semantic HTML5 multi-page website built without CSS or JavaScript, covering all Week 1 Frontend Developer Roadmap concepts.

## Files Included
- `index.html` — Home page with agency introduction, responsive hero image (`srcset` and `sizes`), page links, and quick facts.
- `services.html` — Services page detailing three core digital services with structured headings, lists, and quote links.
- `projects.html` — Projects page showcasing two client case studies (*GreenLeaf Organic Store* and *Apex Real Estate*) with descriptive alt text, captions, and safe external links.
- `contact.html` — Accessible contact inquiry form grouped with `fieldset` and `legend`, visible labels, and native browser validation.
- `images/` — Local folder containing `home.png`, `project-1.png`, and `project-2.png`.

## What I Checked (QA Checklist)
- **Page Load & Structure:** Opened all four HTML files in the browser and confirmed valid HTML5 document setup, English language attribute, UTF-8 encoding, and descriptive titles and meta descriptions.
- **Navigation & Links:** Tested all relative links across `index.html`, `services.html`, `projects.html`, and `contact.html`, plus external links (`target="_blank" rel="noopener noreferrer"`).
- **Images & Accessibility:** Verified that all three images load properly from the `images/` folder with descriptive `alt` text and `figcaption` elements.
- **Keyboard Navigation:** Navigated through all page links and form controls using the `Tab` key to verify logical focus order.
- **Form Validation:** Submitted an empty form and invalid email formats on `contact.html` to confirm native browser validation triggers correctly.

## What Still Needs Work (Future Improvements)
- **Styling & Layout (Week 2–3 CSS):** Add an external CSS stylesheet for visual branding, typography, spacing, and responsive Flexbox/Grid layouts.
- **Interactive Form Handling (Week 4–6 JavaScript):** Add JavaScript validation feedback and a real backend or API endpoint so the contact form can send messages and display a custom confirmation state.
