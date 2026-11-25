# Vindhya Vasini Degree College — Unofficial Website Demonstration

A multi-page, mobile-first static website concept prepared for presentation to the college. It is not an official college website and does not imply approval or commissioning. The project does not connect to or change `vvdcp.in`.

**Developer:** Purandar Sahu & Team · [purandarsahu.in](https://www.purandarsahu.in)

## Verified details used in the demo

- Institution: Vindhya Vasini Degree College, Paikmal, Bargarh, Odisha.
- University directory lists Sambalpur University affiliation and college contact details.
- Sambalpur University profile records establishment in 1994 and aided management.
- A 2023 Sambalpur University affiliation letter refers to +3 Arts and selected honours subjects for earlier sessions. The demo labels these as historical and asks the college to confirm current offerings.
- `vvdcp.in` is included only as a reported existing-domain reference. Ownership, account access, domain configuration and the present site status must be confirmed by the institution. Do not edit DNS, hosting or site files without written authorisation.

Sources and links are included on the About page and in `assets/js/data.js`.

## Project files

- Root HTML files: 15 institutional pages plus `404.html`.
- `admin/`: student login mock-up, admin login mock-up and content dashboard mock-up.
- `assets/css/site.css`: shared responsive design system.
- `assets/js/site.js`: shared rendering and demo interactions.
- `assets/js/data.js`: editable institution facts, notices, courses and gallery labels.
- `assets/images/`: original SVG emblem, favicon and campus illustration placeholders.
- `robots.txt`, `sitemap.xml`: preview indexing controls and an editable sitemap template.

## Run and edit on Android

1. Download and extract the ZIP using your phone's file manager.
2. Open the extracted folder in GitHub's mobile website or the GitHub app, then upload the project files while preserving folders.
3. In the repository, open **Settings → Pages**. Choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
4. GitHub Pages publishes at `https://YOUR-GITHUB-USERNAME.github.io/YOUR-REPOSITORY/`. Use that preview link for the presentation.
5. For a profile repository, GitHub Pages may publish at `https://YOUR-GITHUB-USERNAME.github.io/` instead. Update every placeholder URL in `sitemap.xml` to the actual approved preview URL.
6. Edit institution facts and demo notices in `assets/js/data.js`. Edit page text and interactions in `assets/js/site.js`; visual styling is in `assets/css/site.css`.
7. Upload approved photographs into `assets/images/` and update the relevant image paths and captions. Replace the illustrative logo only with a college-approved mark.

The project is plain HTML, CSS and JavaScript; it does not require a build command, npm, a paid hosting plan or secrets. It can also be opened locally by loading `index.html`, though some browsers may restrict embedded maps when opened from a local file.

## Demo behavior and limitations

- Website search indexes the site's configured page titles and sample notice text.
- Notice category and text filters work. “View details” displays the labelled placeholder information.
- Gallery tiles open a lightbox-style placeholder preview.
- The admission enquiry preview only takes a general topic and optional question; it sends nothing and clears the question after preview. Do not enter personal information.
- Student and admin login fields are disabled. No credentials are collected or checked.
- Dashboard tabs switch preview panels; management and upload actions are disabled and changes do not persist.
- The English/Odia control switches navigation labels and the demo banner. The rest of the content remains English and needs professional Odia translation and institutional approval.
- The map uses a Google Maps search embed and can be replaced with an institution-verified pin.
- No current notice, official document, faculty listing, student data, campus photograph, current admission claim or achievement is fabricated.

## Before an official launch

Get written approval from the college and the domain owner. Confirm the current academic information, contact details, official logo, campus photographs, staff directory, notices, downloads and privacy text. Secure the existing domain through the institution's authorised account holder. Remove the demo label only after formal approval. Update the sitemap to the authorised production domain and configure robots indexing intentionally.

For real authentication, database-backed notices, file uploads and saved admin changes, use Firebase or Supabase with access rules, server-side validation and an institution-controlled account. Do not treat a GitHub Pages dashboard or client-side password check as secure. Connect form submissions only after the college approves the data collection and privacy process.

## GitHub Pages deployment checklist

- Upload the complete directory tree to the repository root.
- Check **Settings → Pages** for the deployed source branch and URL.
- Open the deployment URL on a phone; test menu, search, filters, gallery and all page links.
- Keep `robots.txt` disallowing indexing while this remains an unofficial demo.
- Do not put student records, credentials, private staff data or internal documents in the repository.
