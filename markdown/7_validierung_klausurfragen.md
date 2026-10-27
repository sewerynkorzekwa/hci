# Klausurfragen – Kapitel 7: Validierung

---

### 35. UX-Evaluationsmethoden: qualitative und quantitative Perspektive.

**Qualitative Methoden:**

Qualitative Methoden liefern Erkenntnisse über das *Warum* — also über Ursachen, Motive und Meinungen der Nutzenden. Sie erlauben tiefe Einblicke, sind aber nicht auf Repräsentativität ausgelegt.

Beispiele:
- **Usability-Walkthrough / Usability-Test im Labor:** Testpersonen bearbeiten Aufgaben an einem Prototyp; Moderator beobachtet und notiert Auffälligkeiten. Findings werden qualitativ ausgewertet (Beobachtetes Finding, Vermutete Ursache, Severity).
- **Think-Aloud-Protokoll (Lautes Denken):** Testpersonen verbalisieren ihre Gedanken während der Aufgabenbearbeitung. Gibt Aufschluss über mentale Modelle und Erwartungen.
- **Konzept-Walkthrough:** Präsentation eines Szenarios; erste Eindrücke und Kontraindikatoren werden gesammelt.
- **Fokusgruppe / Interview:** Offene Gespräche zur Meinung oder Erfahrung.

**Quantitative Methoden:**

Quantitative Methoden liefern messbare Daten, die mit statistischen Methoden ausgewertet werden können. Sie eignen sich für Vergleiche und Benchmarks.

Beispiele:
- **A/B-Test:** Zwei Varianten eines Interface werden unter realen Bedingungen mit vielen Nutzenden verglichen (z.B. Klickrate, Bearbeitungszeit).
- **Fragebogen (Benchmarking):** Standardisierte Skalen (z.B. SUS) liefern quantifizierbare Zufriedenheitswerte, die mit Durchschnittswerten oder Mitbewerbern verglichen werden können.
- **GOMS-Analyse:** Analytische Methode zur Berechnung von Aufgabenbearbeitungszeiten — ergibt eine konkrete Zahl (z.B. 20% schneller).
- **Datenanalyse:** Analyse existierender Nutzungsdaten (z.B. wie viele User buchen auf Projekte).

---

### 36. Welche Methoden sind eher geeignet, etwas über Verhalten auszusagen?

Methoden, die **beobachtbares Verhalten** erfassen, sind besonders geeignet, wenn man verstehen will, *wie* Nutzende mit einem System interagieren — unabhängig davon, was sie darüber sagen.

Geeignete Methoden:

- **Usability-Test / Walkthrough:** Testpersonen bearbeiten realistische Aufgaben. Moderator beobachtet direkt, wie die Person vorgeht, wo sie stockt, welche Fehler auftreten. → Verhaltensbeobachtung
- **Think-Aloud-Protokoll:** Zusätzlich zur Beobachtung werden die Gedanken verbalisiert → gibt Aufschluss über mentale Prozesse *während* des Verhaltens
- **Videoanalyse:** Aufgezeichnete Sessions werden nachträglich ausgewertet, Marker werden gesetzt
- **GOMS-Analyse:** Analytische Simulation von Interaktionsverhalten (keine direkte Beobachtung, aber Modellierung von Verhalten)
- **A/B-Test / Datenanalyse:** Misst tatsächliches Verhalten vieler Nutzender unter realen Bedingungen (Klicks, Abbruchraten, Bearbeitungszeiten)

**Warum nicht Fragebögen oder Interviews?** Diese erfassen *berichtetes* Verhalten — also was Nutzende glauben oder sagen zu tun. Das weicht oft vom tatsächlichen Verhalten ab.

---

### 37. Welche Methoden sind eher geeignet, etwas über Meinungen und Präferenzen auszusagen?

Methoden, die **subjektive Wahrnehmungen** erfassen, sind geeignet, wenn man verstehen will, was Nutzende *denken*, *fühlen* oder *bevorzugen*.

Geeignete Methoden:

- **Fragebogen:** Standardisierte Fragen mit Skalen (z.B. Likert-Skala) erfassen Meinungen und Präferenzen quantifizierbar. Benchmarks und Vergleiche möglich.
- **Interview / Fokusgruppe:** Offene Gespräche erlauben vertiefte Auseinandersetzung mit Meinungen und Erfahrungen. Fokusgruppen ermöglichen zusätzlich die Beobachtung von Gruppendynamiken.
- **Konzept-Walkthrough:** Erste Eindrücke, Zustimmung oder Ablehnung werden direkt erfragt.
- **Nachbefragung nach Usability-Test:** Anschlussfragen nach den Testaufgaben (z.B. "Wie haben Sie sich beim Lösen der Aufgaben gefühlt?") geben Aufschluss über Zufriedenheit und Präferenzen.

**Abgrenzung:** Während Beobachtungsmethoden zeigen, *was* Nutzende tun, zeigen Befragungsmethoden, *warum* sie etwas tun oder wie sie es bewerten. Beide Perspektiven ergänzen sich.

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

**Anwendung:** Für jedes negative Finding wird ein Severity-Level vergeben. Zusätzlich wird der **Lösungsaufwand** (Aufwand zur Überwindung des Problems) geschätzt. Für positive Findings werden keine Schweregrade oder Lösungsaufwände festgehalten.

Die Kombination aus Severity und Lösungsaufwand ermöglicht eine fundierte Priorisierung im Team-Workshop.

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
