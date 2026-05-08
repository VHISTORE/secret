# Car catalog images

Drop car preview images here. Filename = car id from `cpm2_car_catalog.json`.

Supported formats (tried in order): `.jpg` → `.png` → `.webp`.
If none of the three exist for a given id, the picker tile collapses to a
text-only strip (id + price + class/hp/year) — no broken image block.

Examples:
  155.jpg
  259.jpg
  4.png

Recommended:
  • 16:9 aspect (640×360 or 800×450)
  • JPG quality 80–85, ~40–80 KB each
  • Cropped tight on the car body, neutral background

Deployment: bundle this directory alongside `webapp/devtool.html` so the
relative path `assets/cars/<id>.jpg` resolves on the hosted mini-app.
