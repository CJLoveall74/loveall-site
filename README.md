# Loveall.tech

A static About and resume site intended for GitHub Pages and `loveall.tech`.
There is no build step or runtime dependency.

## Editing

- `index.html`: text, links, and page structure.
- `resume.html`: experience, education, and skills.
- `style.css`: layout, colors, and responsive styling.
- `favicon.svg`: browser icon.

Preview by opening `index.html` in a browser or running
`python3 -m http.server 8000` in this directory.

## Publishing

After enabling GitHub Pages for the desired branch, configure the custom domain
in GitHub Pages settings and follow GitHub's DNS instructions. Preserve the
domain's existing email and other DNS records. Changes to the published branch
will be deployed by GitHub Pages.

The site is static and can be moved to another host without changing its content.
