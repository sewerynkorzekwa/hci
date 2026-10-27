# Ausblick: Delivery

Wir haben das Entwicklungsteam von 4Service nun durch insgesamt acht Workshops begleitet, haben Diskussionen zur Auswahl, Anwendung und Auswertung verschiedener Methoden aus dem UX Design verfolgt und stehen nun vor dem Erreichen eines wesentlichen Ziels: Die Vision für ein neues Modul zur Leistungserfassung ist erstellt und validiert und eine Roadmap zur Umsetzung des Moduls wurde aufgestellt.

In diesem Kapitel möchten wir den Leserinnen und Lesern (die das Buch tatsächlich bis hierhin gelesen haben) aufzeigen, wie die Arbeit unseres Teams weitergehen könnte – und wie der Übergang von der Vision über die Roadmap in die eigentliche Umsetzung aussehen könnte. Wie arbeiten die involvierten Stakeholder – insbesondere User Experience Designer und Developer – in der folgenden Projektphase zusammen? Bevor wir einen Ausblick hierauf geben, möchten wir zunächst den Zusammenhang von User Experience Design und agiler Entwicklung näher beleuchten.

---

## Theorie: User Experience Design und Agile Entwicklung

### User Stories

Im Kapitel »Workshop: Konzept« sind wir das erste Mal auf die Begriffe *User Story* und *User Story Maps* gestoßen. Es war unser Ziel, unter Rückgriff auf diese Artefakte eine möglichst vollständige Sicht über den geplanten Funktionsumfang der zukünftigen Leistungserfassung zu erhalten. User Stories beschreiben eine Funktionalität aus Nutzersicht und stellen damit ein kleines Inkrement einer Software dar.

Wir hatten bereits ein Formulierungsschema vorgestellt: »Als ›Persona‹ muss ich bei der ›Zielerreichung‹ eine ›Aufgabe‹ durchführen, weil ›Begründung‹.« Das vorgestellte Formulierungsschema ist *eine* Möglichkeit zur Notation von User Stories: Wichtig ist vor allem deren informelle Beschreibung aus Nutzersicht – hierdurch werden sie für alle Stakeholder nachvollziehbar. User Stories können informell als Elemente einer Checkliste für die Umsetzung gesehen werden, die im späteren Verlauf weiter diskutiert werden können. Im Kapitel »Workshop: Roadmap« haben wir User Stories priorisiert und daraus eine Roadmap abgeleitet. Die einzelnen User Stories wurden Releases zugeordnet. Diese Attribute können wir direkt auf den User Stories festhalten.

*Abbildung 86: User Stories zur Beschreibung von Produktinkrementen*

- Schichten: User Interface, Businesslogik, Datenbank
- Jede User Story ist ein vertikaler Schnitt durch alle drei Schichten.
- Eine Gruppe von User Stories bildet ein Release, alle User Stories zusammen das Produkt.

Bei der Planung der Umsetzung einer User Story ist eine Aufwandsschätzung hilfreich. Üblicherweise werden dazu *Story Points* verwendet. Story Points sind ein Maß für den zur Umsetzung der Story Card erwarteten Aufwand. Ergänzend kann auch der Sicherheitsgrad der angegebenen Schätzung festgehalten werden. In der Praxis verwenden Entwicklerinnen und Entwickler auch weitere Attribute: Manchmal wird die Rückseite von Story Cards dazu genutzt, Erfüllungskriterien zu beschreiben, die dann auch beim Testen umgesetzter Features zum Einsatz kommen können.

*Abbildung 87: Ausformulierte User Story Card*

| Element der Karte | Inhalt |
|---|---|
| Priorität der User Story | Hoch |
| Vorgesehenes Release | Release 1 |
| Personas / Begründung der User Story | »Als leistungserfassende Person möchte ich mich autorisieren, damit unberechtigte Personen keinen Zugriff auf meine Daten haben.« |
| Aufwand für die Entwicklung | 24, sicher |

*Abbildung 88: Rückseite einer User Story Card mit Erfüllungskriterien*

