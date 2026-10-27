# Workshop: Validierung

Je früher ein Produkt- oder Servicekonzept evaluiert werden kann, umso kostengünstiger und in ihrer Reichweite umfassender sind die Möglichkeiten, resultierende Erkenntnisse bei dessen Fortentwicklung berücksichtigen zu können. Empirische Validierungen mit prospektiven Usern gestatten eine besonders belastbare und aussagekräftige Prüfung unserer Annahmen. In diesem Workshop werten wir die Ergebnisse der Validierung des entwickelten Prototyps mit dem Ziel aus, vorliegende Unzulänglichkeiten in unserem Konzept zu identifizieren und Hinweise auf dessen Stärken zu erhalten.

## Überblick Validierung

Hinter einem Lösungskonzept verbergen sich viele Annahmen. Im Kapitel »Workshop: Prototyping« erstellte das Projektteam eine Validierungsplanung und leitete hieraus die zur Validierung notwendigen Prototypen ab. Abhängig von den zu validierenden Annahmen können in diesem Schritt unterschiedliche Prototypen erforderlich sein. In Abbildung 62 zeigen wir nochmals das übergeordnete Vorgehen.

**Ziel**
- Validierung eines Prototyps, gegebenenfalls Ableitung von Maßnahmen zu dessen Optimierung

**Teilnehmende**
- Projektteam, Vertretung der Auftraggeberin

**Hauptergebnisse**
- Erkenntnisse
- Schlussfolgerungen

**Vor dem Workshop**
- Evaluationen durchführen
- Evaluationen auswerten

**Ablauf**
- Ergebnisse vorstellen und Schlussfolgerung ziehen

**Nach dem Workshop**
- Konzept iterativ überarbeiten (Kapitel »Workshop: Konzept«) oder Roadmap zur Umsetzung festlegen (siehe Kapitel »Workshop: Roadmap«)

*Abbildung 62: Vorgehen zur Validierung eines Konzepts*
- Konzept → Kapitel Prototyping: Workshop: Planen der Validierung → Bauen der Prototypen
- → Kapitel Validierung: Durchführen der Validierung → Workshop: Schlussfolgerungen ziehen
- Von »Workshop: Schlussfolgerungen ziehen« entweder zurück zum Konzept oder weiter zur Umsetzung

Ziel des Teams ist es nun, unter Rückgriff auf den oder die erstellten Prototypen die wesentlichen Konzeptannahmen zu validieren. Je nach Ergebnis des in diesem Kapitel beschriebenen Validierungs-Workshops wird dann das Team darüber entscheiden, ob Anpassungen des Konzepts nötig sind oder die Stützung von Annahmen den Weg zur Umsetzung frei macht.

In diesem Kapitel beschreiben wir, wie das Team einen Walkthrough zur Validierung der User Journey durchführt, und gehen auch auf die theoretischen Grundlagen von Validierungsstudien ein. Hierbei stellen wir einige praktische Checklisten vor, die sich in unserer Projektarbeit bewährt haben.

## Theorie: Usability-Tests & Walkthroughs

Die bekannteste empirische Methode, Feedback von aktuellen oder zukünftigen Nutzenden eines Produkts zu erheben, ist die Durchführung von Usability-Tests: Bei einem Usability-Test werden repräsentativ ausgewählte Testpersonen dabei beobachtet, wie sie typische Testszenarien mit einem interaktiven System bearbeiten.

Hierbei wird in der Regel auf prototypische Realisierungen eines zukünftigen Systems zurückgegriffen: Auch in unserem Fallbeispiel hat das Team einen Prototyp der Leistungserfassung von 4Service entwickelt. Erreichen Testpersonen bei der Bearbeitung von Testszenarien mit dem Prototyp ein vorgegebenes Arbeitsziel nicht oder weichen sie auffällig von einem für die Aufgabe vorgesehenen optimalen Pfad ab, so ist dies ein Hinweis für das Vorliegen eines möglichen Usability-Problems. Im ersten Fall wird von einer fehlenden Effektivität ausgegangen, im zweiten Fall von unzureichender Effizienz der Bearbeitung.

Während der Durchführung eines Usability-Tests werden Teilnehmende gebeten, »laut zu denken« – also alles laut auszusprechen, was ihnen bei der Aufgabenbearbeitung durch den Kopf geht. Wir können bei einem Usability-Test also nicht nur das Vorgehen von Testpersonen detailliert beobachten, sondern erhalten durch ihre Verbalisierungen auch direkte Hinweise auf ihre mentalen Prozesse, Annahmen, Ziele und Präferenzen.

