# Prajit T. Rajendran

Personal portfolio and academic website of **Prajit T. Rajendran**, Research Engineer at CEA LIST and PhD graduate in Computer Science from Université Paris-Saclay.

**[Visit the portfolio](https://prajit-rajendran.github.io/)** · [Google Scholar](https://scholar.google.com/citations?user=R2wEeSEAAAAJ) · [LinkedIn](https://linkedin.com/in/prajitrajendran) · [Email](mailto:praj99T@gmail.com)

## Research

My work focuses on trustworthy AI and AI safety, with interests in:

- LLM safety, hallucination detection, and factuality evaluation
- Uncertainty estimation and unknown-unknown detection
- Human-in-the-loop learning and stream-based active learning
- Safety-aware learning and cooperative AI
- Efficient video coding and quality assessment

## Explore the website

- **[About](https://prajit-rajendran.github.io/)** — background, research interests, and contact details
- **[Publications](https://prajit-rajendran.github.io/publications.html)** — research outputs with search and publication-type filters
- **[Projects](https://prajit-rajendran.github.io/projects.html)** — selected projects and interactive demos
- **[Experience](https://prajit-rajendran.github.io/experience.html)** — research and industry experience
- **[Education](https://prajit-rajendran.github.io/education.html)** — academic qualifications and doctoral research
- **[Recognition & activities](https://prajit-rajendran.github.io/service.html)** — awards, peer review, and teaching
- **[Curriculum vitae](assets/CV_Prajit_Rajendran.pdf)** — downloadable CV

## Built with

The site uses HTML, CSS, and vanilla JavaScript, with responsive layouts, light and dark themes, and client-side publication filtering. It is configured for static hosting on GitHub Pages and requires no build step or package installation.

## Run locally

Clone the repository and start a local server from its root:

```sh
git clone https://github.com/prajit-rajendran/prajit-rajendran.github.io.git
cd prajit-rajendran.github.io
python -m http.server 8000
```

Open [localhost:8000](http://localhost:8000) in your browser.

## Repository structure

```text
├── index.html           # About and research interests
├── publications.html    # Searchable publications
├── projects.html        # Selected projects and demos
├── experience.html      # Research and industry experience
├── education.html       # Academic background
├── service.html         # Recognition and academic activities
├── assets/
│   ├── style.css        # Site styles and responsive layouts
│   ├── main.js          # Theme toggle and publication filters
│   ├── photo.jpg        # Profile photograph
│   └── CV_Prajit_Rajendran.pdf
└── .nojekyll            # Serve the site as static files
```

## Updating the site

Edit the relevant HTML page to update its content. The profile sidebar and navigation are shared manually across all six pages, so keep them consistent when changing profile details or links.

Replace `assets/photo.jpg` to update the profile photograph, and replace `assets/CV_Prajit_Rajendran.pdf` to update the downloadable CV. Site styling lives in `assets/style.css`; theme switching and publication filters live in `assets/main.js`.

To publish through GitHub Pages, select **Deploy from a branch** in the repository's **Settings → Pages**, then choose the publishing branch and **/ (root)** folder.