- Passwort und Nutzername müssen exakt übereinstimmen.
- Groß- und Kleinschreibung sind relevant.
- Nach drei Fehlversuchen wird der Zugang gesperrt.

User Stories können relativ große Inkremente einer Software beschreiben oder auch kleinere. Beschreiben sie umfassende Inkremente einer Software, so spricht man auch von *Epics*. Beispiele für Epics in unserem Fallbeispiel wären:

- Es können Leistungen erfasst werden
- Es können Spesen erfasst werden

User Stories können also auf unterschiedlichen Auflösungsgraden beschrieben werden. Betrachten wir das Beispiel der oben beschriebenen User Story für die Autorisierung:

*Abbildung 89: Aufteilung von User Stories*

- Ausgangs-Story (Hoch, Release 1, 24, sicher): »Als leistungserfassende Person möchte ich mich autorisieren, damit unberechtigte Personen keinen Zugriff auf meine Daten haben.«
- Aufgeteilt in drei User Stories (jeweils Hoch, Release 1):
  - »Als leistungserfassende Person möchte ich mich mit Benutzername und Passwort anmelden, damit unberechtigte Personen keinen Zugriff auf meine Daten haben.« (12, sicher)
  - »Als leistungserfassende Person möchte ich mein Passwort neu setzen können, damit die Sicherheit gewahrt bleibt.« (8, sicher)
  - »Als leistungserfassende Person möchte ich, dass der Zugang nach mehreren Fehlversuchen gesperrt wird, damit die Sicherheit gewahrt bleibt.« (4, sicher)

Im dargestellten Fall wurde die User Story *Autorisieren* in drei User Stories aufgeteilt, in denen die Besonderheiten oder Details bei der Anmeldung differenziert werden. Jeff Patton benutzt in seinem Buch »User Story Mapping« [Patton 2014] bei der Erläuterung von User Stories das Bild eines großen Steins, der zur weiteren Bearbeitung in drei kleinere Steine aufgeteilt wird.

### Sprints

Software wird heute immer seltener in großen monolithischen Blöcken implementiert – agile Softwareentwicklung greift auf kurze *Sprints* zurück, in denen eine überschaubare Anzahl von User Stories entwickelt werden. Ein Team nimmt sich einen begrenzten Zeitrahmen vor – üblicherweise sind dies zwei bis drei Wochen – und setzt in diesem eine zuvor ausgewählte Reihe von User Stories *fertig* um – *fertig* bedeutet, dass die entwickelten Softwareelemente in der Zielumgebung lauffähig und getestet sind. Am Ende eines Sprints werden die erreichten Ergebnisse präsentiert und im Team beurteilt. Typisch ist auch ein besonderes Ritual: In einer *Retrospektive* diskutiert das Team zum Abschluss über die positiven und auch verbesserungswürdigen Punkte des Vorgehens und der Zusammenarbeit im vergangenen Sprint.

Ein Sprint kann als eine Art Miniprojekt gesehen werden: Das Ergebnis eines Sprints muss jedoch kein Release sein. Liefert das Team nicht kontinuierlich aus, wird das Ergebnis intern präsentiert. Ein Release fertigzustellen, bedeutet dann, dass dessen Umsetzung in mehreren Sprints erfolgt.

Damit User Stories für einen Sprint eingeplant werden können, darf deren Umsetzung nicht zu viel Zeit in Anspruch nehmen. Würde beispielsweise die Umsetzung einer User Story vier Wochen dauern, so ließe sie sich nicht innerhalb eines Sprints realisieren. Ziel ist es daher, User Stories so weit aufzuteilen, dass sie typischerweise innerhalb von wenigen Tagen umgesetzt werden können.

Die Inhalte eines Sprints – die vorgesehenen User Stories – werden direkt vor dessen Start geplant. Nach Beginn eines Sprints wird der zur Bearbeitung vorgesehene Inhalt nicht mehr geändert. Eigene Sprint Planning Workshops stellen eine Art Sollbruchstelle dar, in denen sich ein Team orientiert und Inhalte neu priorisiert werden können. Kann in der Praxis eine User Story nicht vollständig umgesetzt werden, so wird sie, aufbauend auf dem erreichten Stand, für den nächsten Sprint wieder eingeplant.

