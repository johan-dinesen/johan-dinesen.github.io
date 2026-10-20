# Johan V. Dinesen | Add Events page (four-page site)

This is the **latest** four-page version: **About · Research · Talks · Events**.
It is based directly on the previous clean three-page site. The existing About, Research and Talks page content has not been rewritten; only the navigation has been extended.

## What is in the Events page

- **Organized Events:** the Finnish Mathematical Days 2026 coding-theory session and the 2024 Workshop on Secure and Private Distributed Computation.
- **Conferences, Workshops and Schools Attended:** a compact reverse-chronological list drawn from the September 2026 academic CV.
- **Upcoming events:** no dates were provided, so no unverified upcoming-event entries were invented. Add them later when they are confirmed.
- Actual event date ranges were checked against official sources where links are given. Where only a month is documented in the CV, the month is shown rather than inventing a conference date range.

## Upload these files to your existing GitHub Pages repository

1. **Extract** this ZIP on your computer. Do not upload the ZIP itself.
2. Upload **all four HTML files at the repository root**: `index.html`, `research.html`, `talks.html`, and the new `events.html`. The first three files include a new Events link in their navigation.
3. Upload `css/phase1.css`, updating the existing stylesheet. Keep its folder structure as `css/phase1.css`.
4. `assets/favicon.svg` and `.nojekyll` are included for completeness and may be retained from your current site.
5. **Do not delete** your custom-domain `CNAME` file or `assets/profile.jpg`. Neither is included in this archive.
6. If your GitHub Pages deployment uses **Deploy from a branch**, edit the branch/folder configured in **Settings > Pages**. If you use a GitHub Actions workflow, edit the actual deployed source instead.
7. Commit the changes and verify that the navigation works on `/`, `/research.html`, `/talks.html`, and `/events.html`. Hard-refresh the browser after deployment.

### Important: old pages

Uploading the ZIP's extracted files does not remove old pages. If `cv.html`, `teaching.html`, or `publications.html` still exist in the publishing branch, those old URLs remain accessible until those pages are explicitly deleted. This package intentionally does not include them.

### Before adding future events

Only confirmable events from the 2026 CV were included. If you want to add attendance not reflected in the CV, or future events, edit `events.html` under the relevant list or create an Upcoming Events section. External links use the event organizers' official websites where available.
