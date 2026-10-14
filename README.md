# bamix / ESGE AG | Woher der Wert kommt und wo der grösste Hebel liegt

Strategiedeck zu bamix (ESGE AG, Mettlen): Geschäftsmodell, Wettbewerb, Portfolio und Wachstumsoptionen, analysiert auf Basis öffentlicher Quellen. 39 Folien, Stand 14. Oktober 2026.

> Alle Zahlen sind gegen die Originalquelle geprüft, das Quellenverzeichnis steht im Anhang (Folien 37 bis 39). Eigene Vorschläge sind als solche gekennzeichnet. Keine internen oder vertraulichen Daten.

---

## Aufbau des Decks

| Teil | Leitfrage | Folien |
|---|---|---|
| Einstieg | Titel, Executive Summary, Aufbau | 1 bis 3 |
| A Ausgangslage | Wofür bezahlen Kunden, und wie ist das Geschäft aufgestellt? | 4 bis 8 |
| B Markt und Wettbewerb | Wer greift bamix an, und womit? | 9 bis 13 |
| C Portfolio und Roadmap | Was fehlt dem Produkt, und was kommt als Nächstes? | 14 bis 19 |
| D Wachstum | Wo liegt der Hebel, und in welcher Reihenfolge? | 20 bis 26 |
| E Fazit und nächste Schritte | Was folgt aus den Befunden, und was passiert in 90 Tagen? | 27 bis 30 |
| Anhang | Woher stammt jede Zahl? | 31 bis 39 |

---

## GitHub Pages

Die Seite `index.html` zeigt alle Folien als Karten mit Vorschaubild, geordnet nach Teilen, mit Vollbild-Viewer.

- Navigation nach Teilen mit fixierter Kopfzeile
- Vorschaubild je Folie, Klick öffnet den Viewer
- Viewer mit Vor und Zurück, Pfeiltasten, Escape
- Button "Deck öffnen" startet das Deck als Vollbild-Präsentation (`deck/bamix_deck.html`)
- Läuft auf Desktop und Mobile

Aktivierung: Settings, Pages, Source: main branch, / (root).

---

## Technik

- `deck/bamix_deck.html`: das Deck als eine Datei, Schriften eingebettet (Inter, Source Serif 4, SIL Open Font License), läuft offline. Navigation mit Pfeiltasten, Leertaste, Übersicht mit Ü, Direktlink je Folie über `#f<Nummer>` (zum Beispiel `#f12`).
- `thumbs/s01.png` bis `s39.png`: Vorschaubilder, gerendert mit Headless Chrome aus dem Deck, 1280 mal 720.
- `index.html`: Landing Page ohne Abhängigkeiten, ein Skript, keine Bibliotheken.

```
.
├── index.html            # Landing Page (GitHub Pages)
├── README.md
├── deck/
│   └── bamix_deck.html   # Deck, 39 Folien, eine Datei
└── thumbs/
    ├── s01.png
    └── ... s39.png
```

---

## Quellen

Primärquellen mit Datum und Link auf den Folien 37 bis 39: bamix.com und bamix.ch, SRF, nau.ch, Gewerbezeitung, NZZ, CEtoday, Unold, Cherry Terrace, Designbase, Google Patents, Brand Affairs, Helbling, SRF Kassensturz, Computer Bild und testbericht.de zu test 07/2021, Galaxus CH und DE, Bosch, Braun, KitchenAid, Smeg, ACCC, EZB, IGE, Fnac.

---

## Autor

**Marcelo Caballero**
Oktober 2026
