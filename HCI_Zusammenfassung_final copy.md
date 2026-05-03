### 1. Bitte erläutern Sie den Einsatz von Progressive Disclosure am Beispiel Ihres Übungsthemas. Was ist Progressive Disclosure?

---

### 2. Welche Vorteile oder Nachteile hat Progressive Disclosure?

---

### 3. Definition Usability:

---

### 4. Bitte erklären Sie den Bedeutungsunterschied zwischen UI (User Interface) und UX (User Experience).

---

### 5. Erläutern Sie Quantitative UX-Metrik:

Eine **Metrik** bildet eine Produkteigenschaft auf ein qualitatives oder quantitatives Gütemaß ab und macht damit das Vorhandensein und/oder die Messung der Ausprägung einer Eigenschaft überprüfbar *(Quelle: 1_scoping.md)*.

Quantitative UX-Metriken messen messbare, numerisch ausdrückbare Aspekte der Nutzungsqualität. Im **Metrikenboard** des Roadmap-Workshops werden typischerweise drei Klassen quantitativer Metriken eingesetzt *(Quelle: 8_roadmap.md)*:

| UX-Metrik | Messmethode | Ausgangswert | Zielwert MVP |
|-----------|-------------|-------------|-------------|
| **Subjektive Beurteilung** | SUS-Befragung (10 Fragen, 5-stufige Skala) | 62 Punkte | 70 Punkte |
| **Effizienz** | Zeitmessung mit Log (Minuten pro Tag für Leistungserfassung) | 14 Min | 13 Min |
| **Effektivität** | Anteil verrechenbarer Stunden pro Tag | 70% | 71% |
| **Fehlrate** | Anzahl Reklamationen pro Kunde pro Monat | 4,2 | 4,2 (MVP) |

**SUS (System Usability Scale):** Standardisierter Fragebogen zur Messung der subjektiven Gebrauchstauglichkeit; ermöglicht den Vergleich mit veröffentlichten Benchmarkwerten *(Quelle: 8_roadmap_vokabular.md)*.

**Zweck quantitativer Metriken:** Durch das Festlegen eines **Ausgangswerts (Baseline)** und eines **Zielwerts** wird der Projekterfolg nach einem Release überprüfbar — und eine Grundlage für Hypothesen der Form *»Wenn Feature X ausgeliefert wird, steigt Metrik Y um Z%«* geschaffen.

---

### 6. Bitte erwähnen Sie 3 oder 4 Heuristiken von Nielsen? Erläutern Sie diese jeweils an einem Beispiel.

---

### 7. Nennen Sie 2 oder 3 der 5 Dimensionen des Interaction Design.

---

### 8. Was ist ein Experiment?

Ein **Experiment** ist eine empirische Methode zur zielgerichteten Überprüfung von Hypothesen und Annahmen. Im Collaborative UX Design wird das Experiment als Instrument beschrieben, um die Gültigkeit von Konzeptannahmen festzustellen, bevor in die vollständige Umsetzung investiert wird *(Quelle: 0_einleitung.md)*:

> *"Wir formulieren explizite Hypothesen und hinterfragen ihre Gültigkeit durch Nutzerforschung oder Experimente."*

**Typen von Experimenten im UX-Kontext** *(Quelle: 6_prototyping.md)*:

| Experiment | Beschreibung |
|-----------|-------------|
| **Fake-Door-Experiment** | Eine noch nicht existierende Funktion wird angekündigt. Das Interesse der Nutzenden wird gemessen (z.B. Klicks auf einen Button), nicht die tatsächliche Nützlichkeit. |
| **Concierge-Experiment** | Eine Dienstleistung wird manuell und individuell erbracht, anstatt sie zu automatisieren. Validiert, ob das Angebot tatsächlich genutzt wird. |
| **Wizard-of-Oz** | Ein Mensch simuliert im Hintergrund das System. Testpersonen glauben, ein echtes System zu bedienen — tatsächlich führt ein Mensch die Aktionen aus. |
| **A/B-Test** | Zwei Varianten eines Interface werden systematisch verglichen. Eignet sich für Plattformen mit vielen Usern. |
| **Vergleichender Usability-Test** | Zwei Prototypen werden mit denselben Testpersonen verglichen; Prototypen als unabhängige Variablen, Bearbeitungszeit/Zufriedenheit als abhängige Variablen. |

**Kernmerkmal:** Vor dem Experiment werden Erfolgskriterien definiert — die sogenannten *"Erfolgreich wenn"*-Bedingungen aus dem Validierungsplan. Nur so kann das Ergebnis intersubjektiv bewertet werden.

---

### 9. Bitte beschreiben Sie, wie wissenschaftlich geprüft werden kann, ob ein Interface a) besser als ein Interface b) zur Durchführung einer Task ist. Welche Überlegungen sind hier jeweils anzustellen? Verwenden Sie bei Ihren Erläuterungen die Begriffe abhängige und unabhängige Variable.

Die Methode, die sich dafür eignet, ist der **Vergleichende Usability-Test** *(Quelle: 6_prototyping.md)*:

> *"In einem vergleichenden Usability-Test werden für zwei unterschiedliche Prototypen die gleichen Aufgaben zur Bearbeitung vorgegeben. Nutzende werden gebeten, die gestellten Aufgaben mit beiden Prototypen zu lösen. Es wird beobachtet: Schwierigkeiten, Bearbeitungszeit, subjektive Beurteilung. Für aussagekräftige Ergebnisse bietet sich der Einsatz inferenzstatistischer Verfahren in experimentellen Versuchsplänen an, in denen die Prototypen als unabhängige Variablen und die Effizienz der Bearbeitung oder die subjektive Zufriedenstellung als abhängige Variablen konzipiert sind."*

**Konzeptionelle Überlegungen:**

| Begriff | Erläuterung im Kontext |
|--------|----------------------|
| **Unabhängige Variable** | Die zwei Interface-Varianten (Interface A vs. Interface B) — das ist das, was systematisch variiert wird |
| **Abhängige Variable** | Das Messergebnis — z.B. Bearbeitungszeit, Fehleranzahl, subjektive Zufriedenheit (z.B. gemessen mit SUS) |
| **Kontrolle** | Alle anderen Bedingungen (Aufgaben, Kontext, Zielgruppe, Moderator) werden konstant gehalten |
| **Stichprobe** | Repräsentative Auswahl aus der tatsächlichen Zielgruppe des Systems |

**Vorgehen im Überblick:**
1. Gleiche Testaufgaben für beide Interfaces definieren
2. Testpersonen bearbeiten Aufgaben mit Interface A und Interface B
3. Bearbeitungszeit, Fehler und Zufriedenheit werden protokolliert
4. Inferenzstatistische Auswertung: Ist der gemessene Unterschied statistisch signifikant oder zufällig?

