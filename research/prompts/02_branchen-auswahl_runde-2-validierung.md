# Deep-Research-Prompt: Branchen-Validierung (erweitertes KMU-Universum)

**Zweck:** Validierung und Eignungsbewertung eines vordefinierten KMU-Branchen-Universums (rund 80 Branchen aus 12 Kategorien) für ein GenAI-Beratungsangebot. Ergänzt den ersten Deep-Research-Lauf (`01_branchen-use-case-mapping.md`), der durch Quellenbias auf wenige kanonische Branchen konvergierte.

**Zieltools:** ChatGPT Deep Research, Gemini Deep Research, Perplexity Deep Research (mit Claude Sonnet 4.6)

---

## Prompt

Recherchiere zitierfähige Quellen und empirische Befunde zur Frage, welche der unten gelisteten KMU-Branchen in Deutschland heute als realistische Erstkandidaten für ein externes GenAI-Beratungsangebot in Frage kommen. Die Branchenliste ist vorgegeben und soll vollständig bewertet werden — eigene Ergänzungen sind nicht erwünscht.

**ANWENDUNGSKONTEXT:**
Die Arbeit ist eine Sondierung, die als Zwischenprodukt ein Branchen-Use-Case-Mapping und ein Business Model Canvas für ein hypothetisches KMU-KI-Beratungsangebot liefert. Ein erster Recherchelauf hat nur eine schmale Branchenauswahl ergeben (Handwerk, Friseurhandwerk, Gastgewerbe, Steuerberatung, Einzelhandel), weil sich generative KI bei der Branchen-Generierung stark an prominent dokumentierten Beispielen aus Verbands- und Bitkom-Quellen orientiert. Der vorliegende Lauf soll diese Verengung systematisch ausgleichen, indem die breitere KMU-Landschaft entlang einheitlicher Kriterien bewertet wird.

**ZU BEWERTENDES BRANCHEN-UNIVERSUM:**

*Handwerk & Bau:* Elektriker, Malerbetrieb, Tischlerei, Dachdecker, Garten- und Landschaftsbau, Sanitär und Heizung, Fliesenleger, Gebäudereinigung, Hausmeisterservice, Trockenbau

*IT & Digitalisierung:* Webentwicklung, App-Entwicklung, KI-Beratung, IT-Support, Cybersecurity, Cloud Services, Softwareentwicklung, Hosting-Anbieter, SEO-Agentur, Social-Media-Management

*Kreativbranche:* Grafikdesign, Fotograf, Videograf, Musikproduktion, Texter, Werbeagentur, UX/UI Design, Content Creator

*Gesundheit & Pflege:* Physiotherapie, Pflegedienst, Ernährungsberatung, Fitness-Coaching, Personal Trainer, Ergotherapie, Heilpraktiker, Seniorenbetreuung

*Gastronomie & Lebensmittel:* Café, Foodtruck, Catering, Bäckerei, Imbiss, Restaurant, Hofladen, Feinkosthandel

*Handel & E-Commerce:* Onlineshop, Amazon FBA, Einzelhandel, Second-Hand-Shop, Technikhandel, Möbelhandel, Tierbedarf, Modegeschäft

*Beratung & Dienstleistungen:* Unternehmensberatung, Steuerberatung, Immobilienmakler, Versicherungsagentur, Coaching, Personalvermittlung, Buchhaltung, Übersetzungen

*Bildung & Training:* Nachhilfe, Sprachschule, Online-Kurse, Musikschule, Weiterbildung, Prüfungsvorbereitung, KI-Schulungen

*Landwirtschaft & Regionale Wirtschaft:* Landwirtschaft, Direktvermarktung, Biohof, Pferdehof, Imkerei, Forstwirtschaft

*Mobilität & Fahrzeuge:* Kfz-Werkstatt, Fahrzeugaufbereitung, Fahrschule, Reifenservice, Carsharing, E-Bike-Verleih

*Medien & Internet:* YouTube-Kanal, Podcast, Newsletter-Business, Twitch-Streaming, Blog, Online-Magazin

*Lokale Dienstleistungen:* Friseur, Kosmetikstudio, Hundesalon, Schlüsseldienst, Umzugsservice, Eventplanung, Kinderbetreuung

**BEWERTUNGSKRITERIEN PRO BRANCHE:**

Jede Branche wird auf einer dreistufigen Eignungsskala für ein externes GenAI-Beratungsangebot eingeordnet:

- **HOHE EIGNUNG:** Beratungsbedarf empirisch belegt, sinnvolle Use-Cases produktionsreif, keine prohibitiven regulatorischen Hürden, KMU-Dichte hoch.
- **EINGESCHRÄNKTE EIGNUNG:** Use-Cases existieren, aber regulatorisch, ökonomisch oder strukturell schwieriger (z. B. starke DSGVO-Last, geringe Zahlungsbereitschaft, sehr kleine Marktbasis).
- **GERINGE EIGNUNG:** Entweder bereits stark KI-affin (kein Beratungsbedarf), zu wenige Use-Cases mit Mehrwert oder strukturelle Ausschlussgründe (Haftung, Berufsrecht, Datenschutz).

Begründung jeweils kompakt entlang folgender fünf Achsen:

1. **Text- und Kommunikationsintensität** der typischen Tätigkeit (wo generative Sprach-, Bild-, Code- oder Daten-KI heute produktiv ist)
2. **KMU-Dichte und Betriebszahlen** in Deutschland (mit Quelle)
3. **Aktueller KI-Adoptionsstand** und Beratungsbedarf (mit empirischem Beleg, falls verfügbar)
4. **Regulatorische Praktikabilität** (DSGVO, Berufsrecht, Haftung)
5. **Eigen-KI-Affinität** der Branche (ist die Branche bereits selbst KI-Anbieter oder -Anwender und damit als Beratungs-Zielgruppe ungeeignet?)

**OUTPUT-FORMAT:**

Pro Kategorie eine Übersichtstabelle mit den Spalten *Branche*, *Eignungsstufe*, *Kernbegründung (1–2 Sätze)*, *Wichtigste Quelle*. Anschließend pro Kategorie ein kurzer Fließtext-Abschnitt (4–8 Sätze), der die Eignungs-Muster innerhalb der Kategorie zusammenfasst (z. B. „IT-nahe Branchen fallen durchgehend in *geringe Eignung*, da Beratungsbedarf gegen Null geht").

Am Ende des Outputs:

- **Top-Empfehlungen:** Die zehn Branchen mit der höchsten Eignung, gerankt mit jeweils einer Satzbegründung.
- **Methodische Einschränkungen** des Recherchelaufs.

**OUTPUT-STIL:**

APA-7-Stil bei Quellenangaben, Direktlinks zu allen zitierten Quellen, BibTeX-Einträge am Ende, methodische Einschränkungen explizit ausgewiesen.

**AUSSCHLÜSSE:** Vendor-Marketing, methodisch intransparente Whitepapers, Pressemitteilungen, Quellen älter als 2023. Keine Ergänzung weiterer Branchen über das vorgegebene Universum hinaus.