Die Rollen bei einem Usability-Test sind klar verteilt: Es werden Testpersonen für eine Teilnahme rekrutiert, die repräsentativ für die aktuellen oder zukünftigen Nutzenden einer Anwendung oder eines Service sind. Ein Moderator oder eine Moderatorin führt die Teilnehmenden durch vorbereitete Testszenarien, die von ihnen eigenständig bearbeitet werden. Das Geschehen können beobachtende Personen auf einem Monitor in einem angrenzenden Beobachtungsraum oder direkt durch einen venezianischen Spiegel, der die Testpersonen von ihnen trennt, mitverfolgen. Die protokollführende Person notiert bedeutsame Ereignisse bei der beobachteten Interaktion. Testsessions werden typischerweise zusätzlich in Videos festgehalten. In solchen Videos werden Bildschirminhalte, Gestik/Mimik der Testpersonen, ihre Verbalisierungen und gegebenenfalls die Nutzung von Hilfsmitteln aufgezeichnet. Digitale Aufzeichnungssysteme erlauben es der protokollführenden Person, einen Marker in der Aufzeichnung zu setzen, wenn auffällige Ereignisse auftreten. Relevante Ereignisse lassen sich so später schnell wiederfinden. Durch die resultierenden Videoaufzeichnungen können Stakeholder wie UX Designer, Entwicklerinnen oder Produktmanager die – positiven oder negativen – Reaktionen prospektiver User bei der Interaktion mit dem System später miterleben. Grundsätzlich kann zur Dokumentation auch ausschließlich auf eine manuelle Protokollierung zurückgegriffen werden: Die oft sehr erkenntnisreiche Möglichkeit der retrospektiven Betrachtung des Interaktionsgeschehens in Videos ist dann jedoch nicht möglich.

Auch wenn für uns das Identifizieren von Usability-Barrieren oder Beeinträchtigungen der UX sehr wichtig ist, möchten wir auch wissen, welche Merkmale Leute an einem Konzept schätzen – diese positiv erlebten Produktattribute sollten wir in der nächsten Iterationsschleife nach Möglichkeit beibehalten. Usability-Evaluationen sind, wie Jacob Nielsen es 2007 treffend formulierte, eben »kein Defätisten-Job«. Wir dokumentieren bei Usability-Evaluationen Beobachtungen daher ganz neutral als *Findings:* Hierbei ist es zunächst unerheblich, ob diese Findings in der Konsequenz positiv oder negativ sind. Wesentlich ist, dass die mit ihnen verbundenen Erkenntnisse Unterstützung zur Fortentwicklung oder Bewertung eines Systems bieten. Wenn wir Erkenntnisse aus Usability-Tests für die Fortwicklung eines Systems in nachfolgenden Iterationsschritten nutzen, so sprechen wir von *formativen* Evaluationen; die Evaluation des Ist-Zustands mit dem Ziel einer zusammenfassenden Bewertung wird als *summative* Evaluation bezeichnet.

Aus den Erfahrungen vieler Praxisprojekte können wir die Bedeutung eines möglichst frühen Einsatzes von Evaluationsmethoden nicht deutlich genug betonen. UX Designer möchten Entwürfe oft vor der ersten Evaluation »noch etwas weiter ausarbeiten, weil sie noch nicht so weit sind«, und bitten daher um mehr Zeit. Wie hilfreich aber sind weitere Ausarbeitungen, wenn der eingeschlagene Weg – gegründet auf unsicheren Annahmen – ein »Holzweg«, ist? Wächst der investierte Aufwand weiter, so forcieren wir den bereits angesprochenen Bestätigungswunsch der mit einem Produkt verbundenen Annahmen. Wir haben dies im vorgehenden Kapitel als Sunk-Cost-Gefahr bezeichnet. Zeitnahes Feedback zu unseren kritischen Designentscheidungen ist essenziell – und hierzu ist häufig bereits der Einsatz einfacher Papierprototypen ausreichend.

Ein Papierprototyp ist nicht ohne weitere Unterstützung »interaktiv«. Wie im letzten Kapitel angesprochen können wir mit ein wenig Kreativität und der Hilfe einer Moderation auch simple Papierprototypen im Labor »bedienbar« machen. So kann die Person, die moderiert, in einem empirischen Usability-Test die Papierskizzen der Screens eines Prototyps – je nach »Input« der teilnehmenden Person – manuell austauschen. Der Input von Teilnehmenden kann beispielsweise das Zeigen auf einen gezeichneten Button als simulierter Mausklick, eine Touch-Geste oder aber auch der durch Testpersonen handgeschriebene Inhalt von Feldern sein. Dies stellt die einfachste Variante eines Usability-Walkthroughs dar: Rohe Konzeptsketches eines Interface sind hierzu ausreichend. Verschiedene Softwarepakete erlauben das einfache Verbinden von Fotos einzelner Screens oder Screenzustände – wir können damit »Interaktivität« dann beim »Drücken« auf einen verlinkten »Button« mit geringem Aufwand simulieren.

Natürlich sollten auch beim Einsatz solcher Low-Fidelity-Prototypen Teilnehmende so wenig wie möglich beeinflusst werden. Wir geben Testpersonen zunächst ein Testszenario zur Bearbeitung vor, Fragen können wir später stellen. Wichtig ist, dass in einem Testszenario ein klares Ziel formuliert ist und das Szenario durch anschauliche Kontextinformation angereichert ist: Testpersonen können sich hierdurch leichter in die vorgegebene, möglichst realistische Arbeitssituation hineinversetzen. Die Vorgabe »Erfasse die Arbeitszeit für ein beliebiges Projekt an einem Tag deiner Wahl« ist eine wenig geeignete Formulierung für ein Testszenario in einem empirischen Usability-Test. Die konkrete Vorgabe einer bestimmten zu erfassenden Arbeitszeit (»3 Stunden Konzeptentwicklung«) für ein gegebenes Projekt »(Projekt ›Kettcar‹ für den Kunden HvG)« zu einem definierten Datum (»30. März 2023«) operationalisiert klar, mit welchem Leistungseintrag eine Testperson das Ziel des Testszenarios erreicht hat.

