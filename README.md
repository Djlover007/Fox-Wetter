# Fox Wetter

Live-Wetter mit PLZ- und Ortssuche (Open-Meteo, Zippopotam; kein API-Key nötig).

## APK über GitHub bauen
1. Neues Repository auf github.com anlegen und alle Dateien dieses Ordners hochladen (inkl. `.github` und `assets`).
2. Tab **Actions** öffnen. Der Workflow „APK bauen" startet automatisch (oder manuell über „Run workflow").
3. Nach ca. 5 Minuten im fertigen Lauf unter **Artifacts** `wetter-apk` herunterladen, entpacken.
4. `app-debug.apk` aufs Handy kopieren und installieren (Installation aus unbekannten Quellen erlauben).

## Lokal testen
`www/index.html` einfach im Browser öffnen.
