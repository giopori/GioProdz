# GioProdz — Chicago Sports Photography

One-page site for GioProdz. Plain HTML, CSS and a small script in `index.html`: no build step and no libraries.

## Preview it

1. Start a local web server in this folder: `python3 -m http.server 8080`
2. Open `http://localhost:8080`

## Put it online

Upload `index.html` and the whole `assets/` folder to any static host.

## Edit it

- **Text, services, contact details:** all in `index.html`.
- **Photos:** each photo in `assets/` has a full-size file and a smaller `-sm` copy (720px wide) used in the hero wall and the grid. The full-size file opens in the photo viewer.
- **Gallery:** the `<button class="card">` blocks inside `.grid`. Add or remove a block to add or remove a photo.
- **Hero photo wall:** the `<div class="wall-col">` blocks. Each column lists its photos twice so the drift loops without a jump.
- **Colors and fonts:** the `:root` block at the top of the `<style>` section.

See `CREDITS.md` for licenses.
