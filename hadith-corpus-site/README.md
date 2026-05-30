# Hadith Corpus — Arabic / English Search

A static, searchable parallel corpus of 36,065 hadith (English translation +
Arabic original) from 8 collections. Search in either language; Arabic search
ignores diacritics (tashkeel). Data from sunnah.com via AhmedBaset/hadith-json.

## Files
- `index.html` — the search page (pure HTML/JS, no build)
- `data/corpus.json.gz` — gzipped corpus (~11 MB), decompressed in-browser
- `.nojekyll` — required so GitHub Pages serves the data/ folder

## Deploy on GitHub Pages
1. Create a repo, upload all files keeping the folder structure
2. Settings → Pages → Deploy from branch → main / (root)
3. Open https://<username>.github.io/<repo>/
