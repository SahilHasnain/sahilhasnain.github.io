# Sahil Hasnain Qadri - Website

## Overview
Personal link-in-bio style website for Sahil Hasnain Qadri, showcasing Islamic apps and translated books.

## Live URL
https://sahilhasnain.github.io

## GitHub Repo
https://github.com/SahilHasnain/sahilhasnain.github.io
- Branch: `main`
- Auto-deploys on push (GitHub Pages)

## Site Structure

```
/
├── index.html      → Landing page (nav to Books + Apps)
├── books.html      → Translated books (Ash-Shifa PDF download)
└── apps.html       → All Islamic apps (Play Store links)
```

## Pages

### index.html - Landing Page
- Profile avatar with initials "SH"
- Name: Sahil Hasnain Qadri
- Bio: Developer · Translator · serving the Ummah
- Two link cards:
  1. Translated Books → books.html
  2. Islamic Apps → apps.html

### books.html - Translated Books
- Ash-Shifa by Imam Qadi Iyad (1083-1145 CE)
  - PDF download: GitHub release v1.0
  - Play Store app link
- Footer: "More translations coming soon, Insha'Allah"
- New books should be added as `.book` divs following the existing pattern

### apps.html - Islamic Apps
Links to Play Store:
1. Owais Raza Qadri - com.owaisrazaqadri
2. Durood Time - com.duroodepak
3. Al Quran - com.livequran
4. Shifa Shareef - com.shifashareef
5. Islamic Library - com.islamiclib
6. Naat Production - com.naatproduction

## PDF Hosting
- Ash-Shifa PDF is hosted as a GitHub release asset
- Release: v1.0
- Direct URL: https://github.com/SahilHasnain/sahilhasnain.github.io/releases/download/v1.0/shifa-shareef-english-digital.pdf
- To add new book PDFs: create new release, upload PDF, update books.html link

## Design
- Dark theme: #0a0a0f background
- Gold accents: #FFD700
- Font: Inter (Google Fonts)
- Arabic font: Amiri (for book covers)
- Mobile-first, max-width 480-520px
- Rounded cards with subtle borders
- Hover effects with gold border highlight

## Analytics
- Google Analytics: G-DLCJ4NCWY1
- Added to all pages via gtag.js

## How to Update

### Add a new book
1. Create a GitHub release with the PDF
2. Copy the download URL
3. In books.html, copy the `.book` div and update:
   - Book title, author, description
   - PDF download link
   - App link (if exists)

### Add a new app
1. In apps.html, add a new `.link` div with Play Store URL

### Deploy
Just push to `main` branch - GitHub Pages auto-deploys.

## Related Projects
- `D:\Projects\islamic-knowledge` - Source manuscripts
- `D:\Projects\islamic-marketing` - Marketing content (reels, emails, scripts)
- Shifa Shareef manuscript: `D:\Projects\islamic-knowledge\publishing\shifa-shareef-english\`

## Contact
- Email: mdsahil1631@gmail.com
- GitHub: SahilHasnain
