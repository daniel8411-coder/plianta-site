# Plianta Website — Projektkontext für Claude Code

## Was ist das?
Statische Website für **plianta.com** — die Suite-Landing und Pflichtseiten für App Store Launch.

## Tech Stack
- **Reines HTML + CSS** (kein JavaScript, kein Build-Prozess)
- **Hosting:** Netlify (publish directory = root `/`)
- **Domain:** plianta.com

## Dateistruktur
```
index.html          — Landing Page (Logo, Tagline, Link zu Fieldnotes)
privacy.html        — Datenschutzerklärung (DSGVO + App Store)
terms.html          — Nutzungsbedingungen
imprint.html        — Impressum (TMG §5)
support.html        — Support/Kontakt + FAQ
delete-account.html — Account-Löschung Anleitung (Apple Pflicht)
styles.css          — Shared CSS (Design System Farben)
icon.svg            — Plianta Icon
icon-192.png        — Favicon
icon-512.png        — OG Image
CLAUDE.md           — Diese Datei
```

## Design System
Gleiche Farbpalette wie Plianta Fieldnotes:
- **Primary:** Navy #111d33 bis #dce8f3
- **Accent:** Cyan #5ec4d4
- **System Fonts** (kein Google Fonts)
- **Responsive** (Mobile-first)

## Verwandte Repos
- **Plianta Fieldnotes:** ../Plianta/ (die PWA unter fieldnotes.plianta.com)

## Sprache
- **Website-Inhalte:** Englisch
- **Konversation mit Daniel:** Deutsch
- **Code-Kommentare:** Englisch

## Offene Punkte
- Impressum: Daniel muss persönliche Daten einfügen (Name, Adresse)
- Privacy Policy: Sollte von Anwalt geprüft werden
- support@plianta.com muss eingerichtet werden
- App Store Badges kommen nach App Store Submission