*Abbildung 90: User Stories werden in Sprints umgesetzt.*

- Schichten: User Interface, Businesslogik, Datenbank
- Jede User Story ist ein vertikaler Schnitt durch alle drei Schichten.
- Wenige User Stories bilden einen Sprint, mehrere Sprints ein Release.

### Backlogs

Die Gesamtmenge aller User Stories, die für einen Sprint vorgesehen sind, wird als *Sprint Backlog* bezeichnet. Das gleiche Namensschema wird auch für ein Release *(Release Backlog)* und das geplante Produkt *(Product Backlog)* verwendet.

Innerhalb eines Backlogs werden User Stories nach ihrer Priorität sortiert. User Stories, die erst für spätere Sprints oder Releases geplant sind, müssen noch nicht feingranular aufgeteilt werden.

Die vorgestellte eindimensionale Sortierung der User Stories nach ihrer Priorität kann nicht immer sicherstellen, dass die hoch priorisierten User Stories im Zusammenhang ein inhaltlich sinnvolles Anwendungsszenario abbilden. Jeff Patton schlägt zur Lösung dieses Problems die Einführung einer *User Story Map* als zweidimensionales Backlog vor. In diesem Backlog wird, wie wir im Konzept-Kapitel des vorliegenden Buches aufzeigten, neben der Priorisierung auch die zeitliche Aufeinanderfolge von User Stories berücksichtigt. Bei der Sprint-Planung streben Teams danach, die einzelnen Sprints inhaltlich so zu organisieren, dass sich sinnvolle Szenarien ergeben. Die Ergebnisse von Sprints können dann aus User-Sicht jeweils als sinnvolle Einheiten getestet werden.

### UX Design und Entwicklung

Grundgedanke agiler Entwicklung ist, eine Software in Inkrementen zu entwickeln. Wir haben die sich hieraus ergebenden Vorteile bereits angesprochen – agile Softwareentwicklung wird heute als große Errungenschaft des modernen Software Engineering gesehen. Leider wurde bislang die Disziplin User Experience Design in den verschiedenen agilen Vorgehensmodellen eher unzureichend berücksichtigt. Ein inkrementelles Vorgehen kann – ohne geeignete Anpassungen – ein User-Experience-Team unter großen Zeitdruck stellen. Die Gründe hierfür sind vielfältig:

- UX-Design-Tätigkeiten, wie beispielsweise User Research oder Validierungen, können mehr Zeit in Anspruch nehmen, als es die kurze Dauer von Sprints oft gestattet. Geraten UX Designer dann unter Zeitdruck, können Mitglieder aus dem Entwicklungsteam nicht einfach für Designtätigkeiten eingeplant werden.
- Manche Schritte im UX Design lassen sich nicht oder nur schwer auf Inkremente beschränken: Wenn beispielsweise in einer Contextual Inquiry ein Arbeitsablauf beobachtet wird, so umfasst diese Beobachtung die Gesamtheit *aller* Aspekte – es lassen sich hierbei nicht nur jene isolieren, die für einen Sprint relevant sind.
- Zwar wird der Entwicklungsaufwand in User Stories abgeschätzt – eine eigene Schätzung des Aufwands notwendiger Designanstrengungen wird indes vielfach außer Acht gelassen.

Zwischenzeitlich wurden verschiedene Lösungsansätze diskutiert, die diese Herausforderungen in der Zusammenarbeit zwischen Personen aus der Entwicklung und dem User Experience Design adressieren. Nachfolgend stellen wir vier dieser Ansätze vor.

### Dual Track Agile

In unserem Projektbeispiel waren die UX Designer gut vorbereitet. Sie haben vor der technischen Realisierung bereits User Research durchgeführt, eine Vision entworfen und diese auch validiert. Es entstand ein tragfähiges Konzept, das nun auf die konkret geplanten User Stories des Sprint Backlog angewandt werden kann.

