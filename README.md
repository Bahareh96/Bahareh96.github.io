# Bahareh Dokhaei — Academic website

A static website prepared from the supplied CV. No build tools are required.

## Publish on GitHub Pages

1. Sign in to GitHub and create a new public repository named `YOUR-USERNAME.github.io`, replacing YOUR-USERNAME with your actual GitHub username.
2. Extract this ZIP. Upload the **contents** of `academic-website` to the repository root (index.html, style.css, .nojekyll, and the assets folder). Commit the files.
3. In the repository, open Settings → Pages. Under Build and deployment choose Deploy from a branch, then main and / (root), and Save.
4. Once deployment finishes, open https://YOUR-USERNAME.github.io. GitHub also displays the exact URL in Settings → Pages.

For an existing repository, preserve its existing files and configuration. You may instead use a new project repository; this website uses relative links and works under a project path too.

## Add your photograph

Save your portrait as `assets/portrait.jpg`. Your supplied portrait is included and displayed on the homepage. Use a portrait crop with your face near the center. Update the page and upload the file to GitHub.

## Edit content

Edit index.html for biography, publications, links, and education. Edit style.css for colors and layout. Replace assets/Bahareh_Dokhaei_CV.pdf with your updated CV, keeping the same filename. The downloadable CV is the supplied PDF, including its contact details.

Google Sites is an alternative for manual editing; these files are intended for GitHub Pages and cannot be directly imported as a Google Sites design.

## Preview

Open index.html in a browser. For a local server, run `python3 -m http.server 8000` in this folder and visit http://localhost:8000.

Content source: supplied 02_Dokhaei_CV_3.pdf. Prepared November 2, 2026. Publication metadata reproduced from that CV. This package has not been deployed to a GitHub account.