**Wichtig:** Die Reihenfolge der Interfaces sollte variiert werden (Counterbalancing), um Lerneffekte als störende Variable auszuschließen.

---

### 10. Bitte nennen Sie Beispiele für Gestaltgesetze.

---

### 11. Erklären Sie was Gestaltgesetze sind und zeigen Sie anhand ausgewählter Beispiele was mit Gestaltgesetzen gemacht werden kann.

---

### 12. Was ist eine Metrik? Wozu ist eine Metrik gut?

**Was ist eine Metrik?**

Eine **Metrik** ist ein messbarer Indikator, der eine bestimmte Eigenschaft eines Produkts oder Systems in einer quantitativen Zahl ausdrückt. Eine Metrik besteht aus:

- **UX-Metrik**: Der zu messende Aspekt (z.B. Effizienz, Effektivität, subjektive Beurteilung)
- **Messmethode**: Wie die Metrik erhoben wird (z.B. Zeitmessung, SUS-Befragung, Loganalyse)
- **Ausgangswert**: Der aktuelle Zustand des Systems
- **Zielwert**: Der angestrebte Wert nach einem Release

**Wozu ist eine Metrik gut?**

1. **Erfolgskontrolle**: Metriken ermöglichen eine zuverlässige Aussage darüber, ob ein Release seine Ziele erreicht hat. Ohne Metriken ist unklar, ob sich ein Produkt tatsächlich verbessert hat.

2. **Hypothesenprüfung**: Aus der Priorisierungsmatrix werden Hypothesen abgeleitet (z.B. "Wenn Leistungen auf temporäre Projekte gebucht werden können, erhöht sich die Anzahl fakturierbarer Stunden um 10%"). Metriken ermöglichen die Prüfung dieser Hypothesen.

3. **Vergleichbarkeit**: Durch einen vorher festgelegten Ausgangswert (Baseline) können die Wirkungen verschiedener Releases gemessen und verglichen werden.

4. **Kommunikation mit Stakeholdern**: Metriken machen den Erfolg eines Produkts für alle Beteiligten messbar und sichtbar.

5. **Benchmarking**: Metriken wie der SUS-Score ermöglichen den Vergleich mit Konkurrenzprodukten oder Branchendurchschnittswerten.

**Beispiel aus 4Service (Metrikenboard):**

| UX-Metrik | Messmethode | Ausgangswert | Zielwert |
|-----------|-------------|-------------|---------|
| Subjektive Beurteilung | SUS-Befragung | 62 Punkte | 70 Punkte (MVP) |
| Effizienz | Zeitmessung mit Log | 14 Min | 13 Min (MVP) |
| Effektivität | Anteil verrechenbarer Stunden | 70% | 71% (MVP) |

---

### 13. Was versteht man unter Contextual Inquiry? Ordnen Sie diese Methode einer Phase im menschzentrierten Entwicklungsmodell an.

Contextual Inquiry ist eine etablierte Beobachtungsform, die auf einem Meister-Schüler-Modell basiert. Eine Beobachterin begleitet eine beobachtete Person in einem offen kommunizierten Rollenspiel: Sie verhält sich so, als habe sie die Aufgabe, die relevanten Arbeitsabläufe der beobachteten Person zu erlernen (Schülerrolle). Die beobachtete Person fühlt sich dadurch in einer sicheren Position — die begleitende Beobachtung wird weniger als Kontrolle wahrgenommen.

**Zentrale Merkmale:**
- Kombination aus Beobachtung und Befragung im realen Nutzungskontext
- Meister-Schüler-Rollenspiel: Beobachterin lernt, beobachtete Person lehrt
- Natürliche Fragen während der Arbeitsdurchführung
- Fokus auf tatsächliches Verhalten, nicht auf berichtetes Verhalten
- Erfassung von Umfeld, Arbeitsabläufen, Zielen, Störungen, Werkzeugen und beteiligten Personen

**Einordnung:** Contextual Inquiry gehört zur *Verstehen*-Phase (Research-Workshop) des menschzentrierten Entwicklungsmodells. Sie dient der empirischen Erkundung des tatsächlichen Nutzungszusammenhangs und der Validierung von Annahmen aus dem Scoping-Workshop.

---

### 14. Was benötigt man zur Berücksichtigung von Farbfehlsichtigkeiten?

---

### 15. Was ist Subitizing? Wie kann das bei Interface Design sinnvoll genutzt werden?

---

### 16. Was ist der Unterschied zwischen Gestaltungsgesetze und Gestaltgesetze?

---

### 17. Erläutern Sie das Fitts'sche Gesetz:

**Definition aus den Skripten** *(Quelle: 6_prototyping_vokabular.md)*:

> *"Fitts'sches Gesetz: Gesetz zur präzisen Berechnung von Selektionszeiten in Abhängigkeit von Zielgröße und Distanz."*

Das Fitts'sche Gesetz (Fitts 1954) ermöglicht eine **präzisere Berechnung der Zeit, die ein Nutzer benötigt, um ein Interface-Element mit der Maus oder dem Finger zu treffen**, als die Pauschalzeit des GOMS-Keystroke-Modells (1,1 Sekunden für eine Selektion).

**Kontext im GOMS-Modell** *(Quelle: 6_prototyping.md)*:

Das GOMS-Modell verwendet für die Aktion "Selektion" einen Durchschnittswert von 1,1 Sekunden. Das Fitts'sche Gesetz erlaubt eine verfeinerte Berechnung, bei der **zwei Faktoren** die Selektionszeit bestimmen:

- **Zielgröße** (je größer das Ziel, desto schneller erreichbar)
- **Distanz zum Ziel** (je weiter weg, desto länger dauert die Bewegung)

**Konsequenz für Interface-Design:** Interaktive Elemente sollten groß genug und nah an den häufig genutzten Ausgangsposition der Maus platziert werden — z.B. an Bildschirmrändern oder -ecken (unendlich großes Ziel nach Fitts), was die Trefferzeit minimiert.

*Hinweis: Die genaue Formel und weitere Ausführungen zum Fitts'schen Gesetz sind in den vorliegenden Kursunterlagen nicht enthalten. Die obige Erläuterung basiert ausschließlich auf den in den Skripten verfügbaren Informationen.*

---

### 18. Kleine Gestaltungsaufgabe (anhand eines Beispiels) mit Begründung

---

### 19. Was ist der Unterschied zwischen geschlossenen und offenen Fragen?