Wir haben es hier, wie in Abbildung 91 verdeutlicht wird, im Grunde mit zwei parallelen Tracks, *Envisioning* und *Delivery*, zu tun. In beiden Tracks arbeiten interdisziplinäre Teams zusammen. Im ersten Track *(Envisioning)* geht es um die Entwicklung einer Produktvision, im zweiten Track *(Delivery)* um das Detaildesign des User Interface und die Umsetzung der bereits definiert vorliegenden und priorisierten User Stories. Diese beiden Tracks werden im Verlauf der Produktentwicklung so weitergeführt.

*Abbildung 91: Dual Track Agile*

- Envisioning: Understand, Explore → Product Backlog → Sprint Backlog
- Delivery: Sprint 0, Sprint 1, Sprint 2, Sprint 3, Sprint 4 (zusammen ein Release)
- Der Envisioning-Track läuft parallel zur Delivery weiter.

### Triple Track Agile

Auch mit einer vorgängig erarbeiteten und validierten Vision kann sich ein Zeitrahmen schnell als sehr eng erweisen. Um dies zu konkretisieren: In einem Sprint von zwei Wochen bleibt für ein UX-Team gerade einmal zwei bis drei Tage Zeit, gestalterische Vorgaben für ein User Interface auszuarbeiten – aus logischen Gründen stellen diese eine Voraussetzung für die Umsetzung dar und müssen zeitlich vorgelagert sein. In der Praxis entscheiden sich viele Teams dafür, ein User Interface jeweils einen Sprint vorher zu gestalten (auch *One Sprint Ahead* oder *Sprint Zero* genannt, siehe unten). Dadurch dehnt sich der Zeitrahmen von zwei bis drei Tagen auf die volle Länge eines Sprints aus.

Wenn wir dieses Vorgehen betrachten, so können wir drei parallele Tracks differenzieren: Im ersten Track *(Envisioning)* wird ein grobes Konzept für das nächste umfassende Produktinkrement entworfen, im zweiten Track *(Delivery: UI Design)* werden die Vorgaben für den nächsten Sprint entworfen und im dritten Track dieser Sprint umgesetzt *(Delivery: Implementierung)*. In der Praxis unterstützen UX Designer oft auch im dritten Track die Umsetzung und klären Detailfragen oder erstellen fehlende Artefakte wie Icons oder Illustrationen.

### Sprint Zero

Manche vorbereitenden Tätigkeiten beziehen sich nicht ausschließlich auf einen einzelnen Sprint, sondern haben Konsequenzen für ein oder sogar mehrere Releases. Als Beispiel kann die Festlegung einer technischen Architektur durch ein Entwicklungsteam oder die Definition des übergreifenden visuellen Erscheinungsbilds durch ein Designteam genannt werden. Dann würde das Team einen sogenannten *Sprint Zero* (auch als *Sprint 0* bekannt) einplanen. In diesem werden übergreifende Grundlagen eines Projekts definiert.

*Abbildung 92: Triple Track Agile*

- Envisioning: Understand, Explore → Product Backlog → Sprint Backlog; läuft parallel weiter
- Delivery – UI Design: Für Sprint 1, Für Sprint 2, Für Sprint 3, Für Sprint 4
- Delivery – Implementierung: Sprint 1, Sprint 2, Sprint 3, Sprint 4 (jeweils um einen Sprint versetzt nach dem zugehörigen UI Design)
- Die Sprints bilden zusammen ein Release.

*Abbildung 93: Triple Track Agile mit Sprint 0*

- Envisioning: Understand, Explore → Product Backlog → Sprint Backlog; läuft parallel weiter
- Delivery – UI Design: Sprint 0 und für Sprint 1, Für Sprint 2, Für Sprint 3, Für Sprint 4
- Delivery – Implementierung: Sprint 0 (parallel zu »Sprint 0 und für Sprint 1«), Sprint 1, Sprint 2, Sprint 3, Sprint 4
- Die Sprints bilden zusammen ein Release.

