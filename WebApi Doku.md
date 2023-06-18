# Web-API-Dokumentation

Diese Dokumentation bietet einen Überblick über die Web-API-Anwendung, die mit .NET Core 6.0 und MongoDB entwickelt wurde. Die Anwendung ermöglicht den Zugriff auf eine MongoDB-Datenbank über verschiedene Endpunkte.

## Docker

Die Anwendung kann in einer Docker-Umgebung ausgeführt werden. Verwenden Sie die folgenden Docker-Befehle, um das Projekt zu erstellen und auszuführen:

`docker-compose up --build`

Stellen Sie sicher, dass Docker und Docker Compose auf Ihrem System installiert sind.

## API-Endpunkte

Die Web-API bietet die folgenden Endpunkte:

- `GET /`: Gibt eine Begrüßungsnachricht zurück. Sie können versuchen, diesen Endpunkt auf `http://localhost:5001/` aufzurufen.
- `GET /check`: Überprüft die Verbindung zur MongoDB-Datenbank und gibt den Status sowie eine Liste der vorhandenen Datenbanken zurück. Versuchen Sie, diesen Endpunkt auf `http://localhost:5001/check` aufzurufen.


