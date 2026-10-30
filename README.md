# notes from my life

A tiny personal writing archive using plain HTML/CSS/JavaScript. No build tools required.

## Files
- `index.html`: public website
- `data.js`: your thoughts, organized by month and themes
- `editor.html`: a lightweight editing interface (drafts stay in *your browser* until exported)

## Publish with GitHub Pages
1. Create a public repository on GitHub.
2. Upload `index.html`, `editor.html`, and `data.js` to its root.
3. In **Settings → Pages**, choose **Deploy from a branch → main → / (root)**.
4. Open your GitHub Pages URL.

## Add thoughts without editing code
1. Open `editor.html` in your browser, either locally or at `https://USERNAME.github.io/REPO/editor.html`.
2. Add or edit your thoughts, choose a month and optional thematic categories.
3. Click **download updated data.js**.
4. Go to the GitHub repository and upload the updated `data.js`, replacing the old version; commit.
5. Refresh the live website after GitHub Pages deploys.

**Important:** The editor is public if your GitHub Pages site is public, but changes only save as drafts inside each visitor's own browser. Visitors cannot publish changes to your GitHub repository through it. It is not authenticated and does not store secrets. You can keep `editor.html` off GitHub and open it locally alongside `data.js` if you don't want the editor page publicly accessible (use a local static server for best results).

**Draft caution:** Use the export button after writing. Browser drafts can be lost if browser data is cleared or you switch devices. To move between devices, always publish the updated `data.js` first.