Die Testszenarien, die Personen in einem empirischen Usability-Test bearbeiten, sollten einen realistischen und typischen Ausschnitt der mit einem System durchzuführenden Aufgaben abbilden. Ebenso sollten die situativen Bedingungen bei der Durchführung eines Usability-Tests in den relevanten Merkmalen jenen des realen Nutzungskontexts entsprechen. Selbstverständlich stellt ein Usability-Test immer eine künstliche Situation dar – aber wir können versuchen, die charakteristischen Attribute einer typischen Nutzungssituation so nachzustellen, dass sie sich der Realität so weit wie möglich annähern. Wenn also Nutzende zumeist bei der Arbeit durch Anrufe gestört werden und dies ein wesentliches Situationsmerkmal ausmacht, so können wir solche Störungen in einem Usability-Test nachbilden und Anrufe auch dort simulieren. Möglich ist auch eine Durchführung von Usability-Tests – statt im Labor – direkt im Arbeitskontext prospektiver Nutzenden – wir sprechen dann von der Durchführung von *Feldtests*.

In einigen Fällen brauchen wir sehr schnelles Feedback und haben keine Zeit für aufwendige Rekrutierungen. Kurzfristig verfügbare Testpersonen sind dann gefragt. Sogenannte *Hallway-Tests* mit zumeist internen Teammitgliedern als Ersatz für eine repräsentative Nutzervertretung können eine Lösung sein, wenn es beispielsweise um die Nachvollziehbarkeit eines innovativen Controls in einem Interface geht. Entscheidungen, die allerdings das spezifische Fachwissen von Usern bei der Interaktion voraussetzen, sollten auf der Basis von Hallway-Tests nicht getroffen werden.

## Vorbereiten des Walkthroughs

Die Testaufgaben und der Prototyp sind nun für den Walkthrough vorbereitet. Tim und Sarah haben nochmals mit dem Unternehmen Kontakt aufgenommen und mit den zehn geplanten Testpersonen einen Termin für den Feldtest vereinbart. Für die Durchführung der Tests veranschlagen sie pro Testperson etwa eine Stunde. Zwischen den Sessions planen sie jeweils halbstündige Pausen ein, in denen sie kurz die beobachteten Findings besprechen und reflektieren können. Das Einladen prospektiver User in ein Usability-Labor hätte die Rekrutierung deutlich erschwert, daher fiel die Entscheidung für einen Feldtest: Die Tests werden direkt beim Kunden vor Ort in einem Sitzungsraum durchgeführt.

Tim und Sarah wollen den Walkthrough auf Video aufzeichnen. Sie bereiten eine Einverständniserklärung vor, um deren Unterzeichnung sie vor der Testdurchführung bitten. Zudem vereinbarten sie vorab mit dem Kunden, dass sie den Testpersonen jeweils einen Gutschein für Konzertkarten als kleines Dankeschön übergeben.

Sarah wendet sich an Tim: »Ist es okay für dich, wenn du die Tests moderierst und ich protokolliere?«

Tim antwortet: »Klar, das können wir gerne so machen. Wir sollten uns zuvor darauf verständigen, bei welchen Beobachtungen du auf jeden Fall Notizen anfertigen solltest. Hierzu können wir sogenannte *kritische Ereignisse* festlegen. Treten diese ein, weist dies eindeutig auf Usability-Probleme hin. Ich sehe die folgende Ereignisse als kritische Hinweise:

- Abweichen der User vom kürzesten Weg zur Zielerreichung
- Nutzung von Suchdiensten
- Langes Zögern (mehr als 10 Sekunden) während der Aufgabenbearbeitung
- Negative Aussagen

Solche Ereignisse solltest du auf jeden Fall protokollieren.« Sarah nickt: »Klar, das passt für mich. Welches Notationsschema schlägst du vor?«

Tim antwortet: »Ich stelle mir ein einfaches Protokoll vor: Es reicht vollkommen aus, wenn du eine Kurzbeschreibung in Stichworten und den genauen Zeitpunkt der Beobachtung notierst. Wir können uns das anschließend gemeinsam im Video genauer ansehen. Lass uns nun einen Pilotlauf mit einer Probeperson durchspielen, um sicherzustellen, dass alles klappt – und unsere Erwartungen an die Dauer auch einigermaßen korrekt sind.«

### Checkliste: Vorbereitung

- Fragestellung festlegen
- Testszenarien ausarbeiten
- Verfügbarkeit eines Prototyps oder Produktivsystems
- Eventuelle Interviewfragen/Fragebögen vorbereiten
- Räumlichkeiten, Testinfrastruktur reservieren
- Vertraulichkeitsvereinbarung vorbereiten
- Einverständniserklärung zur Aufzeichnung von Videos vorbereiten
- Personen aus dem Projekt zur Beobachtung einladen
- Teilnehmende rekrutieren
- Einladungsmail verfassen
- Pilottest durchführen
- Terminerinnerung für die Teilnehmenden formulieren