**Offene Fragen** können nicht einfach mit Ja oder Nein beantwortet werden. Sie laden befragte Personen ein, über neue und unerwartete Aspekte zu berichten, und eröffnen Möglichkeiten für Anschlussfragen.

- *Beispiel:* "Wie verläuft die Erfassung der Leistungen? An welchen Stellen treten Schwierigkeiten auf?"

**Geschlossene Fragen** lassen sich knapp mit Ja oder Nein beantworten. Sie können sinnvoll sein, wenn sie den weiteren Verlauf des Interviews ebnen.

- *Beispiel:* "Erfassen Sie auch Spesen?" — ebnet den Weg zu tiefergehenden Fragen zur Spesenerfassung.

**Empfehlung:** Offene Fragen bevorzugen, da sie reichhaltigere Ergebnisse liefern. Geschlossene Fragen nur gezielt als Überleitung einsetzen.

---

### 20. Was ist der Unterschied zwischen Persona und Proto-Persona. Wie kommt man von Proto-Persona zu einer Persona?

**Proto-Persona:** Eine durch das Projektteam erstellte, hypothetische Beschreibung einer Nutzergruppe — basierend auf Annahmen, ohne empirische Grundlage. Im Scoping-Workshop wurden z.B. acht Proto-Personas angenommen (z.B. Simone Extern, Marie Beraterin, Monika Mitarbeiterin-Großprojekt).

**Persona:** Eine durch empirische Daten validierte, evidenzgestützte Beschreibung einer Nutzergruppe. Sie ersetzt die Annahmen der Proto-Persona durch Erkenntnisse aus Nutzerforschung.

**Der Weg von Proto-Persona zur Persona (4 Schritte nach Salazar):**

1. **Durchführung einer empirischen Studie:** Bedeutsame Merkmale der Nutzer tatsächlich kennenlernen — z.B. durch Contextual Inquiry, Tagebuchstudien oder Fragebögen.
2. **Identifikation von Merkmalen:** Herausfinden, welche Merkmale für das Design entscheidend sind (z.B. Häufigkeit der Erfassung, Anzahl Projekte, Abstimmungsbedarf).
3. **Analyse von Merkmalsausprägungen:** Ausprägungen untersuchen und in Kategorien zusammenfassen (Codierung). Iterativer Prozess der Kategorienbildung.
4. **Identifikation übergreifender Patterns:** Muster über verschiedene Merkmalskategorien hinweg suchen — Kombinationen von Ausprägungen identifizieren, die auf unterschiedliche Persona-Typen hinweisen.

**Konkretes Ergebnis im Fallbeispiel:** Von 8 Proto-Personas wurden durch empirische Validierung 6 Personas abgeleitet. Drei Proto-Personas wurden zu einer einzigen Persona (Marie Beraterin) konsolidiert, da die Daten keine Unterscheidung stützten.

---

### 21. Was sind wesentliche Attribute einer Persona?

Anhand der validierten Persona »Marie Beraterin« lassen sich vier zentrale Attributkategorien identifizieren:

**1. Persönliche Attribute:**
- Beruf/Rolle (z.B. Betriebswirtin, 32 Jahre alt)
- Erfahrung mit Technologie (z.B. viel Erfahrung in Nutzung von Apps)
- Arbeitskontext (z.B. oft bei Kunden)

**2. Aufgaben:**
- Konkrete Tätigkeiten, die die Persona mit dem System ausführt (z.B. Reisezeiten erfassen, Leistungen erfassen, Kontrolle und Freigabe, Abwesenheiten dokumentieren)

**3. Probleme und Herausforderungen:**
- Schwierigkeiten im aktuellen Prozess (z.B. hoher Abstimmungsaufwand, fehlende Projekte, keine Wiederverwendung bestehender Daten)

**4. Bedürfnisse und Ziele:**
- Was die Persona erreichen möchte (z.B. konkrete Erfassung, effiziente Erfassung, gute Übersicht über Überstunden und Urlaubsanspruch)

**Wichtig:** Nur designrelevante Attribute werden aufgenommen — rein schmückende demografische Details (Haarfarbe, Geburtsort) sind nicht relevant, da sie keinen Einfluss auf Designentscheidungen haben.

---

### 22. Warum erstellt man Personas?

- Um die **Wirklichkeit zu reduzieren und zu modellieren**: Personas sind Modelle, die von unnötigen Details abstrahieren und zielorientiert beschreiben, was für die Ableitung von Nutzungsanforderungen von Bedeutung ist.
- Um **Designentscheidungen** zu fundieren: Die den Personas zugeschriebenen Eigenschaften werden herangezogen, um zu prüfen, ob Lösungen geeignet sind, den Bedürfnissen einer Persona zu entsprechen.
- Um **Komplexität zu reduzieren**: Statt eine Vielzahl individueller Nutzer zu betrachten, bündeln Personas die wesentlichen Merkmale in handhabbare Archetypen.
- Um **Empathie** für Nutzende zu entwickeln: Durch die detaillierte Beschreibung von Aufgaben, Problemen und Zielen können Teammitglieder die Perspektive der Nutzenden einnehmen.
- Um **Annahmen explizit und überprüfbar** zu machen: Proto-Personas machen Vermutungen sichtbar, die dann durch Nutzerforschung validiert oder revidiert werden können.

---

### 23. Was ist ein Szenario?

Ein Szenario beschreibt eine handelnde Person, ihr Ziel und den Kontext, in dem dieses Ziel erreicht werden soll.

**Zentrale Merkmale:**
- Fokussiert in **narrativer Form** auf das Erleben von Nutzerinnen und Nutzern
- Beschreibt eine konkrete, situative Nutzungssituation
- Abstrahiert von gestalterischen Details und implementierungstechnischen Merkmalen
- Macht das zukünftige Produkt in seinem Nutzungskontext erlebbar

**Arten von Szenarien:**
- **Happy Case (Soll-Szenario):** Beschreibt den typischen, reibungslosen Ablauf — der Normalfall, mit dem die Konzeptarbeit beginnt
- **Edge Case:** Beschreibt einen Sonderfall oder Ausnahmefall (wird erst nach dem Happy Case behandelt)

**Zweck von Szenarien im Konzept-Workshop:**
- Aus dem Szenario können die notwendigen **Funktionalitäten** der zukünftigen Lösung abgeleitet werden
- Sie dienen als Grundlage für die Erstellung einer **User Story Map**
- Szenarien fungieren als **validierende Komponente** bei der Überprüfung von Frameworks und Keyscreens

**Beispiel (aus dem Fallbeispiel 4Service):**
»Es ist früher Abend. Marie sitzt an ihrem Schreibtisch, sie hat den ganzen Tag im Büro gearbeitet. Sie meldet sich bei 4Service an und kann ohne Umwege ihre Leistungen erfassen. Marie überprüft, wann sie ihre Leistungen zuletzt erfasst hat...«

