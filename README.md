# field-equation-website

Placeholder site for [Field Equation AS](https://fieldequation.co), served via GitHub Pages.

- **Domain:** `fieldequation.co`
- **Hosting:** GitHub Pages (deploys from `main` branch, root folder)
- **Stack:** Plain HTML + CSS, no build step

## Local preview

Open `index.html` in a browser, or run a tiny HTTP server:

```sh
python3 -m http.server 8000
```

Then visit <http://localhost:8000>.

## DNS (at Namecheap)

Apex `fieldequation.co` → four A records:

```
185.199.108.153
185.199.109.153
185.199.110.153
185.199.111.153
```

`www` → CNAME `vctrh.github.io`.

Source: <https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site>.
