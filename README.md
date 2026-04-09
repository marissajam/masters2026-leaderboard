# Masters Tracker — GitHub Pages package

This package is ready to publish on GitHub Pages.

## Files
- `index.html` — the live Masters leaderboard app
- `.nojekyll` — tells GitHub Pages to serve the site as-is

## Publish in GitHub Pages
1. Create a new GitHub repository.
2. Upload `index.html` and `.nojekyll` from this folder to the root of the repo.
3. In GitHub, go to **Settings → Pages**.
4. Under **Build and deployment**, choose:
   - **Source:** `Deploy from a branch`
   - **Branch:** `main`
   - **Folder:** `/ (root)`
5. Save.
6. Wait for GitHub Pages to publish the site.
7. Your site URL will look like:
   - `https://YOUR-USERNAME.github.io/REPO-NAME/`

## Updating tracked players
Open the site in the browser and edit the 5 tracked players in the compact settings area.

## Notes
- The page pulls live leaderboard data from ESPN endpoints, with a fallback route included in the file.
- If you later want a cleaner URL, you can connect a custom domain through GitHub Pages settings.
