# Text Formatter & GST Calculator

A free two-in-one **utility dashboard** for Indian users: a WhatsApp-style text formatter and a GST (Goods and Services Tax) calculator — both in a single static page, no signup, no backend.

## Tools Included

### 1. WhatsApp & Social Media Text Formatter
Type or paste any text and instantly apply WhatsApp-compatible formatting:
- **Bold** (`*text*`), *Italic* (`_text_`), Strikethrough (`~text~`), Underline, Monospace
- One-click **copy to clipboard** for pasting into WhatsApp, Instagram, Telegram, etc.
- Clear-format button to reset

### 2. GST Calculator
- Enter an amount and pick a GST rate (standard slabs: 0%, 5%, 12%, 18%, 28%)
- Add GST (exclusive → inclusive) or remove GST (inclusive → exclusive)
- Shows GST amount, original amount, and total — with CGST/SGST split
- Built-in toast notifications for copy/calc feedback

## Tech Stack

- Plain HTML5 / CSS / JavaScript (single `index.html`, zero build step)
- Custom CSS (responsive grid dashboard, gradient header)
- Font Awesome icons via CDN

## Quick Start

```bash
git clone https://github.com/girishlade111/Text-Formatter-GST-Calculator.git
cd Text-Formatter-GST-Calculator
# open index.html in a browser, or:
npx serve .
```

## Project Structure

```
Text-Formatter-GST-Calculator/
├── index.html     # Entire dashboard: markup, styles, and JS in one file
└── README.md
```

## Deploy Notes

- Pure static site: works on GitHub Pages, Cloudflare Pages, Netlify, or any file host.
- No environment variables, no API keys, no build step, 100% client-side.

---

Built by [Girish Lade](https://github.com/girishlade111) · [ladestack.in](https://ladestack.in)
