# Use-Case-Ergänzung — Ergebnis (Gemini)

**Quelle:** Gemini Deep Research
**Datum:** 2026-05-17
**Zugehöriger Prompt:** [`../prompts/13_use-cases_runde-10-ergaenzung.md`](../prompts/13_use-cases_runde-10-ergaenzung.md)

> *Methodische Anmerkung:* Gemini hat ZWEI Anti-Anchoring-Probleme kumuliert:
> 1. **Format-Verstoß** (wie Round 4, 7, 9): Strategie-Analyse-Stil mit Pro-Branche-Tabellen, aber Funktionsbereich-Notation mit Ampersand statt vorgegebener "und"-Schreibweise.
> 2. **Branchen-Mismatch** (wie Round 3): Gemini hat den vorgegebenen Branchen-Pool eigenmächtig erweitert und ersetzt — eingefügt wurden **Fahrschulen** (gehört zu Mobilität, nicht Bildung), **Volkshochschulen** (nicht im Bestand), **Kinderbetreuung** (gehört zu Lokale Dienstleistungen), **Weinbau** (komplett neu), **GaLaBau** (gehört zu Handwerk & Bau und ist dort schon gemappt), **Ackerbau** und **Milchvieh** statt "Landwirtschaft", **Reitschule** statt "Pferdehof". Beim Merge wird auf den korrekten Bestand zugeordnet; Weinbau-Themen werden nicht aufgenommen (Branche nicht im Sondierungs-Universum).
>
> Dies ist nun das vierte konsistente Anti-Anchoring-Versagen von Gemini in Folge — sehr belastbares Material für Beispiel C im Phase-2-Portfolio.

---

## Transformation der deutschen KMU-Landschaft durch künstliche Intelligenz: Eine sektorale Analyse produktiver Anwendungsfälle unter Berücksichtigung regulatorischer Rahmenbedingungen

Die Integration künstlicher Intelligenz in den deutschen Mittelstand, insbesondere in Kleinstunternehmen und Betriebe mit bis zu 50 Mitarbeitenden, markiert den Übergang von einer experimentellen Phase hin zu einer Phase der industriellen Standardisierung. Dieser Prozess wird maßgeblich durch zwei Faktoren getrieben: die technische Reife generativer und prädiktiver Modelle sowie die sich verschärfende regulatorische Architektur, bestehend aus dem EU AI Act, dem Barrierefreiheitsstärkungsgesetz (BFSG) und sektoralen Verordnungen wie der EU-Öko-Verordnung oder dem Düngerecht.

Unternehmen stehen vor der Herausforderung, KI-Systeme so zu implementieren, dass sie nicht nur operative Effizienzgewinne erzielen, sondern auch die Anforderungen des Artikels 4 des EU AI Acts erfüllen, der seit dem 2. Februar 2025 eine verbindliche KI-Kompetenz für alle Personen vorschreibt, die mit dem Betrieb solcher Systeme befasst sind.

### Cluster 1: Bildung & Training

Im Bildungssektor ist die Anwendung von KI untrennbar mit dem Schutz besonders schutzbedürftiger Personengruppen verknüpft. Die Verarbeitung biometrischer Daten, das Profiling von Lernfortschritten bei Minderjährigen und die Wahrung des Urheberrechts in einer Ära generativer Inhalte bilden den Kern der strategischen Auseinandersetzung.

#### Nachhilfeinstitute

| Funktionsbereich | KI-Anwendungsfall | Reifegrad | Regulatorischer Fokus |
| --- | --- | --- | --- |
| Geschäftsleitung & Strategie | KI-basiertes Compliance-Audit der KI-Kompetenz des Personals (Art. 4 AI Act) | PR | EU AI Act Art. 4, DSGVO |
| Marketing & Kommunikation | Automatisierte barrierefreie Werbekampagnen in Leichter Sprache (BFSG) | PR | BFSG, UrhG |
| Vertrieb & Angebote | Churn-Prediction unter Berücksichtigung von Notenentwicklungs-Trends | EE | DSGVO Art. 5, Art. 22 |
| Verwaltung & Personal | Skill-Gap-Analyse für Lehrkräfte zur inklusiven Pädagogik | PR | EU AI Act Art. 4, Art. 14 |
| Operatives Kerngeschäft | Stylometrische Analyse von Schülertexten zur Früherkennung kognitiver Barrieren (z. B. Dyslexie-Muster) | EE | DSGVO (DSFA-Pflicht), Art. 35 |
| Kundenservice & Beziehung | Eltern-Feedback-System: Lernfortschritte in wertschätzende Narrative übersetzt | PR | DSGVO (Einwilligung Erziehungsberechtigte) |

