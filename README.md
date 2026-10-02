# scaffoldingriverside.com

Static HTML and CSS site. No build step and no JavaScript.

Pages:

- `/` Scaffolding in Riverside, CA (city page)
- `/services/`
- `/about/`
- `/instant-quote/` (Netlify form `quote`)
- `/contact/` (Netlify form `contact`)

Shared styles are in `assets/style.css`.

## Deploy on Netlify

Connect this repo in Netlify. Leave the build command empty. The publish directory is the repo root (set in `netlify.toml`).

Form submissions show up under Site > Forms. Turn on form detection and add an email notification there.