### Dual Track Sprint Planning

In vielen Teams wird, wie oben angesprochen, lediglich der Realisierungsaufwand zur Umsetzung vorliegender User Stories aus Sicht der Softwareentwicklung geschätzt. Die hierzu notwendigen Designaufwände bleiben unberücksichtigt. Dieser Unzulänglichkeit kann durch getrennte Schätzungen beider Aufwände begegnet werden: Aufwände sowohl für die Entwicklung als auch für das Design der User Stories werden jeweils geschätzt und Story Points für Design- und Entwicklungssprints vergeben. Dem zusätzlichen Schätzaufwand bei der Erstellung der Story Cards steht eine größere Planungssicherheit bei der Durchführung der Sprints gegenüber.

*Abbildung 94: Um Designaufwände ergänzte User Story Card*

| Element der Karte | Inhalt |
|---|---|
| Priorität / Release | Hoch / Release 1 |
| Text | »Als leistungserfassende Person möchte ich mich anmelden, damit unberechtigte Personen keinen Zugriff auf meine Daten haben.« |
| Aufwand für das UX Design (links) | 8, sicher |
| Aufwand für die Entwicklung (rechts) | 24, sicher |

---

## Sprint Planning Workshop

Wie könnte ein Sprint Planning Workshop für unser Team aussehen? Zum Abschluss möchten wir einen Ausblick geben: Das gesamte Team nimmt an dem Workshop teil. Für den initialen Sprint Planning Workshop bietet es sich an, etwas mehr Zeit einzuplanen. Der Workshop beginnt mit einem Überblick: Andrea, die Produktmanagerin von 4Service, präsentiert die wichtigsten Ergebnisse der Envisioning-Phase. Sie erklärt die Businessziele, die mit der neuen Version adressiert werden sollen, sowie die Chancen, die aufgrund der User Research ersichtlich wurden, und stellt den gewählten und validierten Lösungsansatz vor. Zum Abschluss erläutert sie auch die erarbeitete Roadmap mit den geplanten Releases.

Peter, der Entwicklungsleiter, übernimmt als Nächster und konzentriert sich in seinen Ausführungen auf die Darstellung des ersten Release. Er präsentiert die von ihm erarbeitete User Story Map, die er auf die für das erste Release geplanten User Stories reduziert hat.

*Abbildung 95: Reduzierte User Story Map für das erste Release*

Epic: Leistungen erfassen

| Leistungserfassung starten | Überprüfen der erfassten Leistungen | Leistung erfassen | Leistung ändern | Leistungen freigeben |
|---|---|---|---|---|
| Anmelden | Aktuelle Woche anzeigen | Leistung manuell erfassen | Leistung löschen | Leistungen freigeben |
| | Woche wechseln | Abschreiben einer Leistung beantragen | Leistungstext oder Projekt ändern | |
| | Termine anzeigen | | Leistungszeitpunkt und -dauer ändern | |
| | Wochen- und Tagessummen überprüfen | | | |
| | Überstunden überprüfen | | | |

Peter fasst zusammen: »Das Release ist überschaubar, wir haben uns in der Roadmap bewusst auf die essenziellen Features für das erste Release konzentriert. Unser Ziel ist es nun, die User Stories – wo dies notwendig und sinnvoll ist – weiter zu verfeinern. Ich schlage vor, dass wir zunächst alle User Stories des geplanten ersten Release reviewen, gegebenenfalls weiter aufteilen und auf der so entstandenen Grundlage den Aufwand für das Release schätzen. Bei der Aufteilung sollten wir darauf achten, dass der Aufwand zur Umsetzung der User Stories den Umfang von zwei Wochen nicht übersteigt. Der Aufwand darf gerne auch geringer sein.«

