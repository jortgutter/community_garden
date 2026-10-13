# The Garden

A static, multi-page community garden site. GitHub Pages can publish these files directly; no build step is required.

## Structure

```text
.
├── index.html                 # Home page
├── pages/
│   ├── handbook.html          # Member handbook
│   ├── news.html              # News and events
│   ├── people.html            # Members and contacts
│   └── plot-records.html      # Seasonal plot and meeting notes
└── assets/
    └── css/
        └── site.css           # Shared site styles
```

Add new pages under `pages/` and link them from the navigation on each page. Pages in that folder should use `../assets/css/site.css` for the shared stylesheet and relative links to their sibling pages.

## Preview in VS Code

Install Microsoft's **Live Preview** extension, open `index.html`, then run **Live Preview: Show Preview** from the Command Palette (`Ctrl+Shift+P`). The local server lets you follow the site's links while previewing.

## Publish with GitHub Pages

1. Push the repository to GitHub.
2. In the repository, open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select the branch containing the site and the `/ (root)` folder, then save.
4. Open the published URL shown in the Pages settings.

This is a GitHub Pages website, rather than GitHub's separate repository **Wiki** feature. Keep the source files in the repository root as shown so Pages can publish them.
