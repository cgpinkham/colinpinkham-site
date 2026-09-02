# Colin Pinkham Astro site, V20

V20 is a corrective mobile navigation build.

Changes:
* Removed the obsolete JavaScript mobile menu CSS.
* Kept one native HTML `<details>` mobile navigation implementation.
* Mobile navigation contains About, Work, Career, Thinking, CV and Contact.
* The desktop Contact button is hidden at mobile widths, so it cannot appear as the only mobile navigation item.
* Desktop navigation remains unchanged.
* Corrected Jembi date wording to 2022–2026 where applicable.

Validation performed on the source:
* BaseLayout contains the mobile menu and all six primary navigation links plus Contact.
* There is one `.mobile-nav` rule and one `.mobile-menu` rule in the stylesheet.
* No `2022–Present` or `2022-Present` remains in `src`.
* Required Contact success and 404 pages are present.

Limitation:
* Full Astro compilation could not be run because `npm install --no-audit --no-fund` timed out in this environment. Netlify remains the deployment build validator.
