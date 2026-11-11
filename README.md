# IPA Practice Lab — GitHub Pages upload

Upload the **contents** of this folder to the top level of a GitHub repository:

```text
index.html
.nojekyll
data/inventory.json
```

Then, in that repository, open **Settings → Pages** and select **Deploy from a branch**, your `main` branch, and the `/(root)` folder. The `index.html` file must stay at the top level, and the `data` folder must stay beside it.

The `.nojekyll` file prevents GitHub Pages from attempting a Jekyll build. The app has no server-side code and needs no build command.

After Pages reports a published URL, add it to Canvas as a Module item of type **External URL**. Opening it in a new tab is recommended for the best mobile and accessibility behavior.
