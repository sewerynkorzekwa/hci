# Ausblick: Delivery

Wir haben das Entwicklungsteam von 4Service durch insgesamt acht Workshops begleitet, Diskussionen zur Auswahl, Anwendung und Auswertung verschiedener Methoden aus dem UX Design verfolgt und stehen nun vor dem Erreichen eines wesentlichen Ziels: Die Vision für ein neues Modul zur Leistungserfassung ist erstellt und validiert und eine Roadmap zur Umsetzung des Moduls wurde aufgestellt.

Dieses Kapitel gibt einen Ausblick darauf, wie der Übergang von der Vision über die Roadmap in die eigentliche Umsetzung aussehen könnte — insbesondere wie UX Designer und Developer zusammenarbeiten.

Das orchestrierende Vorgehensmodell dieser Kollaboration wird **Collaborative UX Design 2.0** genannt.

> **"Wir sollten uns vornehmen, unsere Ideen nicht bestätigen zu wollen, sondern nach Hinweisen zu suchen, sie zu widerlegen."**

---

## Theorie: User Experience Design und Agile Entwicklung

### User Stories

**User Stories** beschreiben eine Funktionalität aus der Perspektive der Nutzenden. Formulierungsschema:

> *"Als [Persona] möchte ich [Zieldurchführung], weil [Begründung]."*

User Stories sind kleine Inkremente. Sie sollten in ihrem Zusammenspiel jeweils lauffähige Funktionsbündel bereitstellen, die inhaltlich sinnvoll sind.

**Story Cards** — Attribute einer User Story Card:
- Formulierungsschema (Vorderseite)
- Rückseitenbeschreibung (Details, Akzeptanzkriterien)
- Story Points (Maß für Implementierungsaufwand aus Sicht der Softwareentwicklung)
- Aufwand für UI Design (separat von Entwicklungsaufwand)

**Epics:** Größere Inkremente, die sich aus mehreren User Stories zusammensetzen. Beispiel: "Leistung erfassen" ist ein Epic; darunter liegen einzelne User Stories wie "Leistung mit Titel erfassen" oder "Leistung mit Details erfassen".

---

## Sprints und Backlogs

### Sprint

Ein **Sprint** ist ein kurzer, zeitlich begrenzter Zeitraum in der Softwareentwicklung (typischerweise 1–4 Wochen). Innerhalb eines Sprints wird eine definierte Menge von User Stories umgesetzt. Am Ende jedes Sprints soll ein potenziell lieferbares Produktinkrement entstehen.

### Backlogs

| Begriff | Definition |
|--------|-----------|
| **Product Backlog** | Gesamtmenge aller User Stories, die für ein Produkt vorgesehen sind; wird priorisiert und laufend gepflegt |
| **Sprint Backlog** | Teilmenge des Product Backlogs; User Stories, die für einen konkreten Sprint geplant wurden |

### Story Points

**Story Points** sind ein Maß für den **relativen Aufwand** einer User Story. Es geht nicht um absolute Zeitangaben, sondern um den Vergleich des Aufwands einzelner User Stories untereinander. Teams einigen sich gemeinsam auf relative Aufwände.

Beispiel: "Anmelden" = 10 Punkte (Entwicklung), "Neu Setzen eines Passworts" = 20 Punkte (doppelter Aufwand).

### Velocity

Die **Velocity** beschreibt die erreichbare Arbeitsmenge (in Story Points), die ein Team in einem Sprint realistisch leisten kann. Beispiel: 130 Punkte für Entwicklung, 110 Punkte für Design pro Sprint. Auf Basis der Velocity wird entschieden, welche User Stories in einen Sprint passen.

---

## Dual Track Agile

**Dual Track Agile** ist ein Arbeitsmodell mit zwei parallelen Tracks:

| Track | Inhalt |
|-------|--------|
| **Envisioning** | Entwicklung und Validierung von Konzepten; UX Design-Tätigkeiten |
| **Delivery** | Detaildesign des User Interface und Implementierung der priorisierten User Stories |

In beiden Tracks arbeiten interdisziplinäre Teams zusammen. Das Modell ermöglicht, dass UX Designer immer einen Sprint voraus sind — während das Entwicklungsteam Sprint N implementiert, bereitet das Design Sprint N+1 vor.

