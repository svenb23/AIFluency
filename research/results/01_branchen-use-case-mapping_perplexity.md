# Branchen-Use-Case-Mapping — Ergebnis (Perplexity Deep Research)

**Quelle:** Perplexity Deep Research mit Claude Sonnet 4.6
**Datum:** 2026-05-14
**Zugehöriger Prompt:** [`../prompts/01_branchen-use-case-mapping.md`](../prompts/01_branchen-use-case-mapping.md)

---

## Ausgewählte KMU-Branchen

Drei Branchen mit hoher KMU-Dichte, text- und kommunikationsintensiven Tätigkeiten sowie niedriger KI-Adoption eignen sich als Erstkandidaten:

1. **Handwerk** (insbesondere Friseurhandwerk)
2. **Gastgewerbe**
3. **Freiberufliche Dienstleistungen** (z. B. Steuerberatung)

Diese erfüllen die Auswahlkriterien:
- Viele kleine Betriebe (>80.000 pro Branche)
- Umsatzrelevanz (>7 Mrd. €)
- Geringe GenAI-Nutzung (ca. 12–20 % KI-Adoption insgesamt, in den Branchen niedriger)
- DSGVO-Hürden überschaubar bei nicht-kritischen Anwendungen
- Empirische Strukturdaten verfügbar (Destatis, Bitkom)

---

## 1. Handwerk (Friseurhandwerk)

**Markt- und Strukturzahlen**
- Ca. **80.500 Betriebe** (2023), meist <5 Beschäftigte
- Umsatz ca. **7,5 Mrd. €** (2023)
- KMU-Anteil ~99 %
- Größere Handwerksgewerbegruppe insgesamt: 564.000 Betriebe, 6 Mio. Beschäftigte

**Use-Case-Mapping**

| Kategorie | Produktionsreif | Eingeschränkt einsatzfähig | Nicht geeignet |
| --- | --- | --- | --- |
| **Kommunikatoren** | Texterstellung (Werbetexte, Social-Media-Posts); Übersetzung (mehrsprachige Flyer) | Zusammenfassung (Kundenfeedback): DSGVO-konform mit Anonymisierung; Bias-Risiko bei Bewertungen | — |
| **Kreative** | Werbe-Visuals (Social-Media-Bilder); Logo-Skizzen | — | — |
| **Ingenieure** | Vorlagenbasierte Websites | Automatisierung (Terminbuchung): Fachkontrolle nötig | — |
| **Analysten** | Umsatzdaten-Auswertung (Trendanalysen aus Buchhaltung) | Bestelldaten (Inventar): Bias bei Vorhersagen | — |

**Branchenspezifische Risiken**
- Sprachvielfalt (Dialekte) erfordert feine Abstimmung
- DSGVO bei Kundendaten streng, aber vertretbar ohne personenbezogene Trainingsdaten

---

## 2. Gastgewerbe

**Markt- und Strukturzahlen**
- Ca. **206.000 Betriebe** (2024), überwiegend klein (Hotels/Gasthöfe <20 Beschäftigte)
- Regional >3 Mrd. € Umsatz (Beispiel Sachsen), bundesweit hochrelevant
- Hohe KMU-Dichte, niedrige Digitalisierung

**Use-Case-Mapping**

| Kategorie | Produktionsreif | Eingeschränkt einsatzfähig | Nicht geeignet |
| --- | --- | --- | --- |
| **Kommunikatoren** | Texterstellung (Menüs, Posts); Übersetzung (Touristenmenüs) | Zusammenfassung (Rezensionen): Bias-Kontrolle erforderlich | — |
| **Kreative** | Social-Media-Bilder (Angebote, Instagram) | Werbe-Visuals (Plakate): Urheberrechtsprüfung | — |
| **Ingenieure** | Websites mit Buchungssystemen (low-code); Bestellautomatisierung via Sprach-KI | — | — |
| **Analysten** | Termin- und Umsatzdaten (Buchungs-Prognosen) | Bestelldaten (Lieferketten mit manueller Validierung) | Autonome Preisanpassungen (Bias-Risiko) |

**Branchenspezifische Risiken**
- Hohe Personalfluktuation erfordert schnelle Anpassung
- DSGVO bei Gästedaten (keine sensiblen Profile)
- Regulatorisch unkompliziert außer Hygiene

---

