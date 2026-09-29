# Radhi's Birthday Surprise

This folder is the complete static version of the birthday website. It includes all eight steps, the eight memory photos, the birthday music, and the final video.

## Publish with GitHub Pages

1. Create a new GitHub repository.
2. Upload everything inside this folder to the repository's root. Keep `index.html` and the `assets` folder together.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and the `/ (root)` folder, then choose **Save**.
6. After GitHub finishes publishing, copy the Pages URL and send it to Radhi.

The `.nojekyll` file is included so GitHub serves the files directly.

## Date wheel storage

GitHub Pages is static hosting, so it cannot run the original private database API. In this version, the wheel result is saved in the visitor's browser using `localStorage`. It will remain saved when the same person returns using the same browser and device.

## Media

All media is already inside `assets/`; no additional uploads or external links are needed.
