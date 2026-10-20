# Johan V. Dinesen | Compact academic website

Static HTML/CSS site for GitHub Pages. No build system, Jekyll installation, JavaScript, or package manager is needed.

## Pages
- `index.html`: Home, short biography, and optional portrait.
- `research.html`: Research interests and selected papers.
- `publications.html`: Compact publication lists.
- `talks.html`: Invited talks, contributed talks, and conference organization.
- `teaching.html`: Course-by-course teaching experience.
- `cv.html`: Compact online academic CV with a PDF link.
- `assets/Johan_Dinesen_CV_public.pdf`: Public CV copied from the user-supplied PDF with the telephone number removed.

## Add your photo
Upload your portrait as `assets/profile.jpg`. It will appear on the right of the biography. Without a photo, that area is left empty. If using a `.png` instead, update the filename in `index.html`.

## Publishing
1. Create a public GitHub repository named `USERNAME.github.io`.
2. Upload the CONTENTS of this folder at the repository root, including `.nojekyll`, `assets/`, and `css/`.
3. Go to Settings > Pages > Deploy from branch > `main` / `(root)`.
4. Visit `https://USERNAME.github.io/` once Pages deploys.

## Maintaining the site
To change the navigation tabs, update the `<nav class="site-nav">` in every HTML page. To change typography, spacing or link colors, update `css/style.css`.

## Notes
- Links between HTML pages are relative and work with GitHub Pages and custom domains.
- Both the web CV and full PDF are included. The PDF copy omits the phone number. Original PDF remains unchanged outside the site files.
- Publication submission statuses and CV dates come from the September 2026 CV. Verify changes before publishing.
- The homepage grant item records the April 2026 award date and September 2026 funding start.
