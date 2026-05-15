# Deep-Research-Prompt: Use-Case-Ergänzung (Handwerks-Branchen, Teil 2)

**Zweck:** Identifikation **fehlender** KI-Use-Cases für zehn weitere Handwerks-Branchen. Im Gegensatz zur vorherigen Vertiefung soll der vorhandene Bestand explizit **nicht** wiederholt werden — gesucht sind ausschließlich Ergänzungen.

**Zieltools:** ChatGPT Deep Research, Gemini Deep Research, Perplexity Deep Research (mit Claude Sonnet 4.6)

---

## Prompt

Recherchiere produktive KI-Anwendungsfälle für zehn deutsche Handwerks-Branchen mit 1 bis 50 Mitarbeitern. **Wichtig:** Die unten gelisteten Use-Cases sind bereits erfasst und sollen nicht erneut genannt werden. Gesucht sind ausschließlich **fehlende, im Bestand nicht aufgeführte** Anwendungsfälle.

**ANWENDUNGSKONTEXT:**
Die Recherche ist Teil einer Sondierung zu einem KMU-KI-Beratungsangebot. Für ein Branchen-Use-Case-Mapping wurde eine Erstfassung modellgeneriert. Nun soll die Vollständigkeit überprüft werden, indem unabhängig recherchiert wird, welche produktiven KI-Anwendungsfälle bislang fehlen.

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

**BEREITS ABGEDECKTER BESTAND (nicht wiederholen):**

### Garten- und Landschaftsbau
Marktbeobachtung Garten-Trends, Wetterprognose-Integration für Einsatzplanung, Social-Media-Posts, Webseiten-Inhalte, Bild-KI für Garten-Entwürfe, Angebotserstellung, Pflanzen-Kalkulation aus Flächenangaben, Bild-Visualisierung am Kundengrundstück, Rechnungserstellung, saisonale Schichtplanung, Pflanzendatenbank-Chat, Material- und Pflanzen-Bestelloptimierung, saisonale Pflegekalender, Terminerinnerungen, Beschwerde-Antworten.

### Sanitär und Heizung
Marktbeobachtung Förderprogramme (BEG, Wärmepumpe), Wettbewerbsanalyse, Social-Media-Posts, Webseiten-Inhalte, Angebotserstellung, Förderfähigkeits-Recherche (BAFA, KfW), Energieberatungs-Vorschläge, Rechnungserstellung, Bewerber-Vorselektion, Hydraulischer Abgleich – Berechnungsunterstützung, Smart-Home-Konfiguration, Anlagen-Dokumentation und Wartungsberichte, Wartungspläne nach Anlagentyp, Terminerinnerungen, Beschwerde-Antworten.

### Fliesenleger
Trendrecherche, Social-Media-Posts, Webseiten-Inhalte, Bild-KI für Verlegemuster-Visualisierung, Angebotserstellung, Materialkalkulation aus Flächenangaben, Bild-Visualisierung am Kundenraum, Rechnungserstellung, Renovierungs-Checklisten, Material- und Werkzeuglisten pro Projekt, Pflegehinweise für gelegte Fliesen, Terminerinnerungen, Beschwerde-Antworten.

### Gebäudereinigung
Marktbeobachtung Reinigungsstandards und Hygiene-Normen, Social-Media-Posts, Webseiten-Inhalte, Angebotserstellung, Kalkulation aus Flächen- und Objekt-Daten, Rechnungserstellung, mehrsprachige Onboarding- und Schulungsmaterialien, Schichtplanung-Vorschläge, Sicherheitsunterweisungen, Tourenplanung-Optimierung, Reinigungsprotokolle automatisiert erstellen, Reklamations-Antworten, Terminerinnerungen.

### Hausmeisterservice
Standortbasierte Tourenplanung, Social-Media-Posts, Webseiten-Inhalte, Angebotserstellung für Hausmeister-Pakete, Service-Level-Vereinbarungen, Rechnungserstellung, Schichtplanung-Vorschläge, Wartungs-Checklisten pro Objekt, Schadens-Dokumentation per Foto und KI-Beschreibung, Übergabeprotokolle, Bewohner-Kommunikation (Aushänge), Mietverwaltung-Korrespondenz, Terminerinnerungen.

### Trockenbau
Marktbeobachtung Ausbau-Trends und Schallschutz-Normen, Social-Media-Posts, Webseiten-Inhalte, Bild-KI für Innenraum-Konzepte, Angebotserstellung, Materialkalkulation (Gipskarton, Profile, Dämmung), Schallschutz-Empfehlungen, Rechnungserstellung, Brandschutz-Normenrecherche per RAG-System, Aufmaß-Auswertung aus Plänen oder Fotos, Bauabschnitts-Dokumentation, Terminerinnerungen, Beschwerde-Antworten.

