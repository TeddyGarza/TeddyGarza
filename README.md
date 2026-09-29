# Teddy Garza — portfolio site

Live at: https://YOUR-USERNAME.github.io

## Files
- `index.html` — all the page content (text, projects, experience)
- `style.css` — colors, fonts, layout
- `images/` — every photo on the site
- `Teddy_Garza_Resume.pdf` — linked from the Resume buttons

## Add a photo to a project
1. Upload the photo into the `images` folder (use a simple name like `hub-on-car.jpg`, no spaces).
2. In `index.html`, find the project and its `<div class="gallery">`.
3. Copy one existing `<figure>...</figure>` line, paste it below, and change the file name, alt text, and caption.
4. Add `class="wide"` to the `<figure>` if you want the photo to span the full width.

## Update your resume
Upload a new PDF with the exact same name, `Teddy_Garza_Resume.pdf`, and replace the old one.

## 3D model
The spinning hub is `model/front-hub-assembly.glb`, shown with Google's model-viewer.
It only loads on the live site (or a local server), not when you double-click index.html.
To swap in a different model, replace the .glb file (keep the name) or change the `src` in index.html.

## About carousel
Photos live in `images/` and videos in `video/`. To add one, copy a `<figure class="slide">` block in the About section of index.html and change the file name and caption.
Keep videos short (under ~20 MB) and saved as H.264 .mp4 so they play in every browser.
