# Velocity GitHub Pages site

This folder is a ready-to-upload GitHub Pages landing page for the Velocity Chrome extension.

## Publish with GitHub Pages
1. Create a GitHub repository, for example `velocity-extension`.
2. Upload `index.html`, this README, and the `downloads/` folder.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**, choose `main` and `/ (root)`, then Save.
5. Wait for GitHub Pages to publish the site.

## Important: one-click Add to Chrome
Chrome does not allow a normal GitHub Pages website to silently/directly install an unpacked extension. For a real **Add to Chrome** button, publish the extension to the Chrome Web Store first.

After publishing:
1. Open `index.html`.
2. Find `const chromeWebStoreUrl = '';`
3. Replace the empty string with the exact public Chrome Web Store listing URL.
4. Commit the change. The button will then say **Add to Chrome** and link to the official listing.

Until then, the page downloads `downloads/VelocityExtension.zip` and explains manual installation.
