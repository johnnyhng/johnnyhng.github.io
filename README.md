# ezTalk public website

A dependency-free static website for ezTalk product information and Google OAuth branding/verification. It includes a homepage, Privacy Policy, Terms of Service, 404 page, favicon, and social sharing image.

## Deploy

Upload the contents of this folder to any static host (for example, GitHub Pages, Cloudflare Pages, Firebase Hosting, or Netlify). No build command or backend is required. Configure the host to serve `index.html` at the site root and use HTTPS.

## Required before publishing

1. Confirm that the Privacy Policy matches the app's actual behavior, Google OAuth scopes, service providers, retention, age requirements, and deletion process.
2. Confirm the Terms with qualified counsel for the developer's jurisdiction and intended users.
3. Update the effective dates if the policies are changed.
4. The configured production URL is `https://johnnyhng.github.io/eztalk/`. Update canonical, Open Graph, sitemap, and robots URLs if the site moves.
5. In Google Cloud Console, use the exact production homepage, Privacy Policy, and Terms URLs. The authorized domain must match the verified production domain.
6. Keep the product name, logo, developer identity, and support address consistent between this site and the OAuth consent screen.

## Files

- `index.html` — product homepage
- `privacy.html` — privacy and Google user data disclosure
- `terms.html` — terms and AI limitations
- `404.html` — static hosting fallback
- `assets/styles.css` — responsive, accessible styling
- `assets/favicon.svg` — site icon and compact brand mark
- `assets/social-card.svg` — social sharing artwork
- `robots.txt` — permits public indexing
- `sitemap.xml` — lists the production URLs

## Local preview

Serve this directory with any static file server and open the local URL in a browser. Directly opening `index.html` also works for basic review.

## Notes

- The site sets no cookies and includes no analytics, tracking, forms, remote fonts, or JavaScript.
- Legal text is a conservative template, not legal advice.
- Preserve public access to all three main pages during OAuth review; do not place them behind authentication.
