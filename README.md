#Docker NodeJS Sample

## Projektbeschreibung

Eine einfache ToDo-Applikation mit Node.js und Express.

## Voraussetzungen

- Node.js
- npm
- Docker
- Docker Compose

## Repository klonen

1. Repository klonen:

```bash
git clone <repository-url>
```

2. In das Projektverzeichnis wechseln:

```bash
cd docker-nodejs-sample
```

## Pakete installieren

```bash
npm install
```

## Anwendung lokal starten

```bash
npm run dev
```

Die Anwendung läuft unter:

http://localhost:3000

## Docker-Image erstellen

```bash
docker build -t todo-app .
```

## Anwendung mit Docker starten

```bash
docker run --name todo-container -p 3000:3000 todo-app
```

## Anwendung mit Docker Compose starten

```bash
docker compose up --build
```

## Anwendung stoppen

```bash
docker compose down
```
