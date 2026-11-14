# Change the project banners

You can change any banner without changing the card layout or buttons.

## Option 1: Replace a banner and keep its filename

1. Open `assets/project-banners/` in the repository.
2. Replace the banner you want to change, keeping the exact same filename, for example `jjk-game.svg`.
3. Commit the change. The README already points to that filename, so the new banner appears automatically.

The current banners are SVG files. You can edit the SVG artwork and text directly, or replace its contents with your own SVG. Keep the SVG valid and use a wide banner canvas around **1200 × 400 px**.

## Option 2: Use a PNG, JPG, or WebP image

1. Upload your image into `assets/project-banners/`, for example `jjk-game.jpg`.
2. Open `README.md` and find that project's banner `<img>` line.
3. Change only the `src` value to the new path. For example:

   ```html
   <img src="assets/project-banners/jjk-game.jpg" alt="Jujutsu Kaisen Game banner" width="100%" />
   ```
4. Commit both the uploaded image and the README change.

Recommended banner proportions: **3:1** (for example 1200 × 400 px). Use a descriptive filename, and keep the alt text meaningful for accessibility.

## Banner filenames currently used

| Project | Banner path |
| --- | --- |
| Jujutsu Kaisen Game | `assets/project-banners/jjk-game.svg` |
| Fabulous AI | `assets/project-banners/fabulous-ai.svg` |
| Octo Focus | `assets/project-banners/octo-focus.svg` |
| Dentist Manager | `assets/project-banners/dentist-manager.svg` |
