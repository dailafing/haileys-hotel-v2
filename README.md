# Hailey’s Hotel – Unit 1 (User-Centric Front-End Dev)

Prototype UI for Hailey’s Hotel online booking system, produced for the Level 5 Diploma (Gateway Quals • Unit 1).  
The goal is to modernise the current paper-based process by giving guests and staff a fast, accessible front-end.

## Core user stories
* *Guest (new)* – browse rooms and book without phoning reception.  
* *Guest (returning)* – log in to view / amend past and current bookings.  
* *Receptionist* – search availability quickly, add reservations, apply loyalty discounts.

## Accessibility & UX pledges
* WCAG-AA colour contrast and keyboard-only navigation.  
* Semantic HTML; ARIA labels only where semantics fall short.  
* Forms & pop-ups give instant feedback and always keep focus trapped.

## Tech stack
HTML5 • CSS (Grid + Flexbox) • vanilla JS (minimal, only for interactions)  
Version control with **Git/GitHub** (commit per feature) • Deployed via **GitHub Pages**.


## Assessment Criteria Evidence (Running Log)

| AO Code | Description (abbreviated)                                                 | Where it's demonstrated                        |
|---------|----------------------------------------------------------------------------|------------------------------------------------|
| 1.1     | Use semantic HTML structure                                               | `<header>`, `<nav>`, `<main>`, `<section>`, `<article>` all used meaningfully. |
| 1.2     | Apply accessible colour schemes with contrast                             | A targeted dark overlay is placed only behind the hero text, ensuring legibility regardless of background image brightness. |
| 1.3     | Write accessible content that communicates clearly                        | Headings and room descriptions use simple, readable language. Hero section introduces the site clearly, with strong text contrast and structure. |
| 1.4     | Responsive design applied for different screen sizes                      | Grid auto-resizes; font size of hero text adjusts for mobile screens. |
| 2.1     | Build responsive layouts with media queries or grid systems               | CSS Grid with `auto-fit` + `minmax()` used to create responsive room cards. |
| 2.2     | Implement accessible form controls                                        | `<label>` tags, `aria-describedby`, and `aria-required` attributes used in the contact form. |
| 2.4     | Provide `alt` attributes for non-decorative images                        | All room images use meaningful, descriptive `alt` text. |
| 2.5     | Apply colour and layout for readability and accessibility                | Visual hierarchy is reinforced through colour contrast (text on dark overlay), padding, and logical grouping of elements. No decorative cropping or obscured content. |
| 2.6     | Use appropriate input types and basic validation                          | Contact form uses `email`, `text`, `textarea`, and required fields. |
| 2.7     | Create interactive components with user feedback                          | Contact form is keyboard-accessible, focus-highlighted, and gives visual feedback on hover/focus states. |
| 2.3     | Ensure external links open in a new tab with safe attributes              | Footer link uses `target="_blank"` and `rel="noopener noreferrer"` for accessibility and security. |
| 3.1     | Create a README that explains the web app and its purpose                 | This file (README) documents the hotel app’s goals and user types. |
| 4.3     | Use Git/GitHub for version control                                        | Every feature committed in its own Git commit with descriptive message. |
