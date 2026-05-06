# TODO — PDF-Lese-Aufgabe

## Aufgabe
Das PDF `HCI 25_26 kompakt.pdf` (475 Seiten) schrittweise (je 20 Seiten) lesen und die Fragen aus `new.md` beantworten. Antworten werden direkt in `new.md` eingetragen.

## Regeln
- Immer 20 Seiten pro Iteration lesen
- Nach jeder Iteration diese Datei aktualisieren:
  1. **Nächste Seiten** — wo weitermachen
  2. **Zusammenfassung** — was die letzten 20 Seiten behandelt haben
- Wenn neue Infos zu einer bereits beantworteten Frage gefunden werden → **immer ergänzen**, nicht ignorieren
- Nach jeder Iteration einen **git commit** erstellen

---

## Status

### Aktueller Stand
- **Nächste Seiten:** 301–320
- **Zuletzt gelesen:** 281–300
- **Achtung:** Mentales Modell ✅ vollständig (Definition, Entstehung, Beispiele Textverarbeitung/Heizung/Time Machine, Zeigarnik-Effekt, Piktorielles Gedächtnis). Fitts's Law ✅ vollständig (Formel, 3 Subprozesse, Mac vs. Windows, Implikationen). Progressive Disclosure ✅ vollständig (Definition, Vor-/Nachteile, Beispiele, Hick's Law + Choice Overload als Kontext). Noch offen: Prototypen/MVP, Nielsen restliche Heuristiken, SUS, Metriken, Top/Left/Right-Label-Alignment (explizit), Summative/Formative, Triangulation, Stakeholder vs. User, Priorisierungsmatrix (Impact×Effort), Aufgabe 2 (Bild bewerten), Gruppe C 8 (Euro-Dollar-Interface).

---

## Iterationslog

