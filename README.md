# SLEEP QUEST 3.0 – Nightfall Chronicles

Eigenständige, offline-fähige Progressive Web App (PWA) für GitHub Pages.

## Neu in 3.0
- Morgen-, Mittags- und Abendquests mit Start- und Endzeitfenstern.
- Quest-Editor: Titel, Beschreibung, Tagesabschnitt, Uhrzeiten, Wiederholungstage, XP und Gold.
- Goldkonto: Quests und pünktliche Bettzeit geben Gold. Upgrades und Echtzeitkämpfe sind für spätere Versionen vorgesehen.
- Tageslimit für **selbst erstellte** Quests: 300 XP / 150 Gold. Jede Quest kann pro Tag nur einmal belohnt werden.
- Wochenendzeiten: So–Do 23:00 Uhr, Fr/Sa 00:00 Uhr (jeweils Folgetag). Samstag/Sonntag 09:00 Uhr aufstehen, sonst 07:00 Uhr.
- Vorhandene Spielstände werden aus dem lokalen Schlüssel `sleepquest-pwa-v1` übernommen.
- Backup-Export/-Import.

## Veröffentlichung über GitHub Pages
1. Alle Dateien aus diesem ZIP **direkt in das Stammverzeichnis** deines Repositories `Sleep-Quest` hochladen und gleichnamige Dateien ersetzen.
2. Unter **Settings → Pages** die Quelle **Deploy from a branch**, Branch `main`, Ordner `/(root)` einstellen.
3. App unter `https://oemer674.github.io/Sleep-Quest/` öffnen, sobald das Deployment fertig ist.
4. Auf iPhone in Safari **Teilen → Zum Home-Bildschirm**.

## Hinweise
- Die App bestätigt Quests und Bettzeit auf Vertrauensbasis. Sie erkennt weder tatsächlichen Schlaf noch die Nutzung anderer Apps.
- Daten liegen lokal im jeweiligen Browser/der installierten Web-App. Vor dem Update ein Backup exportieren, falls möglich.
- Offline-Nutzung nach erstem vollständigen Laden. Browser-Benachrichtigungen sind noch nicht implementiert.
- Für vergangene Tage ohne Bettbestätigung wird nach der jeweiligen Deadline eine Niederlage verbucht, sobald die App wieder geöffnet wird, sofern der Spielstand bereits begonnen hat.
- Der Bett-Button kann nach Mitternacht für die Freitag- oder Samstagnacht noch angezeigt werden, aber die Deadline ist dann bereits verpasst.
- XP und Gold bereits abgeschlossener Quests werden bei späterem Bearbeiten oder Löschen nicht rückwirkend geändert.
