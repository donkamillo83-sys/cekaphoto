# CEKA Photo

Web-App, die Autofotos direkt am Handy aufbereitet: Belichtung, Weißabgleich, Himmel-Blaustich, Schatten, Lackglanz, Schärfe, Spiegelungen, Format und Wasserzeichen.

Alles läuft lokal im Browser. Es werden keine Fotos hochgeladen und es wird keine KI-API verwendet.

## Dateien

| Datei | Zweck |
|---|---|
| `index.html` | die komplette App |
| `manifest.webmanifest` | macht die App installierbar (Startbildschirm) |
| `sw.js` | Offline-Cache |
| `icons/` | App-Symbole |

## Aufruf

Nach dem Aktivieren von GitHub Pages: `https://BENUTZERNAME.github.io/cekaphoto/`

## Update einspielen

1. Neue `index.html` hochladen und die alte ersetzen.
2. In `sw.js` die Zeile `const CACHE='cekaphoto-v1';` hochzählen (v2, v3 …), damit die Handys die neue Version laden.
