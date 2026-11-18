# rimeltobgui.github.io

Personal research website of Rim ElTobgui (KUCARS, Khalifa University).

Static HTML and CSS, no build step. Fonts load from Google Fonts.

## Structure

- `index.html` home page
- `paper-*.html` one page per publication
- `css/site.css` shared styles
- `img/` figures, thumbnails and headshot
- `posters/` poster PDFs
- `video/` narrated video summaries (MP4)
- `.nojekyll` tells GitHub Pages to serve the files as they are

## Publish on GitHub Pages

1. Create a public repository named `rimeltobgui.github.io`.
2. Upload the contents of this folder to the root of the repository (not the folder itself).
3. In the repository, open Settings, then Pages. Under "Build and deployment", set Source to "Deploy from a branch", branch `main`, folder `/ (root)`, and save.
4. After a minute or two the site is live at https://rimeltobgui.github.io

To use a different repository name, the site will be served at `https://rimeltobgui.github.io/<repository-name>/`. All links are relative, so no changes are needed.

## Notes

- The largest files are the videos (up to about 20 MB each). This is within GitHub's 100 MB per-file limit.
- The browser upload on github.com accepts up to 100 files per batch, so the folder can be uploaded in one go.
- To update a page, edit the HTML file and commit. Changes go live within a few minutes.
