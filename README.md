# Academic website – Nurul Momen

Static site, no build step, no JavaScript, no third-party requests.

## Deploy on GitLab Pages
1. Push this folder to a GitLab repository (default branch).
2. The `pages` job in `.gitlab-ci.yml` publishes `public/`.
3. Find the URL under **Deploy → Pages** in the project.

A repository named `<username>.gitlab.io` is served at the root domain;
any other name is served under `/<repo-name>/`. All paths are relative, so both work.

## Editing
- Content: `public/index.html`
- Styling: `public/styles.css` (light/dark follows the visitor's system setting)
- Add publications by copying an existing `<li class="pub">` block.
- Add Google Scholar / ORCID links in the commented block in the sidebar.
