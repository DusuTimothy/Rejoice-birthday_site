# Rejoice's Birthday Website

A mobile-friendly, static birthday surprise for Rejoice. The site uses only HTML, CSS and JavaScript, plus the two supplied photos in `assets/`.

## Preview locally
Open `index.html` in a browser. For best results, use a local static server.

## Deploy free with Vercel (mobile-friendly steps)
1. Extract `rejoice-birthday-site.zip`.
2. Go to https://vercel.com and sign in.
3. In the Vercel dashboard choose **Add New → Project**.
4. Import the folder from a Git repository, or use Vercel's supported deployment flow to upload/deploy the project.
5. Framework Preset: **Other**. Build Command: leave blank. Output Directory: `.`.
6. Deploy. Vercel will provide a public `*.vercel.app` URL to share with Rejoice.

Alternative: create a GitHub repository, upload the contents of this folder (make sure `index.html` is at the repository root), then import that repository into Vercel.

## Personalise before sending
- Check the birthday date in the hero pill in `index.html` (currently set to NOVEMBER 02).
- Edit any wording in `index.html` if you'd like it to sound more like you.
- Keep the `assets` folder beside `index.html`; the image paths depend on it.

No payment, custom domain, database, or API key is required. The ambient sound is generated in the browser and only starts when the visitor taps its button.