### Iteration 15 — Seiten 281–300 (Folien ~561–600)
**Inhalt:** Mentale Rotation/Bildhaftes Gedächtnis (Shepard & Metzler 1977 — lineare Reaktionszeit/Rotationswinkel-Beziehung). Piktorielles Gedächtnis (Folie 563): vorstellbare Wörter besser memoriert, bildhafte + propositionale Repräsentation. Komplexeres Gedächtnismodell (Folie 564): parallele Kanäle Sprache+Bild im Arbeitsgedächtnis. Mentale Modelle (Folien 565–568): subjektives Annahmengerüst, handlungsleitend aber nicht notwendig korrekt; Entstehung aus Erfahrungen + visueller Struktur + vergleichbaren Systemen; Beispiele Textverarbeitung (Autosave vs. Manuell) und Heizung/Backofen. Time Machine als gelungenes Interface-Mentales-Modell (Folie 569). Zeigarnik-Effekt (Folie 572): unvollendete Tasks besser erinnert — Progress Bars als Implikation. Design-Implikationen Gedächtnis (Folie 573): Chunks, externe Hinweise, Mehrfachkodierung, Rekognition, Erwartungskonformität. Aufmerksamkeit (Folie 575): selektive Auswahl, Change Blindness. Fitts's Law (Folien 579–583): T = a + b·log₂(D/W+1), 3 Subprozesse (ballistisch/Homing/Stop), Mac-Menü vertikale Endlosigkeit, Implikationen (große Controls, Select vs. Type, Default Selections, Auto-Complete). Hick's Law (Folien 585–591): Entscheidungszeit als Funktion der Optionsanzahl, 4 Schritte, Beispiele Menüs/Bremsen/Device-Settings, Implikationen (Subtask-Zerlegung, Highlighting). Paradox of Choice (Folien 593–597): Marmeladen-Studie (6→30% Käufer vs. 24→3% Käufer), Choice Overload (Analysis Paralysis + Buyer's Remorse), Lösungen (Kategorisierung, Highlighting, Exklusion+Vergleich). Progressive Disclosure (Folien 599–600): Informationen in Schichten, nur relevantes anzeigen, Vorteile (Clutter, Lernbarkeit, Fehlerreduktion), Nachteile (Hidden Affordance, mehr Klicks).

**Beantwortete/ergänzte Fragen:**
- Gruppe A, 11: Mentales Modell ✅ vollständig (Definition, Entstehung, Beispiele, Zeigarnik, Piktorielles Gedächtnis, Gedächtnis-Design-Implikationen)
- Gruppe B, 3: Fitts'sches Gesetz ✅ vollständig (Formel, Subprozesse, Mac vs. Windows, Implikationen)
- Gruppe C, 5: Fitts'sches Gesetz ✅ Kurzfassung + Verweis
- Gruppe B, 8: Progressive Disclosure ✅ vollständig (Hick's Law + Choice Overload + PD Definition + Vor-/Nachteile)
- Gruppe C, 7: Progressive Disclosure ✅ Kurzfassung + Verweis
- Aufgabe 1: Progressive Disclosure ✅ vollständig (Vorteile/Nachteile/eigene Beispiele)
- Gruppe A, 1: Zeigarnik-Effekt + Piktorielles Gedächtnis + Design-Implikationen ergänzt

### Iteration 14 — Seiten 261–280 (Folien ~522–560)
**Inhalt:** Lesen-Kapitel: R-E-A-D-I-N-G Intro (Folie 522). Fixationen (~200–300ms, Informationsaufnahme) + Sakkaden (50ms, Vor-/Rückwärtssakkaden) (Folie 523). Stroop-Effekt (Folien 524–526): Lesen als automatisierte Fertigkeit; Average Stroop ~40s vs. Average Matching ~17s bei 30 Wörtern. All Caps (Folien 527–528): Lesbarkeit hängt von oberer Worthälfte ab; Großschrift = monotone Rechtecke, schlechter lesbar. Fare Details (Folien 529–532): Beispiele für Clutter (Textblöcke in Tickets). Scannability (Folie 534): Strukturierter Text schneller erfassbar. Nielsen's F-Pattern (Folie 535): Eye-Tracking zeigt F-förmiges Scan-Muster. Gedächtnis-Kapitel (ab Folie 536): Enkodierung + Zugriff auf Wissen. Strukturelle Systeme (Folie 538): Sensorisches → Arbeitsgedächtnis (7±2 Chunks, FILO) → Langzeitgedächtnis. Prozesse (Folie 539): Enkodierung/Speicherung/Retrieval. Vergessenskurve (Folie 541): 100%→55%→45%→30%→15%. Miller's Gesetz (Folien 543–544): Magic Number 7±2, Chunking-Definition. Chunks-Beispiele (Folie 546–547): Pi, ungerade Zahlen, bekannte Phrasen, CSPBUSAIR. Schach-Experiment (Folien 548–549): Experten nutzen Chunks für echte Positionen. Serial Position Effect (Folie 550–551): Primacy + Recency Effect. Von Restorff Effect (Folie 552): Das abweichende Element wird am besten erinnert. Peak-End Rule + Serial/Von-Restorff-Verbindung (Folie 553). Sperling Task (Folien 554–556): Evidenz für sensorisches Gedächtnis. Recognition vs. Recall (Folien 557–558): Recognition > Recall; WIMP = Recognition-Paradigma. Interferenz (Folie 559–560): Design A (konsistent) am besten erlernbar.

**Beantwortete/ergänzte Fragen:**
- Gruppe A, 1: Chunking ✅ vollständig (Miller's Law, Gedächtnissystem, Vergessenskurve, Schach-Experiment, Serial Position Effect, Von Restorff Effect)
- Aufgabe 4: Heuristiken ✅ Recognition rather than Recall + Stroop/All Caps/Scannability/F-Pattern/Interferenz ergänzt



### Iteration 13 — Seiten 241–260 (Folien ~481–520)
**Inhalt:** Group Labels with their Inputs (Folie 481): Label close together, genug Abstand zwischen Feldern. Group Related Information (Folie 482–483): lange Formulare in logische Abschnitte unterteilen; Slider-Werte direkt beim Control. Priorisierung (Folie 484–488): Visuell / Hierarchie (Kontrast, Größe, Gewicht) / Auszeichnung (gezielter Farbeinsatz für Schlüsselelemente). Erkennen von Farben (Folie 490–492): Stäbchen (peripher, Hell/Dunkel) vs. Zäpfchen (Fovea, Farbsehen 3 Typen S/M/L); Farbfehlsichtigkeit Rot/Grün: 8% Männer, 0,4% Frauen, Ursache X-Chromosom. Redundante Kodierung (Folie 495–496): Ampel-Icons (Grün/Rot → grau/grau bei Blindheit → Haken/Kreuz nötig); Dashboard-Metriken (Farbänderung + Pfeil). Kontrast statt Farbe (Folie 497). Supporting Cognition with Colors (Folie 498–503): zeige nur relevant; Sättigung für quantitative Darstellung; Natural Order of Objects. Intentional Misuse (Folie 503–504): Jobs-Tortendiagramm. Farbkonventionen (Folie 505–507): Delete-Dialog (Yes=grün, No=rot); Fehlermeldung in falscher Farbe. Unterscheidbarkeit von Farben (Folie 508–512): angrenzend/größer/gesättigter leichter zu unterscheiden. Farben sind relativ (Folie 513–516): Checkerboard-Illusion. Zurückhaltung Farben (Folie 519–520): wenige, Signalfarben reservieren, Rot+Blau anstrengend, Blau = 4× mehr Lesefehler, kulturabhängig, Design monochrome first.

**Beantwortete/ergänzte Fragen:**
- Aufgabe 5: Redundante Kodierung ✅ vollständig (Ampel-Icons, Dashboard, Stäbchen/Zäpfchen, Farbfehlsichtigkeit, Kontrast-statt-Farbe-Regel)
- Aufgabe 4: Heuristiken ✅ Farbkonventionen ergänzt (Delete-Dialog, Farbregeln)
- Aufgabe 6 / Gruppe B, 5: Label-Alignment ✅ Group Labels + Group Related Information ergänzt
- Gruppe B, 9: Priorisierungsmatrix ⚠️ Visuelle Priorisierung (Hierarchie/Auszeichnung) ergänzt — Impact×Effort-Matrix noch offen

### Iteration 12 — Seiten 221–240 (Folien ~441–480)
**Inhalt:** Design in Greyscale First (Spacing/Contrast/Size erzwingen klare Hierarchie). Use Color to Direct Attention. Principle of Focal Point (Uber-Beispiel: einziger farbiger Button = Call-to-Action; Pop-Out-Zahlen-Beispiel). Using Color for Attentional Control (komplexe Interfaces). Folie 447: „Finde alle Werte >1.0" — parallele Erkennung durch Farbhervorhebung. Continuity (Folie 448–450): Elemente in Linie/Kurve = zusammengehörig. Gestalt Principles in a Nutshell (Folie 450): Zusammenfassung aller 7 Gesetze. Applying Gestalt Principles (Sony Fernbedienung). Wahrnehmung abstrahiert: G/g-Buchstaben-Beispiel; Euro vs. Schweizer Franken (redundante Kodierung); Chihuahua vs. Muffin; Boundary Extension. Parallele Wahrnehmung + Wahrnehmung und Komplexität (Folien 464–467). Lineare vs. parallele Wahrnehmung — Reaktionszeitgraph. Subitizing: 2–4 Objekte 50ms/Obj., 6+ Objekte 250–300ms/Obj. Reduktion der Komplexität durch Ordnung (Folie 471). Gruppierung und Abstände — Nielsen-Heuristik „Ästhetisches und minimalistisches Design" (Folien 472–480): Abstandsregel (Abstand zwischen Feldern > Abstand Label-Feld), Farbe zur Gruppenbildung reduziert wahrgenommene Komplexität.

**Beantwortete/ergänzte Fragen:**
- Gruppe A, 1: Chunking ⚠️ Subitizing + Parallele Wahrnehmung als Grundlage ergänzt (Miller's Law noch offen)
- Gruppe A, 6: Gestaltgesetze ✅ vollständig + Continuity + Focal Point + Nutshell-Übersicht
- Gruppe C, 6: Gestaltungsgesetz und Interface-Beispiel ✅ Continuity + Focal Point ergänzt
- Aufgabe 4: Heuristiken ✅ Nielsen "Ästhetisches und minimalistisches Design" vollständig (psychologische Basis, Abstandsregel, Farbe)
- Aufgabe 5: Redundante Kodierung ✅ vollständig (Definition, Euro/Franken-Beispiel, Interface-Anwendung)
- Gruppe B, 5: Label-Alignment ⚠️ Abstandsregel ergänzt (Top/Left/Right noch offen)
- Aufgabe 6: Links/Rechts/Top-Alignment ⚠️ Grundprinzip ergänzt (Details noch offen)

### Iteration 11 — Seiten 201–220 (Folien ~401–438)
**Inhalt:** Gestaltgesetze vollständig: Einführung (80 % sehen Kopf im Baum, kognitives System sucht Sinn im Ganzen). Geschlossenheit/Closure (Gehirn füllt Lücken: Apple, IBM, Toblerone, Paris 2024 Logos). Gesetz der Nähe (Proximity: Elemente nah beieinander = Gruppe, kein Rahmen nötig, Die Post-Beispiel). Gesetz der Ähnlichkeit (Similarity: ähnliche Elemente = Gruppe; Navigation vs. Text differenzieren; Ähnlichkeit > Nähe). Law of Common Region (gemeinsame Region = Gruppe; explizit durch Rahmen/Farbe oder implizit durch Symmetrie+Nähe). Gesetz der Symmetrie. Figur/Hintergrund Prinzip (kleinere Fläche = Figur, konvexe Muster = Figur; trivial: Modal-Dialog; komplex: Rexton-Interface). Law of Prägnanz (einfachste mögliche Interpretation). Pop-Out Effekt / Merkmalswahrnehmung (Farbe, Form, Größe, Orientierung, Animation → parallele Suche; Reijnen & Wallach 2008). Las Vegas Effect (zu viele Hervorhebungen → keine Hervorhebung).

**Beantwortete/ergänzte Fragen:**
- Gruppe A, 6: Gestaltgesetze ✅ vollständig (alle 7+ Gesetze mit Definitionen, Beispielen, Interface-Implikationen)
- Gruppe B, 10: Nähe-Gesetz ✅ vollständig (Definition, Zeichnung, Interface-Beispiel)
- Gruppe C, 6: Gestaltungsgesetz und Interface-Beispiel ✅ vollständig (Kurzfassung + Verweis)

### Iteration 10 — Seiten 181–200 (Folien ~361–400)
**Inhalt:** Tufte-Praxisbeispiel Abschluss (Eliminierung Hintergrund/Rahmen, strukturierende Segmente, „Zu wenig des Guten?"). Neues Kapitel: Psychologische Grundlagen des Interaction Design. Dieter Rams-Zitat. UX Designer als „holistic empathic problem solvers". Einfache Theorie: Wissen + Ziele → Rationalität → Verhalten. Peter Morville 2002 (construction materials → Cognitive Architecture / behavior → Contextual Inquiry). Cognitive Psychology of Interaction Design: Cognitive re-engineering. Cognitive Architecture (Card, Moran, Newell 1983). Angeboren vs. gelernt (Gesichtserkennung, Johnson & Morton 1991 — 7 Minuten alte Neugeborene). Visuelle Wahrnehmung: 50 % Cortex, 70 % Rezeptoren, 80 % Information. Fovea (Daumennagel-Faustregel), periphere Wahrnehmung. Klassisches Experiment Clark 1998 (Eye-Tracker). Lokales Feedback: „Specify Errors Inline" — Feedback direkt beim Button. Periphere Wahrnehmung: Bewegungserkennung. Sehen als aktiver Konstruktionsprozess (Bottom-up / Top-down, abhängig von Wissen/Zielen/Kontext). Kontext-Beispiel (1N73LL1G3NC3). Optische Täuschungen.

**Beantwortete/ergänzte Fragen:**
- Aufgabe 3: Noise vs. Clutter ✅ ergänzt (Tufte-Praxisbeispiel Abschluss + „Zu wenig des Guten")
- Aufgabe 4: Heuristiken ⚠️ Psychologische Grundlage ergänzt (visuelles System, foveales Sehen, lokales Feedback, Sehen als Konstruktionsprozess) — Nielsen 10 noch offen
- Gruppe A, 6: Gestaltgesetze ⚠️ Fundament ergänzt (visuelle Mustererkennung) — Gesetze selbst noch offen
- Gruppe A, 11: Mentales Design Modell ⚠️ Cognitive Architecture + einfache Theorie ergänzt — Norman's Mental Model noch offen

### Iteration 9 — Seiten 161–180 (Folien ~321–360)
**Inhalt:** Design Funnel (Elaborate & Reduce, 4 Iterationen: General/Coarse/Medium/Fine). Progression: Sketches → Wireframes → Visual Design. Wireframe-Definition vollständig (skeletal framework, information architecture, grid, floor plan Analogie). Tullis-Studie 1987 (Struktur = 3,2 vs. 5,5 Sek.). Harris 2018-Zitat. Von grob zu fein: 6 Schritte. Grid als Designgrundlage (Nutzen für Designer/Teams/Users). Noise & Clutter: Visual Noise Definition, Saint-Exupéry-Zitat, Cluttered Interfaces. 5 Grand Principles of Data Visualization (Edward Tufte): Show data / Data-ink ratio / Erase non-data-ink / Erase redundant data-ink / Revise and edit. Praxisbeispiel Balkendiagramm-Vereinfachung.

**Beantwortete/ergänzte Fragen:**
- Aufgabe 10: Sketches vs. Wireframes ✅ vollständig (Wireframe-Definition + Progression ergänzt)
- Aufgabe 3: Noise vs. Clutter ✅ vollständig (Tufte 5 Prinzipien, Saint-Exupéry, Cluttered Interfaces)
- Gruppe B, 2: Lo-Fi/Hi-Fi ✅ Wireframe-Zwischenstufe ergänzt (MVP noch offen)

### Iteration 1 — Seiten 1–20
**Inhalt:** Einführungsvorlesung. Kursinfos (Dieter Wallach, WS 25/26). Definition von Design (Herbert A. Simon). UX-Mythen (#1 Kunst, #2 Beautification, #3 UI-Design, #4 Testing, #5 Teuer). Konzentrische Kreise: UI → UX → Product Design → CX Design → Service Design. Business Value of Design (DMI 228%, McKinsey 10%). Einführung Psychologie als empirische Wissenschaft. Moore'sches Gesetz vs. kognitive Komplexität.

**Beantwortete Fragen:**
- Gruppe A, 3: UX (teilweise — Usability noch nicht definiert)
- Gruppe A, 4: Service Design vs. UX Design ✅

### Iteration 2 — Seiten 21–40 (Folien ~41–80)
**Inhalt:** Usability & UX-Kapitel. ISO 9241-11 (2018) Usability-Definition (effective, efficient, satisfactory). 5 Neuerungen ISO 2018 vs. 1998 (Interactive Systems, Stakeholder-Ziele, Zufriedenstellung neu, Umgebung erweitert, menschzentrierte Qualität). UX-Definition (Donald Norman + ISO). UX-Zeitstrahl: UX = before/during/after, Usability = only during. „Nutzerzentrierung is a lie" → Balance User/Technik/Ökonomie/Ökologie. Menschzentrierte Gestaltung (DIN EN ISO 9241-210:2019). Myth #6: Planung ist alles. 7 Interaction Design Prinzipien (1–6 gezeigt: Visibility, Consistency, Mapping, Feedback, Constraints, Simplicity).

**Beantwortete Fragen:**
- Gruppe A, 3: UX vs. Usability ✅ vollständig
- Gruppe B, 6: Konsistenz-Prinzip ✅
- Gruppe B, 7: Interaction Design Prinzipien ⚠️ (Prinzip #7 fehlt noch)

### Iteration 8 — Seiten 141–160 (Folien ~281–320)
**Inhalt:** User Story Mapping vollständig (Zweck, Durchführung, Struktur mit Ziel/Aufgaben/Teilaufgaben). Konzept-Kapitel: Steve Jobs Design Philosophy. Interaction Design: Definition, Three Levels of Experiences (Interaction/Journey/Relationship). Was ist Interaktion? (inter agere, perceive•think•act-Zyklen, Sinnesmodalitäten, Handlungsoperatoren). Interaktivität kein binäres Attribut. Architecture (statisch) vs. Interaction Design (dynamisch). 5 Dimensions of Interaction Design (Silver 2018): Words/Visual Representations/Physical Objects or Space/Time/Behaviour. Affordance, Signifier und Feedback: Definition, 4 Signifier (Button), Inherited Affordance, Basic/Complex/Hidden Signifier. Sunk Cost Fallacy: Definition, Concorde-Beispiel, Skireise-Studie, Sunk Cost Loop. Sketches: Definition, Low-Fi by intention, focus on essence.

**Beantwortete/ergänzte Fragen:**
- Gruppe A, 7: Was ist Affordance ✅ vollständig
- Gruppe B, 7: Dimensionen des Interaction Design ✅ 5 Dimensionen ergänzt
- Gruppe B, 11: Phasen + Artefakte ✅ User Story Mapping vollständig ergänzt
- Gruppe C, 1: Sunk Cost Fallacy ✅ vollständig
- Aufgabe 10: Sketches vs. Wireframes ⚠️ Sketches-Teil ergänzt (Wireframes folgen)

### Iteration 7 — Seiten 121–140 (Folien ~241–280)
**Inhalt:** Ideation-Phase vollständig: Ideation fehlt in ISO 9241-210 (Kritik). Iteration vs. Ideation (Cartoon). Satisficing (Herbert Simon). Bill Buxton: Design Elaborate ↔ Reduce. Brainstorming-Problematik (Dominanz einzelner). Decomposition (Simon 1962: bounded rationality). Opportunity Areas: Definition, Entstehung, Prozessfluss (Journey → Challenge → OA → Ideas → Concept → Use-Scenarios). Insight Statements. What-if-Analyse. HMW-Fragen (HOW/MIGHT/WE). 6-3-5 Methode (6 TN, 3 Ideen, 5 Runden, Uhrzeigersinn). Prinzipien Ideation. Nutzungszenario (Definition, Sabine-Frank-Beispiel). User Stories + User Story Mapping.

**Beantwortete/ergänzte Fragen:**
- Gruppe A, 5: 6-3-5 / HMW / Opportunity Areas ✅ vollständig beantwortet
- Gruppe B, 11: Phasen + Artefakte ✅ ergänzt (Ideation, Nutzungszenario, User Story Mapping)
- Aufgabe 8: UX Workshop Ablauf ✅ ergänzt (Ideations-Workshop)

### Iteration 6 — Seiten 101–120 (Folien ~201–240)
**Inhalt:** Analyse-Regel (24h), Confirmation Bias (Bias der User Research). User Research Prozess vollständig: Proto → Research → Validiert. Customer/User Journey Map: Definition, 8 Elemente (Who/What/Phases/Actions/Thoughts/Emotional Exp./Opportunities/Ownership), 3 Zonen (Lens/Experience/Insights), Mapping-Prozess (Steps → Details → Problems → Insight Statements → Feelings → User Needs → Opportunity Areas). Marketing-Phasen (Awareness → Conversion). Peak-End Rule (Kahneman). Service Design: Definition, Produkt vs. Service, UX vs. Service Experience, 5 Prinzipien (Human-Centered/Co-Creation/Sequencing/Evidencing/Holistic). Erfordernisse + Nutzungsanforderungen (Root-Cause Analysis, Wecker-Beispiel). Übergang zu Phase Explore.

**Beantwortete/ergänzte Fragen:**
- Gruppe A, 4: Service Design vs. UX Design ✅ vollständig ergänzt (5 Prinzipien, Service vs. Produkt, Service Experience)
- Gruppe A, 9: Contextual Inquiries ✅ ergänzt (Confirmation Bias, 24h-Analyse-Regel)
- Gruppe A, 10: Erfordernisse + Nutzungsanforderungen ✅ ergänzt
- Gruppe B, 11: Phasen + Artefakte ✅ ergänzt (Von Research zur Synthese, Journey Map als Artefakt)
- Aufgabe 8: UX Workshop Ablauf ✅ vollständig beantwortet

### Iteration 5 — Seiten 81–100 (Folien ~163–200)
**Inhalt:** Vertiefung Contextual Inquiries: Filter-Modell (4 Filter zwischen Forscher und Nutzer), Interview-Typen (Free / Structured / Semi-Structured), Master-Apprentice Model, Fragetypen (Open / Closed / Neutral), Best Practices für Interview-Durchführung, Auswertungsprozess (Sighting → Classify → Extract → Organize → Insights). Jakob Nielsen „First Rule of Usability: Don't Listen!" — Beobachtung vor Interview. Anzahl: 3–6 Interviews/Observationen pro Rolle. Beginn neues Kapitel „Nützliche Methoden": Empathy Maps (4 Quadranten: Says/Thinks/Does/Feels), Feature Maps (Funktionen je nach Relevanz zur Persona), Focus Groups (Steve Jobs-Kritik).

**Ergänzte Fragen:**
- Gruppe A, 9: Contextual Inquiries ✅ vollständig ergänzt (Filter, Interview-Typen, Master-Apprentice, Auswertungsprozess)
- Aufgabe 9: Contextual Inquiries ✅ vollständig ergänzt

### Iteration 4 — Seiten 61–80 (Folien ~121–160)
**Inhalt:** Persona vollständig erklärt (fictional archetypical user, goals/backgrounds/behaviors/utilization). Warum Personas (consensus-building, anti self-referential design, Cooper 2004). Primary vs. Secondary Persona. Proto-Persona vs. Validierte Persona (Annahmen vs. empirische Daten). Prince Charles/Ozzy Osbourne Beispiel (gleiche Demografie ≠ gleiche Designanforderungen). Scenarios (Persona + Context + Goals): Ist-Szenario vs. Soll-Szenario. User Research: Zielsetzung, Methoden. Annahmen-Board / Annahmen-Map (Impact × Unsicherheit). Contextual Inquiries Definition + Funktionsweise + Job Shadowing (GOOB).

**Beantwortete/ergänzte Fragen:**
- Gruppe A, 9: Contextual Inquiries ✅ vollständig
- Gruppe B, 1: Proto-Persona und Persona ✅ vollständig
- Gruppe C, 3: Persona / Proto-Persona ✅ (Kurzfassung)
- Aufgabe 9: Contextual Inquiries ✅
- Aufgabe 14: »Proto« vor Artefakten ✅

### Iteration 3 — Seiten 41–60 (Folien ~81–120)
**Inhalt:** Abschluss 7 Prinzipien (Prinzip 7: Flexibility). Widerspruch Simplicity vs. Visibility. Discoverability-Konzept. Collaborative UX Design Prozess (Double Diamond, 3 Phasen: Understand/Explore/Deliver). Gegen Wasserfall — lineares Modell vs. iteratives. Scoping-Workshop: Proto-Problem Statement, Proto-Persona, Proto-Journey. Problem Statement Vorlage. „Who is the user?" Einstieg Proto/Persona.

**Beantwortete/ergänzte Fragen:**
- Gruppe B, 7: Interaction Design 7 Prinzipien ✅ vollständig (Prinzip 7 ergänzt)
- Gruppe B, 11: Phasen und Artefakte Collaborative UX ✅
- Gruppe B, 1: Proto-Persona ⚠️ (Einstieg, Details folgen)
