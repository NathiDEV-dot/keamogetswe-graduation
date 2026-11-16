# Keamogetswe's graduation scrapbook

Celebrating Keamogetswe Paula Moekets and her BSc in Network Engineering.

The live GitHub Pages website is `index.html`. It is self-contained, with no backend or upload form. Friends send their photos and messages to the organiser for inclusion.

## Editing

Download and extract `editable-source.zip`. Run `npm install` and `npm run dev` to preview. Add real entries to `github-pages/memories.json`, using objects with `id`, `name`, `memory`, `appreciation`, and `photo` (a relative photo URL or null). Place photos in `github-pages/public/photos` and reference them as `./photos/filename.jpg`.

Run `npm run build`. Upload `github-publish/index.html` as the repository root `index.html`. If photographs have been added, also upload the `pages-dist/photos` folder at the repository root, preserving paths. Update the source archive after source edits.

GitHub Pages serves the `main` branch, root folder. Only publish photos and messages intended for public sharing.
