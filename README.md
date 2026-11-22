# Portfolio template

Files: `index.html` (the whole site), `assets/` (put your images and `CV.pdf` here).

## Edit
1. Open `index.html` in any text editor. Search for `[Your Name]`, `your.email`, `your-profile`, `your-username` and replace them.
2. Each project is one `<article>` block. Copy it to add one, change its `id`, delete the ones you don’t need. The project list at the top builds itself from these blocks (first image = thumbnail).
3. Images: put files in `assets/` and change `src="assets/placeholder.svg"`. Always fill in `alt`. Keep each image under ~500 KB (JPG, ~1600 px wide).
4. SolidWorks: export a PNG render (File > Save As > PNG, or PhotoView 360). An interactive 3D viewer is possible later (export GLB + `<model-viewer>`), but PNGs are enough.
5. YouTube: set the video to Unlisted, copy the code after `v=` in its link, and paste it in place of `VIDEO_ID`.
6. Save your CV as `assets/CV.pdf`.

## Publish
- **Netlify:** app.netlify.com/drop, drag the whole folder in. Rename the site in settings.
- **GitHub Pages:** create a repo, upload the files, then Settings > Pages > deploy from the `main` branch.

Open the live link on your phone before sending it, and keep it online until you get the results.