## Durchführung des Walkthroughs

Tim und Sarah haben alle Vorbereitungen zur Durchführung des Usability-Tests getroffen. Seit der Entwicklung des Prototyps haben sie

- Software zur Aufzeichnung der Testsessions auf dem Testcomputer installiert,
- alle Testszenarien mit dem Prototyp nochmals durchgespielt – an manchen Stellen wurde der Prototyp angepasst, um die Durchführung aller Testszenarien möglichst umfassend zu unterstützen –,
- Termine mit den Testpersonen vereinbart und kurz vor dem verabredeten Termin Erinnerungen via E-Mail verschickt.

Die erste Testsession steht nun an. Als die erste Testperson eintrifft, wird sie von Tim begrüßt und gebeten, direkt vor dem Testcomputer Platz zu nehmen. Tim setzt sich neben sie, während Sarah im Hintergrund bleibt. Tim leitet die Testsession ein: »Herzlichen Dank dafür, dass Sie sich Zeit nehmen.«

Tim stellt Sarah und sich selbst kurz vor und fährt dann fort:

»Aktuell beschäftigt sich unser Team damit, die Leistungserfassung von 4Service, mit der Sie täglich arbeiten, weiterzuentwickeln. Wir möchten das bislang entwickelte Konzept nun auf seine Eignung überprüfen. Hierzu möchten wir Sie gerne bitten, einige Aufgaben zu bearbeiten. Wir haben Aufgaben vorbereitet, die aus unserer Sicht typisch für Leistungserfassungen sind. Bitte bearbeiten Sie diese, wir werden hinter Ihnen sitzen und möchten Ihnen gerne dabei zusehen. Bitte verhalten Sie sich so, als wären wir nicht da. Nachdem Sie alle Aufgaben bearbeitet haben, bitten wir Sie, uns einige Verständnisfragen zu beantworten. Die Bearbeitung der Aufgaben wird ungefähr 30 bis 45 Minuten Ihrer Zeit in Anspruch nehmen. Ich hoffe, das ist so in Ordnung für Sie?«

Die Testperson nickt und Tim fährt fort: »Für uns ist ganz wichtig, zu erwähnen, dass es nicht darum geht, Sie zu testen – wir überprüfen den Konzeptvorschlag. Wenn Sie Schwierigkeiten haben, die Aufgaben zu lösen, dann ist das für uns ein Hinweis darauf, dass unser Konzept noch nicht ganz ausgereift ist. Wir werden die Sessions auf Video aufnehmen. Selbstverständlich verwenden wir das Video nur für Auswertungszwecke und löschen es unmittelbar anschließend. Wenn Sie mit dem Vorgehen einverstanden sind, möchten wir Sie gerne bitten, diese Einverständniserklärung zu unterzeichnen.«

Nachdem die Testperson das Dokument unterzeichnet hat, fährt Tim fort: »Bei der Anwendung, die wir Ihnen gleich zeigen, handelt es sich um einen ersten Prototyp. Er bildet ausgewählte Szenarien ab, ist aber noch nicht vollständig. Es kann durchaus sein, dass Sie etwas auf dem Bildschirm auswählen, das wir noch nicht ausgearbeitet haben. In diesem Fall kann der Prototyp kein passendes Ergebnis anzeigen – wir würden Sie einfach darauf hinweisen. Bitte arbeiten Sie in einer Ihnen genehmen Geschwindigkeit. Sollten Sie mit einer Aufgabe nicht zurechtkommen, können Sie diese jederzeit abbrechen – dies gilt selbstverständlich auch für die komplette Session: Sagen Sie uns einfach, wenn Sie nicht mehr fortfahren möchten, und wir beenden dann umgehend die Sitzung. Bitte beachten Sie, dass wir Ihnen während der Bearbeitung nach Möglichkeit keine Lösungshinweise geben möchten: Uns interessiert ja gerade, wie Personen ohne Unterstützung mit der möglichen neuen Version der Leistungserfassung zurechtkommen. Nun haben wir noch ein besonders wichtiges Anliegen: Für uns ist es überaus hilfreich, wenn Sie während der Bearbeitung der Aufgaben ›laut denken‹. Wir möchten Ihnen hierzu gerne ein kurzes Video zeigen, in dem eine Person gezeigt wird, die laut denkt, während sie eine Aufgabe löst. Dies macht es vielleicht etwas klarer, was wir damit meinen.«

Tim spielt ein kurzes Video ab und fährt fort: »Haben Sie nun noch Fragen an uns? Wenn nicht, gebe ich Ihnen nun die erste Aufgabe und starte den Prototyp.«

### Checkliste: Einführung

- Vorstellungsrunde
- Ziele der Sitzung darlegen (zu testende Applikation, Entwicklungsphase etc.)
- Hinweis: Nicht die Testperson wird getestet, sondern die Anwendung!
- Dauer des Tests und des Ablaufs erklären
- Testinfrastruktur erklären
- Einverständnis für Videoaufzeichnung einholen
- Vertraulichkeitserklärung unterzeichnen
- Hinweis: Aufgaben können nach eigenem Tempo bearbeitet werden
- Hinweis: Abbrechen ist jederzeit möglich
- Hinweis: Bitte laut denken!
- Hinweis: Wir melden uns nur im »Notfall«
- Eventuell Kurzinstruktion zur Anwendung
- Nachfragen, ob die Testperson Fragen hat

