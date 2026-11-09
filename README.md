# oliverkraus-source.github.io

Source of my portfolio site: **https://oliverkraus-source.github.io**

A single `index.html` with no build step and no dependencies, served by GitHub Pages.

## Editing

All content lives in the `PROFILE` object near the bottom of `index.html`: text, skills,
projects, experience and contact details. The page builds itself from it. Push to `main` and
GitHub Pages republishes within a minute or two.

To add a CV download button, put the file next to `index.html` as `cv.pdf` and set
`cvUrl: "cv.pdf"`.

## Projects shown

- [DocuChat](https://github.com/oliverkraus-source/docuchat): ask questions about PDFs, with page-level citations
- [Job-Match Agent](https://github.com/oliverkraus-source/job-match-agent): AI agent that matches a CV against a job ad, with verified evidence
