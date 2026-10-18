# SLEEP QUEST 2.0 – Nightfall Chronicles

Dark-Fantasy-PWA für GitHub Pages. Keine externen Abhängigkeiten, keine Anmeldung.

## Update auf GitHub Pages

Lade alle Dateien aus diesem Ordner **direkt ins Hauptverzeichnis** deines bestehenden Repositories `Sleep-Quest` hoch und ersetze gleichnamige Dateien. GitHub Pages: Settings → Pages → Deploy from a branch → main → /(root). Die neue Version wird nach dem Deployment unter https://oemer674.github.io/Sleep-Quest/ erreichbar sein.

**Wichtig:** Nicht das ZIP selbst hochladen. Die Datei `style.css` und die neuen PNG-Icons müssen mit hochgeladen werden. `index.html`, `app.js`, `sw.js` und `manifest.webmanifest` ersetzen die alten Versionen.

## Daten & Regeln

Bestehende lokale Daten unter dem Schlüssel `sleepquest-pwa-v1` werden weiterverwendet. Auf demselben Gerät und derselben URL bleibt der Spielstand normalerweise erhalten. Vor Updates empfiehlt sich ein Backup unter Regeln → Backup exportieren. Private-Browsing-Modus, gelöschte Websitedaten oder ein anderes Gerät können die Speicherung beeinflussen.

Die drei Vorbereitungsquests geben je +20 XP, pünktlicher Bett-Check-in bis 23:00:00 +100 XP, Versäumnis −150 XP und Streak-Reset. Pro 500 XP ein Level. Nicht bestätigte vergangene Tage werden ab dem ersten aktiven Spieltag als verpasst gewertet. Die App erkennt keine tatsächlichen Schlafzeiten und blockiert Social-Media-Apps nicht.

## Offline

Nach erstmaligem Laden kann die App über einen Service Worker offline funktionieren. GitHub Pages liefert die PWA per HTTPS aus.
