# Orologeria Oreficeria Biella – sito web

Sito vetrina dell'Orologeria Oreficeria Biella, Via San Francesco 6, Airuno (LC).
Realizzato da [Kiso Studio](https://www.kisostudio.it/).

## Struttura

- `index.html` – il sito completo (una pagina, HTML + CSS + JS in un unico file)
- `privacy.html` – Informativa privacy
- `cookie.html` – Cookie policy (il sito non usa cookie)
- `img/` – favicon, icone e immagine di anteprima per i social

## Pubblicazione con GitHub Pages

1. Carica tutti i file nella radice del repository (branch `main`).
2. Settings → Pages → Source: "Deploy from a branch" → `main` / `(root)` → Save.
3. Dopo qualche minuto il sito è online all'indirizzo indicato in Settings → Pages.

### Dominio personalizzato (es. orologeriabiella.it)

1. In Settings → Pages → Custom domain inserisci il dominio e attiva "Enforce HTTPS".
2. Dal pannello del registrar del dominio crea i record DNS:
   - 4 record `A` sul dominio principale verso 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
   - 1 record `CNAME` per `www` verso `<utente>.github.io`
3. Quando il dominio è attivo, in `index.html` sostituisci `img/og-image.png` nel tag `og:image`
   con l'indirizzo completo (es. `https://www.orologeriabiella.it/img/og-image.png`),
   così l'anteprima funziona bene su WhatsApp e Facebook.

## Da completare

- Foto del negozio (sezione "La nostra storia")
