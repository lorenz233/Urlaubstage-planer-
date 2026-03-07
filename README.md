# Urlaubstage-Planer

Ein einfacher Web-Urlaubsrechner für **Mecklenburg-Vorpommern (Deutschland)**.  
Die App berechnet, wie viele Urlaubstage du zwischen Start- und Enddatum brauchst – Wochenenden und regionale Feiertage werden automatisch berücksichtigt.

## Funktionen

- Berechnung benötigter Urlaubstage in einem Zeitraum
- Automatische Berücksichtigung von Wochenenden
- Berücksichtigung MV-spezifischer Feiertage (inkl. beweglicher Feiertage über Ostern)
- Tagesgenaue Aufschlüsselung (Urlaub / Wochenende / Feiertag)
- Sprachumschaltung Deutsch/Englisch

## Projektstruktur

- `index.html` – komplette App (UI, Logik, Feiertagsberechnung)

## Lokal starten

Da das Projekt ohne Build-Setup auskommt, reicht ein Browser:

1. Repository klonen oder herunterladen
2. `index.html` im Browser öffnen

Optional mit lokalem Server:

```bash
python -m http.server 8000
```

Danach im Browser öffnen: `http://localhost:8000`

## Ideen für zukünftige Verbesserungen

- Unterstützung für weitere Bundesländer oder Länder (wählbare Feiertagsregion)
- Export-Funktion (z. B. iCal/CSV/PDF) für die geplanten Urlaubstage
- Persistenz der Eingaben über `localStorage`
- Validierungs- und Unit-Tests für Feiertags- und Datumslogik
- Trennung von HTML, CSS und JavaScript in eigene Dateien für bessere Wartbarkeit
- Progressive Web App (PWA) mit Offline-Unterstützung
- Barrierefreiheit weiter verbessern (ARIA, Tastatur-Navigation, Kontrastprüfung)
