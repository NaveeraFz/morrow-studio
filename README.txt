MORROW STUDIO — WEBSITE PROJECT

FILES
- index.html: Home and product catalogue
- about.html: About page
- contact.html: Contact page
- login.html: Login page (noindex)
- signup.html: Sign-up page (noindex)
- location.html: Browser-permission location page with map preview
- product-details.html: Product details (product selected by URL id)
- style.css: Responsive styling
- app.js: Product, cart, account, forms and location interactions

RUN LOCALLY
1. Open this folder in Visual Studio Code.
2. Install/enable the Live Server extension if needed.
3. Right-click index.html and choose Open with Live Server.
4. Test the location page at http://localhost (Live Server). Allow location permission when prompted.

LOCATION TROUBLESHOOTING
- Browser geolocation requires HTTPS on a published website; localhost is also treated as a secure context for development.
- Click the location button and choose Allow in the browser prompt.
- If blocked, click the site controls icon beside the address bar > Site settings > Location > Allow, then reload.
- Device location services and a working internet/network signal may also be required.
- The page displays coordinates and an OpenStreetMap preview/link after permission is granted.

SEO CHECKLIST
- Each page has a unique title and meta description, semantic headings, descriptive image alt text and internal links.
- Login and signup pages are marked noindex,follow because private account forms generally should not appear in search results.
- Before launch, add canonical URLs and a sitemap.xml using the real public domain. Do not use placeholder or localhost canonical URLs.
- After publishing, test each public page with Chrome Lighthouse (Mobile and Desktop), Google Search Console URL Inspection, and PageSpeed Insights.
- Lighthouse SEO checks technical basics; it cannot guarantee rankings or indexing. Search performance also depends on useful original content, crawlability, links, page speed and competition.

PUBLISH WITH HTTPS (GITHUB PAGES)
1. Create/sign in to GitHub and make a new public repository.
2. Upload the contents of this project folder (not the ZIP itself) to the repository root.
3. In the repository open Settings > Pages.
4. Under Build and deployment, choose Deploy from a branch, select main and /(root), then Save.
5. Wait for the published site URL shown in Pages. GitHub Pages supplies HTTPS.
6. Open Settings > Pages and ensure Enforce HTTPS is enabled when available.
7. Use the https:// URL to test location access and submit the public pages in Google Search Console.

NOTE
This is a front-end learning project. Account information and cart data are stored in the browser only; there is no secure server authentication, database, payment processor or order fulfilment. Never use a real password.


LATEST UPDATE
- Location page now displays Clifton Block 4, Karachi, Pakistan as a clearly labelled sample map location. It does not request or display visitor coordinates.
- Light/dark theme switch is available in the navigation and remembers the selected theme on the same device.
- To test location map, use an internet connection because the embedded map is loaded from Google Maps.