Tim unterstützt Peter und ergänzt: »Wir sollten die User Stories smart aufteilen – sie sollten in ihrem Zusammenspiel jeweils lauffähige Funktionsbündel bereitstellen, die inhaltlich sinnvoll sind. Anhand der Leistungserfassung möchte ich euch ein Beispiel vorstellen. Eine allzu grobe Aufteilung der User Stories in ›Frontend für Leistungserfassung‹ und ›Backend für Leistungserfassung‹ wäre selbstverständlich nicht zielführend. Damit lägen auch keine User Stories vor – nicht allein wegen des massiven Umfangs, sondern eben auch weil diese Blöcke jeweils für sich genommen keine Produktinkremente mehr darstellen, die Usern einen potenziellen Nutzen liefern. Angemessen wäre hingegen eine Aufteilung in ›Leistung mit Titel erfassen‹ und ›Leistung mit Details erfassen‹. Im ersten Fall brauchen wir beispielsweise kein Bemerkungsfeld, hier haben wir eine sehr kompakte User Story.«

Andrea beginnt damit, jede einzelne User Story kurz vorzustellen. Nicht nur die Mitglieder des Entwicklungsteams stellen immer wieder herausfordernde Fragen. In einigen Fällen führen sie zur weiteren Aufteilung einzelner User Stories. Diese werden anschließend neu priorisiert und entsprechend vertikal im Board positioniert.

Der nächste Schritt ist besonders spannend: Nun werden die Aufwände geschätzt. In unseren Projekten haben wir gelernt, dass es bei diesen Schätzungen weniger die konkreten quantitativen Punktlandungen – beispielsweise in absoluten Aufwandsschätzungen wie etwa Personentagen – sind, die einen Workshop weiterbringen, sondern eher die Bestimmung der relativen Aufwände im Vergleich einzelner User Stories. So sieht unser Team beispielsweise das »Neu Setzen eines Passworts« als doppelt so aufwendig in der Umsetzung wie den Prozess »Anmelden« an. Story Points eignen sich recht gut für diese Schätzungen: Das Team einigt sich für das Anmelden auf 10 Punkte und vergibt für das »Neu Setzen eines Passworts« entsprechend 20 Punkte.

*Abbildung 96: User Story Map für das erste Release mit aufgeteilten User Stories und Schätzung für Design (links) und Entwicklung (rechts) auf den Karten*

Epic: Leistungen erfassen (Angaben je Karte: Design / Entwicklung)

| Leistungserfassung starten | Überprüfen der erfassten Leistungen | Leistung erfassen | Leistung ändern | Leistungen freigeben |
|---|---|---|---|---|
| Anmelden (5 / 10) | Aktuelle Woche anzeigen (80 / 80) | Leistung mit Titel erfassen (5 / 10) | Leistungsdetails ändern (40 / 80) | Ganze Woche freigeben (5 / 20) |
| Zugang sperren (10 / 20) | Woche vor- und zurückspringen (5 / 10) | Leistung mit Details erfassen (10 / 20) | Projektzuordnung einer Leistung ändern (10 / 20) | Tag freigeben (5 / 20) |
| Passwort neu setzen (20 / 20) | Wochen- und Tagessumme anzeigen (5 / 20) | Abschreiben einer Leistung beantragen (20 / 20) | Verlängern oder verkürzen (20 / 20) | Direkt einzelne Leistung freigeben (5 / 20) |
| | Gesamte Überstunden anzeigen (5 / 10) | Leistung kopieren (5 / 10) | Löschen einer einzelnen Leistung (5 / 10) | |
| | Wochenüberstunden anzeigen (5 / 20) | | Verschieben einer Leistung (5 / 40) | |
| | Bestimmte Woche wählen (30 / 40) | | Projektzuordnung mehrerer Leistungen (10 / 20) | |
| | | | Löschen mehrerer Leistungen (10 / 20) | |

Sind die Aufwände für User Stories geschätzt, kann mit der Auswahl für den ersten Sprint begonnen werden. Tim hat eine klare Vorstellung und präsentiert sie dem Team. Er argumentiert für die Umsetzung eines recht einfachen, aber vollständigen Szenarios. Er pinnt die Karten für seinen Vorschlag für den ersten Sprint an das Whiteboard:

