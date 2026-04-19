# Workshop: Roadmap

Im vorangegangenen Validierungs-Workshop konnten zentrale Aspekte der entwickelten Vision in ihrer erwarteten Bedeutung gestützt werden. Ziel des nun folgenden Roadmap-Workshops ist es, die erkundeten Konzeptideen Realität werden zu lassen und in eine Releaseplanung zu gehen.

---

## Überblick

**Ziel:** Festlegung eines MVP (Minimum Viable Product) und möglicher Folgereleases, Definition von Metriken zur Validierung von Releases

**Teilnehmende:** Projektteam

**Hauptergebnis:** Roadmap, Metriken-Map

**Vor dem Workshop:** Vorliegen eines validierten Konzepts

**Ablauf:**
1. Priorisieren von Produktfeatures in einer Priorisierungsmatrix
2. Erstellung einer Roadmap
3. Definition einer Metriken-Map

**Nach dem Workshop:** Umsetzung (Kapitel Delivery)

---

## Theorie: Continuous Delivery und MVP

### Traditionelle Softwareentwicklung vs. Continuous Delivery

**Traditionell:** Wenige Releases pro Jahr (z.B. jährlich); große Bündel von Features werden auf einmal ausgeliefert.

**Continuous Delivery:** Fortlaufend neue Releases mit jeweils vergleichsweise kleinen Neuerungen. Features werden inkrementell ausgeliefert.

**Vorteile von Continuous Delivery:**
- Features können schneller an Markt gebracht werden
- Geringeres Risiko: kleine Bündel mit wenig Merkmalkombinationen sind bei einer geringen Akzeptanz leichter überarbeitbar
- Frühzeitiges Erkennen von Fehlern: kleinere Releases sind nach Attributen einfacher unterscheidbar
- Direktes Nutzerfeedback: Begleitung der Produktentwicklung über mehrere Releases

### MVP – Minimum Viable Product

Das **MVP (Minimum Viable Product)** ist das erste Release eines Produkts mit nur den essenziellen Merkmalen, die eine spürbare Verbesserung gegenüber der bestehenden Lösung bieten. Es ist der erste Schritt im Continuous Delivery.

**Zweck des MVP:**
- Stellt eine erste, bereits nutzbare Verbesserung bereit
- Bildet einen **Ausgangswert (Baseline)** für zukünftige Messungen
- Ermöglicht früh Feedback aus dem Markt
- Reduziert das Investitionsrisiko: erst wenn sich ein Feature bewährt hat, wird in Folgereleases weiterentwickelt

**Wichtige Einschränkungen beim MVP:**
- Einschränkung der unterstützten **Zielgruppe** (nicht alle Nutzergruppen müssen von Anfang an bedient werden)
- Einschränkung der unterstützten **Workflows** (Pareto-Prinzip: 80/20-Regel – die häufigsten 20% der Fälle abdecken)
- Einschränkung der unterstützten **Funktionen** (nur das Notwendigste)

---

## Priorisierungsmatrix

### Zweck

Die **Priorisierungsmatrix** ist ein Werkzeug zur systematischen Gegenüberstellung von Features der Produktvision und ihrer Bedeutung aus verschiedenen Perspektiven. Sie hilft dabei zu entscheiden, welche Features in welches Release kommen.

Abzuwägende Aspekte:
- Aspekte der User Experience (Nutzerziele)
- Wirtschaftliche Rahmenbedingungen (Businessziele)
- Technische Machbarkeit und Realisierungsaufwand

### Aufbau der Priorisierungsmatrix

**Spalten:** Features/Themen (aus der User Story Map)

**Zeilen:**
| Zeile | Bedeutung |
|-------|-----------|
| Gewichtung der Businessziele | Management bewertet, wie stark ein Feature die Businessziele unterstützt |
| Gewichtung der Nutzerziele | Team bewertet den erwarteten Einfluss der Funktionen auf das Nutzererlebnis |
| Businessziele (einzeln) | Mehr verrechenbare Stunden / Reduktion von Reklamationen / Effiziente Erfassung |
| Zwischensumme | Summe der kombinierten Einflüsse auf Business- und Nutzerziele |
| Aufwand | Schätzung des technischen Realisierungsaufwands durch das Entwicklungsteam |
| Gesamtpunkte | Zwischensumme ÷ Aufwand (Faustformel) |

**Punktesystem:** 3 Punkte = höchste Priorität, 1 Punkt = niedrigste Priorität

**Farben:**
- Grün: Gewichtungen (Management / Nutzerziele)
- Rot/Gelb: Einfluss eines Themas auf ein Businessziel
- Blau: Aufwand

### Berechnung der Priorisierungsmatrix

Für jede mit Punkten gefüllte Zelle (Einfluss auf ein Businessziel) wird das **Produkt** aus Zeilen- und Spaltengewichtung berechnet:

> **Zellenwert = Spaltengewichtung × Zeilengewichtung**

