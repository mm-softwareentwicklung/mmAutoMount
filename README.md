# mmAutoMount

Verbindet deine Netzwerklaufwerke automatisch, sobald du dich am Mac anmeldest – ohne Anmeldefenster des Finders. Die Passwörter liegen im Schlüsselbund.

## Download und Installation

1. Unter [Releases](../../releases/latest) die Datei `mmAutoMount-<Version>.dmg` herunterladen.
2. DMG öffnen und mmAutoMount in den Ordner „Programme“ ziehen.
3. Beim ersten Start fragt macOS nach einer Freigabe: Systemeinstellungen › Datenschutz & Sicherheit › „Trotzdem öffnen“. Details stehen in der Anleitung in der DMG.

Danach aktualisiert sich mmAutoMount selbst: Die App sucht täglich nach neuen Versionen und installiert sie nach Bestätigung (Einstellungen › „Jetzt suchen …“).

## Funktionen

- Läuft nur in der Menüleiste; ein Klick auf das Symbol öffnet die Einstellungen.
- Beliebig viele Laufwerke (SMB, AFP, NFS, WebDAV), lokal oder über VPN. Gerade im Finder verbundene Laufwerke lassen sich mit einem Klick übernehmen, Einträge duplizieren.
- Anmeldung mit Benutzer und Passwort (im Schlüsselbund gesichert), mit dem Eintrag, den der Finder im Schlüsselbund angelegt hat, oder als Gast.
- Verbindet nach der Anmeldung, nach dem Ruhezustand, bei Netzwerkwechsel und nach dem VPN-Aufbau erneut. Von Hand ausgeworfene Laufwerke bleiben getrennt.
- Die Laufwerke erscheinen wie beim Finder unter `/Volumes` – Aliase funktionieren ohne Login-Fenster.

## Voraussetzungen

- macOS 14 (Sonoma) oder neuer, Mac mit Apple-Chip oder Intel

---

© 2026 Matthias Müller – Softwareentwicklung · [www.mm-softwareentwicklung.de](https://www.mm-softwareentwicklung.de)

Alle genannten Produkt- und Firmennamen sind Marken ihrer jeweiligen Inhaber.
