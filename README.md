# For Loop Arcade (C Edition)

This folder is a standalone static site for deployment to Vercel. It is intentionally separate from the CURA Vite application.

## Deploy with the Vercel dashboard

1. Push this repository to GitHub.
2. In Vercel, select **Add New > Project** and import this repository.
3. Set **Root Directory** to `for-loop-arcade`.
4. Choose **Other** as the Framework Preset. Leave the Build Command, Install Command, and Output Directory empty; this site has no build step or dependencies.
5. Deploy. No environment variables are required.

If the repository is already connected to a Vercel project for CURA, create a **separate Vercel project** for the arcade and set its Root Directory as above. Do not change the root directory of the existing CURA project.

## Preview locally

From this directory, start any static file server and open its local URL. For example, with Python installed:

```powershell
py -m http.server 8000
```

Then visit `http://localhost:8000`. The page loads its optional fonts from Google Fonts; the game itself has no runtime API or environment-variable requirements.
