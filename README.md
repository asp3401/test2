# GitHub Pages Starter Website

A complete, responsive static website you can upload directly to a GitHub repository. It does not need Node.js, a build command, or any dependencies.

## Project structure

```text
github-pages-starter/
├── index.html
├── README.md
└── assets/
    ├── style.css
    └── home-image.svg
```

## Edit the sample content

Open `index.html` and search for `Alex Morgan`, `Creative Designer & Digital Creator`, the sample description, `+1 (555) 010-2345`, and `hello@example.com`. Replace them with your own details. Update the copyright/name in the footer too.

The home illustration is `assets/home-image.svg`; replace it with your own image if you want. If you use a different filename, update the image `src` in `index.html`.

## Publish on GitHub Pages

1. Create a GitHub repository (for a project site, any repository name is fine).
2. Upload **the contents of this folder** to the repository's root. `index.html` must be at the top level—not inside another nested project folder.
3. Open **Settings → Pages** in the repository.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select branch `main` and folder `/(root)`, then click **Save**.
6. Wait a few minutes and open the URL shown in the Pages settings. A project site normally looks like `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`.

For a user/org site whose repository is named exactly `YOUR-USERNAME.github.io`, the URL is `https://YOUR-USERNAME.github.io/`.

## If you still see a 404

- Confirm `index.html` is in the repository root and the filename is lowercase.
- Confirm Pages is enabled and configured for the branch/folder where you uploaded the files.
- Use the URL shown in Settings → Pages; project sites need the repository name in the path.
- Wait a few minutes after saving, then refresh or try a private/incognito window.
- GitHub Pages serves static HTML/CSS/JS; it does not run server-side code such as PHP.
