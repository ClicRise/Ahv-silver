# AHV Silver

Static retail and wholesale jewellery catalogue, deployed to GitHub Pages.

## Local use

Requires Node.js 22 or later. No dependencies are needed.

```
npm run build
npm run check
npm start
```

Open http://127.0.0.1:4173. The build generates Home, Collection, About, Contact and ten individual product pages in `dist/`.

Product names and AHV-001–AHV-010 codes are editorial identifiers pending business review. Edit names and descriptions in `scripts/build.mjs`. Product weights, finishes, pricing, availability and delivery terms are confirmed directly by the business. WhatsApp enquiries go to +91 9820788694 and include the product name, code and canonical page URL. Font loading uses Google Fonts with local serif/sans-serif fallbacks.

## Deployment

Push to `main` to run `.github/workflows/pages.yml`. GitHub Pages must use GitHub Actions as its publishing source. Expected URL: https://clicrise.github.io/Ahv-silver/.
