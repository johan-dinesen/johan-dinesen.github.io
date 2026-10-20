# Academic website starter

This is a lightweight, editable academic website designed to resemble the general organization of a minimalist academic portfolio such as Nikolaj Thams's website. It is **not** a copy of his repository and does **not** require Jekyll, Ruby, npm, or a build process.

## Pages

- `index.html`: homepage, brief biography, profile photograph, research interests, news
- `research.html`: research overview and projects
- `publications.html`: publications, working papers, presentations
- `cv.html`: CV entries and a print/save-as-PDF button
- `css/style.css`: typography, colors, layout, responsive behavior, print rules
- `assets/profile-placeholder.svg`: replace this with your photograph
- `assets/favicon.svg`: generic initial-based icon, replace if desired

## Publish on GitHub Pages without using a terminal

1. Sign in to GitHub. Create a new **public** repository with the exact name `YOUR-GITHUB-USERNAME.github.io` (substitute your GitHub account name). Choose "Add a README" if the form requires initial content.
2. Extract this ZIP on your computer. Open the GitHub repository, select **Add file > Upload files**, then upload the **contents of the extracted folder**, not the folder itself. `index.html` must be at the top/root of your GitHub repository. GitHub's web uploader does not always include hidden files such as `.nojekyll`; this file is optional for this plain static website, but you can create it with **Add file > Create new file**.
3. Commit the files. Go to **Settings > Pages > Build and deployment**. Select **Deploy from a branch** and choose the `main` branch, folder `/(root)`, then save.
4. Open `https://YOUR-GITHUB-USERNAME.github.io/` after GitHub Pages finishes publishing. GitHub says this can take up to approximately 10 minutes.

If GitHub does not offer **Add file > Upload files** for multiple folders in the way you expect, use github.dev (press the `.` key in the repository) and drag the extracted files/folders into the file explorer, then commit from Source Control. Alternatively upload each folder's contents with GitHub's web uploader. The key is preserving paths, for example `css/style.css`.

## Personalize

1. Replace every instance of `Your Name`, `Your University`, `your.email@university.edu`, and all bracketed placeholders.
2. Edit `<title>` and `meta description` in each `.html` page.
3. Add your real academic portrait at `assets/profile.jpg`; in `index.html`, change the image path from `assets/profile-placeholder.svg` to `assets/profile.jpg`, and update its alternative text to describe the photo.
4. For your CV, replace the illustrative dates, degrees, experience, teaching, and awards. Remove categories you don't need.
5. For publications, replace placeholders with proper bibliographic citations and real paper/DOI links. You can hide the peer-reviewed section until you have content.
6. Add links to Google Scholar, ORCID, GitHub, or your institutional profile in the `link-row` element on `index.html`.
7. Optionally upload `assets/cv.pdf` and uncomment/add a PDF download link as indicated in `cv.html`. A browser's **Print / Save PDF** action already works without an uploaded PDF.
8. Adjust colors in `css/style.css` using the variables at the beginning of the file.
9. Change dates on the example news entries and the footer year as required.

## Editing after launch

To make small edits, open a file in GitHub and click the pencil icon. Change the content and click **Commit changes**. GitHub Pages will publish the update automatically.

## Check before sharing

- All bracketed example text and fictional dated entries have been replaced or removed.
- Your real email and links are correct.
- Your photo is suitable for public viewing.
- Home, Research, Publications, and CV links work on mobile and desktop.
- No unpublished sensitive material appears anywhere in the site.

## Reference and alternative

- Nikolaj Thams's site: https://nikolajthams.github.io/
- His public repository: https://github.com/nikolajthams/nikolajthams.github.io
- Original Jekyll template that his repo was forked from: https://github.com/alshedivat/al-folio
- Official GitHub Pages setup: https://docs.github.com/en/pages/quickstart

If you want the same Jekyll foundation rather than a simple HTML lookalike, use the **Use this template** button on al-folio and follow its quick-start guide. Its `gh-pages` deployment instructions are different from the `main` branch setup for this static starter.