---

### 24. Was ist eine User Journey?

Eine User Journey (Journey Map) dokumentiert den beobachteten Ablauf zur Erreichung eines Ziels einer Persona. Im Synthese-Workshop wird die im Scoping formulierte Proto-Journey anhand empirischer Beobachtungen validiert und zur **validierten User Journey** weiterentwickelt.

**Aufbau einer Journey Map (am Beispiel der Leistungserfassung):**

| Zeile | Beschreibung |
|---|---|
| **Persona** | Name der zugeordneten Persona (z.B. Marie Beraterin) |
| **Hauptschritte** | Übergeordnete Phasen (z.B. Anmelden → Leistungen erfassen) |
| **Schritte** | Detaillierte Einzelschritte innerhalb der Hauptschritte |
| **Findings** | Beobachtete Barrieren, positive Aspekte und offene Fragen (auf Karten) |
| **Mengengerüste** | Häufigkeiten von Tätigkeiten und Anzahl erfasster Daten |
| **Insight Statements** | Für das Team neue und bedeutsame Einsichten aus der Forschung |
| **Opportunity Areas** | Identifizierte Chancen zur Produktoptimierung |

**Zweck der Proto-Journey:** Die Prozessperspektive hilft, Annahmen zu vervollständigen und die Aufmerksamkeit in der Nutzerforschung auf zu beobachtende Ereignisse, ihre Sequenz, Häufigkeit und Variation zu richten.

---

### 25. Was ist die Peak-End Rule?

---

### 26. Wie kann man Peak-End Rule in Bezug auf User Journey anwenden?

---

### 27. Was ist der Unterschied zwischen Erfordernissen und Nutzungsanforderungen?

---

### 28. Was ist der Unterschied zwischen einem Brainstorming und einem 6-3-5? Warum ist 6-3-5 nicht einfach nur ein Brainstorming? Was sind entscheidende Vorteile von 6-3-5?

**Klassisches Brainstorming:**
Beim klassischen Brainstorming werden Ideen gemeinsam in einer Gruppe gesammelt. Forschungsergebnisse zeigen jedoch, dass Brainstormings in Gruppen oft nicht effizient sind:
- Die Qualität der Ideen ist geringer als bei Einzelarbeit
- Je größer die Gruppe, desto weniger produktiv
- Soziale Hemmungen (Höflichkeit, Dominanz einzelner Personen) bremsen kreative Beiträge

**Die Methode 6-3-5:**
6-3-5 ist eine strukturierte Kreativmethode:
- **6** Teilnehmende entwickeln zunächst jeweils **allein 3** Lösungsideen zu einer HMW-Frage
- Die Ideen werden als Überschriften in drei Spalten auf ein Blatt Papier geschrieben
- Das Blatt wird im Uhrzeigersinn weitergegeben
- Jede Person ergänzt die Ideen der anderen durch Kommentare (typisch: 4 Minuten Timebox)
- Dieser Prozess wird **5** Mal wiederholt

**Warum 6-3-5 mehr als Brainstorming ist:**

| Aspekt | Brainstorming | 6-3-5 |
|---|---|---|
| Arbeitsform | Rein gemeinsam | Wechsel Einzel-/Gruppenarbeit |
| Soziale Hemmung | Hoch (Kritik, Dominanz) | Gering (Einzelarbeit schützt) |
| Ideenqualität | Tendenziell niedriger | Höher durch Einzelarbeit |
| Kreuzbestäubung | Zufällig | Systematisch durch Weitergabe |
| Struktur | Offen | Klar strukturiert mit Timebox |

**Entscheidende Vorteile von 6-3-5:**
1. **Systematische Kreuzbestäubung:** Jede Idee wird von anderen aufgegriffen, weiterentwickelt und in neue Richtungen gelenkt
2. **Schutz vor Gruppendenken:** Durch die Einzelarbeit können Ideen ohne sozialen Druck entwickelt werden
3. **Quantität und Vielfalt:** Bei 6 Personen entstehen bis zu 108 Ideen-Kommentare (6 Blätter × 3 Spalten × 5 Kommentarrunden)
4. **Zeiteffizienz:** Klare Timebox verhindert endlose Diskussionen
5. **Gleiche Beteiligung:** Alle Personen tragen gleichmäßig bei — keine Dominanz einzelner Teilnehmender

---

### 29. Beispiele für Erfordernisse oder Signifier oder Feedback?

---

### 30. Was versteht man unter Mapping in Kontext im Interface Designs?

---

### 31. Was versteht man unter einem Interface-Raster? Wie setzt man das ein?

---

### 32. Das Alignieren von Labels zu den zugeordneten Feldern. Welche Möglichkeiten gibt es? Welche Möglichkeiten ist wann zu empfehlen?

---

### 33. Übersicht Grafik zum menschzentrierten Design: Welche Phasen kann man grundsätzlich auseinander halten? Was fehlt denn da noch?

**Collaborative UX Design** beschreibt ein menschzentriertes Vorgehensmodell mit acht aufeinander aufbauenden Workshops, die sich in drei übergeordnete Phasen gliedern lassen:

**Phase 1: Verstehen (Problemraum)**

Die ersten drei Workshops beschäftigen sich mit dem Verstehen des eigentlichen Problems:

- **Scoping:** Projektziele und Randbedingungen klären, Metriken definieren, Annahmen identifizieren
- **Research:** Annahmen durch Nutzerforschung empirisch prüfen
- **Synthese:** Forschungsergebnisse auswerten, Personas und Nutzungsanforderungen ableiten

**Phase 2: Erkunden (Lösungsraum)**

Die folgenden fünf Workshops konzentrieren sich auf die Lösungsfindung:

- **Ideation:** Lösungsideen generieren, Kreativmethoden einsetzen
- **Konzept:** Lösungskonzept skizzieren, Nutzungsszenarien entwickeln, User Journey und erste Wireframes erstellen
- **Prototyping:** Annahmen im Konzept identifizieren, Validierungsplan erstellen, Prototyp ausarbeiten
- **Validierung:** Prototypen empirisch validieren, Konzeptannahmen überprüfen, Erkenntnisse auswerten
- **Roadmap:** Produktfunktionalitäten priorisieren, MVP und Folgereleases planen

**Phase 3: Delivery (Umsetzung)**

Nach der Roadmap folgt die eigentliche technische Umsetzung in agilen Sprints (Dual/Triple Track Agile).

