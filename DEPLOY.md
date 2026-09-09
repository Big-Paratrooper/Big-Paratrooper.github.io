# Publish this site

The contents of this folder are a complete static website. Upload the folder itself as the publish directory.

## GitHub Pages

1. Create a new public repository, for example `ke-cheng-wu.github.io`.
2. Upload every file in this folder to the repository root.
3. In **Settings > Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
4. GitHub will provide the public URL after the deployment finishes.

## Netlify

Use **Add new site > Deploy manually**, then drag this folder into the upload area. No build command or publish command is required.

## Cloudflare Pages

Create a Pages project from the uploaded files. Set the build command to empty and the output directory to `/`.

The site has no server-side runtime or environment variables. The external links in the page point to HKUST(GZ), FengGao Lab, the MICCAI paper page, the open-access PDF, and the DOI.
