# Colin Pinkham Astro site, V23

V23 is a controlled mobile navigation revision based on V21.

Changes:
* Replaces the previous mobile navigation CSS with one explicit checkbox based implementation.
* Mobile header shows a clearly labelled Menu control and hamburger icon.
* Opening the control reveals About, Work, Career, Thinking, CV and Contact.
* Desktop navigation and desktop Contact control remain unchanged.
* Retains the V21 homepage portrait sizing fix.

Validation:
* BaseLayout.astro and global.css were inspected directly after modification.
* The mobile navigation selector and markup were checked for matching structure.
* A full Astro production build could not be completed in this environment because the Astro dependency is not installed locally and package installation times out.
* Therefore this package is NOT described as browser-validated or production-validated. Use a Netlify Deploy Preview, not a production deploy, for validation.