Die Bearbeitung der ersten Aufgabe bereitet der Testperson keinerlei Mühe. Im Gegenteil – sie äußert sich gleich mehrmals positiv zur kalenderähnlichen Ansicht und scheint intuitiv zu wissen, wie sie damit die in der Testaufgabe vorgegebenen Leistungen erfassen kann. Bei der zweiten Aufgabe geht es um Gruppeneinträge. Hier erklärt die Testperson, dass sie vor einem Eintrag ihre Kolleginnen und Kollegen, mit denen sie ein gemeinsames Meeting hatte, anrufen würde, um sich mit ihnen abzustimmen. Sie erwartet keine eigene Funktionalität zur Unterstützung solcher Gruppeneinträge. Erst im Verlauf ihrer Bearbeitung des dritten Testszenarios wird sie stutzig und entdeckt die Möglichkeit, auch für andere Personen im Team direkt Leistungen zu erfassen.

Während der Beobachtung verhält sich Sarah betont zurückhaltend: Sie möchte nur im Notfall intervenieren oder unterstützen. Sie spricht weder Lob noch Ermunterung aus, sondern bleibt still und nimmt eine möglichst neutrale, jedoch freundliche Haltung ein. Manchmal wird sie von den Testpersonen gefragt: »Muss ich diesen Button wählen?« Dann fragt Sarah einfach zurück: »Was erwarten Sie als Reaktion des Systems, wenn Sie diesen Knopf drücken?«

Nach der Bearbeitung der Aufgaben stellt Sarah der Testperson einige zusätzliche Fragen. Sie zeigt auf die Liste mit den Projektvorlagen und fragt die Testperson nach ihrer Interpretation dieser Liste. Ebenso fragt sie, wie viele Stunden sie ihrer Meinung nach für diese Woche schon erfasst hat – und wie viel Budget auf dem Projekt noch verfügbar ist. Die Testperson hat bei keiner dieser Fragen Probleme damit, passende Antworten zu finden. Zum Abschluss der Sitzung fragt Sarah die Testperson: »Wie haben Sie sich beim Lösen der Aufgaben gefühlt?«

»Ich finde die Lösung super«, erklärt die Testperson. »Mir ist nicht sofort aufgefallen, dass ich auch Leistungen für meine Kolleginnen und Kollegen erfassen kann. Tatsächlich ist diese Funktion aber wirklich sehr hilfreich. Damit kann ich sicherstellen, dass wir die gleiche Dauer für Meetings erfassen, ohne dass ich mich eigens abstimmen muss. Sie ahnen gar nicht, wie umständlich es ist, wenn ich diese nicht erreiche und die Stunden irgendwo zwischenparken muss. Na ja, dann gerät auch schnell mal etwas in Vergessenheit … Bei der Bearbeitung der dritten Aufgabe habe ich dann selbst gemerkt, dass diese Funktion viel Arbeit sparen kann.«

### Checkliste: Moderation

- Eine möglichst neutrale Haltung einnehmen
- Sich ruhig verhalten, im Hintergrund bleiben
- Nicht loben, nur beobachten
- Nicht zu früh intervenieren
- Keine versteckten Lösungshinweise geben, wenn nachgefragt wird
- Fragen von Testpersonen mit Gegenfragen nach ihren Erwartungen begegnen
- Offene Fragen stellen
- Zuerst generische Fragen stellen, bevor auf konkrete Aspekte des User Interface eingegangen wird
- Fragen nach Möglichkeit erst nach Abschluss einer Aufgabe stellen. Beispiel: »Sie zögerten öfter bei der Bearbeitung dieser Aufgabe: Was war der Grund dafür?«
- Die einzelnen Testaufgaben jeweils auf eigenen Seiten vorlegen

## Auswertung des Walkthroughs

Nach Abschluss der Testsessions an diesem Tag beginnen Tim und Sarah mit der Auswertung der Daten aus den verschiedenen Walkthroughs. Auch zwischen den Sitzungen hatten sie bereits über auffällige Findings gesprochen. Die Eindrücke sind noch frisch – und mit den Videos der Walkthroughs können alle Details gesichtet und diskutiert werden.

Tim spricht Sarah an: »Du hattest dir ja während der Sessions jeweils Notizen gemacht und Marker in der Aufzeichnung gesetzt. Dies spart uns nun eine Menge Arbeit: Wir können die jeweiligen Stellen im Video nochmals anschauen und müssen nicht alle Videos in voller Länge durchsehen. Ich habe Karten vorbereitet, auf denen wir die Findings jeweils festhalten können. Jedes Finding kommt auf eine eigene Karte.«

Die Karten haben folgende Attribute:

- Screen
- Testperson
- Beobachtetes Finding
- Vermutete Ursache
- Severity (bei negativen Findings)
- Lösungsaufwand (bei negativen Findings)

