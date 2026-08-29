# 11.5.2 Avionics Systems - Interactive Revision

A GitHub Pages-ready course revision site.

## Current structure

```text
avionics-systems-revision/
├── index.html
├── .nojekyll
└── chapters/
    └── ata23/
        └── index.html
```

## Publish on GitHub Pages

1. Create a new **public** GitHub repository, for example `avionics-systems-revision`.
2. Extract this ZIP.
3. In the GitHub repository, choose **Add file > Upload files** and upload the contents of this folder so `index.html` is at the repository root.
4. Open **Settings > Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select branch **main** and folder **/(root)**, then **Save**.
7. After deployment, GitHub will show the public site URL.

## Add another chapter later

For example, if your next chapter is ATA 24:

```text
chapters/
├── ata23/
│   └── index.html
└── ata24/
    └── index.html
```

Rename the new chapter file to `index.html`, place it inside its folder, then add a chapter card/link to the root `index.html` such as:

```html
<a href="chapters/ata24/">Open ATA 24</a>
```

Use relative links so the site works both locally and on GitHub Pages.
