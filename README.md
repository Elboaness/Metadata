# 🏷️ Metadata Editor

App super semplice (un solo file HTML) per **caricare una foto JPEG, modificare i suoi metadati EXIF e riscaricarla**.

- ✅ Funziona al 100% nel browser — **nessun file viene caricato online**, niente server, zero costi.
- ✅ Modifica: autore, copyright, descrizione, marca/modello fotocamera, software, data, e **posizione GPS**.
- ✅ Pulsante per **rimuovere tutti i metadati** (utile per la privacy).

## Provarla in locale

Apri semplicemente `index.html` con doppio clic nel browser. Fatto.

## Metterla online gratis (GitHub Pages)

1. Vai su **Settings → Pages** del repository.
2. Alla voce *Branch* seleziona il branch che contiene `index.html` e cartella `/ (root)`, poi **Save**.
3. Dopo qualche minuto l'app sarà raggiungibile a:
   `https://<tuo-utente>.github.io/<nome-repo>/`

Alternative gratuite altrettanto valide: trascinare `index.html` su [Netlify Drop](https://app.netlify.com/drop) o [Vercel](https://vercel.com).

## Note tecniche

I metadati EXIF esistono solo nei file **JPEG/TIFF** (PNG e WebP non li usano).
La modifica usa la libreria [piexif.js](https://github.com/hMatoba/piexifjs).