*Abbildung 97: Mögliche Planung für den ersten Sprint*

- User Story Map wie in Abbildung 96; eine Linie »Sprint 1« trennt die oberste Kartenreihe ab.
- Oberhalb der Linie (Sprint 1): Anmelden (5 / 10), Aktuelle Woche anzeigen (80 / 80), Leistung mit Titel erfassen (5 / 10), Leistungsdetails ändern (40 / 80), Ganze Woche freigeben (5 / 20)
- Alle übrigen Karten liegen unterhalb der Linie.

Inhaltlich findet Tims Vorschlag schnell Zustimmung – wichtig ist jedoch die Klärung des Sprint-Umfangs: Ist dieser realistisch bemessen? Unter Rückgriff auf das Konzept der Story Points können wir konkret fragen, wie viele Story Points durch das Entwicklungs- und Designteam in einem zweiwöchigen Sprint tatsächlich geleistet werden können. Wir sprechen hier von der erreichbaren *Velocity* als Maß für die Arbeitsmenge, die ein Team im Verlauf eines Sprints bewältigen kann. Das von uns begleitete Team sieht 130 Punkte für die Entwicklung und 110 Punkte für das Design als realistisch umsetzbar an. Eine kurze Inspektion der von Tim vorgeschlagenen Inhalte zeigt einen größeren erwarteten Aufwand für den ersten Sprint. Nach kurzer Diskussion verständigt sich das Team darauf, das »Ändern der Leistungsdetails« im ersten Sprint wegzulassen. Das für die Umsetzung vorgesehene Szenario bleibt damit inhaltlich dennoch abgeschlossen.

*Abbildung 98: Reduzierte User Story Map für das erste Release mit passender Planung für den ersten Sprint*

- Wie Abbildung 97, jedoch ist »Leistungsdetails ändern« (40 / 80) unter die Linie verschoben.
- Sprint 1: Anmelden (5 / 10), Aktuelle Woche anzeigen (80 / 80), Leistung mit Titel erfassen (5 / 10), Ganze Woche freigeben (5 / 20)

---

## Weitere Planung

In den vergangenen Kapiteln haben wir die Arbeit eines interdisziplinären Teams in einem kollaborativen Prozess miterleben können – vom initialen Ausgangspunkt, der in einem Proto-Problem Statement formuliert wurde, bis hin zu ersten Schritten der implementationstechnischen Realisierung eines validierten Konzepts. Wir haben die Bedeutung von Annahmen (und die Notwendigkeit ihrer empirischen Überprüfung) ebenso diskutiert wie die verbindende Rolle von Ideation als Brücke von User Research zu konzeptionellen Aktivitäten. Vor allem aber haben wir zu verdeutlichen versucht, wie bedeutsam die erfolgreiche Kollaboration von Stakeholdern in Workshops für die Entwicklung innovativer Produkte und Services ist. Das orchestrierende Vorgehensmodell dieser Kollaboration haben wir Collaborative UX Design 2.0 genannt. Das Team um Tim und Sarah wird an der Leistungserfassung von 4Service weiterarbeiten – der Plan für die kommenden Sprints ist bereits sorgfältig ausgearbeitet.

*Abbildung 99: Planung und Vorbereitung von Sprints*

| Phase | Aktivitäten |
|-------|-------------|
| Sprint 0 | Begutachten; Anpassung der Screens (Release 1); Varianten Visuelle Gestaltung; Fertigstellung Visuelle Gestaltung |
| Vorbereitung Sprint 1 | Anpassung der Screens (Sprint 1); Zusätzliche Wireframes; Spezifikation aller visuellen Elemente |
| Vorbereitung Sprint 2 | Anpassung der Screens (Sprint 1); Zusätzliche Wireframes; Spezifikation aller visuellen Elemente |
| Während Sprint 1 | Vorbereiten und Durchführen von Usability-Tests |

---

> **»Wir sollten uns vornehmen, unsere Ideen nicht bestätigen zu wollen, sondern nach Hinweisen zu suchen, sie zu widerlegen.«**
