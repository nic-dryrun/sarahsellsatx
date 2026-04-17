# Sarah Sells ATX

The personal website for **Sarah Lechner**, realtor with Magnolia Realty and The Schauer Team in the greater Austin, Texas area.

**Live site:** https://nic-dryrun.github.io/sarahsellsatx/

## What's inside

A fast, modern, single-page static site — no framework, no build step. Deployable anywhere that serves static HTML.

```
sarahsellsatx/
├── index.html        # All page content
├── styles.css        # Design tokens, layout, components
├── main.js           # Theme toggle, sticky header, scroll reveal, mobile nav
├── assets/
│   └── images/       # Portraits + "Who I serve" photos
└── README.md
```

## Design

- **Type:** Fraunces (display serif) + Inter (body sans)
- **Palette:** Warm cream surface, deep olive primary, terracotta accent
- **Dark mode:** Follows system preference with a manual toggle
- **Responsive:** Mobile-first, tested down to 375px

## Content sources

- Bio and voice: [sarahsellsatx.com](https://www.sarahsellsatx.com/)
- Reviews: [experience.com](https://www.experience.com/reviews/sarah-lechner-274281)
- Team information: [schauerteamrealty.com](https://www.schauerteamrealty.com/meet-the-team)

## Local development

Open `index.html` directly in a browser, or run any static server:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Hosting

This site is hosted via **GitHub Pages** from the `main` branch. Any push to `main` automatically redeploys.

### First-time GitHub Pages setup

1. Go to **Settings → Pages**
2. Under **Source**, select **Deploy from a branch**
3. Branch: `main`, Folder: `/ (root)`
4. Save — your site will publish at `https://<username>.github.io/sarahsellsatx/`

### Custom domain

To use `sarahsellsatx.com`:

1. Add a `CNAME` file to the repo root containing `sarahsellsatx.com`
2. In your domain registrar, add these DNS records:
   - `A` records for the apex (`@`) pointing to GitHub Pages IPs:
     `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
   - `CNAME` record for `www` pointing to `nic-dryrun.github.io`
3. In **Settings → Pages**, enter your custom domain and enable **Enforce HTTPS**

## License

All content and photography © Sarah Lechner. Code is available for personal reference.
