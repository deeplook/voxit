# Voxit — 3D voxel explorer

[Open Voxit](https://deeplook.github.io/voxit/) to view and explore voxel data in 3D.

Voxit runs as a single `index.html` file. Its styles, JavaScript, 3D renderer, and the **QR Cube** and **Torus** example datasets are embedded in the page. No build step or companion files are needed to publish it.

## Use Voxit

- Choose **QR Cube** or **Torus** to load an example, or upload your own CSV file.
- Rotate, zoom, and pan the view; use the **View** and **Appearance** controls to adjust the display.
- Export the data as CSV, an image as PNG, a 3D model as GLB, or a recording as video when supported by your browser.

CSV files use one voxel per row with `x,y,z` coordinate columns. An optional color column can assign a color to each voxel. The viewer also accepts the supported coordinate and color header variants described in its on-page Help section.

## Update the GitHub Pages site

Replace `index.html` with the updated standalone Voxit file, then commit and push to `main`. GitHub Actions publishes the repository root to GitHub Pages.