## 3. Freiberufliche Dienstleistungen (Steuerberatung)

**Markt- und Strukturzahlen**
- KMU-Anteil >99 %, ca. **500.000+ Betriebe** (freie Berufe gesamt)
- Umsatzrelevant (BStBK-Daten)
- Kleine Betriebsgröße, textintensiv — Top-3 KMU-Branche

**Use-Case-Mapping**

| Kategorie | Produktionsreif | Eingeschränkt einsatzfähig | Nicht geeignet |
| --- | --- | --- | --- |
| **Kommunikatoren** | Zusammenfassung (Berichte, Dokumentation); Texterstellung (Klientenmails) | Übersetzung (international): Fachvalidierung erforderlich | — |
| **Kreative** | — | — | — |
| **Ingenieure** | Code-Automatisierung (interne Skripte) | Websites: Compliance-Prüfung erforderlich | — |
| **Analysten** | Umsatzdaten-Auswertung (automatisierte Analysen) | — | Autonome Entscheidungen im Steuerrecht |

**Branchenspezifische Risiken**
- Hohe DSGVO-Strenge (persönliche Finanzdaten)
- Bias in Analysen
- Berufsrechtliche Haftung erfordert menschliche Kontrolle

---

## Quervergleich der Branchen

**Branchenübergreifende Quick Wins** (produktionsreif, niedriges Risiko):
- Texterstellung und Zusammenfassung (Kommunikatoren)
- Werbe-Visuals und Social-Media-Bilder (Kreative)
- Umsatzanalysen (Analysten)
- Bitkom: 54 % der Unternehmen sehen KI-Mehrwert für Arbeitsabläufe

**Branchenspezifische Stärken**
- **Gastgewerbe:** Ordermanagement mit Sprach-KI
- **Friseurhandwerk:** Terminbuchung

---

## Wettbewerbsumfeld (Förder- und Beratungslandschaft)

- **go-digital** (BMWK-Förderprogramm)
- **Mittelstand-Digital-Zentren**
- **Handwerk Digital**

Diese bieten KI-Einstieg, decken aber **GenAI-spezifische Beratung für KMU** noch nicht systematisch ab — erkennbare Marktlücke.

---

## Methodische Einschränkungen

- Datenstand bis 2024/2025 (Destatis, Bitkom)
- Umfragen repräsentativ (n > 600), aber Selbstselektion möglich
- Fokus auf KMU mit >10 Beschäftigten; GenAI nicht immer separat ausgewiesen
- Keine branchenspezifischen GenAI-Studien vorhanden; Ableitung aus allgemeiner KI-Adoption

---

## Quellen (APA-7)

- Bitkom e. V. (2024). *Künstliche Intelligenz in Deutschland — Status quo und Ausblick*. <https://bitkom-research.de/KI-in-deutschland-status-quo>
- DEHOGA. (2025). *Anzahl der Unternehmen im Gastgewerbe*. <https://www.dehoga.de/zahlen-fakten/anzahl-der-unternehmen>
- Statistisches Bundesamt. (2026). *Handwerksunternehmen 2024*. <https://www.destatis.de>
- Zentralverband Deutsches Friseurhandwerk. (2024). *Die wirtschaftliche Lage des Friseurhandwerks*. <https://imsalon.de/branchen-news/>

### BibTeX

```bibtex
@techreport{bitkom2024,
  author = {{Bitkom e.\,V.}},
  title  = {K{\"u}nstliche Intelligenz in Deutschland -- Status quo und Ausblick},
  year   = {2024},
  url    = {https://bitkom-research.de/KI-in-deutschland-status-quo}
}

@techreport{destatis2026handwerk,
  author = {{Statistisches Bundesamt}},
  title  = {Handwerksunternehmen 2024},
  year   = {2026},
  url    = {https://www.destatis.de}
}

@misc{dehoga2025,
  author = {{DEHOGA}},
  title  = {Anzahl der Unternehmen im Gastgewerbe},
  year   = {2025},
  url    = {https://www.dehoga.de/zahlen-fakten/anzahl-der-unternehmen}
}

@misc{friseur2024,
  author = {{Zentralverband Deutsches Friseurhandwerk}},
  title  = {Die wirtschaftliche Lage des Friseurhandwerks},
  year   = {2024},
  url    = {https://imsalon.de/branchen-news/}
}
```
