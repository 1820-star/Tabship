# Tabship

Ein einfacher Launcher als statische Web-App mit Cloudflare Workers Assets.

## Lokal starten

1. Abhaengigkeiten installieren:

```bash
npm install
```

2. Deploy trocken pruefen:

```bash
npm run deploy:dry
```

## Deploy

```bash
npm run deploy
```

## Wichtige Dateien

- `public/index.html`: Die Launcher-Oberflaeche.
- `wrangler.toml`: Cloudflare-Konfiguration fuer statische Assets.
- `package-lock.json`: Lockfile fuer reproduzierbare CI-Builds.