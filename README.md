# Personal academic website

Plain HTML/CSS. No build step and no Jekyll, so GitHub Pages serves it as is.

## Deploy on GitHub Pages
1. Create a **public** repo named exactly `<your-github-username>.github.io`.
2. Upload every file in this folder (including `.nojekyll`) to the repo root.
3. Settings → Pages → Source: "Deploy from a branch", branch `main`, folder `/ (root)`.
4. After about a minute the site is live at `https://<your-github-username>.github.io`.

## Files to add
- `photo.jpg`: headshot, portrait ratio about 5:6. Then in index.html replace `<div class="photo">photo.jpg</div>` with `<div class="photo"><img src="photo.jpg" alt="Your Name"></div>`
- `cv.pdf`
- `papers/JMP.pdf`, `papers/JMP_appendix.pdf`, `papers/pareto_weight.pdf`

## To edit
Search index.html for `[` and `Your Name` to find every placeholder.
The accent color is `--accent` at the top of the `<style>` block.
