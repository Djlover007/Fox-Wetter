# Fox Wetter

Live-Wetter mit PLZ- und Ortssuche (Open-Meteo, Zippopotam; kein API-Key nötig).

## APK und automatische Updates
Bei jedem Upload auf `main` baut GitHub Actions die App und veröffentlicht sie als **Release**.

- Neueste APK immer hier: `https://github.com/Djlover007/Fox-Wetter/releases/latest/download/Fox-Wetter.apk`
- Die App prüft beim Start, ob ein neueres Release existiert, und zeigt dann oben ein Banner „Neue Version verfügbar". Ein Tipp auf „Aktualisieren" lädt die APK, danach installieren.
- Damit die App Updates findet, muss das Repository **öffentlich** sein (Settings → General → Danger Zone → Change visibility).
- Alle Versionen sind mit demselben Schlüssel (`fox-wetter.keystore`) signiert, deshalb lässt sich jede neue APK einfach über die alte installieren.

## Lokal testen
`www/index.html` einfach im Browser öffnen.
