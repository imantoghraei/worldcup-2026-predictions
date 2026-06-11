# World Cup 2026 Prediction App

This folder is ready to publish with GitHub Pages.

## Files

- `index.html` — the website. GitHub Pages will open this file by default.
- `.nojekyll` — tells GitHub Pages not to process the site with Jekyll.

## Important note about collecting people's entries

This is a static GitHub Pages site. It can run the app in everyone's browser, but it cannot automatically save everyone's predictions to your GitHub repository or to a central database.

In the current app, each person's predictions are saved locally in their own browser. To collect results, ask each person to press the export/save button in the app and send you the JSON file. You can then import those JSON files into your own copy of the app.

For automatic central collection, you would need an external form/backend service such as Google Forms, Formspree, Netlify Forms, Firebase, or a small server.

## Publish with GitHub Pages

1. Create a new public GitHub repository, for example `worldcup-2026-predictions`.
2. Upload `index.html` and `.nojekyll` to the root of the repository.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/root`, then save.
6. After GitHub finishes publishing, your site will be available at:

   `https://YOUR-USERNAME.github.io/worldcup-2026-predictions/`

Replace `YOUR-USERNAME` and the repository name with your own values.
