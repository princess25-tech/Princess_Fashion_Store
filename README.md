# Princess_Fashion_Store
## Project overview
A responsive static website concept for Princess Fashion Store, a clothing retailer in Polokwane, South Africa. It includes a home page, a product/service enquiry page and a general contact page.

## Files
- `index.html` — home page, business information, clothing categories and category search/sort.
- `enquiry.html` — product, availability, pricing and partnership/volunteer enquiry form with a dynamic summary.
- `contact.html` — general message form and embedded Google Maps search.
- `style.css` — responsive styling, focus states, animations and reduced-motion support.
- `script.js` — category search/sort, interactive category cards, client-side form validation, dynamic enquiry summary, email composition and scroll reveal.
- `robots.txt` — crawler guidance (replace placeholder domain before deployment).
- `sitemap.xml` — sitemap (replace placeholder domain before deployment).

## Run locally
Open `index.html` in a browser, or use Visual Studio Code with the Live Server extension. Test all three pages and use browser developer tools to check for errors.

## Forms: important limitation
This is a static website, so it has no server or database. JavaScript validates each form and composes a message addressed to `info@princessfashionstore.com` using the visitor's default email application. The visitor must review and send the email. The site does **not** send messages automatically, store submissions, check live inventory or confirm prices. For true AJAX submission, connect a form backend/service (for example, a configured Netlify Forms endpoint or a serverless function) and update the form handler/action. Do not claim AJAX or automatic delivery until it is implemented and tested with a real endpoint.

## SEO work
- Unique page titles and meta descriptions.
- Relevant keywords, semantic heading hierarchy and descriptive navigation.
- Responsive/mobile-friendly CSS and keyboard focus states.
- Searchable category content and internal links.
- `robots.txt` and `sitemap.xml` included; replace `YOUR-GITHUB-USERNAME` and `YOUR-REPOSITORY` with the real deployed URL before publishing.
- Google Maps embedded on the contact page.
- Image guidance: use descriptive filenames and meaningful `alt` text for any real product photos added later. Only use images you own or have permission to use, and document the source/licence below.
- Off-page SEO tasks such as earning reputable backlinks and maintaining social profiles require ongoing promotion and cannot be completed by HTML alone.

## Testing checklist
- [ ] Home, enquiry and contact pages load and navigation links work.
- [ ] Search filters categories; sorting changes order.
- [ ] Forms show field-level errors for missing/invalid inputs.
- [ ] Valid enquiry shows a summary and opens an email draft.
- [ ] Valid contact message opens an email draft.
- [ ] Check desktop and mobile layouts, keyboard navigation and reduced-motion setting.
- [ ] Check console for errors and test on current Chrome, Firefox, Safari and Edge.
- [ ] Replace placeholder sitemap/robots URLs and test after deployment.
- [ ] Verify the recipient email address and store details with the business before submission.

## Deployment (GitHub Pages)
1. Create a GitHub repository and upload the project files to the repository root.
2. Commit changes with descriptive messages, e.g. `Add validated contact and enquiry forms`.
3. Open **Settings → Pages**, choose deployment from the `main` branch and `/ (root)`, then save.
4. After the site is published, update `robots.txt` and `sitemap.xml` to use the exact live URL.
5. Test all links and forms on the published website. The email draft workflow requires a mail app configured by the visitor.

## Changelog
### Part 3 — 27 October 2026
- Renamed the original `index html.html` to `index.html` so it works as the default home page on common static hosting platforms.
- Added `script.js` for category search and sorting, keyboard-accessible category interactions, client-side form validation, dynamic enquiry summary, email-draft composition and scroll-reveal animation.
- Added dedicated `enquiry.html` and `contact.html` pages with distinct form purposes and HTML5 constraints.
- Added embedded Google Maps search to the contact page.
- Added page-specific SEO titles, meta descriptions, keywords, robots metadata, `robots.txt` and `sitemap.xml`.
- Added responsive form styling, accessibility focus states and reduced-motion handling.
- Kept the site static; no backend/AJAX endpoint or live inventory service is configured. See the Forms limitation above.

### Feedback from Part 2
No formal Part 2 marker feedback was included with the files supplied for this update. Add each actual feedback correction here once the feedback sheet is available; do not claim unverified corrections.

## References (Harvard style — IIE-adapted; accessed 27 October 2026)
- Google (n.d.) *Maps Embed API*. Available at: https://developers.google.com/maps/documentation/embed/ (Accessed: 27 October 2026).
- MDN Web Docs (n.d.) *Constraint validation*. Available at: https://developer.mozilla.org/en-US/docs/Web/HTML/Constraint_validation (Accessed: 27 October 2026).
- MDN Web Docs (n.d.) *Form validation*. Available at: https://developer.mozilla.org/en-US/docs/Learn/Forms/Form_validation (Accessed: 27 October 2026).
- MDN Web Docs (n.d.) *Intersection Observer API*. Available at: https://developer.mozilla.org/en-US/docs/Web/API/Intersection_Observer_API (Accessed: 27 October 2026).
- Google Search Central (n.d.) *SEO Starter Guide*. Available at: https://developers.google.com/search/docs/fundamentals/seo-starter-guide (Accessed: 27 October 2026).
- Sitemaps.org (n.d.) *Sitemaps XML format*. Available at: https://www.sitemaps.org/protocol.html (Accessed: 27 October 2026).
- The Apache Software Foundation (n.d.) *Robots.txt introduction*. Available at: https://httpd.apache.org/docs/2.4/howto/htaccess.html (Accessed: 27 October 2026).

The page copy and JavaScript in this project were written for this project. No third-party product images or logos have been added. If you add external code, fonts, images or other assets, cite each source and licence here.