#### Musikschulen

| Funktionsbereich | KI-Anwendungsfall | Reifegrad | Regulatorischer Fokus |
| --- | --- | --- | --- |
| Geschäftsleitung & Strategie | Strategische Lizenz-Inventur über das Lehrmaterial (KI-generierte Inhalte) | EE | UrhG, GEMA-Vorgaben |
| Marketing & Kommunikation | Image-Filme mit lizenz-vertraglich geklonten Lehrer-Stimmen | EE | Persönlichkeitsrecht, UrhG |
| Vertrieb & Angebote | Instrumenten-Leihverträge nach physischer Eignung (Handgröße via Bild-KI) | EE | DSGVO (Biometrie-Verbot) |
| Verwaltung & Personal | GEMA-Reporting-Tool mit akustischer Werk-Erkennung im Unterricht | EE | UrhG, GEMA-Abrechnung |
| Operatives Kerngeschäft | Echtzeit-Feedback für Intonation und Rhythmik mit anonymisiertem Referenz-Vergleich | PR | DSGVO, UrhG (Zitatrecht) |
| Kundenservice & Beziehung | KI-Bot zur Instrumentenwahl-Beratung mit klanglichen Präferenzen und pädagogischen Zielen | PR | EU AI Act (Transparenz) |

> *Hinweis: Gemini fügte hier Fahrschulen, Volkshochschulen, Kinderbetreuung und Reitschulen ein, die NICHT zum Cluster Bildung & Training gehören. Diese werden beim Merge ignoriert bzw. an den passenden Cluster verwiesen. Auszüge mit relevanten generischen Bildungs-Themen werden trotzdem unten aufgenommen.*

#### Volkshochschulen (Gemini-Erweiterung — beim Merge auf Weiterbildung gemappt)

| Funktionsbereich | KI-Anwendungsfall | Reifegrad | Regulatorischer Fokus |
| --- | --- | --- | --- |
| Geschäftsleitung & Strategie | Strategische Inklusionsplanung aus regionalen Demografiedaten | PR | BFSG, EU AI Act Art. 4 |
| Marketing & Kommunikation | KI-Übersetzung Kursprogramm in Leichte Sprache und Audio-Descriptoren | PR | BFSG, UrhG |
| Vertrieb & Angebote | Förderberechtigungs-Prüfung (Bildungsgutscheine) per Dokumentenanalyse | EE | AZAV, DSGVO |
| Verwaltung & Personal | Onboarding-Pflichtschulung Dozenten (KI-Kompetenz Art. 4 AI Act) | PR | EU AI Act Art. 4 |
| Operatives Kerngeschäft | Echtzeit-Untertitel und Gebärdensprach-Avatare für hybride Kurse | EE | BFSG, DSGVO |
| Kundenservice & Beziehung | Inklusions-Assistent zur Auswahl barrierefreier Kurse | PR | BFSG, DSGVO |

#### Berufliche Weiterbildung / Coaching

| Funktionsbereich | KI-Anwendungsfall | Reifegrad | Regulatorischer Fokus |
| --- | --- | --- | --- |
| Geschäftsleitung & Strategie | Marktanalyse neuer Berufsbilder durch AI Act (KI-Compliance-Beauftragte) | PR | EU AI Act Art. 4 |
| Marketing & Kommunikation | Whitepaper-Generierung aus aktueller Rechtsprechung (z. B. GEMA vs. OpenAI) | PR | UrhG |
| Vertrieb & Angebote | Personalisierte Firmen-Curricula aus Skill-Gap-Analyse der Belegschaft | PR | BBiG, EU AI Act Art. 4 |
| Verwaltung & Personal | AZAV-konforme Kursberichte und Qualitätsdoku per KI-Transkription | EE | AZAV, DSGVO |
| Operatives Kerngeschäft | Reflexionstool für Führungskräfte mit Bias-/Führungsstil-Analyse (post-session) | EE | DSGVO (explizite Einwilligung), Art. 22 |
| Kundenservice & Beziehung | Mentor-Bot für Transfer-Begleitung in den Arbeitsalltag | EE | FernUSG, DSGVO |

#### Sprachschulen

