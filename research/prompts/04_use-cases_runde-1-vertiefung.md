# Deep-Research-Prompt: Use-Case-Vertiefung (Handwerks-Branchen)

**Zweck:** Validierung und Ergänzung des bestehenden Branchen-Use-Case-Mappings für vier Handwerks-Branchen (Elektriker, Malerbetrieb, Tischlerei, Dachdecker). Die Erstfassung wurde modellgeneriert (Claude Opus 4.7) und soll durch externe Recherche überprüft, korrigiert und mit fehlenden Anwendungsfällen ergänzt werden.

**Zieltools:** ChatGPT Deep Research, Gemini Deep Research, Perplexity Deep Research (mit Claude Sonnet 4.6)

---

## Prompt

Recherchiere zitierfähige Quellen und empirische Befunde zu produktiven KI-Anwendungsfällen für vier deutsche Handwerks-Branchen mit 1 bis 50 Mitarbeitern. Validiere die unten gelisteten Use-Cases hinsichtlich ihrer Reifegrad-Einstufung, ergänze fehlende Anwendungen und versieh ausgewählte Einschätzungen mit empirischen Belegen.

**ANWENDUNGSKONTEXT:**
Die Recherche ist Teil einer Sondierung zu einem KMU-KI-Beratungsangebot. Für ein Branchen-Use-Case-Mapping werden produktionsreife, eingeschränkt einsatzfähige und nicht geeignete KI-Anwendungen pro Funktionsbereich erfasst. Zielgruppe sind lokale Handwerksbetriebe in Deutschland mit 1 bis 50 Mitarbeitern; Großbetriebe mit eigener IT-Abteilung sind nicht im Scope.

**METHODIK:**

Die Bewertung erfolgt entlang von sechs Funktionsbereichen:
1. Geschäftsleitung und Strategie
2. Marketing und Kommunikation
3. Vertrieb und Angebote
4. Verwaltung und Personal
5. Operatives Kerngeschäft
6. Kundenservice und Beziehung

Reifegrade:
- **PR (Produktionsreif):** heute mit überschaubarem Aufwand und akzeptablem Risiko einsetzbar.
- **EE (Eingeschränkt einsatzfähig):** technisch möglich, mit definierten Auflagen (DSGVO, Bias-Kontrolle, fachliche Validierung).
- **NG (Nicht geeignet):** aktuell ohne erhebliches Risiko nicht produktiv einsetzbar.

**BESTEHENDES MAPPING:**

### Elektriker
- Marktbeobachtung Förderprogramme und Smart-Home-Trends — EE
- Wettbewerbsanalyse lokaler Mitbewerber — EE
- Social-Media-Posts und Blog-Beiträge — PR
- Webseiten-Inhalte (Leistungsbeschreibungen, FAQ) — PR
- Lokale Werbeflyer-Texte — PR
- Angebotserstellung aus Kundenanfragen — PR
- Förderfähigkeits-Recherche (KfW, BAFA) — EE
- Normenrecherche (VDE 0100, DIN) per RAG-System — EE
- Rechnungserstellung aus Stundenzetteln — PR
- Bewerber-Vorselektion — EE
- Fehlerdiagnose-Assistent für elektrische Installation — EE
- Materiallisten-Erstellung aus Bauplänen — EE
- Dokumentation und Prüfprotokolle — PR
- Terminerinnerungen und Folgekontakte — PR
- Beschwerde-Antworten generieren — PR
- Wartungsempfehlungen nach Installation — EE

### Malerbetrieb
- Trendrecherche (Farbtrends, Raumgestaltungs-Stile) — PR
- Social-Media-Posts mit Vorher-Nachher-Bildern — PR
- Webseiten-Inhalte — PR
- Bildgenerierung von Wandgestaltungs-Beispielen — PR
- Angebotserstellung — PR
- Farb-Visualisierung am Kunden-Raumfoto — PR
- Quadratmeter-/Mengenkalkulation aus Raumfotos — EE
- Rechnungserstellung — PR
- Schichtplanung-Vorschläge — EE
- Materialberechnung aus Aufmaßen — EE
- Renovierungs-Checklisten generieren — PR
- Terminerinnerungen — PR
- Pflege-Tipps für Wandflächen nach Abschluss — PR

