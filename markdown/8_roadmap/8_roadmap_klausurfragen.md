# Klausurfragen – Kapitel 8: Roadmap

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

Beim traditionellen Entwicklungsmodell werden Produkte mit vielen Features auf einmal ausgeliefert (z.B. jährliche Releases). Continuous Delivery hingegen liefert fortlaufend kleine Releases aus. Das MVP ist das erste dieser kleinen Releases — es bietet bereits einen echten Mehrwert, obwohl die vollständige Produktvision noch nicht umgesetzt ist.

**Beispiel aus 4Service:**

Das MVP enthielt nur die Grundfunktionalitäten der Leistungserfassung (Anmelden, Woche anzeigen, Leistung manuell erfassen). Erweiterte Funktionen wie Gruppenleistungen oder die Übernahme von Terminen wurden erst in späteren Releases hinzugefügt.
