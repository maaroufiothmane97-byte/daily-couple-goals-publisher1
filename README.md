# Daily Couple Goals Publisher — GitHub Pages site

This folder contains a small static website for the TikTok developer-app setup:

- `index.html` — official app information page
- `privacy.html` — Privacy Policy template
- `terms.html` — Terms of Service template
- `styles.css` — shared styling

## Before publishing

Replace every placeholder in square brackets, especially:

- `[YOUR NAME OR BUSINESS NAME]`
- `[YOUR-EMAIL@example.com]`
- `[MONTH DAY, 2026]`
- `[OPTIONAL BUSINESS ADDRESS]`

The legal pages must describe what your real app actually does. These templates are general starting points, not legal advice.

## Publish with GitHub Pages

1. Create or sign in to a GitHub account at <https://github.com/>.
2. Create a new **public** repository. A name such as `daily-couple-goals-publisher` is fine.
3. Upload all four files from this folder to the repository root. Do not upload the parent folder itself as the only item.
4. Open the repository's **Settings** tab.
5. In the left menu, open **Pages**.
6. Under **Build and deployment**, select **Deploy from a branch**.
7. Select the `main` branch and the `/ (root)` folder, then select **Save**.
8. Wait for GitHub to publish the site. The URL will usually look like:

   `https://YOUR-GITHUB-USERNAME.github.io/daily-couple-goals-publisher/`

9. Test these pages in an incognito/private browser window:

   - `https://YOUR-GITHUB-USERNAME.github.io/daily-couple-goals-publisher/`
   - `https://YOUR-GITHUB-USERNAME.github.io/daily-couple-goals-publisher/privacy.html`
   - `https://YOUR-GITHUB-USERNAME.github.io/daily-couple-goals-publisher/terms.html`

10. In TikTok Developer Portal, use the public Privacy Policy page URL as the Privacy Policy URL. Also provide the public homepage as the Web/Desktop URL if TikTok requests it.
11. Use TikTok's **URL properties** verification flow if it appears. TikTok may ask you to verify the domain or URL prefix before app review.

## Important TikTok review caveat

TikTok's current app-review guidance says apps must not be for private or personal use. A site can satisfy the public-information requirement, but it does not guarantee approval for an app intended only for one personal account. Do not submit the app until the app's purpose, privacy policy, terms, and actual implementation are accurate.