### Tischlerei
- Trendrecherche (Möbelstile, Materialinnovationen) — EE
- Social-Media-Posts mit Projekt-Fotos — PR
- Portfolio-Texte für Webseite — PR
- Bild-KI-Visualisierungen für Möbel-Entwürfe — PR
- Angebotserstellung mit Leistungsverzeichnis — PR
- Materialkalkulation aus Skizzen — EE
- Maßanfertigungs-Visualisierung für Kunden — PR
- Rechnungserstellung — PR
- Lagerbestand-Bewirtschaftung (Bestellvorschläge) — EE
- CAD-Skizzen in Klartext-Beschreibungen überführen — EE
- Holzart- und Materialberatung per Chat-Assistent — EE
- Terminerinnerungen — PR
- Pflegehinweise für gelieferte Möbel — PR

### Dachdecker
- Marktbeobachtung Förderprogramme (Dachsanierung, PV-Pflicht) — EE
- Social-Media-Posts — PR
- Webseiten-Inhalte — PR
- Vorher-Nachher-Vergleichsbilder — PR
- Angebotserstellung — PR
- Förderfähigkeits-Recherche (KfW, Solar) — EE
- Drohnen-Bildauswertung für Aufmaß und Zustandsanalyse — EE
- Rechnungserstellung — PR
- Sicherheitsunterweisungen aus BG-Bau-Vorgaben — EE
- Dachflächenberechnung aus Luft- oder Drohnenbildern — EE
- Dokumentation und Abnahme-Protokolle — PR
- Terminerinnerungen — PR
- Wartungsvertrags-Inhalte generieren — PR

**AUFGABE:**

Für jede der vier Branchen:

1. **Validierung:** Stimmt die Reifegrad-Einstufung der gelisteten Use-Cases nach aktuellem Stand der KI-Technologie und der branchenspezifischen Regulatorik? Begründe Abweichungen mit Quelle.
2. **Ergänzung:** Welche produktionsreifen oder eingeschränkt einsatzfähigen Use-Cases fehlen im bestehenden Mapping? Pro fehlendem Use-Case: Funktionsbereich, Reifegrad-Einstufung und kurze Begründung.
3. **Empirischer Beleg:** Pro Branche mindestens zwei bis drei Use-Cases mit zitierfähigen Quellen unterlegen (Bitkom-Studien, Handwerks-Verbandspublikationen, ZDH, BG-Bau, KfW, Mittelstand-Digital, branchenspezifische Berufsverbände).
4. **Markierung konvergenter Use-Cases:** Anwendungen, die in mehreren der vier Branchen identisch oder nahezu identisch wiederkehren, in der Anmerkungsspalte als *konvergent* kennzeichnen.

**OUTPUT-FORMAT:**

Pro Branche eine aktualisierte Tabelle mit folgenden Spalten:

| Funktionsbereich | KI-Use-Case | Reifegrad | Anmerkung / Quelle |

Reifegrad-Änderungen gegenüber dem Erstmapping in der Anmerkungsspalte explizit ausweisen (zum Beispiel *vorher EE, jetzt PR mit Quelle X*). Ergänzte Use-Cases erkennbar markieren. Am Ende des Outputs eine kurze Synthese der Konvergenz-Muster über die vier Branchen.

**OUTPUT-STIL:**

APA-7-Stil bei Quellenangaben, Direktlinks zu allen zitierten Quellen, BibTeX-Einträge am Ende. Methodische Einschränkungen des Recherchelaufs explizit ausweisen.

**AUSSCHLÜSSE:**

- Vendor-Marketing und Werbeaussagen von KI-Anbietern.
- Methodisch intransparente Whitepapers.
- Quellen älter als 2023.
- Aussagen ohne empirischen oder fachlichen Beleg.
- Anwendungen für Großbetriebe mit eigener IT-Abteilung.
