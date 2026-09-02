# ayushjha.github.io — academic website

Static site. No build step, no dependencies.

## Files

- `index.html` — the whole site (Home / Research / Teaching, hash-routed)
- `styles.css` — design tokens and components
- `Ayush_Jha_CV.pdf` — linked from the nav and footer
- `.nojekyll` — tells GitHub Pages to serve files as-is

## Add your photo

Drop a portrait named exactly `photo.jpg` next to `index.html`. Portrait
crop, roughly 4:5, at least 800px wide. Until it exists the page shows a
placeholder in its slot.

## Write your bio

Open `index.html`, find `Your bio goes here`, and replace the two
placeholder paragraphs. Delete `font-style: italic` and the muted
`color:` from those two `<p class="lede">` tags so the text sets in the
normal body colour.

## Deploy on GitHub Pages

1. Copy everything in this folder to the root of the `main` branch of
   `Ayush0345/Website`.
2. Repo → **Settings → Pages**.
3. Source: **Deploy from a branch**. Branch: `main`, folder: `/ (root)`. Save.
4. Live in a minute or two at `https://ayush0345.github.io/Website/`.

To use a bare `ayush0345.github.io` address instead, rename the repository
to `Ayush0345.github.io`.

## Updating the CV

Replace `Ayush_Jha_CV.pdf` with the new file, keeping the same filename, and
commit. Nothing else needs to change.