Die *Severity* beschreibt, wie schwerwiegend das Usability-Problem, das hinter einem negativen Finding steht, einzuschätzen ist. Für positive Findings werden keine Schweregrade oder Lösungsaufwände festgehalten. Tim und Sarah unterscheiden bei der Einordnung der negativen Findings die folgende Schweregrade:

1. Kosmetisches Problem, das nicht mit Priorität gelöst werden muss.
2. Mittelschweres Problem, das prioritär beseitigt werden sollte.
3. Schweres Usability-Problem, das dringend beseitigt werden muss, da es zum Abbruch der Aufgabenbearbeitung führen kann.

Tim und Sarah gehen alle protokollierten Stellen in den Session-Videos gemeinsam durch, diskutieren und erstellen direkt Karten zu den jeweils betroffenen Screens. In der Abbildung 63 ist ein solches Ergebnis zu einem Finding dargestellt.

*Abbildung 63: Wireframe mit der Beschreibung eines Findings*
- Wireframe der Wochenansicht (Oktober 2023 – W40) mit Projektliste (Kunde 1–4, UX Design) und Teammitgliedern (Mitarbeiter\*in 1–3, UX Designer); über der Projektliste eine Finding-Karte:
- Problem: Vorlagen werden nicht genutzt.
- Vermutete Ursache: Der Titel “Meine Projekte” lässt nicht auf Leistungsvorlagen schließen.
- Mögliche Lösung: Titel auf “Leistungsvorlage” ändern.
- Severity: 2, Aufwand: 1

Gerade die Lösungsfindung für beobachtete Usability-Barrieren kann angemessen im Rahmen eines Workshops geklärt werden. Dies gilt auch für zuverlässige Schätzungen für den – gestalterischen wie technischen – Aufwand, der zu deren Überwindung notwendig ist. Die vorläufigen Ergebnisse der Analyse von Tim und Sarah stellen damit den Input für weiter gehende Diskussionen mit den Teilnehmenden des Validierungs-Workshops dar.

## Validierungs-Workshop

Die Validierungsplanung umfasste neben dem Walkthrough noch weitere Maßnahmen. Die ursprüngliche Planung zeigen wir in Abbildung 64:

*Abbildung 64: Übersicht über die Validierungsplanung*

| | Erfassung im Kalender fühlt sich effizient an | Erfassung von Gruppeneinträgen wird genutzt | Zentrale Dienste erfassen nicht auf Projekte | Übernahme von Kalenderdaten liefert gute Vorlagen | Nutzende buchen nicht auf temporäre Projekte |
|---|---|---|---|---|---|
| **Unsicherheit** | ●●● | ●● | ●●● | ●●● | ● |
| **Einfluss** | ●●● | ●● | ●●● | ●● | ● |
| **Methode** | GOMS-Analyse | Walkthrough mit passendem Szenario | Datenanalyse | Funktionaler Test | Walkthrough mit passendem Szenario |
| **Prototyp** | Wireframe | Wireframe | Kein Prototyp notwendig | Funktionaler Prototyp | Wireframe |
| **Stichprobe** | Keine Stichprobe notwendig | 5-6 Teammitglieder | Vollerhebung | Keine Stichprobe notwendig | 8-10 Teammitglieder |
| **Erfolgreich wenn** | GOMS-Analyse ergibt Vorteil für Kalender | Keine grundlegenden Bedenken | Mehr als 5% der Nutzenden haben keine Projekte | 90% der Kalendereinträge werden richtig erkannt | Es sind keine schweren Usability-Probleme erkennbar |
| **Aufwand** | ● | ● | ● | ●● | ● |

Die Durchführung der beschlossenen Methoden zur Validierung wurden, wie in Kapitel »Workshop: Prototyping« angesprochen, an verschiedene Zweierteams delegiert:

- Mit einem Walkthrough wurde die Leistungserfassung unter Rückgriff auf Gruppeneinträge überprüft. Ziel war es, herauszufinden, ob die Erfassung von Leistungen für User nachvollziehbar ist.
- Mit einer GOMS-Analyse des vorgeschlagenen Erfassungsablaufs wurde geprüft, ob mit dem neuen Konzept Leistungen effizient erfasst werden können.
- Durch eine Datenanalyse sollte festgestellt werden, in welchem Umfang Mitarbeitende der zentralen Dienste bisher auf Projekte gebucht haben.
- Mit einem technischen Prototyp wurde eruiert, ob eine robuste Datenübernahme aus dem Kalender möglich ist.

Die Ergebnisse aller Validierungssessions mit den eingeladenen Testpersonen liegen nun vor. Tim hat das ganze Team im Workshop versammelt: »Wir haben nun die Validierungsstudie durchgeführt und ausgewertet. Die Ergebnisse haben wir kurzgefasst auf Karten geschrieben. Bitte schaut sie euch an, wir sind auf eure Kommentare gespannt. Danach möchte ich Tom und Peter bitten, die Ergebnisse zum technischen Prototyp vorzustellen.«

### Technischer Prototyp

