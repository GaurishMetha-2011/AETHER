# AETHER Website

A static, scroll-led project website. No software installation or build step is needed.

## Files to publish

```text
index.html                 # The website; keep this at the repository root
assets/aether-logo.png     # Required logo and favicon
README.md                  # Optional project and publishing notes
```

`Info.md` and the original `AETHER (1).png` are source files and are not required by the live website. Keep the `assets` folder and its name unchanged.

## Publish on GitHub Pages

1. Sign in at [github.com](https://github.com/) and create a new repository, for example `aether-website`.
2. Set the repository to **Public** if you are using GitHub Free, then create it.
3. In the new repository, select **Add file → Upload files**.
4. Upload `index.html` and the `assets` folder containing `aether-logo.png`. Make sure the finished repository shows `index.html` at the top level and `assets/aether-logo.png` inside the `assets` folder. You can also upload `README.md`.
5. Enter a short commit message, such as `Add AETHER website`, then select **Commit changes**.
6. Open the repository's **Settings** tab, then choose **Pages** in the sidebar.
7. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
8. Set the branch to **main** and the folder to **/(root)**, then select **Save**.
9. Wait for GitHub Pages to finish deploying. The Pages screen will show the website address. For a repository named `aether-website`, it usually looks like `https://YOUR-USERNAME.github.io/aether-website/`.

The first deployment can take a few minutes. Refresh the Pages screen to see when the published link appears.

## If the page does not appear

- Confirm `index.html` is at the repository root, not inside another project folder.
- Confirm Pages is set to the `main` branch and `/(root)`.
- Confirm the logo path is exactly `assets/aether-logo.png`; GitHub filenames are case-sensitive.
- Check the repository's **Actions** tab for a Pages deployment that is still running or reports an error.

To update the website later, upload the changed files and commit them. GitHub Pages will publish the new version automatically.

The architectural photos and display fonts load from external services and need an internet connection. The optical and material illustrations are conceptual; no unvalidated performance, lifetime or experimental results are claimed.