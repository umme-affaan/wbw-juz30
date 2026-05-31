# Juz 30 Multi-PDF Surah Viewer

A simple GitHub Pages website for Juz 30 where each surah has its own PDF.

## Features

- Simple sidebar list of Surahs 78–114
- Click a surah name to open its PDF inside the viewer
- Scrollable page view
- Page jump
- Zoom in / zoom out
- Previous / next surah buttons
- Download current PDF button
- Mobile-friendly sidebar
- Works on GitHub Pages

## Folder structure

```text
juz30-multi-pdf-viewer-no-search/
├── index.html
├── style.css
├── script.js
├── surahs.json
├── README.md
└── files/
    ├── 078-an-naba.pdf
    ├── 079-an-naziat.pdf
    ├── 080-abasa.pdf
    └── ...
```

## How to use

1. Put each surah PDF inside the `files` folder.
2. Rename each PDF to match the names in `surahs.json`.

Example:

```text
files/078-an-naba.pdf
files/079-an-naziat.pdf
files/080-abasa.pdf
```

3. Open `surahs.json` and edit file names if your PDFs use different names.

Example:

```json
{
  "number": 78,
  "title": "An-Naba",
  "arabic": "النبأ",
  "file": "files/078-an-naba.pdf"
}
```

The `file` value must exactly match the actual PDF file name.

## GitHub Pages notes

GitHub Pages is case-sensitive.

This means these are not the same:

```text
078-an-naba.pdf
078-An-Naba.pdf
```

Use simple lowercase file names with hyphens. Avoid spaces in file names.
