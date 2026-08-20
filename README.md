# Zorn ZFG - PWA

Proiect PWA gratuit pentru calculatorul EVD.

## Fișiere

- `index.html` — aplicația și calculatorul
- `manifest.json` — permite instalarea pe ecranul principal
- `sw.js` — permite funcționarea offline după prima încărcare
- `icon-192.png` și `icon-512.png` — iconițele aplicației

## Publicare gratuită

Poți publica proiectul gratuit cu GitHub Pages sau Cloudflare Pages.

Important: PWA trebuie servită prin HTTPS pentru instalare și Service Worker. GitHub Pages și Cloudflare Pages oferă HTTPS gratuit.

## iPhone

În Safari:
1. Deschide adresa aplicației.
2. Apasă Share.
3. Alege „Add to Home Screen / Adaugă la ecranul principal”.
4. Aplicația va apărea cu iconița „Zorn ZFG”.

## Android

În Chrome:
1. Deschide adresa aplicației.
2. Alege „Add to Home screen / Instalează aplicația”.
3. Aplicația va apărea pe ecranul principal.

Calculatorul nu folosește server sau bază de date. După ce PWA a fost încărcată și cache-ul s-a creat, calculatorul poate fi folosit offline.

NOTĂ: Codul păstrează logica de calcul furnizată inițial. Dacă formula/variația aleatorie trebuie modificată pentru utilizarea profesională, verifică formula tehnică înainte de folosirea rezultatelor pe teren.
