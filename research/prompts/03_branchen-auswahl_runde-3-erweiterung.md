# Deep-Research-Prompt: Branchen-Erweiterung

**Zweck:** Ergänzung der bestehenden KMU-Branchen-Übersicht (14 Kategorien, rund 100 Branchen) um bislang nicht erfasste Branchen, die in Deutschland als KMU-typische Tätigkeitsfelder existieren. Ziel ist ausschließlich eine möglichst vollständige Auflistung; eine Eignungsbewertung, Quellenangabe oder Begründung ist nicht erforderlich.

**Zieltools:** ChatGPT Deep Research, Gemini Deep Research, Perplexity Deep Research (mit Claude Sonnet 4.6)

---

## Prompt

Recherchiere KMU-typische Branchen in Deutschland, die in der unten gelisteten Branchen-Übersicht noch nicht enthalten sind, und ergänze diese in der vorgegebenen Kategorien-Logik.

**ANWENDUNGSKONTEXT:**
Die Branchen-Übersicht ist Arbeitsgrundlage einer Sondierung zu lokalen KMU-Branchen in Deutschland. Sie soll möglichst vollständig sein, also auch kleine, traditionelle oder selten genannte Branchen abdecken. Eignungsbewertung, Beratungspotenzial und Quellen sind in dieser Recherche bewusst kein Thema; es geht ausschließlich um die Erweiterung der Branchen-Liste.

**BESTEHENDE BRANCHEN-ÜBERSICHT:**

*Handwerk & Bau:* Elektriker, Malerbetrieb, Tischlerei, Dachdecker, Garten- und Landschaftsbau, Sanitär und Heizung, Fliesenleger, Gebäudereinigung, Hausmeisterservice, Trockenbau, Schornsteinfeger, Zimmerei, Glaser, Metall- und Schmiedebetrieb, Steinmetz, Lackiererei

*IT & Digitalisierung:* Webentwicklung, App-Entwicklung, KI-Beratung, IT-Support, Cybersecurity, Cloud-Services, Softwareentwicklung, Hosting-Anbieter, SEO-Agentur, Social-Media-Management

*Kreativbranche:* Grafikdesign, Fotograf, Videograf, Musikproduktion, Texter, Werbeagentur, UX/UI Design, Content Creator

*Gesundheit & Pflege:* Physiotherapie, Pflegedienst, Ernährungsberatung, Fitness-Coaching, Personal Trainer, Ergotherapie, Heilpraktiker, Seniorenbetreuung, Zahnarztpraxis, Allgemein- und Facharztpraxis, Tierarztpraxis, Apotheke, Hebamme, Logopädie, Psychotherapie, Optiker, Hörgeräteakustiker

*Gastronomie & Lebensmittel:* Café, Foodtruck, Catering, Bäckerei, Imbiss, Restaurant, Hofladen, Feinkosthandel

*Handel & E-Commerce:* Onlineshop, Amazon FBA, Einzelhandel, Second-Hand-Shop, Technikhandel, Möbelhandel, Tierbedarf, Modegeschäft, Buchhandlung, Floristik/Blumenladen, Drogerie, Sportgeschäft, Spielwarengeschäft, Reformhaus/Bioladen

*Beratung & Dienstleistungen:* Unternehmensberatung, Steuerberatung, Immobilienmakler, Versicherungsagentur, Coaching, Personalvermittlung, Buchhaltung, Übersetzungen, Rechtsanwaltskanzlei, Notar, Wirtschaftsprüfer, Architekturbüro, Ingenieurbüro, Hausverwaltung, Vermessungsbüro

*Bildung & Training:* Nachhilfe, Sprachschule, Online-Kurse, Musikschule, Weiterbildung, Prüfungsvorbereitung, KI-Schulungen

*Landwirtschaft & Regionale Wirtschaft:* Landwirtschaft, Direktvermarktung, Biohof, Pferdehof, Imkerei, Forstwirtschaft

*Mobilität & Fahrzeuge:* Kfz-Werkstatt, Fahrzeugaufbereitung, Fahrschule, Reifenservice, Carsharing, E-Bike-Verleih, Taxiunternehmen, Autohaus/Gebrauchtwagenhandel, Spedition/Lokale Logistik

*Medien & Internet:* YouTube-Kanal, Podcast, Newsletter-Business, Twitch-Streaming, Blog, Online-Magazin

*Lokale Dienstleistungen:* Friseur, Kosmetikstudio, Hundesalon, Schlüsseldienst, Umzugsservice, Eventplanung, Kinderbetreuung, Reisebüro, Wäscherei/Textilreinigung, Nagelstudio, Tattoo-Studio, Massagestudio, Yogastudio, Tanzschule

*Beherbergung & Tourismus:* Hotel, Pension, Ferienwohnung, Campingplatz, Reiseleitung/Stadtführung

*Persönliche Übergänge & Soziales:* Bestattungsunternehmen, Hochzeitsplanung, Trauerredner/Zeremonienleitung, Gemeinnützige Träger

**AUFGABE:**

1. Identifiziere KMU-typische Branchen in Deutschland, die in der obigen Übersicht nicht vorkommen. Berücksichtige insbesondere:
   - klassische Handwerksgewerke, die in der Handwerksordnung verzeichnet sind, aber oben fehlen
   - freie Berufe und akademische Praxen, die nicht aufgeführt sind
   - traditionelle stationäre Fachhandelszweige
   - persönliche und körpernahe Dienstleistungen
   - regulierte oder lizenzpflichtige Tätigkeitsfelder mit KMU-Struktur (z. B. Sicherheits-, Wach-, Bewachungsgewerbe)
   - kleinteilige Produktions- und Verarbeitungsbetriebe
   - Pflege- und Sozialdienste, die jenseits der klassischen Heilberufe operieren
   - religiöse, kulturelle und vereinsnahe Tätigkeitsfelder, sofern erwerbswirtschaftlich betrieben

2. Sortiere ergänzte Branchen in die bestehende Kategorien-Logik ein. Wenn eine Branche thematisch zu keiner bestehenden Kategorie passt, schlage eine neue Kategorie vor.

**OUTPUT-FORMAT:**

Reine Markdown-Liste in der bestehenden Struktur. Pro Kategorie nur die *neu ergänzten* Branchen aufführen; bestehende Branchen nicht wiederholen. Keine Eignungsbewertung, keine Quellen, keine Begründungen.

```
## [Kategoriename]

- [neue Branche]
- [neue Branche]
```

Falls eine vollständig neue Kategorie vorgeschlagen wird, diese ans Ende stellen und entsprechend einleiten.

**AUSSCHLÜSSE:**

- Keine Wiederholung bereits gelisteter Branchen.
- Keine Bewertung von Eignung, Beratungsbedarf, KI-Affinität oder Marktattraktivität.
- Keine Quellenangaben, keine empirischen Belege, keine BibTeX-Einträge.
- Keine Branchen, die ausschließlich Großunternehmen oder Konzernstrukturen betreffen (z. B. Schwerindustrie, Automobilhersteller, Energieversorger).
- Keine reinen Berufsbezeichnungen ohne eigene Geschäftseinheit (z. B. einzelne Arbeitnehmertätigkeiten).
