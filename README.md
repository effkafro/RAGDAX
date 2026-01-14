# RAG Chat

Eine minimalistische Chat-Webanwendung, die mit einem RAG-Backend (n8n Webhook) kommuniziert.

## Features

- Einfache, responsive Chat-Oberfläche
- Dunkles Design
- Passwortgeschützter Zugang
- Session-Management (Konversationsverlauf pro Browser-Session)
- Automatisches Scrollen zu neuen Nachrichten
- Ladeanimation während der Antwortgenerierung

## Technologie

- Reines HTML, CSS und JavaScript (keine Abhängigkeiten)
- Backend: n8n Webhook für RAG-Verarbeitung

## Verwendung

1. `index.html` in einem Webserver hosten oder lokal öffnen
2. Zugangscode im Passwortfeld eingeben
3. Nachrichten eingeben und mit Enter oder "Senden" absenden

## Konfiguration

Die API-URL kann in `index.html` angepasst werden:

```javascript
const API_URL = 'https://your-webhook-url.com/webhook/...';
```

## API-Format

Die Anwendung sendet POST-Requests mit folgendem Format:

```json
{
  "chatInput": "Benutzernachricht",
  "password": "Zugangscode",
  "sessionId": "sess_xxxxx_timestamp"
}
```

Erwartetes Antwortformat:

```json
{
  "output": "Antworttext"
}
```

## Lizenz

MIT