Beispiel (4Service):
- Temporäre Projekte × Mehr verrechenbare Stunden: **2 × 3 = 18**
- Effiziente Erfassung × Kürzlich verwendete Leistungen: **1 × 3 = 9**

Die **Zwischensumme** einer Spalte = Summe aller Produkte für dieses Feature.

Die **Gesamtpunkte** = Zwischensumme ÷ Aufwand

### Ergebnis der Priorisierungsmatrix (4Service, Abbildung 80)

| Feature | Gesamtpunkte |
|---------|-------------|
| Temporäre Projekte | 26 |
| Gruppenleistungen | 11 |
| Kürzlich verwendete Leistungen | 9 |
| Übernahme von Terminen | 2 |
| Projektbudget | 1 |

→ **Temporäre Projekte** haben die höchste Priorität.

---

## Roadmap

Aus der Priorisierungsmatrix leitet das Team eine konkrete **Roadmap** ab: Sie beschreibt, welche Releases in welcher Abfolge ausgeliefert werden.

### Releases im 4Service-Beispiel (Abbildung 83)

| Release | Name | Inhalt |
|---------|------|--------|
| **Release 1 (MVP)** | — | Anmelden, Aktuelle Woche anzeigen, Leistung manuell erfassen, Woche wechseln, Abschreiben einer Leistung beantragen, Leistungszeitpunkt und -dauer ändern, Leistung löschen, Leistungen freigeben |
| **Release 2** | Temporäre Leistung | Urlaubstage überprüfen, Temporäre Leistung erfassen, Überstunden überprüfen |
| **Release 3** | Gruppenleistungen | Gemeinsame Leistungen anzeigen, Leistungen von Teammitgliedern überprüfen/übernehmen/entfernen |
| **Release 4** | Kürzlich verwendete Leistungen | Kürzlich erfasste Leistung übernehmen, Termine anzeigen, Leistung aus Terminen übernehmen, Projektbudget überprüfen |

**Strategische Überlegung zum MVP:** Es wird zunächst eine Kalenderansicht als Grundlage lanciert — ohne erweiterte Funktionen. Dies gibt einen Ausgangswert (Baseline) für zukünftige Messungen und ermöglicht die Messung der Wirkung späterer Features.

---

## Metrikenboard

### Zweck

Das **Metrikenboard** ist ein Werkzeug zur Definition relevanter Metriken und ihrer Messmethoden für die Releases eines Produkts. Es ermöglicht eine zuverlässige Aussage zum Erfolg des Produkts und bildet die Grundlage für abgestimmte Studien zur Erfolgskontrolle.

### Komponenten eines Metrikenboards

| Komponente | Beschreibung |
|-----------|-------------|
| **UX-Metrik** | Geeigneter messbarer Indikator (z.B. Subjektive Beurteilung, Effizienz, Effektivität) |
| **Messmethode** | Methode zur quantitativen Erfassung der Metrik (z.B. SUS-Befragung, Zeitmessung mit Log) |
| **Persona** | Welche Persona wird zur Bestimmung der Metrik herangezogen? |
| **Szenario** | Welches Szenario wird zur Messung verwendet? |
| **Ausgangswert** | Quantitative Ausprägung der Metrik im aktuellen System |
| **Zielwert MVP** | Angestrebter Wert nach dem ersten Release |
| **Zielwert Release 2** | Angestrebter Wert nach dem zweiten Release |

### Metrikenboard 4Service (Abbildung 85)

| UX-Metrik | Messmethode | Ausgangswert | Zielwert MVP | Zielwert Release 2 |
|-----------|-------------|-------------|-------------|------------------|
| Subjektive Beurteilung | SUS-Befragung | 62 | 70 | 72 |
| Effizienz | Zeitmessung mit Log | 14 Min | 13 Min | 12 Min |
| Effektivität | Anteil verrechenbarer Stunden pro Tag | 70% | 71% | 72% |
| Fehlrate der Leistungseinträge | Anzahl Reklamationen pro Kunde | 4,2/Monat | 4,2/Monat | 3,5/Monat |

### System Usability Scale (SUS)

Die **SUS (System Usability Scale)** ist ein kompakter Fragebogen zur Messung des subjektiven Eindrucks der Gebrauchstauglichkeit. Er umfasst **10 Fragen**, bei denen Nutzende ihre Zustimmung auf **5 Stufen** angeben können. Veröffentlichte Benchmarkwerte ermöglichen den Vergleich mit anderen Produkten.

---

## Zusammenfassung

In diesem Workshop erarbeitete das Team eine konkrete Roadmap für die Releaseplanung. Features mit dem größten Nutzen für alle Stakeholder sollten priorisiert ausgeliefert werden. Hierfür wurde eine **Priorisierungsmatrix** eingesetzt. Im **Metrikenboard** wurden relevante Metriken und Messmethoden definiert. Das Metrikenboard bildet die Grundlage für abgestimmte Studien zur Erfolgskontrolle von Releases.
