KyuHo Song Lab — GitHub Pages
Files
`index.html`
`styles.css`
`script.js`
Deploy to GitHub Pages
Put these three files in the root of your GitHub Pages repository.
Commit and push.
In GitHub: Settings → Pages
Under Build and deployment, choose Deploy from a branch.
Select your main branch and `/ (root)`.
Save.
Easy edits
Main headline
Edit in `index.html`:
`<h1>Advancing Quantitative Medical Imaging</h1>`
Research sections
Search for:
Quantitative MRI
Multinuclear & Metabolic MRI
RF Engineering & MR Hardware
Computational Imaging
Publications
Replace the placeholder publication blocks inside:
`<div class="publication-list">`
PI photo
Currently the page uses a KS monogram. If you want to use a portrait:
Add a photo, e.g. `images/kyuho-song.jpg`
Replace:
`<div class="person-avatar">KS</div>`
with:
`<img class="person-photo" src="images/kyuho-song.jpg" alt="KyuHo Song">`
Add this CSS:
`.person-photo { width: 140px; height: 140px; object-fit: cover; border-radius: 22px; }`
Notes
The hero graphic is built entirely with CSS + SVG, so no external image file is required.
