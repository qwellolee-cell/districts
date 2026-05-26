# DESERT VISION — Struttura Progetto

> Label indipendente · Cultural Districts · Ancona · Mediterraneo

---

## File e Cartelle

```
DV/
│
├── index.html                          ← Microsite (apri nel browser)
│
├── css/
│   └── style.css                       ← Stile del microsite
│
├── assets/
│   ├── images/
│   │   ├── hero/                       ← Immagine/video di sfondo hero
│   │   ├── districts/                  ← Foto quartiere Piano / San Lazzaro
│   │   ├── sessions/                   ← Visual per ogni Cultural Session
│   │   └── releases/                   ← Artwork release (1:1)
│   └── video/
│       └── [teaser.mp4 qui]            ← Video teaser del progetto
│
├── Desert_Vision_Cultural_Districts.md ← Documento progetto
├── desert_vision_brand_identity.md     ← Brand system
├── video_script.md                     ← Script completo video teaser
├── ai_prompts.md                       ← Prompt Midjourney / DALL-E
└── README.md                           ← Questo file
```

---

## Come usare il microsite

1. **Apri `index.html`** nel browser (doppio clic oppure trascina nel browser)
2. Il sito funziona offline — non serve un server
3. Per aggiungere immagini: sostituisci i placeholder `<div class="img-placeholder">` con `<img src="assets/images/..." />`
4. Per aggiungere il video teaser: cerca `<!-- Esempio con YouTube -->` nell'HTML e decommenta/modifica

---

## Come aggiungere le immagini

Ogni sezione del sito ha un placeholder con indicazione del formato consigliato:

| Sezione        | File da aggiungere                        | Formato  |
|----------------|-------------------------------------------|----------|
| Hero           | `assets/images/hero/hero_bg.jpg`          | 1920×1080 |
| Label          | `assets/images/hero/label_photo.jpg`      | 1920×1080 |
| Quartiere      | `assets/images/districts/quartiere.jpg`   | 800×1100 |
| Mediterranean  | `assets/images/sessions/mediterranean.jpg`| 800×600  |
| Middle Eastern | `assets/images/sessions/middle_eastern.jpg`| 800×600 |
| North African  | `assets/images/sessions/north_african.jpg`| 800×600  |
| Latin          | `assets/images/sessions/latin.jpg`        | 800×600  |
| Release 1      | `assets/images/releases/stroopwafel_kita.jpg` | 1:1   |
| Release 2      | `assets/images/releases/hollow.jpg`       | 1:1      |
| Release 3      | `assets/images/releases/stroopwafel_rx.jpg` | 1:1    |

---

## Come aggiungere il video teaser

### Opzione A — File locale
Nel file `index.html`, trova la sezione `<!-- Inserisci qui: -->` e sostituisci con:
```html
<video autoplay muted loop playsinline src="assets/video/hero_loop.mp4"></video>
```

### Opzione B — YouTube / Vimeo
Trova `<!-- Esempio con YouTube -->` nell'HTML e decommenta, inserendo il tuo VIDEO_ID.

---

## Generare le immagini mancanti

Usa i prompt in `ai_prompts.md` con:
- **Midjourney** (migliore qualità fotografica)
- **DALL-E 3** via ChatGPT Plus
- **Adobe Firefly** (royalty-free commercial use)
- **Ideogram** (per immagini con testo)

---

## Generare il video teaser

1. Leggi lo script completo in `video_script.md`
2. Per il video AI: usa **Kling AI** o **Runway Gen-3**
3. Per il montaggio: DaVinci Resolve (gratuito) o CapCut

---

*Desert Vision — Ancona · Mediterraneo · 2026*
