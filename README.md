# Ram Wasankar — Portfolio

A responsive, dependency-free portfolio for GitHub Pages. Open `index.html` in a browser to preview it. No installation or build step is required.

## Publish on GitHub Pages

1. Create a public GitHub repository named `YOUR-USERNAME.github.io`, replacing `YOUR-USERNAME` with your exact GitHub username.
2. Upload `index.html`, `research.html`, and `.nojekyll` to the repository root. Upload the extracted files, not the ZIP itself.
3. In the repository, open Settings → Pages.
4. Under Build and deployment, select Deploy from a branch, choose `main` and `/ (root)`, and save.
5. After deployment completes, your portfolio will be at `https://YOUR-USERNAME.github.io/`.

## Finish the links

The GitHub button links to the verified ram-wasankar profile. LinkedIn remains a disabled button until its actual URL is provided. Replace that disabled button in index.html with an anchor element using class="button" and your verified URL. Project repository, demo, publication, and résumé download links also await verified URLs or files. Email and Call buttons are functional.

## Edit

All content and styles are in `index.html`. Colors are defined at the top of its style block. The site uses system fonts, loads no external scripts or fonts, and includes mobile and print layouts, visible keyboard focus, and a skip link.

## Update current research later

The Current research & project button opens `research.html`, a separate page. Open that file and find the comments `EDIT CURRENT RESEARCH BELOW` and `EDIT ONGOING PROJECT BELOW`. Replace the “Details coming soon” paragraphs with your content. Each section can contain headings (`<h3>`), paragraphs (`<p>`), bullet lists (`<ul><li>`), and links (`<a href="...">`). Commit the updated file to GitHub to deploy your changes. No changes to the homepage button are needed.