Tom stellt sich vor die Gruppe und beginnt: »Wir haben verschiedene Kolleginnen und Kollegen gebeten, uns Zugriff auf ihre Kalender zu gewähren – wir möchten für die technische Analyse unbedingt auf reale Daten zugreifen. Wir haben uns die Einträge im Kalender genau angeschaut und einen Algorithmus entwickelt, der die Einträge einlesen und sie Projekten zuordnen soll. Das Einlesen der Daten aus unterschiedlichen Kalendersystemen war kein Problem. Jetzt kommt jedoch ein großes Aber: Die Zuordnung zu Projekten funktionierte leider nicht zuverlässig. In deutlich mehr als der Hälfte der Fälle waren manuelle Korrekturen durch die User notwendig – die Fehlerquote war einfach zu hoch. Wenn wir das verlässlich hinbekommen wollen, müssten die Leute bei den Termineinträgen jeweils explizit die Projektnamen in den Terminen mitangeben. Wir hatten als Kriterium gefordert, dass 90 % der Einträge erfolgreich erkannt werden – hiervon sind wir weit entfernt: Kaum mehr als 30 % der Einträge konnten automatisiert korrekt und ohne Nacharbeiten einem Projekt zugeordnet werden. Wenn wir eine höhere Zuverlässigkeit erreichen wollen, müssen entweder wir deutlich mehr Arbeit in den Algorithmus investieren – oder die User den Eintrag des Projektnamens bei Terminen explizit vornehmen.«

Tim bedankt sich bei Tom und Peter und wendet sich an die Teilnehmenden des Workshops: »Was sagt ihr zu den Ergebnissen?«

Daniela, die Produktmanagerin, meldet sich zu Wort: »Ich sehe das Feature weiter als hilfreich an – dies allerdings nur dann, wenn wir eine weitgehend zuverlässige automatische Zuordnung hinbekommen. Nutzenden den Eintrag des Projektnamens abzuverlangen ist nicht nur umständlich – wenn sie dies dann doch mal vergessen, funktioniert der automatische Eintrag nicht. Das ist nicht verlässlich. Dies sollten wir bei der Releaseplanung berücksichtigen – und das Feature nicht als Erstes umzusetzen versuchen.«

»Danke für deine Einschätzung Daniela. Ich verstehe das so, dass du das Feature weiterhin als hilfreich erachtest, aber dass der zu einer reifen Umsetzung notwendige Aufwand gegen eine Priorisierung im nächsten Release spricht. Ich trage das direkt in unsere Planung so ein.« Tim erstellt die notwendigen Karten und bittet als Nächstes Andrea darum, ihre Analyse vorzustellen.

*Abbildung 65: Validierungsplanung mit einem ersten Ergebnis*
- Validierungsplanung wie in Abbildung 64, ergänzt um die Zeilen »Ergebnis« und »Schlussfolgerung«; ausgefüllt nur für die Annahme »Übernahme von Kalenderdaten liefert gute Vorlagen«:
- Ergebnis: 30% der Kalendereinträge erkannt
- Schlussfolgerung: Feature wird für ein späteres Release geplant

### Datenanalyse

»Wir haben überprüft, ob Personen der zentralen Dienste auch auf Projekten arbeiten und Leistungseinträge vornehmen. Grundsätzlich konnten wir feststellen, dass es einige gibt, die tatsächlich häufig auf Projekten arbeiten. Allerdings handelt es sich dabei meist um interne Projekte. Diese werden aber in der Leistungserfassung ähnlich wie Kundenprojekte gehandhabt – bloß, dass die erfassten Stunden eben für Vorgesetzte und nicht für Kunden relevant sind. Auf der anderen Seite gibt es zahlreiche User, die tatsächlich nie auf Projekte buchen. Wir schließen daraus, dass eine separate Erfassungsmaske für einige User wirklich hilfreich wäre. Das Kriterium ist aus unserer Sicht also erfüllt.«

Tim bedankt sich auch für diesen Beitrag und bittet Sarah gleich fortzufahren und ihre Ergebnisse vorzustellen.

### Walkthrough

»Wir haben zwei Annahmen überprüft. Wir wollten herausfinden, ob es grundlegende Vorbehalte gegen die Nutzung von Gruppenleistungen gibt und ob temporäre Projekte genutzt werden.

Hinweise auf Vorbehalte gegen Gruppenleistungen konnten wir nicht finden – im Gegenteil. Der Nutzen dieses Features wurde von allen befragten Usern sofort erkannt. Jedoch hatten sie teilweise etwas Mühe damit, das Feature anzuwenden: Sie haben diese Funktion schlicht nicht erwartet.

Die Möglichkeit, auf ein temporäres Projekt zu buchen, haben die Testpersonen bei der Projektauswahl erkannt. Sie haben, als sie kein regulär angelegtes Projekt gefunden haben, das temporäre Projekt genutzt. Aus unserer Sicht haben sich daher die Annahmen bestätigt.«

### GOMS-Analyse

Sarah fährt gleich fort: »Bei der GOMS-Analyse zeigt sich hingegen ein zweigeteiltes Bild. Verwenden die User Leistungsvorlagen, so sind sie fast 20 % schneller als mit der Erfassung in einer Tabellenkalkulation. Ohne Vorlagen dauert hingegen die Erfassung jedoch länger.«

Tim wendet sich an Sarah: »Wie interpretierst du dieses Ergebnis?«

