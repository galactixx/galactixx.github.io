# Nicholas Wlezien — Academic Homepage

A minimalist, white-background academic website, inspired by [Minimal Academic Homepage](https://github.com/yangxinrui811/minimal-academic-homepage), customized with verified publication details from the [ACL Anthology](https://aclanthology.org/people/nicholas-wlezien/) and an [ORCID](https://orcid.org/0009-0006-5576-3672) link.

## Preview locally

Double-click `index.html` to open it in your browser. No installation, dependencies, server, or build step is required.

## Publish with GitHub Pages

1. Sign in at [github.com](https://github.com/).
2. Create a **public** repository named `<your-github-username>.github.io` (replace the angle-bracketed text with your exact GitHub username). You can use another repository name, but then the URL includes that repository's name.
3. Upload `index.html`, `assets/favicon.svg`, and `.nojekyll` from this directory to the **root** of the repository (keep the `assets` folder).
4. Commit these files to the default `main` branch.
5. Open **Settings → Pages → Build and deployment**. Choose **Deploy from a branch**, select **main**, and select **/(root)**; save.
6. Your homepage will be at `https://<your-github-username>.github.io/` once GitHub Pages finishes publishing. For a repository with another name, the URL is generally `https://<your-github-username>.github.io/<repository-name>/`.

## Customize

All content and styles live in `index.html`.

- Search for `Nicholas Wlezien` to edit your name and site titles.
- Update the About and Research sections as your interests evolve.
- Add publications by duplicating an `<article class="publication">...</article>` entry and changing its details and links.
- Add a GitHub **profile** link, personal email link, university affiliation, CV, or education information when you want to make them public. These are deliberately omitted, not guessed.
- To use a portrait in place of the initials tile, place your photo in `assets/profile.jpg` and replace the `<div class="avatar" ...>NW</div>` with `<img class="avatar" src="assets/profile.jpg" alt="Nicholas Wlezien">`; consider adding `object-fit: cover;` to the `.avatar` CSS declaration.
- To change the accent blue, edit `--link` and `--link-hover` at the start of the CSS.

## Verified publication

Nicholas Wlezien and Rakesh M. Verma. 2026. *When LLMs Say No: Diagnosing and Mitigating Conservative Bias in Authorship Verification*. In *Proceedings of EMNLP 2026*, 33771–33788. [ACL Anthology](https://aclanthology.org/2026.emnlp-main.1477/).

The supplied ORCID profile is linked, but any additional personal/education details on ORCID have not been assumed. This is an original static implementation inspired by the structure and ease of editing of the Minimal Academic Homepage template, not a fork of its source code.
