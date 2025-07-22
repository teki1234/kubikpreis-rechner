# kubikpreis-rechner

# Kubikpreis-Rechner (PWA)

Ein einfacher, offline-fähiger Kubikmeter-Preisrechner für verschiedene Holzarten – als **Progressive Web App (PWA)** nutzbar auf PC, Tablet oder Smartphone.

![App Icon](./Kubik-Rechner.png)

## ✨ Funktionen

- Holzarten mit individuellen m³-Preisen speichern
- Kubikmeter-Menge eingeben und Preis berechnen
- Holzarten löschen oder aktualisieren
- **Daten bleiben lokal gespeichert** (via `localStorage`)
- **Installierbar als App** (über Chrome, Edge, Safari)
- Offline nutzbar dank Service Worker

## 🚀 Live-Demo

👉 [Hier klicken, um die App zu starten](https://teki1234.github.io/kubikpreis-rechner/) *(nur wenn GitHub Pages aktiviert ist)*

## 🧱 Technologie

- HTML5
- CSS3
- JavaScript (ES6)
- PWA: `manifest.json` + `service-worker.js`
- Speicherung via `localStorage`

## 📲 App installieren

### Auf dem Handy:
1. Öffne die App im mobilen Browser (z. B. Chrome)
2. Wähle „Zum Startbildschirm hinzufügen“ oder „App installieren“

### Auf dem Desktop (Chrome/Edge):
1. Öffne die App im Browser
2. Klicke auf das **Installieren-Symbol** (⤓ oder ➕ in der Adresszeile)

## ⚙ Lokale Entwicklung

```bash
# Lokalen Webserver starten (z. B. mit Live Server oder:
npx serve .
