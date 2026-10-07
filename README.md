# Arabic Trainer — versione PWA

Questa cartella contiene la versione pronta per GitHub Pages.

## File
- `index.html` — sito principale
- `manifest.json` — configurazione PWA/installazione
- `sw.js` — cache/offline
- `icons/` — icone dell'app

## Pubblicazione
Carica tutti i file mantenendo questa struttura nella root del repository GitHub:

arabic-trainer/
├── index.html
├── manifest.json
├── sw.js
└── icons/
    ├── icon-180.png
    ├── icon-192.png
    └── icon-512.png

Poi GitHub → Settings → Pages → Deploy from a branch → `main` → `/ (root)` → Save.

Nota: i progressi del quiz continuano a essere salvati nel browser tramite localStorage. La PWA/offline non aggiunge ancora la sincronizzazione cloud tra dispositivi.
