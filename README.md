# Sanford lab literature

Synthesis of Sanford lab publications and related m6A reader biology, prepared in advance of rotation discussions with Jeremy Sanford. Christian Ortiz, UC Santa Cruz MCD Biology.

## Live site

Once GitHub Pages is enabled:
**https://cfortiz.github.io/sanford-lab-literature/**

(Replace `cfortiz` with your actual GitHub username.)

## Structure

```
sanford-lab-literature/
├── index.html              Table of contents
├── assets/
│   └── style.css           Shared styles, light + dark mode
└── papers/
    ├── palanichamy_2016.html
    ├── tran_2022.html
    ├── sharma_2025.html
    ├── li_2025.html
    └── nicastro_2023.html
```

## How to add a new paper

1. Copy an existing paper file in `papers/` as a template.
2. Update the title, citation, sections, and SVG diagram.
3. Add a new card to `index.html` linking to the new paper.
4. Commit and push. GitHub Pages rebuilds automatically.

## Setup checklist

- [ ] Create repo on GitHub (public)
- [ ] Push these files
- [ ] Settings → Pages → Source: deploy from `main` branch, root folder
- [ ] Wait two minutes for first deploy
- [ ] Open the live URL to confirm

## Stack

Plain HTML and CSS, no build step, no JavaScript framework, no dependencies. Diagrams are inline SVG. Auto-adapts to light and dark mode based on browser preference.
