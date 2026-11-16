# GioProdz — Chicago Sports Photography

One-page site for GioProdz, built on the HorizonX NOVARA Creative Studio template. Static HTML, CSS and JavaScript: no build step.

## Preview it

1. Start a local web server in this folder: `python3 -m http.server 8080`
2. Open `http://localhost:8080`

## Put it online

Upload `index.html` and the whole `assets/` folder to any static host (Netlify, Vercel, GitHub Pages, Cloudflare Pages).

## Edit it

- **Text, photos, services:** everything is in `index.html`. The services slider content is the `quotes` list in the script near the bottom.
- **Hero spiral:** the photo list is the `"images"` array in the Spiral Flux config near the bottom of `index.html` (20 photos max). Update the matching `<img>` tags inside `.sf-fallback` too.
- **Photos:** files live in `assets/`. Gallery cards are the `<figure class="wcard">` blocks; add or remove a block to add or remove a photo.
- **Contact details:** search `index.html` for `giopori@icloud.com` and `8722256752`.
- **Colors and fonts:** the `:root` block at the top of the `<style>` section.

