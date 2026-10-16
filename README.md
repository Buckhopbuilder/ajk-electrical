# AJK Electrical website

Responsive website rebuilt from the original repository. No dependencies required.

- `npm run build` generates the 17 pages and local assets in `dist/`.
- `npm run check` checks the generated page links and metadata.
- `npm run preview` serves the build at http://127.0.0.1:4173.

The current site is a private design preview. Contact details were intentionally deferred. The enquiry planner reviews and downloads a text file locally; it does not submit enquiries, store them or book appointments. Unsupported testimonials and availability promises from the old site are not used.

Before customer launch: confirm business contact details, enquiry delivery, service scope, licence/insurance claims and business privacy/terms; then configure the public domain and search indexing. The original root HTML is retained as historical source; `build.mjs`, `site.js` and `css/site.css` define the new site.
