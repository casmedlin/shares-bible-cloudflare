# Sharer's Bible

Read, copy, and share Bible passages across 60+ languages and hundreds of translations.

## Features

- **Multi-translation** – Browse dozens of Bible translations per language
- **Verse range** – Select any passage by book, chapter, and verse range
- **One-click copy** – Copy a passage or individual verse to your clipboard
- **Export** – Download passages as Markdown or HTML
- **Themes** – Light, Dark, Sepia, and System themes
- **Adjustable font** – Customize reading size
- **Hideable header** – Toggle the controls bar for distraction-free reading
- **Deep linking** – Share any passage via URL (`/read/en/esv/john/3:16`)
- **Offline cache** – Previously viewed translations are cached in IndexedDB
- **Responsive** – Works on desktop and mobile

## Live Site

[**bible.wbem.org**](https://bible.wbem.org)

## Supported Languages

Afrikaans, Akposso, Arabic, Bacama, Batak Karo, Burmese, Cebuano, Cheyenne, Chin (Hakha), Chinese (Simplified & Traditional), Croatian, Danish, Dangme, Dan (Gio), Dinka, Dutch, English, Finnish, French, German, Greek (Ancient), Haitian Creole, Hausa, Hebrew, Hindi, Hmong (Lus), Hungarian, Iban, Igbo, Ilocano, Indonesian, Italian, Japanese, Jarai, K'iche', Karaboro, Kekchi, Kinyarwanda, Korean, Kpelle, Kwangali, Latin, Luganda, Malay, Malayalam, Maori, Marathi, Mizo, Mongolian, Ndonga, Nepali, Norwegian (Bokmal), Nsenga, Nyankole, Nyanja (Chichewa), Nzema, Oriya, Pampanga, Papua New Guinea, Polish, Portuguese, Punjabi, Romanian, Russian, Sambal, Sango, Shona, Slovak, Somali, Spanish, Swahili, Swati, Swedish, Tagalog, Tamil, Telugu, Thai, Tonga, Tswana, Tsonga, Turkish, Twi, Ukrainian, Urdu, Venda, Vietnamese, Xhosa, Yoruba, Zou, Zulu

## English Translations

57 English translations including: Amplified Bible (AMP), Christian Standard Bible (CSB), English Standard Version (ESV), King James Version (KJV), New American Standard Bible (NASB), New International Version (NIV 1984 & 2011), New King James Version (NKJV), New Living Translation (NLT), The Message (MSG), and many more.

## How It Works

1. Select a **language** and **translation**
2. Choose a **book** and **chapter**
3. Optionally narrow the **verse range**
4. Hit **Refresh** to load the passage
5. **Copy**, **export**, or **share** the URL

## Data Source

Bible text is fetched from [APIBible](https://apibible.wbem.org/api) and cached locally via IndexedDB for offline access. The manifest of available languages and versions is served from `public/bibles/manifest.json`.

## Development

```bash
npm install
npm run dev
```

### Build

```bash
npm run build
```

### Deploy (Cloudflare Pages)

```bash
npm run build
npx wrangler pages deploy dist
```

## Acknowledgments

Bible text data is provided by various open Bible data projects. Each translation carries its own copyright and license terms, displayed in-app when a passage is loaded.