> **Was fehlt:** Die **Delivery-Phase** wird in vereinfachten Darstellungen des menschzentrierten Designprozesses häufig weggelassen oder nur als "Ausblick" behandelt. Außerdem fehlen in typischen Grafiken oft die **Iterationsschleifen**: Die Phasen sind nicht streng linear, sondern erlauben Rückschritte (z.B. nach der Validierung zurück zur Ideation oder zum Konzept).

**Kurzübersicht:**

| Phase | Workshops | Ziel |
|-------|-----------|------|
| **Verstehen** | Scoping, Research, Synthese | Problemraum verstehen |
| **Erkunden** | Ideation, Konzept, Prototyping, Validierung, Roadmap | Lösungsraum erkunden und validieren |
| **Delivery** | Sprints (agile Umsetzung) | Produkt inkrementell ausliefern |

---

### 34. Funktionen eines Prototypen. Warum macht man Prototypen? Was sind typische Funktionen eines Prototypen?

**Warum macht man Prototypen?**

Prototypen sind zentrale Artefakte in menschzentrierten Gestaltungsmodellen. Ein zentrales Ziel ist die **Validierung erarbeiteter Konzepte** während der Produkt- oder Serviceentwicklung. Konkret:

- **Annahmen überprüfen**: Hinter jedem Konzept stecken explizite und implizite Annahmen. Prototypen erlauben es, die Gültigkeit dieser Annahmen zu überprüfen, bevor in die vollständige Umsetzung investiert wird.
- **Gestaltungslösungen erlebbar machen**: Durch Prototypen veranschaulichen wir unsere Designentscheidungen und schaffen Möglichkeiten, diese zu evaluieren.
- **Frühzeitiges Feedback einholen**: Besonders Low-Fidelity-Prototypen signalisieren Teilnehmenden, dass das Konzept noch nicht in Stein gemeißelt ist — dies fördert offenes, reichhaltiges Feedback.
- **Kommunikation im Team**: Prototypen machen Konzepte für alle Beteiligten konkret und diskutierbar.

**Typische Funktionen eines Prototypen:**

1. **Validierung des Nutzens** – Wird das Produkt tatsächlich gebraucht und gewollt? (Konzept-Walkthrough, Fake-Door-Experiment)
2. **Validierung der Anforderungen** – Sind alle notwendigen Funktionalitäten vorhanden? (Anforderungs-Walkthrough, Concierge-Experiment)
3. **Optimierung des Designs** – Wo gibt es Usability-Probleme? (Usability-Walkthrough, Usability-Test im Labor)
4. **Auswahl zwischen Varianten** – Welche Designvariante ist besser? (A/B-Test, Vergleichender Usability-Test)
5. **Benchmarking** – Wie gut ist die Lösung im Vergleich? (Fragebogen)
6. **Validierung der Machbarkeit** – Ist die technische Umsetzung machbar? (Vertical Slice, Funktionaler Prototyp)

**Wichtige Einschränkung:** Je mehr Aufwand in einen Prototypen investiert wird, desto schwerer fällt es, das Ergebnis zu verwerfen. Daher sollte der Detaillierungsgrad eines Prototypen immer dem Validierungsziel angemessen sein.

---

### 35. UX-Evaluationsmethoden: qualitative und quantitative Perspektive.

**Qualitative Methoden:**

Qualitative Methoden liefern Erkenntnisse über das *Warum* — also über Ursachen, Motive und Meinungen der Nutzenden. Sie erlauben tiefe Einblicke, sind aber nicht auf Repräsentativität ausgelegt.

Beispiele:
- **Usability-Walkthrough / Usability-Test im Labor:** Testpersonen bearbeiten Aufgaben an einem Prototyp; Moderator beobachtet und notiert Auffälligkeiten. Findings werden qualitativ ausgewertet (Beobachtetes Finding, Vermutete Ursache, Severity).
- **Think-Aloud-Protokoll (Lautes Denken):** Testpersonen verbalisieren ihre Gedanken während der Aufgabenbearbeitung.
- **Konzept-Walkthrough:** Präsentation eines Szenarios; erste Eindrücke und Kontraindikatoren werden gesammelt.

**Quantitative Methoden:**

Quantitative Methoden liefern messbare Daten, die mit statistischen Methoden ausgewertet werden können. Sie eignen sich für Vergleiche und Benchmarks.

Beispiele:
- **A/B-Test:** Zwei Varianten eines Interface werden unter realen Bedingungen mit vielen Nutzenden verglichen (z.B. Klickrate, Bearbeitungszeit).
- **Fragebogen (Benchmarking):** Standardisierte Skalen (z.B. SUS) liefern quantifizierbare Zufriedenheitswerte.
- **GOMS-Analyse:** Analytische Methode zur Berechnung von Aufgabenbearbeitungszeiten.
- **Datenanalyse:** Analyse existierender Nutzungsdaten.

| | Qualitativ | Quantitativ |
|---|---|---|
| **Beobachtung** | Contextual Inquiry, Tagebuch | Web Analytics, A/B-Test |
| **Interview** | Experteninterview | Telefoninterview |
| **Fragebogen** | Offener Fragebogen | Geschlossener Fragebogen, SUS |

---

### 36. Welche Methoden sind eher geeignet, etwas über Verhalten auszusagen?

Methoden, die **beobachtbares Verhalten** erfassen, sind besonders geeignet, wenn man verstehen will, *wie* Nutzende mit einem System interagieren — unabhängig davon, was sie darüber sagen.

Geeignete Methoden:
- **Usability-Test / Walkthrough:** Testpersonen bearbeiten realistische Aufgaben. Moderator beobachtet direkt, wie die Person vorgeht, wo sie stockt, welche Fehler auftreten. → Verhaltensbeobachtung
- **Think-Aloud-Protokoll:** Zusätzlich zur Beobachtung werden die Gedanken verbalisiert → gibt Aufschluss über mentale Prozesse *während* des Verhaltens
- **Videoanalyse:** Aufgezeichnete Sessions werden nachträglich ausgewertet
- **GOMS-Analyse:** Analytische Simulation von Interaktionsverhalten
- **A/B-Test / Datenanalyse:** Misst tatsächliches Verhalten vieler Nutzender unter realen Bedingungen (Klicks, Abbruchraten, Bearbeitungszeiten)

**Warum nicht Fragebögen oder Interviews?** Diese erfassen *berichtetes* Verhalten — also was Nutzende glauben oder sagen zu tun. Das weicht oft vom tatsächlichen Verhalten ab.

---

### 37. Welche Methoden sind eher geeignet, etwas über Meinungen und Präferenzen auszusagen?

Methoden, die **subjektive Wahrnehmungen** erfassen, sind geeignet, wenn man verstehen will, was Nutzende *denken*, *fühlen* oder *bevorzugen*.