| Funktionsbereich | KI-Anwendungsfall | Reifegrad | Regulatorischer Fokus |
| --- | --- | --- | --- |
| Geschäftsleitung & Strategie | Kursperformance-Analyse für Fachkräfte-Zertifizierungen (FachkrEinwG) | PR | AZAV, BBiG |
| Marketing & Kommunikation | Virtual-Immersion-Avatare mit kulturellen Nuancen | EE | UrhG, EU AI Act |
| Vertrieb & Angebote | Einstufungssystem mit pragmatischer Kompetenz-Bewertung (Höflichkeitsformen) | PR | DSGVO |
| Verwaltung & Personal | FernUSG-konforme Korrektur von Einsendeaufgaben | EE | FernUSG, DSGVO |
| Operatives Kerngeschäft | Prüfungs-Chatbot (TELC, Goethe) mit Echtzeit-Niveau-Feedback | EE | DSGVO, FernUSG |
| Kundenservice & Beziehung | Visumsantrags- und Behördenkommunikations-Assistenz für Drittstaaten-Schüler | EE | DSGVO, Rechtsdienstleistungsgesetz |

### Cluster 2: Landwirtschaft & Regionale Wirtschaft

#### Ackerbaubetriebe (auf "Landwirtschaft" zu mappen)

| Funktionsbereich | KI-Anwendungsfall | Reifegrad | Regulatorischer Fokus |
| --- | --- | --- | --- |
| Geschäftsleitung & Strategie | Agri-PV-Investitionsrechnung (Strom vs. Ernteertrag) | EE | EEG, EU-GAP |
| Marketing & Kommunikation | Reporting reduzierter Herbizideinsatz für Lieferketten (Transparenz-Marketing) | PR | PflSchG, EU-Öko-VO |
| Vertrieb & Angebote | Preisabsicherung/Hedging aus globalen Ernteprognosen und Wettertrends | EE | – |
| Verwaltung & Personal | Schlagkartei-Abgleich mit Copernicus-Sentinel für InVeKoS-Kontrollen | PR | EU-GAP, InVeKoS |
| Operatives Kerngeschäft | NDVI-Trockenstress-Zonen für variable Bewässerung | PR | Wasserhaushaltsgesetz, EU-GAP |
| Kundenservice & Beziehung | Humusaufbau-Dashboard für Verpächter (Bodenfruchtbarkeits-Beleg) | EE | DüV, Bodenschutzgesetz |

#### Milchviehbetriebe (auf "Landwirtschaft" zu mappen)

| Funktionsbereich | KI-Anwendungsfall | Reifegrad | Regulatorischer Fokus |
| --- | --- | --- | --- |
| Geschäftsleitung & Strategie | CO2-Cradle-to-Farm für bessere Molkerei-/Bank-Konditionen | EE | CSRD (KMU-Standard), ISO 14067 |
| Marketing & Kommunikation | Echtzeit-Tierwohl-Einblicke (Aktivitätsindex) für Weidemilch-Branding | PR | TierSchG, LMIV |
| Vertrieb & Angebote | Milchzusammensetzungs-Prädiktion für Fütterungsstrategie und Bonus-Auszahlung | PR | – |
| Verwaltung & Personal | HIT-Datenbank-Bilderkennung für Zu-/Abgangs-Meldung | EE | Viehverkehrs-VO, HIT |
| Operatives Kerngeschäft | Lahmheits- und Stoffwechselstörungs-Früherkennung aus Bewegung und Wiederkau | PR | TierSchG, TierSchNutztV |
| Kundenservice & Beziehung | Tierärztliche Behandlungs-Doku (TAM) per Spracherkennung im Stall | EE | Arzneimittelgesetz (AMG) |

#### Weinbaubetriebe (Branche NICHT im Sondierungs-Universum — beim Merge nicht aufgenommen)

Gemini hat diese Branche eigenmächtig hinzugefügt. Die relevanten Themen (Klima-Resilienz-Rebsorten, Storytelling, Weinbuch-Automation, Peronospora-Bilderkennung, Virtual Sommelier) werden beim Merge ignoriert.

#### Forstbetriebe (auf "Forstwirtschaft" zu mappen)

