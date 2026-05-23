# Sharer's Bible

A web app for reading, copying, and sharing Bible passages across translations and languages.

## Features

- **Multi-translation support** – Browse dozens of Bible translations across multiple languages
- **Passage selection** – Pick book, chapter, and verse range with ease
- **One-click copy** – Copy a passage or a single verse to your clipboard
- **Export** – Download passages as Markdown or HTML
- **Theme support** – Light, Dark, Sepia, and System themes
- **Adjustable font size** – Customize reading comfort
- **Header hide/show** – Toggle the controls bar for distraction-free reading
- **Deep linking** – Share any passage via a clean URL (`/read/en/esv/john/3:16`)
- **Responsive** – Works on desktop and mobile

## Usage

Open the app, select a language and translation, choose a book and chapter, optionally narrow the verse range, then hit **Refresh**. Copy the passage, export it, or share the URL directly.

## Development

```bash
npm install
npm run dev
```

Build for production:

```bash
npm run build
```

Deploy to Cloudflare Pages (auto-routed via `_routes.json`):

```bash
npm run build
npx wrangler pages deploy dist
```
