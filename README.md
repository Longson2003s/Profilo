# Nguyễn Viết Long Sơn — Web Design Portfolio

A lightweight, responsive, single-page portfolio for freelance landing page and e-commerce website services. The site is built as one standalone HTML file with its CSS and JavaScript embedded, so it can be opened directly in a browser or hosted as a static site.

## Features

- English is the default language; visitors can switch between English and Vietnamese with the language button in the header.
- The selected language and light/dark theme are saved in the browser when storage is available.
- Responsive layout with services, workflow, project placeholders, pricing, testimonials, FAQs, and contact links.
- Lightweight scroll-reveal effects that respect the reduced-motion preference.
- SEO description and Open Graph metadata for link previews.
- No build step, framework, or external library required.

## Run locally

Open `index.html` in a modern web browser. No server or dependencies are required.

## Customize before publishing

Edit `index.html` and replace the sample content with accurate information:

- Experience and the platforms or technologies you actually support.
- Project screenshots, descriptions, client-approved names, and verified outcomes.
- Package prices, delivery estimates, revisions, and post-launch support terms.
- Email address, phone/Zalo/WhatsApp number, and social profile URLs.
- The sample testimonial text and client details.
- The sample response-time commitment.
- `og:url` and `og:image` with the published site URL and a real preview image.

Search for bracketed notes such as `[add years]` or `[Add your phone number]`. Also replace sample email and profile links such as `son@example.com`, `0000000000`, and `your-profile`. The contact links and prices are examples until updated.

## Publish free with GitHub Pages

1. Push the repository to GitHub.
2. Open the repository's **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the `main` branch and the `/ (root)` folder, then save.
5. Wait for deployment. GitHub Pages will show the published URL in the Pages settings.

The repository needs `index.html` at its root, which is already the case here. Changes pushed to the selected branch will trigger a new deployment.

## Publish free with Netlify

1. Sign in to Netlify and choose **Add new site → Deploy manually**.
2. Drag and drop the project folder containing `index.html`.
3. Netlify will publish the static site and provide a site URL.

## Project files

```text
.
├── index.html   # Complete website: markup, embedded styles, and scripts
└── README.md    # Project and publishing instructions
```