| Funktionsbereich | KI-Anwendungsfall | Reifegrad | Regulatorischer Fokus |
| --- | --- | --- | --- |
| Geschäftsleitung & Strategie | Bewertung Waldflächen für freiwillige CO2-Zertifikate (Carbon Credits) | EE | EUTR, Bundeswaldgesetz |
| Marketing & Kommunikation | Aufbereitung von Walddaten (Biodiversitäts-Visualisierung) für PR | PR | – |
| Vertrieb & Angebote | Holzpreis-Prädiktion zur Steuerung der Einschlags- und Vermarktungszeitpunkte | EE | – |
| Verwaltung & Personal | LiDAR-Drohnen-Baumzählung und Baumartenbestimmung für Inventurpflicht | PR | ForstvermGG, EUTR |
| Operatives Kerngeschäft | Borkenkäfer-Früherkennung aus multispektralen Sentinel-Daten | EE | Pflanzengesundheits-VO |
| Kundenservice & Beziehung | Digitaler Holz-Lebenslauf vom GPS-Standort bis zum Sägewerk | PR | EUTR, HolzSiG |

#### GaLaBau (Branche im Cluster Handwerk & Bau bereits gemappt — beim Merge nicht aufgenommen)

Gemini hat diese Branche eigenmächtig hinzugefügt. Die Themen werden ignoriert (sie wurden bereits im Handwerk-&-Bau-Cluster behandelt).

#### Imkerei

| Funktionsbereich | KI-Anwendungsfall | Reifegrad | Regulatorischer Fokus |
| --- | --- | --- | --- |
| Geschäftsleitung & Strategie | Wanderimkerei-Routenoptimierung für maximalen Honigertrag bei minimalem Transportstress | PR | TierSchG, Bienenseuchen-VO |
| Marketing & Kommunikation | Bestäubungsleistungs-Doku für Landwirte als ökologischer Ausgleichsbeleg | PR | – |
| Vertrieb & Angebote | Honigzusammensetzungs-Analyse für rechtssichere Sortenhonig-Deklaration (Pollenanalyse) | EE | Honigverordnung, LMHV |
| Verwaltung & Personal | Stockkarten-Spracherkennung direkt am Bienenstand für Doku-Pflicht | PR | Bienenseuchen-VO |
| Operatives Kerngeschäft | Akustische Schwarmprognose per FFT-Frequenzspektrum-Analyse | PR | TierSchG |
| Kundenservice & Beziehung | Alarmservice für Kunden (Landwirte) zu optimalen Bestäubungszeitpunkten | PR | – |

#### Baumschulen

| Funktionsbereich | KI-Anwendungsfall | Reifegrad | Regulatorischer Fokus |
| --- | --- | --- | --- |
| Geschäftsleitung & Strategie | Nachfrageprognose klimaresilienter Stadtbäume zur Steuerung Anzuchtzyklen | EE | – |
| Marketing & Kommunikation | Profi-Bot (Landschaftsarchitekten) für botanische Konsistenz und Verfügbarkeit | PR | – |
| Vertrieb & Angebote | Ersatzpflanzen-Finder mit botanisch gleichwertigen Alternativen | PR | SortenSchG |
| Verwaltung & Personal | Pflanzenpass-Generierung integriert in Warenwirtschaft | PR | Pflanzengesundheits-VO |
| Operatives Kerngeschäft | Vitalitätsprüfung Containerpflanzen per Bildanalyse vor Versand | EE | Pflanzengesundheits-VO |
| Kundenservice & Beziehung | Schädlings-Identifikations-Assistent per Foto-Upload für Endkunden | PR | PflSchG |

#### Direktvermarktung / Hofläden

| Funktionsbereich | KI-Anwendungsfall | Reifegrad | Regulatorischer Fokus |
| --- | --- | --- | --- |
| Geschäftsleitung & Strategie | Standortanalyse für Verkaufsautomaten aus Bewegungs- und Kaufkraftdaten | PR | – |
| Marketing & Kommunikation | Rezepte basierend auf tagesaktuellem Erntebestand | PR | LMHV, LMIV |
| Vertrieb & Angebote | Dynamic Pricing für verderbliche Ware (Food-Waste-Reduktion) | PR | LMHV |
| Verwaltung & Personal | LMIV-konforme Zutatenlisten und Allergen-Kennzeichnung verarbeiteter Produkte | EE | LMIV, LMHV |
| Operatives Kerngeschäft | Machine-Vision-Qualitätskontrolle bei Eigenverarbeitung (Obst-Sortierung) | EE | LMHV |
| Kundenservice & Beziehung | Hof-Assistent-Chatbot mit Verfügbarkeit und Erntezeitpunkten | PR | DSGVO |
