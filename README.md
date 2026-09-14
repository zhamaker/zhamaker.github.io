# Zachary Hamaker — academic website

A static academic website for **https://zhamaker.github.io/**. It includes an introduction, 31 publication entries with arXiv links, teaching history, Ph.D. students, and a downloadable CV.

## Publish on GitHub Pages

1. Add these files and folders to the root of `zhamaker/zhamaker.github.io` and commit them to `main`.
2. Open the repository's **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select **main** and **/(root)**, then **Save**.
5. The website will appear at https://zhamaker.github.io/. GitHub may take several minutes to finish publishing.

No package installation or build command is needed. GitHub's current instructions: https://docs.github.com/en/pages/quickstart

## Make updates

| Content | File |
| --- | --- |
| Introduction, contact information, recent papers | `index.html` |
| Complete publication list | `research.html` |
| Courses and teaching history | `teaching.html` |
| Ph.D. students and mentorship | `students.html` |
| Downloadable CV | `files/HamakerCV.pdf` |
| Colors, spacing, and responsive layout | `assets/style.css` |
| Browser icon | `assets/favicon.svg` |

You can edit the HTML directly in GitHub using the pencil icon. Add new publications to `research.html`, then update the recent-work section in `index.html`. Replace the PDF with the same filename to keep the CV link stable. Adding a PDF to `files/` makes it available at `https://zhamaker.github.io/files/your-filename.pdf`; link it from any page with `<a href="files/your-filename.pdf">Download PDF</a>`.

The pages are readable without JavaScript and use system fonts. The `.nojekyll` file allows GitHub Pages to serve them directly. There are no trackers, external font requests, or forms.

## Content notes for the owner

The supplied LaTeX CV is the source for appointments, publications, teaching, and students. The introduction summarizes the research subjects represented in the CV and on the existing UF research page. Current publication statuses follow the supplied CV; they have not all been independently rechecked with publishers. The course list is historical through Spring 2026 and does not claim a Fall 2026 assignment.

Obvious spelling and formatting errors were cleaned up for the website: “Associate,” “Joshua Arroyo,” and the `MHF 3202` course prefix (confirmed on the existing UF teaching page). The downloadable CV was compiled from a separate working copy of the supplied source, with small compilation/formatting fixes and the two spelling fixes. The original Dropbox file was not edited. The PDF retains the effective 10-point type of the supplied source.

Useful source pages:

- https://people.clas.ufl.edu/zhamaker/research/
- https://people.clas.ufl.edu/zhamaker/teaching/

All HTML links are relative, so the site can also be previewed by opening `index.html` locally.
