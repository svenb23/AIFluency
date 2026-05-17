# research/ — Arbeitsverzeichnis der Sondierung

Dieser Ordner enthält alle Arbeitsdokumente der Sondierung zu einem KMU-KI-Beratungsangebot. Die finalen Portfolio-Dokumente liegen unter `../report/`.

## Übersicht

```
research/
├── README.md              dieses Dokument
├── methodik.md            Methodik des Branchen-Use-Case-Mappings (6 Funktionsbereiche, 3 Reifegrade)
├── branchen.md            Branchen-Universum der Sondierung (Kategorien mit Einzelbranchen)
│
├── use-cases/             Use-Case-Mappings pro Branche, gruppiert nach Cluster
│   └── handwerk-bau/      14 Handwerks-Branchen (Stand: erste Bearbeitungswelle)
│
├── prompts/               Deep-Research-Prompts, chronologisch nummeriert
└── results/               Deep-Research-Ergebnisse, pro Prompt und Tool eine Datei
```

## Namenskonvention

### Prompts und Ergebnisse

Schema: `[NN]_[bereich]_[runde-zweck](_[tool]).md`

- `NN` — chronologische Nummer (01, 02, 03, …)
- `bereich` — `branchen-auswahl` oder `use-cases`
- `runde-zweck` — z. B. `runde-1-offen`, `runde-2-validierung`, `runde-3-erweiterung`
- `tool` — nur bei Ergebnissen: `chatgpt`, `gemini`, `perplexity`

Beispiele:
- `prompts/04_use-cases_runde-1-vertiefung.md` — der Prompt für die erste Use-Case-Vertiefung
- `results/04_use-cases_runde-1-vertiefung_chatgpt.md` — ChatGPT-Ergebnis dazu

### Branchen-Mappings

Eine Datei pro Branche unter `use-cases/[cluster]/[branche].md`. Dateinamen klein, mit Bindestrich, ohne Umlaute.

Beispiele:
- `use-cases/handwerk-bau/elektriker.md`
- `use-cases/handwerk-bau/sanitaer-heizung.md`
- `use-cases/beratung-dienstleistungen/steuerberater.md` (folgt später)

## Aktueller Bearbeitungsstand

| Cluster | Status | Mappings |
| --- | --- | --- |
| Handwerk & Bau | vollständig | 34 von 34 |
| IT & Digitalisierung | vollständig | 10 von 10 (Cluster in Section 1.1 als Beratungs-Zielgruppe ausgeschlossen, methodisch dennoch gemappt) |
| Kreativbranche | vollständig | 7 von 7 (Cluster in Section 1.1 als Beratungs-Zielgruppe ausgeschlossen, methodisch dennoch gemappt) |
| Gesundheit & Pflege | vollständig | 18 von 18 (Cluster in Section 1.1 wegen DSGVO/§203 StGB ausgeschlossen, methodisch dennoch gemappt; alle Mappings enthalten Datenschutz-Hinweis-Block) |
| Gastronomie & Lebensmittel | vollständig | 11 von 11 — Round-7-Ergänzung aus ChatGPT und Gemini eingearbeitet |
| Handel & E-Commerce | vollständig | 19 von 19 — Round-8-Ergänzung aus ChatGPT eingearbeitet (Gemini/Perplexity offen). Cluster in Section 1.1 ausgeschlossen, methodisch dennoch gemappt |
| Beratung & Dienstleistungen | vollständig | 15 von 15 — Round-9-Ergänzung aus ChatGPT und Gemini eingearbeitet |
| Bildung & Training | vollständig | 7 von 7 — Round-10-Ergänzung aus ChatGPT und Gemini eingearbeitet (Cluster in Section 1.1 ausgeschlossen, methodisch dennoch gemappt) |
| Landwirtschaft & Regionale Wirtschaft | vollständig | 9 von 9 — Round-10-Ergänzung aus ChatGPT und Gemini eingearbeitet |
| Mobilität & Fahrzeuge | offen | 0 von 11 |
| Gesundheit & Pflege | ausgeschlossen | DSGVO/Berufsrecht |
| IT & Digitalisierung | ausgeschlossen | gesättigter Remote-Beratungsmarkt |
| Kreativbranche | ausgeschlossen | gesättigter Remote-Beratungsmarkt |
| Handel & E-Commerce | ausgeschlossen | gesättigter Remote-Beratungsmarkt |
| Bildung & Training | ausgeschlossen | gesättigter Remote-Beratungsmarkt |
| Medien & Internet | ausgeschlossen | gesättigter Remote-Beratungsmarkt |
| weitere Cluster | offen | siehe `branchen.md` |

## Arbeitsweise

1. **Methodik** ist in `methodik.md` fixiert und sollte vor Erweiterungen geprüft werden.
2. **Branchen-Universum** in `branchen.md` ist die Auswahlbasis.
3. **Pro Branche** entsteht eine Mapping-Datei unter `use-cases/[cluster]/[branche].md`.
4. **Deep-Research-Läufe** werden über Prompts in `prompts/` gesteuert; die Ergebnisse landen pro Tool getrennt in `results/`.