### Schornsteinfeger
Marktbeobachtung (1. BImSchV, Heizungsförderung), Routenplanung für Kehrbezirke, Webseiten-Inhalte (Bauherrenberatung), Social-Media-Posts mit Energietipps, Angebotserstellung für freiwillige Leistungen, Rechnungserstellung, Compliance-Recherche (Schornsteinfegergesetz, BImSchV), Feuerstättenbescheid-Erstellung aus Messdaten, Messprotokolle automatisch generieren, Energieeffizienz-Empfehlungen an Eigentümer, Bauherren-Beratung zu Heizungsanlagen (Chat-Assistent), Terminerinnerungen für Kehrtermine.

### Zimmerei
Marktbeobachtung Holzbau-Förderung und Klimaschutz-Bauvorschriften, Social-Media-Posts, Webseiten-Inhalte, Bild-KI für Holzbau-Visualisierungen (Carport, Anbau, Dachstuhl), Angebotserstellung mit Leistungsverzeichnis, Materialkalkulation (Holzmenge, Verbinder), Statik-Vorab-Recherche, Rechnungserstellung, Bauantragsvorlagen und Schriftverkehr mit Behörden, Holzart- und Materialberatung per Chat-Assistent, Bauabschnitts-Dokumentation, Pflegehinweise für Holzkonstruktionen, Terminerinnerungen.

### Glaser
Marktbeobachtung Wärmeschutz-Verglasung und Förderprogramme, Social-Media-Posts, Webseiten-Inhalte, Bild-KI für Glaselement-Visualisierungen, Angebotserstellung, Materialkalkulation (Glasflächen, Profile, Beschläge), Rechnungserstellung, Sicherheitsglas-Normenrecherche (DIN 18008), Aufmaß- und Schnittoptimierung, Montagedokumentation, Reparatur- und Pflegehinweise, Terminerinnerungen, Beschwerde-Antworten.

### Metall- und Schmiedebetrieb
Marktbeobachtung Material-Innovationen und Designtrends, Social-Media-Posts mit Projekt-Fotos, Webseiten-Inhalte, Bild-KI für Schmiede-Entwürfe (Geländer, Tore, Treppen), Angebotserstellung, Materialkalkulation (Stahl, Profile, Halbzeuge), Maßanfertigungs-Visualisierung, Rechnungserstellung, Schweißprotokoll- und Sicherheits-Dokumentation, Zuschnitt- und Nesting-Optimierung, Pflegehinweise (Rostschutz, Wartung), Terminerinnerungen, Beschwerde-Antworten.

**AUFGABE:**

Identifiziere pro Branche **ausschließlich Use-Cases, die im obigen Bestand nicht enthalten sind**. Die KI-Anwendungen müssen:

- für Betriebsgrößen von 1 bis 50 Mitarbeitern realistisch sein
- mindestens den Reifegrad *Eingeschränkt einsatzfähig (EE)* aufweisen
- entlang der sechs Funktionsbereiche zugeordnet werden
- spezifisch genug formuliert sein, um nicht mit bestehenden Use-Cases zusammenzufallen

Gehe bei der Recherche von branchen-typischen Tätigkeiten aus, die im Bestand bisher unberücksichtigt sind: digitale Bauakte, Bauleiter-Kommunikation, Logistik-Optimierung zwischen Baustellen, Lieferanten-Kommunikation, Versicherungs- und Schadensabwicklung, Subunternehmer-Koordination, Förder-Antragsbearbeitung, Aus- und Weiterbildung, Werbeplakat-Gestaltung, Auftragsbuch-Auswertung, Wettbewerbs-Monitoring auf Plattformen und vergleichbare Aspekte.

**OUTPUT-FORMAT:**

Pro Branche eine separate Liste mit ausschließlich **neuen** Use-Cases:

```
## [Branche]

| Funktionsbereich | KI-Use-Case | Reifegrad | Kurzanmerkung |
| --- | --- | --- | --- |
```

Keine Quellen, keine BibTeX-Einträge, keine Belege erforderlich. Kein Wiederholen des Bestands. Wenn für eine Branche keine sinnvollen Ergänzungen gefunden werden, dies explizit benennen.

**AUSSCHLÜSSE:**

- Keine Wiederholung des oben gelisteten Bestands.
- Keine Anwendungen für Großbetriebe (über 50 Mitarbeiter).
- Keine generischen oder allgemein gehaltenen Vorschläge ohne konkreten Branchenbezug.
- Keine Use-Cases mit Reifegrad *Nicht geeignet*.