---

## Triple Track Agile

**Triple Track Agile** erweitert Dual Track Agile um einen dritten parallelen Track:

| Track | Inhalt |
|-------|--------|
| **Envisioning** | Grobe Konzeptentwicklung für das nächste umfassende Produktinkrement |
| **Delivery: UI Design** | Gestalterische Vorgaben für den nächsten Sprint ausarbeiten |
| **Delivery: Implementierung** | Umsetzung des vorherigen Sprints |

In der Praxis unterstützen UX Designer oft auch den Implementierungs-Track durch Klärung von Detailfragen oder Erstellung fehlender Artefakte (Icons, Illustrationen).

---

## Sprint Zero (One Sprint Ahead)

**Sprint Zero** (auch: *Sprint 0* oder *One Sprint Ahead*) ist ein vorbereitender Sprint vor Beginn der eigentlichen Entwicklung. Das Designteam erarbeitet darin:

- Übergreifendes visuelles Erscheinungsbild
- Grundlegende Projektgrundlagen
- Erste Wireframes und visuelle Varianten

Sprint Zero dauert oft die volle Sprintlänge (2–3 Wochen) und findet parallel zu den Vorbereitungen des Entwicklungsteams statt.

**Planung im 4Service-Beispiel (Abbildung 99):**

| Phase | Aktivitäten (Design) |
|-------|---------------------|
| Sprint 0 | Begutachtungen, Anpassung der Screens (Release 1), Varianten visuelle Gestaltung, Fertigstellung visuelle Gestaltung |
| Vorbereitung Sprint 1 | Anpassung der Screens, zusätzliche Wireframes, Spezifikation aller visuellen Elemente |
| Vorbereitung Sprint 2 | Anpassung der Screens (Sprint 1), zusätzliche Wireframes, Spezifikation aller visuellen Elemente |
| Während Sprint 1 | Vorbereiten und Durchführen von Usability-Tests |

---

## Dual Track Sprint Planning

Beim **Dual Track Sprint Planning** werden Aufwände **getrennt** für Entwicklung und Design geschätzt. Auf jeder Story Card gibt es separate Story Points für:
- Aufwand für das UI Design
- Aufwand für die Entwicklung

Dies gibt mehr Planungssicherheit bei der Durchführung der Sprints.

---

## Sprint Planning Workshop

Der **Sprint Planning Workshop** findet mit dem gesamten Team statt. Typischer Ablauf:

1. **Überblick**: Produktmanagerin präsentiert die wichtigsten Ergebnisse der Envisioning-Phase — Businessziele, User Research-Erkenntnisse, Lösungsansatz, Roadmap
2. **User Story Map**: Entwicklungsleiter zeigt die reduzierte User Story Map für das erste Release
3. **User Stories verfeinern**: User Stories werden SMART aufgeteilt — sie sollen lauffähige Funktionsbündel bereitstellen, die inhaltlich sinnvoll sind
4. **Aufwand schätzen**: Team schätzt Story Points relativ (keine absoluten Zeitangaben)
5. **Sprint-Umfang festlegen**: Auf Basis der Velocity werden User Stories dem ersten Sprint zugeordnet

---

## Zusammenfassung

In diesem Ausblick haben wir gesehen, wie der Übergang von der UX-Design-Phase in die agile Entwicklung aussehen kann. Die wichtigsten Konzepte sind:

- **User Stories** als Beschreibung von Produktinkrementen aus Nutzerperspektive
- **Sprints** als kurze, iterative Entwicklungszyklen mit klarem Ergebnis
- **Dual/Triple Track Agile** als Modell für die Zusammenarbeit von UX Design und Entwicklung
- **Sprint Zero** zur Vorbereitung des Designteams
- **Story Points und Velocity** als Grundlage für realistische Sprintplanung

Das übergreifende Vorgehensmodell des gesamten Prozesses — von Scoping über Research, Synthese, Ideation, Konzept, Prototyping, Validierung, Roadmap bis zur Delivery — wird **Collaborative UX Design 2.0** genannt.
