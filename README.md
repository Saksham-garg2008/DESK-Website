# DESK Website

A lightweight, multi-page static website for the [DESK](https://github.com/Saksham-garg2008/DESK) open-source desktop AI assistant.

## Pages

- Home
- Features
- Downloads
- Documentation
- Contributing

## Tech

- HTML
- CSS
- Minimal vanilla JavaScript
- No build step or package manager required

## Preview locally

Open `index.html` in a browser. For a local server, run from this directory:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deploy with GitHub Pages

1. Create a repository named `DESK-Website` under `Saksham-garg2008`.
2. Add the files from this project to the repository root.
3. Push the files to the `main` branch.
4. In the repository, open **Settings → Pages**.
5. Under **Build and deployment**, select **Deploy from a branch**.
6. Choose `main` and `/(root)`, then save.
7. Wait for the deployment to complete. The expected URL is `https://Saksham-garg2008.github.io/DESK-Website/`.

## Before publishing

- Confirm links to repository documentation and contribution instructions.
- Check the live release page and update platform wording if the supported builds change.
- If the repository name or Pages URL changes, update the canonical URLs in `sitemap.xml`.
- The Google Fonts import is optional; the site has system-font fallbacks if it is unavailable.

## License

This website is a separate project from DESK itself. Add a license file for this repository after deciding how you want the website's own code and content to be licensed.