Geeignete Methoden:
- **Fragebogen:** Standardisierte Fragen mit Skalen (z.B. Likert-Skala) erfassen Meinungen und Präferenzen quantifizierbar. Benchmarks und Vergleiche möglich.
- **Interview / Fokusgruppe:** Offene Gespräche erlauben vertiefte Auseinandersetzung mit Meinungen und Erfahrungen.
- **Konzept-Walkthrough:** Erste Eindrücke, Zustimmung oder Ablehnung werden direkt erfragt.
- **Nachbefragung nach Usability-Test:** Anschlussfragen nach den Testaufgaben geben Aufschluss über Zufriedenheit und Präferenzen.

**Abgrenzung:** Während Beobachtungsmethoden zeigen, *was* Nutzende tun, zeigen Befragungsmethoden, *warum* sie etwas tun oder wie sie es bewerten. Beide Perspektiven ergänzen sich.

---

### 38. Was sind typische Kriterien für gute Tasks?

Für die Formulierung von Testszenarien in einem Walkthrough oder Usability-Test gelten folgende Kriterien:

- **Relevanter Kontext**: Szenarien sollen in einen anschaulichen, realistischen Kontext eingebettet sein.
- **Kompaktheit**: Aufgaben sollen kompakt formuliert sein; lange Sätze sind zu vermeiden.
- **Warm-up**: Die erste Testaufgabe soll einfacher gehalten sein, damit sich Testpersonen schnell in die Situation eindenken können.
- **Eindeutigkeit**: In jedem Testszenario soll ein konkretes, spezifisches Ziel formuliert sein. Es muss eindeutig sein, ob eine Testperson das Ziel erreicht hat.
- **Datenverfügbarkeit**: Sind zur Bearbeitung eines Ziels bestimmte Daten notwendig, sollen diese in der Aufgabenbeschreibung bereitgestellt werden.
- **Unabhängigkeit**: Bei Aufgaben, die von mehreren Nutzenden abhängig sind, müssen diese Aspekte unabhängig voneinander präsentiert werden.
- **Keine Fachbegriffe**: In Testaufgaben sollen keine Begriffe aus dem System vorkommen, damit Teilnehmende keine Lösungshinweise erhalten.
- **Markierung**: Werden Testaufgaben ausgedruckt, soll klar erkennbar sein, an welcher Aufgabe sich der User befindet.

---

### 39. Bitte definieren Sie eine Beispielaufgabe für ein Testing von X.

**Beispiel aus dem 4Service-Fallbeispiel (Testing der Leistungserfassung):**

*Aufgabe (Warm-up):*
> Es ist 17 Uhr und Sie möchten Ihren Tag abschließen. Bevor Sie sich auf den Nachhauseweg machen, möchten Sie Ihre Leistungen erfassen. Sie erinnern sich, dass Sie um 8:00 h bei Ihrem Kunden eingetroffen sind und dann zwei Stunden lang am Konzept für das Projekt "Neues Branding" gearbeitet haben. Bitte erfassen Sie diese Leistung mit unserem Tool.

**Warum ist diese Aufgabe gut formuliert?**
- Enthält anschauliche Kontextbeschreibung (17 Uhr, Nachhauseweg)
- Erklärt die Motivation des Users (Tag abschließen)
- Liefert alle notwendigen Daten (Ankunftszeit 8:00, Projekt "Neues Branding", 2 Stunden)
- Endet mit einer klaren Aufforderung ("Bitte erfassen Sie…")
- Kein Fachbegriff aus dem System wird vorweggenommen

---

### 40. Was ist die Rolle eines Styleguides?

---

### 41. Was hat Collaborative UX-Design mit Unterscheidung zwischen Problemraum und Lösungsraum zu tun?

**Was ist Collaborative UX Design?**

**Collaborative UX Design** (auch: Collaborative UX Design 2.0) ist das orchestrierende Vorgehensmodell, das beschreibt, wie ein interdisziplinäres Team in aufeinanderfolgenden Workshops von der Problemstellung über die Lösungsentwicklung bis zur Umsetzung zusammenarbeitet.

**Was ist der Unterschied zwischen Problemraum und Lösungsraum?**

| | Problemraum | Lösungsraum |
|--|-------------|-------------|
| **Frage** | Was ist das Problem? Wer hat es? Warum? | Wie kann das Problem gelöst werden? |
| **Ziel** | Verstehen der Nutzenden, ihres Kontexts und ihrer Bedürfnisse | Entwicklung, Ausarbeitung und Validierung von Lösungskonzepten |
| **Typische Fehler** | Problemraum überspringen; Lösung vor Analyse | Lösungsraum ohne validierten Problemraum betreten |

**Wie ordnet sich Collaborative UX Design ein?**

**Problemraum (Workshops 1–3):**
- **Workshop 1: Scoping** — Problem Statement und Projektrahmen formulieren
- **Workshop 2: Research** — Nutzungskontext verstehen, Erkenntnisse sammeln
- **Workshop 3: Synthese** — Erkenntnisse verdichten, Persona, User Journey, Nutzungsanforderungen ableiten

**Lösungsraum (Workshops 4–8):**
- **Workshop 4: Ideation** — Lösungsideen entwickeln
- **Workshop 5: Konzept** — Lösungskonzept ausarbeiten
- **Workshop 6: Prototyping** — Prototypen erstellen, Annahmen sichtbar machen
- **Workshop 7: Validierung** — Konzeptannahmen empirisch prüfen
- **Workshop 8: Roadmap** — Priorisieren, MVP und Folgereleases planen, Metriken definieren

**Warum ist diese Unterscheidung wichtig?**

Ein häufiger Fehler im Designprozess ist das vorzeitige Betreten des Lösungsraums — das Team beginnt mit der Gestaltung von Lösungen, bevor das Problem wirklich verstanden wurde. Die Synthese-Phase bildet dabei explizit die Brücke: Die gewonnenen Erkenntnisse aus dem Problemraum werden in Nutzungsanforderungen überführt, die den Lösungsraum strukturieren.

---

### 42. Was ist ein Minimum Viable Product?

Ein **Minimum Viable Product (MVP)** ist das erste Release eines Produkts, das nur die essenziellen Merkmale enthält, die eine spürbare Verbesserung gegenüber der bisherigen Lösung bieten.

**Kerngedanke:** Das MVP ist der erste Schritt in einer Continuous-Delivery-Strategie. Es wird bewusst minimal gehalten — nicht weil Qualität unwichtig ist, sondern um:

1. **Risiko zu minimieren**: Statt in vollem Umfang zu entwickeln, wird zuerst das Nötigste ausgeliefert. Wenn ein Feature am Markt nicht ankommt, kann früh reagiert werden.
2. **Früh Feedback zu erhalten**: Mit jedem Release sammelt das Team reales Nutzerfeedback und kann die Weiterentwicklung datenbasiert steuern.
3. **Eine Baseline zu schaffen**: Das MVP stellt den Ausgangswert für Metriken dar, anhand derer der Erfolg nachfolgender Releases gemessen wird.

**Was gehört ins MVP?**

Beim MVP werden bewusst Einschränkungen vorgenommen:
- **Zielgruppe einschränken**: Nicht alle Nutzergruppen müssen von Anfang an bedient werden
- **Workflows einschränken**: Nur die häufigsten und wichtigsten Aufgaben (Pareto-Prinzip: 20% der Workflows decken 80% der Nutzung ab)
- **Funktionen einschränken**: Nur das Notwendigste — Features mit höchster Priorität laut Priorisierungsmatrix

**Abgrenzung zu Continuous Delivery:**

Beim traditionellen Entwicklungsmodell werden Produkte mit vielen Features auf einmal ausgeliefert (z.B. jährliche Releases). Continuous Delivery liefert fortlaufend kleine Releases aus. Das MVP ist das erste dieser kleinen Releases — es bietet bereits einen echten Mehrwert, obwohl die vollständige Produktvision noch nicht umgesetzt ist.

**Beispiel aus 4Service:** Das MVP enthielt nur die Grundfunktionalitäten der Leistungserfassung (Anmelden, Woche anzeigen, Leistung manuell erfassen). Erweiterte Funktionen wurden erst in späteren Releases hinzugefügt.

---

### 43. Miller'sches Gesetz (Arbeitsgerechtes Chunking). Was hat das für Interface-Design für Konsequenzen? Welche Konsequenzen folgen daraus?

---

### 44. Was versteht man unter dem Principle of Focal Point? Wie kann man das einsetzen?

---

### 45. Wovon hängt es ab, dass bestimmte Farben herausstechen?

---

### 46. Kognitive Architektur

---

### 47. Return on Investment

---

### 48. Usability / UX

---

### 49. Worauf bezieht sich Design? Was sind typische Ziele von Design?

---

### 50. Nennen Sie 3 Thesen der 10 Grundlagen von Dieter Rams

---

### 51. Zusammenhang User Experience und Usability

---

### 52. Definition von UX-Design?

**User Experience Design** wird im Collaborative UX Design wie folgt verstanden *(Quelle: 0_einleitung.md)*:

> *"Wir verstehen User Experience Design als Balance zwischen – mitunter konfligierenden – Anforderungen aus menschlichen Nutzungsbedürfnissen, technischen Restriktionen und wirtschaftlichen Rahmenbedingungen."*

UX Design ist demnach keine rein gestalterische Tätigkeit, sondern ein **Ausgleichsprozess** zwischen drei Interessensfeldern:

| Dimension | Beschreibung |
|----------|-------------|
| **Menschliche Nutzungsbedürfnisse** | Was brauchen und wollen die Nutzenden? (Usability, Nützlichkeit, Zufriedenheit) |
| **Technische Restriktionen** | Was ist technisch umsetzbar und wartbar? |
| **Wirtschaftliche Rahmenbedingungen** | Was ist wirtschaftlich sinnvoll? (Business-Ziele, Budgets, Markterfolg) |

**Kollaborativer Ansatz:** Designentscheidungen sind im Collaborative UX Design nicht das alleinige Ergebnis spezialisierter UX Designer, sondern das Resultat der interdisziplinären Zusammenarbeit eines Teams, das Produktmanagement, UX Design, Implementierung und Testen vereint *(Quelle: 0_einleitung.md)*.

**Grundpfeiler von Collaborative UX Design:** menschzentriert, kollaborativ, hypothesenbasiert und agil.

---

### 53. Verhältnis von Design zu Kunst?

---

### 54. Was sind mentale Modelle?

Ein **mentales Modell** ist die interne Vorstellung einer Person darüber, wie ein System funktioniert *(Quelle: 7_validierung_vokabular.md)*. Es repräsentiert die subjektiven Erwartungen, Analogien und Annahmen, die Nutzende über ein System mitbringen — unabhängig davon, ob diese korrekt sind.

**Woher kommen mentale Modelle?**
- Frühere Erfahrungen mit ähnlichen Systemen
- Analogien zu bekannten Konzepten (z.B. "ein Ordner auf dem Computer = ein physischer Ordner")
- Visuelle Hinweise und Bezeichnungen im Interface

**Relevanz für das Interface-Design:**
- Stimmt das **Systemmodell** (das, was das Interface zeigt) mit dem **mentalen Modell** der Nutzenden überein, ist die Nutzung intuitiv
- Stimmen sie **nicht** überein, entstehen Usability-Probleme (Fehler, Verwirrung, Frustration)

**Wie werden mentale Modelle sichtbar gemacht?**
Durch das **Think-Aloud-Protokoll (Lautes Denken)** bei Usability-Tests: Testpersonen verbalisieren, was sie wahrnehmen, denken und planen — dadurch werden ihre mentalen Modelle und Erwartungen direkt beobachtbar *(Quelle: 7_validierung_vokabular.md)*:

> *"Mentales Modell: Interne Vorstellung einer Person darüber, wie ein System funktioniert; wird durch lautes Denken sichtbar gemacht."*

---

### 55. Was ist Design-Studie / Design Thinking?

---

### 56. Was sind Severity Levels?

Severity Levels (Schweregrade) sind eine standardisierte Klassifikation der Schwere von Usability-Problemen, die bei der Auswertung von Usability-Tests oder Walkthroughs eingesetzt wird.

**Zweck:** Priorisierung der gefundenen Usability-Barrieren, damit das Team entscheiden kann, welche Probleme zuerst behoben werden müssen.

**Drei Schweregrade:**

| Grad | Bezeichnung | Bedeutung |
|------|-------------|-----------|
| **1** | Kosmetisches Problem | Muss nicht mit Priorität gelöst werden |
| **2** | Mittelschweres Problem | Sollte prioritär beseitigt werden |
| **3** | Schweres Usability-Problem | Muss dringend beseitigt werden, da es zum Abbruch der Aufgabenbearbeitung führen kann |

**Anwendung:** Für jedes negative Finding wird ein Severity-Level vergeben. Zusätzlich wird der **Lösungsaufwand** geschätzt. Für positive Findings werden keine Schweregrade oder Lösungsaufwände festgehalten.

Die Kombination aus Severity und Lösungsaufwand ermöglicht eine fundierte Priorisierung im Team-Workshop.

