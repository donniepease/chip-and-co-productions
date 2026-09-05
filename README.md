# Chip & Co. Productions Website

Static site with no build step and no paid website builder required.

## Files
- `index.html` — page content
- `styles.css` — styling
- `script.js` — mobile navigation and automatic copyright year

## Preview locally
Open `index.html` in a browser.

## Free hosting option 1: GitHub Pages
1. Create a new GitHub repository.
2. Upload these files to the repository root.
3. Open Repository Settings → Pages.
4. Set the source to deploy from the `main` branch and `/root`.
5. Add your custom domain under Pages settings.
6. Update your domain's DNS records using the values GitHub provides.

## Free hosting option 2: Cloudflare Pages
1. Create a Cloudflare account.
2. Import the GitHub repository or upload the site.
3. No build command is needed.
4. Set the output directory to the repository root.
5. Add your custom domain in Pages → Custom domains.

## Customize
Search `index.html` for:
- `hello@chipandcoproductions.com` and replace it if needed.
- The three `.placeholder` blocks can be replaced with real images.

A simple image replacement example:
```html
<img class="work-image" src="images/portrait.jpg" alt="Portrait project description">
```

Create an `images` folder beside `index.html` and place your files there.
