<p align="center">
  <img src="assets/banner.svg" alt="SheetStack" width="100%">
</p>

<p align="center">
  Clean, dark, swipe-ready cheat sheets for developers.<br>
  Every sheet is <b>15 pages</b>, made for Instagram, Stories and Reels, and comes with a <b>PDF</b>.
</p>

<p align="center">
  <img alt="Pages" src="https://img.shields.io/badge/pages-15%20per%20sheet-6a4df0?style=for-the-badge">
  <img alt="Size" src="https://img.shields.io/badge/size-1080%C3%971920-2f7fd6?style=for-the-badge">
  <img alt="PDF" src="https://img.shields.io/badge/PDF-included-1fae7c?style=for-the-badge">
</p>

---

## What is SheetStack?

SheetStack is a growing collection of quick-reference cheat sheets. Each sheet is a short, swipeable set of pages: one topic per page, small sections, and one command per row with a plain-English explanation next to it.

No long theory. Open a page, find the line, copy it, keep coding.

## Features

- **15 pages per sheet**: the same length everywhere, so every sheet feels familiar
- **Portrait 1080 × 1920 (9:16)**: fits phone screens, Stories, Reels and carousels
- **A PDF for every sheet**: print it, share it, or read it offline
- **Clean dark design**: one accent color per sheet, rounded section tags and easy-to-scan rows
- **No watermarks**: the creator handle is already in every page footer

## How a page looks

Every page follows the same layout, so you always know where to look.

| Part | What it holds |
| --- | --- |
| **Header** | Sheet name and page counter, like `03 / 15` |
| **Title** | The topic of the page, with a short subtitle |
| **Progress line** | Shows how far you are in the sheet |
| **Section tags** | Small rounded labels that group related commands |
| **Rows** | Code on the left, what it does on the right |
| **Footer** | GitHub icon, `@hafizibrahimsuriya`, and `Swipe >` |

The last page of every sheet is *Tips* plus a short "Made by" card.

## Folder structure

```text
SheetStack/
├── assets/
│   └── banner.svg
├── <name>-cheatsheet/
│   ├── 01-basics.jpg
│   ├── 02-....jpg
│   ├── ...
│   ├── 15-end.jpg
│   └── <name>-cheatsheet.pdf
└── README.md
```

Each sheet lives in its own `<name>-cheatsheet` folder with 15 numbered images and one PDF.

## Adding a new sheet

1. Create a folder named `<name>-cheatsheet`.
2. Make exactly **15** pages at **1080 × 1920** and number them `01` to `15`.
3. Start with **Basics** and finish with a **Tips** page named `15-end`.
4. Keep the same layout: title, subtitle, section tags, then code and description rows.
5. Pick one accent color for the sheet and keep it on every page.
6. Put the page counter in the header (`01 / 15`) and the footer handle with the GitHub icon on every page.
7. Export all pages into one PDF named `<name>-cheatsheet.pdf`.

## Using the sheets

- **On your phone:** open the images and swipe through them in order.
- **For posting:** upload the 15 images as a carousel, in file order.
- **For printing or offline use:** open the PDF.

## Made by

Made by [**@hafizibrahimsuriya**](https://github.com/HafizIbrahimSuriya)

If a sheet helped you, save it, share it and practice daily.
