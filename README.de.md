# Lehren und Lernen mit digitalen Werkzeugen

[English](README.md)

Zwei kleine statische Web-Hilfen, ausgeliefert über GitHub Pages:

- **`prompts/`**: Prompting-Tipps für Studierende. Prompt aus fünf Bausteinen bauen (Kontext, Rolle, Aufgabe, Format, Prüfauftrag), Vorlagen fürs wissenschaftliche Arbeiten und die Prüfungsvorbereitung ausfüllen und das Ergebnis kopieren. Gespeichert wird nur die Sprachwahl.
- **`werkzeuge/`**: „Erst das Ziel, dann das Werkzeug“, ein Leitfaden für Lehrende. Er nennt zu sieben Lernzielen passende Moodle- und KI-Werkzeuge, auf Grundlage von Anderson & Krathwohl und TPACK. Dazu gibt es ein A3-Plakat (PDF, deutsch und englisch).

Beide Seiten funktionieren auf Deutsch und Englisch, offline als Einzeldatei, im Dunkelmodus und mit der Tastatur.

## Lokal ansehen

```bash
python3 -m http.server 8000
# http://localhost:8000 öffnen
```

## Quellen und Aktualisierung

`werkzeuge/` ist ein Bauergebnis. Die Quelle (`werkzeuge.json`, `bauen.py`) liegt in einem eigenen, nicht öffentlichen Repository. Dort ändern, neu bauen und `werkzeuguebersicht.html` als `werkzeuge/index.html` samt beiden Plakaten hierher kopieren.

## Lizenz

Inhalte: CC BY-NC-SA 4.0, Christian-Maximilian Steier, Hochschule Düsseldorf. Der Werkzeug-Leitfaden bearbeitet den Moodle Tool Guide (Joyce Seitzinger, Gavin Henrick; deutsche Fassung Hilgenstock, Gebauer, Hartwig; FH Düsseldorf 2013). Icons: Lucide (ISC-Lizenz).
