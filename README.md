# Clean & Clear Services — Website

Static website for Clean & Clear Services (Tirupati, Chandragiri, Renigunta, Karkambadi).

## Files
- `index.html` — the full website (single file, all styles/images/scripts embedded)
- `sitemap.xml` — tells search engines what pages exist
- `robots.txt` — tells search engines they're allowed to crawl the site

## How to host this for free on GitHub Pages

1. **Create a repository**
   - Go to github.com → New repository
   - Name it anything, e.g. `clean-and-clear-website`
   - Make it Public
   - Click "Create repository"

2. **Upload the files**
   - On the repo page, click "Add file" → "Upload files"
   - Drag in `index.html`, `sitemap.xml`, and `robots.txt`
   - Click "Commit changes"

3. **Turn on GitHub Pages**
   - In the repo, go to Settings → Pages
   - Under "Source", choose the `main` branch and `/ (root)` folder
   - Click Save
   - GitHub will give you a live URL like:
     `https://yourusername.github.io/clean-and-clear-website/`
   - It usually goes live within a minute or two.

4. **(Optional) Connect your own domain**
   - If you buy `cleanandclearservices.com`, go to Settings → Pages → "Custom domain" and enter it
   - Follow GitHub's instructions to point your domain's DNS at GitHub Pages
   - Note: if you do this, update the URLs inside `sitemap.xml` and the `<meta>`/JSON-LD tags in `index.html` to match your real domain (they currently assume `https://www.cleanandclearservices.com/`)

5. **Submit to Google**
   - Once live, go to Google Search Console (search.google.com/search-console)
   - Add your GitHub Pages URL (or custom domain) as a property
   - Submit the sitemap: `sitemap.xml`

## Notes
- The sample testimonials in the Reviews section are placeholders — replace them with real customer quotes once you have them.
- All booking is routed through WhatsApp (no online booking or pricing shown), as designed.