»Wir haben uns dazu einige Gedanken gemacht. Es ist in unserem Konzept wichtig, dass User von einem Geschwindigkeitsvorteil beim Eintrag von Leistungen profitieren. Bei der Diskussion sind wir auf die Idee gekommen, keine allgemeinen Vorlagen anzubieten, sondern stattdessen eine Liste kürzlich verwendeter Leistungsbeschreibungen. So haben die User Zugriff auf eine Art Vorlage, deren Inhalt sie nur noch anpassen müssen – sie haben durch die einfache Selektion einer Leistungsbeschreibung einen Geschwindigkeitsvorteil. Auch müssen sie Vorlagen dann nicht selbst verwalten. Mit dieser Anpassung unserer ursprünglichen Idee, das zeigt uns auch das erste Feedback von Usern, können wir dann das Effizienz-Kriterium als erfüllt betrachten.«

Die Idee findet breiten Zuspruch. Tim hatte nach und nach die Ergebnisse in die Validierungsplanung (Abbildung 66) eingefügt.

*Abbildung 66: Validierungsplanung mit allen Ergebnissen*

| | Erfassung im Kalender fühlt sich effizient an | Erfassung von Gruppeneinträgen wird genutzt | Zentrale Dienste erfassen nicht auf Projekte | Übernahme von Kalenderdaten liefert gute Vorlagen | Nutzende buchen nicht auf temporäre Projekte |
|---|---|---|---|---|---|
| **Unsicherheit** | ●●● | ●● | ●●● | ●●● | ● |
| **Einfluss** | ●●● | ●● | ●●● | ●● | ● |
| **Methode** | GOMS-Analyse | Walkthrough mit passendem Szenario | Datenanalyse | Funktionaler Test | Walkthrough mit passendem Szenario |
| **Prototyp** | Wireframe | Wireframe | Kein Prototyp notwendig | Funktionaler Prototyp | Wireframe |
| **Stichprobe** | Keine Stichprobe notwendig | 5-6 Teammitglieder | Vollerhebung | Keine Stichprobe notwendig | 8-10 Teammitglieder |
| **Erfolgreich wenn** | GOMS-Analyse ergibt Vorteil für Kalender | Keine grundlegenden Bedenken | Mehr als 5% der Nutzenden haben keine Projekte | 90% der Kalendereinträge werden richtig erkannt | Es sind keine schweren Usability-Probleme erkennbar |
| **Aufwand** | ● | ● | ● | ●● | ● |
| **Ergebnis** | Kalender nur schneller, wenn Templates genutzt | Gruppeneinträge trotz Herausforderungen sehr geschätzt | 8% der Nutzenden buchen nicht auf Projekte | 30% der Kalendereinträge erkannt | Die allermeisten Nutzenden hatten keine Probleme |
| **Schlussfolgerung** | Ansatz mit Kalender wird weiter verfolgt | Design verbessern; Feature jedoch bestätigt | Es wird eine eigene Erfassungsmaske geplant | Feature wird für ein späteres Release geplant | Konzept wird beibehalten |

Tim stellt nun eine zentrale Frage: »Okay, brauchen wir dann jetzt nochmals eine Konzept-Iteration oder können wir uns direkt in Richtung Detaildesign bewegen?« Das Team ist einstimmig der Meinung, dass zum Detaildesign übergegangen werden kann.

## Ergänzende Hinweise

In diesem Kapitel haben wir einen Walkthrough zur Validierung der Annahmen durchgeführt, die unserem Konzept zugrunde liegen. Ein Walkthrough bei den Kunden von 4Service erwies sich hierzu als praktikabel – der mit der Einladung in ein Usability-Labor verbundene logistische Aufwand konnte so vermieden werden. Neben qualitativen Methoden können bei einer Validierung auch quantitative Methoden wie A/B-Tests zum Einsatz kommen. Bei einem solchen A/B-Test würde das Team ein Experiment durchführen, bei dem zwei Varianten von 4Service miteinander verglichen würden, um beispielsweise konkrete Informationen zu den quantitativen Größenordnungen gefundener Unterschiede zu gewinnen. Wir stellen ein solches Vorgehen im folgenden Kapitel vor.

## Zusammenfassung Validierung

Bei einer Validierung werden kritische Annahmen, auf denen ein Lösungskonzept fußt, unter Rückgriff auf Prototypen überprüft. Das von uns begleitete Team setzte verschiedene Methoden zur Validierung ein. So wurde ein technischer Prototyp erstellt und überprüft, eine Datenanalyse durchgeführt, ein Walkthrough mit Wireframes und eine GOMS-Analyse eingesetzt. Alle diese Validierungen nahmen direkten Bezug auf die im Kapitel Prototyping erstellte Planung zur Überprüfung der damit verbundenen Annahmen. Etwas ausführlicher haben wir die Planung, Durchführung und Auswertung des Walkthroughs vorgestellt und Checklisten zur Unterstützung zusammengefasst.

Auf der Basis der erhaltenen Ergebnisse des Validierungs-Workshops konnte das Team abschließend informiert über den Status der Annahmen entscheiden und das Konzept als robust für eine Umsetzung bewerten.
