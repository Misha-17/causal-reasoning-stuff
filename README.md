# Causal reasoning research website

A portable static website with five pages: overview, results, methods, searchable exact examples, and wider research. HTML, CSS, JavaScript and SVG assets are included. No build step, account, API key, package installation or external fonts are required.

## Preview

Open `index.html` in a browser after extracting this entire folder. Keep the HTML files and `assets` folder together. Navigation, the example search and the deterministic operation explorer work locally.

## Publish on GitHub Pages

1. Upload the contents of this folder to the root of your repository, including `assets` and `.nojekyll`. The entry file `index.html` must be at the root of the selected publishing folder.
2. In the repository, open **Settings → Pages**.
3. Under **Build and deployment**, select **Deploy from a branch**.
4. Select your branch, choose **/(root)**, and save.

If you prefer a `docs` publishing folder, place all these files inside `docs` and select that folder instead. Relative links also support project sites hosted beneath a repository URL.

Official GitHub guidance: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Content and evidence

The site synthesizes two supplied sources: a 112-page causal reasoning research report and a 68-package archived perturbation appendix, dated 9 October 2026. Page references identify locations within that supplied report. It is an evidence snapshot, not a live benchmark. Original private documents, local paths and personal metadata are intentionally excluded from the published bundle. Exact scientific prompt text is preserved where available, with private file references removed.

The results remain separated by population and evidence status. Historical archive labels are not independently authenticated model releases. Generated contrast tasks are not completed model evaluations. Manuscript results are not treated as raw-backed replications. The October run remains partial.

## Editing

Edit the HTML files directly. Shared appearance is in `assets/style.css`; browser-only interactions are in `assets/app.js`; charts and diagrams are vector SVGs. All links use relative paths.
