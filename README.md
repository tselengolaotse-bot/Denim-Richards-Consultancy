# Denim Richards — Official Website

Personal website for **Denim Richards** — Hollywood actor (*Yellowstone*, Paramount), AU Global Director for Media, Arts & Culture, producer, director, and CEO of Opulent Entertainment Group.

## Structure

```
DRC/
├── index.html              # Single-page website (all CSS + JS inline)
├── favicon.svg             # DRC brand favicon
├── D R C Logo.png          # Brand logo asset
├── assets/
│   └── images/             # Local fallback images (photos served via Google Drive)
│       └── logos/          # Social media and brand logos
├── books/                  # Downloadable PDF resources
├── LICENSE
├── README.md
└── .gitignore
```

> **Images** are served directly from Google Drive (`drive.google.com/uc?export=view`).
> Ensure the Drive folder remains shared as **"Anyone with the link can view"**.

## Deployment

This is a static site — no build step required.

**GitHub Pages:**
1. Push this folder to a GitHub repository
2. Go to Settings → Pages → Source: Deploy from branch → `main` / root
3. Site will be live at `https://<your-username>.github.io/<repo-name>/`

**Custom domain:** Add a `CNAME` file to the repo root containing your domain (e.g. `denimrichards.com`), then configure DNS with your registrar.

## External Dependencies (CDN)

- Google Fonts: Playfair Display, Cormorant Garamond, Inter
- Calendly widget (booking integration)
- Google Drive (image hosting)

No npm packages or build tools needed.

## Contact

`marketing@opulententertainmentgroup.com`
WhatsApp: +267 76 788 024