# Prajit Rajendran — personal website

A responsive, dependency-free academic website, inspired by the clean AcademicPages layout of the supplied reference.

## Preview

From this folder run `python3 -m http.server 8000`, then visit http://localhost:8000. You can also open index.html directly.

## Edit

- `index.html`: recruiter-facing introduction and research interests
- `publications.html`: all 24 CV-listed research outputs, searchable and filterable
- `experience.html`: research and industry experience
- `service.html`: awards, recognition, peer review and teaching
- `assets/style.css`: layout, colours and responsive styles
- `assets/main.js`: theme toggle and publication filters
- `assets/CV_Prajit_Rajendran.pdf`: downloadable original CV

Replace the PR initials in each profile sidebar with a real photograph when available. Profile information is repeated in the four HTML files; update all four when changing contact details. No invented photograph or publication links were added. DOI and arXiv links come from the CV. The CV is copied unchanged and includes personal contact information; review it before public deployment.

## Publish on GitHub Pages

Put these files in the root of a GitHub repository. In repository Settings → Pages, select Deploy from a branch, choose the branch and / (root), and save. The .nojekyll file permits serving this static site directly. All internal links are relative, so project repositories also work. No build process is required.

This website has been saved locally; it has not been published.

## Add project code links

In `projects.html`, find each `<!-- Add this project` comment and replace it with a link, for example `<a href="https://github.com/your-account/your-project">Code ↗</a>`. The three project summaries are grounded in the supplied CV; no performance numbers or availability claims have been added.

## Deployed portfolio demos

The Projects page features FedSALAT Lab (https://fedsalat-lab.vercel.app/), The Judgment Lab (https://ai-debate-judgment-lab.vercel.app/), and Kinghunter (https://kinghunter-ogss.vercel.app/). Summaries describe the deployed experiments and distinguish research findings from visitor interactions. Add repository links at the existing HTML comments.

- `projects.html`: dedicated portfolio page with three deployed demos and project summaries. The Projects tab appears in the navigation on all pages.

- `education.html`: dedicated Education tab with doctoral, master’s and bachelor’s degrees, thesis title, and locations.
