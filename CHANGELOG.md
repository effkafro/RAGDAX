# Changelog

Alle wichtigen Änderungen an diesem Projekt werden in dieser Datei dokumentiert.

## [1.3.1] - 2026-01-14

### Fixed

- Willkommensnachricht wird jetzt beim Sprachwechsel ebenfalls übersetzt

## [1.3.0] - 2026-01-14

### Added

- Sprachumschaltung Deutsch/Englisch (DE | EN)
- Alle UI-Texte werden dynamisch übersetzt
- Sprache wird an API gesendet (language-Parameter)

## [1.2.0] - 2026-01-14

### Changed

- Login-System auf Supabase Auth umgestellt
- Neues Login-Formular mit Email und Passwort
- Chat wird erst nach erfolgreicher Authentifizierung angezeigt
- Fehleranzeige bei ungültigen Anmeldedaten

### Removed

- Altes Passwort-Feld im Header entfernt

## [1.1.0] - 2026-01-14

### Added

- Überschrift "Your Report Assistant" oberhalb des Chat-Fensters
- Willkommensnachricht beim Laden der Seite
- Dark/Light Mode Toggle-Button (oben rechts)
- Theme-Präferenz wird im localStorage gespeichert
- Impressum-Seite (impressum.html)
- Footer mit Link zum Impressum

## [1.0.1] - 2026-01-14

### Fixed

- Zeilenumbrüche werden jetzt korrekt in Bot-Antworten angezeigt
- XSS-Schutz durch HTML-Escaping hinzugefügt

## [1.0.0] - 2026-01-14

### Added

- Initiale Version der RAG Chat-Anwendung
- Chat-Interface mit dunklem Design
- Passwortgeschützter Zugang
- Session-Management für Konversationsverlauf
- Ladeanimation während der Antwortgenerierung
- Responsive Design
