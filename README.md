# Johan V. Dinesen: academic website

A static academic website based on the provided September 2026 academic CV. This package is an editable HTML/CSS project for GitHub Pages, not an imported copy of any other academic site and not a Jekyll site.

## Included pages

- `index.html`: biography, affiliation, obfuscated contact email, research interests, and documented highlights
- `research.html`: research overview and topics linked to preprints
- `publications.html`: five papers from the CV, grouped by preprints and conference/journal papers
- `cv.html`: HTML academic CV, including education, employment, papers, awards, organization, invited/contributed talks, visits, secondment, teaching, services, skills
- `css/style.css`: all style rules (responsive on mobile)
- `assets/favicon.svg`: JD initials favicon

The visible contact address is `johan.dinesen [at] aalto [dot] fi`, as requested. There is **no mailto link**, **no print-CV button**, **no PDF download**, and **no phone number** on the public site. The original CV file is **not included** in this package.

## How to publish without installing software

1. In GitHub, create a **public** repository called `YOUR-GITHUB-USERNAME.github.io`, substituting your GitHub username exactly.
2. Download and unzip this website. Upload the *contents* of the unzipped directory to the root of that repository, preserving the `css/` and `assets/` directories. `index.html` must be at the top level. Commit the upload.
3. Go to **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, `main`, and `/(root)`, then **Save**.
4. Visit `https://YOUR-GITHUB-USERNAME.github.io/`. Your CV appears at `/cv.html`.

The `.nojekyll` empty file is included to bypass Jekyll processing on GitHub Pages. It is optional for these simple files.

## Editing and updating

Edit the relevant `.html` file in GitHub and commit the changes. Changes are published automatically.

- The name, institutional affiliation, degrees, dates, papers, events, awards, services and skills come from your supplied CV, last updated **September 2026**.
- The *research overview* and *highlights* condense wording from that CV. Review before publishing in case you prefer different phrasing.
- Publication submission statuses are accurate to the supplied CV's date, not independently checked against journal websites; update them when decisions/publications change.
- Links to the three arXiv preprints are based on the identifiers in your CV.
- I have not invented links to a Google Scholar account, ORCID, personal GitHub profile, or your institutional profile. Add verified links when ready.
- The homepage displays a neutral "JD" initials block, not a stock portrait. If you want a photograph, upload it as `assets/profile.jpg`, and change the `.initial-monogram` element in `index.html` to an `<img>` element. Adjust CSS for `.profile-aside` as needed.
- You can edit the email's text format on `index.html` and `cv.html`. It is deliberately not clickable.
- I omitted your telephone number on the public site for privacy. Add it only if you want it discoverable online.

## Before publishing

Review your introductory biography, research themes and 2026 highlights; confirm all names and dates; decide whether you want to add a photo; check that any manuscript status has not changed since September 2026.

## Useful references

- GitHub Pages: https://docs.github.com/en/pages/quickstart
