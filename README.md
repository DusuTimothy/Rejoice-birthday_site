# Rejoice's Birthday Website

A mobile-friendly static birthday surprise created for Rejoice. The site combines a celebratory hero section, personal message, photo gallery, music interaction, and decorative effects into a lightweight browser experience.

## Preview

Open `index.html` directly in a modern browser, or run a local static server:

```bash
python3 -m http.server 4173
```

Visit `http://localhost:4173`.

## Features

- Responsive design for phones, tablets, and desktop browsers
- Birthday greeting and personal message
- Photo and memory sections
- Ambient browser-generated sound activated by the visitor
- Lightweight visual animations and confetti effects
- No database, API key, backend, or third-party runtime service required

## Project Structure

```text
.
├── index.html    # Page structure, content, styles, and interactions
└── assets/       # Photos and other static media
```

## Personalization

Before sharing the site, review and customize the following in `index.html`:

- Rejoice's name and birthday date
- Personal message and timeline details
- Photo captions and page copy
- Colors or decorative effects

Keep the `assets/` directory beside `index.html` because the page references images relative to the repository root.

## Deployment

The project can be deployed to any static hosting provider.

### GitHub Pages

1. Push the repository to GitHub.
2. Open **Settings → Pages**.
3. Select the repository's default branch and the root directory.
4. Save and wait for GitHub Pages to publish the site.

### Vercel or Netlify

- Framework preset: **Other**
- Build command: leave blank
- Output directory: `.`

## Browser Notes

Audio is generated in the browser and normally requires a user interaction before playback. Keep the image files inside `assets/` to preserve relative image paths.

## License

License terms have not yet been specified for this project.
