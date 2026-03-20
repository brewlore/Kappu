# Kappu Brew Log

A single-origin drip coffee brew logger. Fill in each brew session and download a formatted `.docx` or `.pdf` log.

## Usage

Open `index.html` in any modern browser. No server or build step required.

## Structure

```
kappu-brew-log/
├── index.html           # Main entry point
├── assets/
│   └── icons/
│       └── favicon.svg  # Brand favicon
├── src/
│   ├── css/
│   │   └── styles.css   # All app styles
│   └── js/
│       └── app.js       # All app logic (form state, docx generation, import/export)
├── vendor/
│   └── docx.umd.js      # docx.js v9.5.3 — client-side .docx generation
└── README.md
```

## Features

- **7 sections** — Coffee Identity, Brew Tech, Brew Story, Sensory Test, Flavour Notes, Kappu Score, Mood Pairing
- **Auto-calculations** — Ratio from dose/water, days rested from roast date
- **Dynamic pours** — Bloom/First Pour fixed, add up to 3 more as needed
- **Hot / Iced** toggle with ice weight fields for iced brews
- **Download as .docx** — Branded Word document, compatible with Google Docs
- **Save as PDF** — Browser print-to-PDF
- **Export / Import JSON** — Save and reload any combination of sections; rename export files
- **Sticky section nav** — Highlights current section as you scroll

## Offline

Once opened in a browser, the app works fully offline (fonts load from Google Fonts on first visit).
