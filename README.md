# Website „Radikal bremsen. Jetzt." — Schiene A (global/DACH)

Statische Info-Seite mit der Kausalkette **Fossile Energie → CO₂ → Erderwärmung → Katastrophen**,
belegten Fakten, Diagrammen und frei herunterladbaren Flyern & Sharepics.

## Ordnerinhalt
```
site/
├─ index.html                → die Seite selbst (muss im Repo-Root liegen)
├─ .nojekyll                 → schaltet GitHub-Jekyll-Verarbeitung aus (nicht löschen)
├─ assets/img/               → die 3 Diagramme
└─ assets/downloads/         → Flyer (PDF) & Sharepics (PNG) zum Download
```

## Lokal ansehen (ohne Internet)
`index.html` doppelklicken — öffnet im Browser, alle Bilder werden angezeigt.

## Auf GitHub Pages veröffentlichen (kostenlos)

1. Auf **github.com** einloggen → oben rechts **„+" → „New repository"**.
2. **Repository name:** z. B. `radikal-bremsen` (klein, keine Leerzeichen/Umlaute).
   Sichtbarkeit **Public**. Dann **„Create repository"**.
3. Auf der neuen Repo-Seite: **„uploading an existing file"** (oder **Add file → Upload files**).
4. Im Windows-Explorer in den Ordner **`site`** gehen, **den gesamten Inhalt markieren**
   (`index.html`, `.nojekyll`, Ordner `assets`, `README.md`) und in das Upload-Feld ziehen.
   Die Ordnerstruktur bleibt erhalten.
   ⚠️ Nicht den Ordner `site` selbst hochladen — nur seinen **Inhalt** (die `index.html` muss im Repo-Root liegen).
5. Unten **„Commit changes"**.
6. Repo → **„Settings"** → linkes Menü **„Pages"**.
7. Unter **„Build and deployment"**: Source **„Deploy from a branch"**, Branch **„main"**,
   Ordner **„/ (root)"** → **„Save"**.
8. 1–2 Minuten warten. Oben auf der Pages-Seite erscheint die Adresse:
   **`https://<dein-benutzername>.github.io/radikal-bremsen/`** — fertig, live.

## Aktualisieren
**Add file → Upload files** → geänderte Datei hochladen → **Commit changes**. Nach ~1 Minute live.

## Tipps
- Willst du die Seite ohne Unterpfad (direkt unter `https://<benutzername>.github.io/`),
  nenne das Repo exakt **`<benutzername>.github.io`**.
- Eigene `.de`-Domain später: ~10 €/Jahr, unter Settings → Pages → „Custom domain" eintragbar.
- **Impressum:** Bei politischer Öffentlichkeitsarbeit in Deutschland vor dem Live-Gang ergänzen
  (Platzhalter steht im Footer der `index.html`).
