# Asset Replacement Guide

Put your custom assets in this folder with the following file names:

- person.webp (preferred)
- person.png (fallback)
- girl.png (anime girl under the sakura tree)
- cake.png
- bg.jpg (optional)

## Recommended sizes

- person.webp/person.png: around 700x900, transparent background
- girl.png: around 800x1200 (portrait), PNG with transparent background recommended
- cake.png: around 300x220, transparent background
- bg.jpg: at least 1920x1080

## Notes

- Keep transparent backgrounds for person.png and cake.png for best blending.
- The page tries person.webp first, then falls back to person.png automatically.
- The sakura scene draws girl.png near the bottom-right under the tree.
- If an image is missing, the page uses built-in fallback drawing.
- After replacing files, refresh index.html to see updates.