---

### 57. Was sind Styleguides?

---

### 58. Was sind Design-Systeme?

---

### 59. Was ist eine retrospective Evaluation?

Eine **retrospektive Evaluation** ist eine Bewertungsmethode, bei der Nutzende im Nachhinein — also nach einer oder mehreren Nutzungssituationen — über ihre Erfahrungen berichten. Das Gegenstück ist die **kontextuelle Erhebung in Echtzeit** (z.B. mit dem Tagebuch).

In den Skripten wird die retrospektive Erhebung explizit dem **Tagebuch** als Kontrastmethode gegenübergestellt *(Quelle: 2_research.md)*:

> *"Die Dokumentation einer Selbstbeobachtung im unmittelbaren kontextuellen Nutzungszusammenhang liefert im Vergleich zur Erhebung eines retrospektiven Fragebogens, mit dem ein summarischer Eindruck über verschiedene Nutzungssituationen hinweg zu erheben versucht wird, in der Regel zuverlässige und besonders detaillierte Daten."*

**Vergleich:**

| | Retrospektive Evaluation | Kontextuelle Evaluation |
|--|--------------------------|------------------------|
| **Zeitpunkt** | Nach der Nutzungssituation (nachträglich) | Während oder unmittelbar nach der Nutzung |
| **Inhalt** | Summarischer Eindruck über mehrere Situationen | Spezifische, aktuelle Erfahrung |
| **Risiko** | Gedächtnisfehler, Verallgemeinerungen | Reaktivität (Methode beeinflusst Verhalten) |
| **Beispiel** | SUS-Fragebogen nach dem Test, retrospektives Interview | Tagebuch, Contextual Inquiry |

**Anwendung in der Validierung:** Bei Usability-Tests wird oft eine **Nachbefragung** nach den Testaufgaben durchgeführt — das ist eine Form der retrospektiven Evaluation. Die Nutzenden kommentieren ihre Erfahrungen nach Abschluss der Aufgabe, nicht während der Durchführung.

---

### 60. Was macht die Methode des lauten Denkens aus?

Die Methode des **lauten Denkens** (Think-Aloud-Protokoll) ist eine Technik, die bei Usability-Tests und Walkthroughs eingesetzt wird.

**Kernprinzip:** Testpersonen werden gebeten, während der Bearbeitung der Aufgaben *kontinuierlich zu verbalisieren*, was sie gerade wahrnehmen, denken, planen und fühlen — also einen laufenden Kommentar ihres mentalen Prozesses abzugeben.

**Warum ist das nützlich?**
- Gibt Einblick in **mentale Modelle**: Was erwartet die Person? Welche Analogien nutzt sie?
- Zeigt **Verwirrung und Missverständnisse** in Echtzeit
- Macht **implizite Annahmen** der Nutzenden sichtbar, die bei stiller Bearbeitung verborgen blieben
- Liefert reichhaltiges qualitatives Datenmaterial neben den reinen Beobachtungen

**Durchführung:**
- Moderator erklärt das Vorgehen und zeigt optional ein Kurzvideo als Beispiel
- Aufforderung: "Bitte laut denken!"
- Moderator interveniert nur im "Notfall" und gibt keine Lösungshinweise
- Protokollführende Person notiert wichtige Äußerungen; Videoaufzeichnung sichert alle Details

**Abgrenzung zu reiner Beobachtung:** Reine Beobachtung zeigt *was* jemand tut; lautes Denken zeigt zusätzlich *warum* — es macht den kognitiven Prozess transparent.

---

### 61. Was ist eine Heuristische Analyse? Was unterscheidet die Heuristische Analyse zu Usability-Tests?

---

### 62. Welche Vorteile und Nachteile haben Usability-Tests?

**Vorteile von Usability-Tests** *(Quelle: 6_prototyping.md, 7_validierung.md)*:

1. **Kleine Stichproben reichen für erste Einsichten:** Bereits mit 3–4 Testpersonen konnten in der Vergangenheit sehr wichtige Erkenntnisse aus empirischen Usability-Tests gewonnen werden. Ein Usability-Walkthrough mit wenigen Personen liefert frühe Hinweise auf Usability-Barrieren.

2. **Frühzeitiges Feedback:** Da Prototypen gezielt für die Validierung erstellt werden, kann schon vor der vollständigen Implementierung erkannt werden, wo Konzeptannahmen falsch liegen.

3. **Einblick in mentale Modelle:** Durch das Think-Aloud-Protokoll werden die Erwartungen und Denkweisen der Nutzenden direkt sichtbar — nicht nur *was* sie tun, sondern *warum*.

4. **Reichhaltiges qualitatives Feedback bei Low-Fidelity:** Die "unfertige Anmutung" eines Papierprototyps signalisiert den Teilnehmenden, dass das Konzept noch veränderbar ist — dies fördert besonders offenes und reichhaltiges Feedback.

5. **Direkte Verhaltensbeobachtung:** Im Gegensatz zu Befragungen erfassen Usability-Tests tatsächliches Verhalten, nicht nur berichtetes Verhalten.

**Nachteile und Einschränkungen** *(Quelle: 6_prototyping.md, 7_validierung.md)*:

1. **Aufwand der Vorbereitung:** Testszenarien ausarbeiten, Prototypen vorbereiten, Testpersonen rekrutieren, Räume reservieren und Pilottests durchführen — der organisatorische Aufwand ist beträchtlich. Detaillierte Labortests sind deutlich aufwendiger als einfache Konzept-Walkthroughs.

2. **Risiko des sunk cost fallacy:** Je mehr Aufwand in die Ausarbeitung eines Prototyps investiert wird, desto schwerer fällt es, das Ergebnis zu verwerfen — auch wenn die Validierung negative Ergebnisse liefert.

3. **Kleine Stichproben sind nicht repräsentativ:** Usability-Tests mit 3–6 Personen liefern qualitative Einsichten, aber keine statistisch repräsentativen Aussagen über die gesamte Nutzergruppe.

4. **Labor-Setting kann Verhalten beeinflussen:** Die Testsituation (Beobachtung, Kamera, Moderator) kann zu Reaktivität führen — Nutzende verhalten sich möglicherweise anders als in ihrer natürlichen Arbeitsumgebung.

5. **Abhängigkeit vom Prototyp:** Die Aussagekraft des Tests ist an die Qualität und den Reifegrad des Prototyps gebunden. Ein zu einfacher Prototyp kann manche Usability-Probleme nicht sichtbar machen (z.B. Drag & Drop bei einem Klick-Prototyp).

---

### 63. Welche Vorteile haben Heuristische Evaluationen?

---
