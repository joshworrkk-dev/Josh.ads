# Joshua — Meta & Google Ads Portfolio

This is the complete static website prepared for GitHub and Vercel.

The website code is separated into three editable files:

- `index.html` — page structure and content
- `style.css` — all visual styling and responsive layouts
- `script.js` — mobile navigation, animations and the automatic footer year

## Upload to GitHub and deploy with Vercel

1. Extract the ZIP.
2. Create a new GitHub repository.
3. Upload the contents of the `Joshua-Portfolio-Vercel` folder to the repository root.
4. In Vercel, choose **Add New → Project** and import the GitHub repository.
5. Choose **Other** as the framework preset.
6. Leave the build command and output directory empty.
7. Click **Deploy**.

Vercel will create the live `.vercel.app` domain after deployment.

You can also deploy the extracted folder directly with the Vercel CLI:

```bash
vercel --prod
```

## Optional GitHub Pages hosting

In the GitHub repository, open **Settings → Pages**, choose **Deploy from a branch**, then select the `main` branch and the repository root.

Keep `index.html`, `style.css`, `script.js`, `favicon.svg` and the `assets/` folder together in the repository root so every image and feature loads correctly.
