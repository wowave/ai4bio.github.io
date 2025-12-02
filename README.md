# ai4bio.github.io

This repository hosts the static homepage for the ai4bio.github.io GitHub Pages site. The site is a single `index.html` file served from the repository root.

## How to publish
1. Push changes to the `main` branch of this repository.
2. In the repository settings on GitHub, open **Settings → Pages** and ensure the source is set to **Deploy from a branch** using the **main** branch and the `/ (root)` folder.
3. If you previously enabled another Pages workflow, disable it or switch it to the branch deployment option above.

> Note: A `.nojekyll` file is included so GitHub Pages serves the site as-is without Jekyll processing.

## Local preview
To preview locally without a build step:

```sh
python3 -m http.server 8000
```

Then open `http://localhost:8000` in your browser.

## Profile image
To avoid committing large binaries, the profile image referenced by `index.html` (`img/Gemini_Generated_Image_yi0p6zyi0p6zyi0p.jpg`) is not tracked in the repository. Place the image manually in the `img/` directory when deploying or testing locally so the sidebar photo renders correctly.
