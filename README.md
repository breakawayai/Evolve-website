# Evolve Data Center Solutions — website

Static HTML site (29 pages). No build step: Netlify publishes this folder as-is.

Live: https://evolve-home-concept-b.netlify.app

Workflow: edit files → commit → push to `main` → Netlify deploys automatically (about a minute).

Conventions: every page is `<path>/index.html` with its own inline CSS/JS; assets live in `img/`. Bump the version suffix (`-v2`, `-v3`…) on any re-rendered image or video so browsers don't serve the cached one.
