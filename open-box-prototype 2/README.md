# Delta Children — PDP + Open Box prototype

A static, responsive HTML/CSS/JS prototype. It has no build step and no dependencies, so it runs on GitHub Pages as-is.

## Pages

| Page | URL |
| --- | --- |
| Regular PDP with the Open Box option | `index.html` |
| Open Box PDP, V1 (a new version exists, shows **Buy New**) | `open-box.html` |
| Open Box PDP, V2 (Open Box only) | `open-box.html?variant=open-box-only` |

A small switcher in the bottom-left corner jumps between the three pages.

## Responsive behavior

- **1024px and wider:** desktop layout (two-column PDP, image grid, full navigation).
- **Under 1024px:** mobile layout (swipeable image carousel with dots, single column, compact header).

## What's interactive

- Open Box button: hover and keyboard-focus states. The info icon shows a tooltip on desktop and a tap-to-open popover on mobile.
- Links: Open Box button → Open Box PDP; **Buy New** → regular PDP.
- Color swatches, quantity stepper (capped at 1 on Open Box pages), info-tab accordions, gallery dots.

## Publish on GitHub Pages

1. Create a repository and upload the contents of this folder (keep the `assets/` structure).
2. In the repository, go to **Settings → Pages** and set **Source** to the `main` branch, root folder.
3. The site will be at `https://<your-user>.github.io/<repo-name>/`.

## Notes

- Prices such as `$000.00`, `SKU OB-[00000]` and the tab contents are placeholders.
- The Poppins font loads from Google Fonts; everything else is local.
