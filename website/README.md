# Valence Client website

One page (`index.html`) plus the icon. No build step.

## Put it online with your own link (free)

You already have a Cloudflare account from the player counter, so Cloudflare Pages is the quickest:

1. Open a terminal in this folder.
2. Run `npm run deploy` (signs you in to Cloudflare the first time).
3. Your site is at **https://valence-client.pages.dev**.

Want a different name? Change `valence-client` in `package.json` before step 2 (it must be free on pages.dev).

### Your own domain (like valenceclient.com)

Buy the domain (Cloudflare Registrar, Namecheap...), then in the Cloudflare dashboard open
Workers & Pages > valence-client > Custom domains > Set up a domain, and follow the steps.

### Other free hosts

- **Netlify Drop:** go to app.netlify.com/drop and drag this folder in. You get a link like valence-client.netlify.app.
- **GitHub Pages:** put these files in a repo, then Settings > Pages > Deploy from branch.

## Changing the download links

Search `index.html` for `releases/latest` and replace both links with where your files are.
