# 🌿 Haveplan-konfigurator
### Huscompagniet × Plantetorvet.dk

En moderne, responsiv haveplan-konfigurator bygget med React, Vite og Tailwind CSS. Guider kunder fra bar nybygget grund til færdig, skræddersyet haveplan med vejledende pris.

---

## Kom i gang

### Krav
- Node.js 18+
- npm 9+

### Installation

```bash
npm install
```

### Udvikling (lokalt)

```bash
npm run dev
```

Åbn [http://localhost:5173](http://localhost:5173) i browseren.

### Byg til produktion

```bash
npm run build
```

Output gemmes i `dist/`-mappen.

### Preview af produktionsbuild

```bash
npm run preview
```

---

## Projektstruktur

```
haveplan-app/
├── public/
│   └── favicon.svg
├── src/
│   ├── App.jsx          # Hele applikationen (konfigurator + logik)
│   ├── main.jsx         # React entry point
│   └── index.css        # Global CSS (Tailwind)
├── index.html
├── package.json
├── vite.config.js
├── tailwind.config.js
├── postcss.config.js
└── .gitignore
```

---

## Funktioner

- **8-trins konfigurator** — grundoplysninger, hæk, græs, bede, træer, stil, tilvalg, resultat
- **Flere bedtyper** — kunden kan tilføje og konfigurere flere bede individuelt
- **Live prisberegning** — opdateres med hvert valg
- **Smarte forslag** — hækmeter og jordforbedring foreslås ud fra kundens øvrige valg
- **Print / PDF** — branded print-layout med begge logoer
- **Gem haveplan** — downloader en .txt-oversigt
- **Mobilvenlig** — responsivt design til alle skærmstørrelser

---

## Næste skridt / Udvidelser

- [ ] Tilslut rigtige produktdata fra Plantetorvet.dk API
- [ ] E-mail integration (send haveplan til kunde + Plantetorvet)
- [ ] Booking-integration til online haveguide
- [ ] Rabatkode-generator til Plantetorvet.dk webshop
- [ ] Visualiseret haveplan (SVG/canvas tegning af grunden)
- [ ] Gemte planer via brugerlogin

---

## Tech stack

| Teknologi | Version |
|---|---|
| React | 18 |
| Vite | 5 |
| Tailwind CSS | 3 |
| Playfair Display | Google Fonts |

---

*Et samarbejde mellem [Huscompagniet](https://www.huscompagniet.dk) og [Plantetorvet.dk](https://www.plantetorvet.dk)*
