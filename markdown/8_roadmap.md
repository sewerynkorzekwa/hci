# Workshop: Roadmap

Im vorangegangenen Validierungs-Workshop konnten zentrale Aspekte der entwickelten Vision in ihrer erwarteten Bedeutung gestützt werden. Ziel des nun folgenden Roadmap-Workshops ist es, die erkundeten Konzeptideen Realität werden zu lassen und in eine Releaseplanung zu gehen.

## Überblick

In diesem Workshop erarbeitet das von uns begleitete Team eine Roadmap zur Umsetzung der Produktvision der neuen Leistungserfassung von 4Service. In einer Roadmap werden die unterschiedlichen Releases definiert, die zur vollständigen Umsetzung der Produktvision notwendig sind.

**Ziel**
- Festlegung eines MVP (Minimum Viable Product) und möglicher Folgereleases, Definition von Metriken zur Validierung von Releases

**Teilnehmende**
- Projektteam

**Hauptergebnis**
- Roadmap, Metriken-Map

**Vor dem Workshop**
- Vorliegen eines validierten Konzepts

**Ablauf**
- Priorisieren von Produktfeatures in einer Priorisierungsmatrix
- Erstellung einer Roadmap
- Definition einer Metriken-Map

**Nach dem Workshop**
- Umsetzung (siehe Kapitel »Ausblick: Delivery«)

Auf dem Weg zur Roadmap müssen zunächst die essenziellen Features der Vision gegenübergestellt und in ihrer Bedeutung priorisiert werden. Hierbei sind verschiedene, einander teilweise widersprechende Aspekte abzuwägen: Aspekte der User Experience und der erwartete Nutzen für User, wirtschaftliche Rahmenbedingungen, Fragen zur technischen Machbarkeit und dem erforderlichen Realisierungsaufwand. Für diesen Zweck hat sich der Einsatz einer *Priorisierungsmatrix* als sehr hilfreich erwiesen. Wir stellen die hinter einer Priorisierungsmatrix stehenden Überlegungen in diesem Kapitel vor. Liegt ein priorisiertes Feature-Set für eine Produktvision vor, so bieten sich *User Story Maps* als belastbare Basis für die Releaseplanung in einer Roadmap an.

An einem Workshop zur MVP-Planung nimmt typischerweise das gesamte Projektteam teil. Kann die Auftraggeberin oder ihre Vertretung selbst nicht teilnehmen, so sollten die mit dem Release eines Produkts verbundenen Businessziele im Vorfeld des Workshops herausgearbeitet und gegeneinander gewichtet werden.

## Theorie: Continuous Delivery und MVP

Traditionelle Ansätze der Softwareentwicklung resultieren typischerweise in einer (sehr) überschaubaren Anzahl von Releases pro Zeitabschnitt, beispielsweise einem Jahr.

Mit dem Begriff *Continuous Delivery* sprechen wir ein Vorgehen an, bei dem ein Produktanbieter nicht jährlich ein oder zwei Releases, sondern in fortlaufender Folge jeweils eine Vielzahl kleiner, um neue Features erweiterte Releases lanciert.

Das mit Continuous Delivery verbundene Vorgehen bietet offensichtliche Vorzüge:

- Durch inkrementelle Erweiterungen um einzelne Features kann ein Produkt schneller auf dem Markt angeboten werden. Wartezeiten auf ein umfassendes Produktrelease mit einer Vielzahl neuer Features sind nicht mehr notwendig.
- Die Marktwirkung von Features lässt sich leichter »isolieren« und damit kontrollierter überprüfen als mit komplexen Releases, die jeweils Bündel neuer Merkmale mit sich bringen. Der Produkterfolg (oder das Ausbleiben desselben) kann, bei ansonsten gleichen Marktbedingungen, auf diese Weise zuverlässiger auf Änderungen im Feature-Set eines Produkts zurückgeführt werden.
- User können neue Releases deutlich einfacher absorbieren, wenn sich Produkte nicht gleich in verschiedenen Attributen ändern – die Gefahr, durch eine Fülle neuer Features in umfassenden Releases Nutzende zu überfordern, ist geringer. Durch die höhere Frequenz von kleinen Neuerungen entsteht außerdem der positive Eindruck einer fortlaufenden Weiterentwicklung eines Produkts.
- Die mit dem Release eines neuen Produkts verbundenen Risiken sind geringer. Fehlinvestitionen lassen sich früher erkennen: Merkmalskombinationen mit geringer Akzeptanz können schneller überarbeitet werden.

*Abbildung 67: Traditionelle Softwareentwicklung*
- Schichten User Interface, Businesslogik, Datenbank; ein Feature durchläuft alle Schichten; viele Features werden gebündelt in wenigen großen Releases (Release, Release) ausgeliefert.

Die mit Continuous Delivery verbundenen Implikationen haben deutliche Auswirkungen auf unsere Arbeit als User Experience Designer. Wir begleiten die Produktentwicklung über mehrere Releases hinweg und überprüfen den Erfolg der einzelnen, jeweils vergleichsweise kleine(re)n Produktinkremente. Wir bekommen kontinuierliches Feedback durch Daten, die den realen Einsatz eines Produkts reflektieren. Bei Modellen der menschzentrierten Gestaltung vergeht typischerweise nach der Spezifikation der einem Produkt zugrunde liegenden Designentscheidungen eine recht lange Zeit bis zur Fertigstellung von dessen Implementierung und dem Release. Wir haben hiervon in der Einleitung des Buches als *Delayed Feedback Problem (DFP)* gesprochen. Im Unterschied hierzu bleiben UX Designer bei Continuous Delivery fortlaufend in Kontakt mit einem Produkt und den Marktreaktionen auf dieses Produkt.

Natürlich können wir in der Praxis kaum ein Produkt mit *genau* einem Feature als Release auf den Markt bringen und dieses dann schrittweise, Feature um Feature, erweitern. Bei der Neuentwicklung von Produkten ist eine erste kritische Masse an relevanten Merkmalen und Funktionalitäten notwendig, damit das Produkt überhaupt seinen Nutzen entfalten kann. Doch den mit Continuous Delivery verbundenen Ansatz können wir auch hier anwenden: Wir suchen nach der kleinstmöglichen Menge an Features, die für Nutzende einen realen Mehrwert bedeuten und uns gleichzeitig wesentliche Einsichten zur Fortentwicklung des Release bietet. Einen solchen Releasekandidaten bezeichnen wir als *Minimum Viable Product (MVP)*.

*Abbildung 68: Continuous Delivery*
- Schichten User Interface, Businesslogik, Datenbank; zunächst ein MVP mit wenigen Features über alle Schichten, danach viele kleine Releases (Release, Release, …) mit jeweils einzelnen Features.

Diesem von Eric Ries propagierten Vorgehen wurde in den letzten Jahren mit einiger Kritik begegnet. Ein MVP, so wurde argumentiert, sei für Nutzende nicht attraktiv. Der per Definition geringere Funktionsumfang eines MVP hinterlasse einen unzulänglichen ersten Eindruck und reduziere daher die Erfolgschancen zukünftiger Produktreleases. Soll dieser Gefahr entgegengetreten werden, so die Argumentation, ist statt eines MVP eben doch ein recht umfassendes Release nötig: Die einem MVP unterstellten Vorzüge ließen sich in der Praxis daher nicht umsetzen.

Aus Sicht der Produktentwicklung bietet ein MVP wertvolle Erkenntnisse aus frühem Marktfeedback bei vergleichsweise geringem Risiko – aus Perspektive von Nutzenden könnte der eher geringe Funktionsumfang eines MVP jedoch enttäuschend sein. Hier liegt offensichtlich ein Zielkonflikt vor. Wie aber können wir den mit einem MVP verbundenen Kompromiss zwischen Funktionalität und Aufwand angemessen wählen? Wie lässt sich die Funktionalität bei der Definition eines MVP einschränken, ohne gleichzeitig den Nutzen für User des MVP infrage zu stellen? Schauen wir uns hierzu einige Möglichkeiten an:

- *Einschränkung der unterstützten Zielgruppe:* Wir könnten uns auf lediglich eine Zielgruppe fokussieren und zunächst alle für andere Zielgruppen relevanten Funktionalitäten ignorieren. Wählen wir die Zielgruppe hinreichend eng, so können wir den Funktionsumfang oft erheblich limitieren, ohne den Nutzen eines MVP zu verlieren.
- *Einschränkung der unterstützten Workflows:* Wir könnten uns lediglich auf die Unterstützung (einer kleinen Menge) ausgewählter Workflows konzentrieren und diese optimieren – für die nicht berücksichtigten Fälle könnte hingegen ein Vorgängerprodukt weiterhin zum Einsatz kommen. Ein Beispiel verdeutlicht das Gesagte: Bei einer Bank soll ein bestehendes System zur Unterstützung der Kundenberatung abgelöst werden. Das Entwicklungsteam entscheidet sich in einem ersten Schritt dazu, lediglich ein neues Einstiegsportal anzubieten: In diesem kann Beratungspersonal effizient nach Kunden suchen. Ist ein Kunde gefunden, wird der Kundenberater zum entsprechenden Modul der Vorgängerapplikation weitergeleitet.
- *Manuelle Abwicklung der Leistung mit einer »Fassade«:* Wir könnten die eigentliche Leistung einer Applikation, die im ausgebauten Stadium automatisiert umgesetzt sein wird, zumindest in Teilen manuell erbringen. Nutzende müssen hierüber nicht zwangsläufig informiert werden: Für sie wird bis zur Fertigstellung entsprechender Funktionen eine professionelle Fassade aufrechterhalten. Wir haben diesen Ansatz schon bei Prototypen betrachtet – wir nennen den Ansatz *Concierge-Experiment* (siehe Kapitel: »Workshop: Prototyping«).
- *Selten verwendete Funktionen, die nicht unbedingt notwendig sind, werden zunächst nicht berücksichtigt.* Nutzende erhalten eine auf das Wesentliche reduzierte Version einer Applikation, mit der sie ihre häufigsten Anliegen in überzeugender Art und Weise lösen können. Das Pareto-Prinzip (80-zu-20-Regel) liefert eine gute Argumentation für diese Fokussierung.

Bei keiner der vier Vorgehensweisen müssen sich zwangsläufig für die beabsichtigte Nutzergruppe wesentliche Einschränkungen ergeben. Auch im Beispiel des Kundenportals sind Nutzende im Vergleich zur aktuellen Lösung deutlich bessergestellt: Sie erhalten zusätzlich zur bestehenden Lösung eine stark verbesserte Einstiegsfunktion.

## Priorisierungsmatrix

Das Projektteam von 4Service ist fast am Ziel angelangt. Nun kann die Planung zur technischen Umsetzung des zukünftigen Moduls zur Leistungserfassung von 4Service initiiert werden. Tim resümiert: »Wir dürfen wirklich zufrieden mit den Ergebnissen zur Validierung unseres Konzepts sein. Wir haben nun eine klare Vorstellung von unserem zukünftigen Produkt: Als Nächstes geht es um die Entscheidung, welche Features wir zuerst in einem neuen Release von 4Service umsetzen. Wir brauchen möglichst früh Feedback aus dem produktiven Einsatz – über die Grenzen von Rückmeldungen aus Walkthroughs hatten wir ja bereits gesprochen.«

Andrea stimmt Tim zu: »Wenn wir nicht alle bislang diskutierten Features gleichzeitig bereits im ersten Release ausliefern, können wir gezielter auf Feedback des Markts reagieren. Wir sollten den Funktionsumfang von Releases so wählen, dass die Wirkung der Features für uns möglichst nachvollziehbar ist. Das ist eine Herausforderung: Wie können wir ein Release bestimmen, das genau die wesentlichen neuen Funktionen für die Leistungserfassung aufweist?« Das Team ist mittlerweile gut eingespielt und durch eine gemeinsame Vorstellung über das Vorgehen im Projekt verbunden.

Sarah macht einen Vorschlag zur Vorgehensweise: »Wir müssen zwei Dinge festlegen: Zum einen benötigen wir eine Roadmap. In der Roadmap definieren wir, wann wir welche Features für welche User in einem Release auf den Markt bringen. Als Nächstes benötigen wir aussagekräftige Metriken, die uns eine Quantifizierung des Markterfolgs unseres Release erlauben. Wenn wir schon Feedback bekommen, dann sollten wir auch wissen, wie wir es interpretieren.«

Tim stimmt Sarah zu: »Damit wir eine belastbare Roadmap informiert erarbeiten können, müssen wir wissen, welche Produktmerkmale oder Features insgesamt den höchsten Nutzen liefern – und mit welchem Aufwand ihre Umsetzung verbunden ist. Dabei hilft uns eine *Priorisierungsmatrix:* In ihr werden die Einflüsse von Nutzerzielen, wirtschaftlichen Zielen und Umsetzungskosten berücksichtigt und gegeneinander abgewogen. Für die Erstellung einer Priorisierungsmatrix ist insbesondere der Input unserer Auftraggeberin absolut essenziell. Ihr Beitrag ist für diesen Schritt daher unverzichtbar.«

Tim hat auch diesen Workshop bereits vorbereitet und Karten mitgebracht, die mit den ursprünglich formulierten Projektzielen beschriftet sind. Die Projektziele hat er der Formulierung des *Problem Statement* entnommen. Mit dem 4Service-Projekt verfolgt das Management der 4Service AG drei wesentliche Ziele:

- Die Fakturierbarkeit der Leistungen von Mitarbeitenden soll erhöht werden.
- Die Anzahl von Kundenreklamationen wegen falscher Rechnungen soll reduziert werden.
- Die notwendige Zeit zur Leistungserfassung soll verkürzt werden.

Auf die Erreichung dieser Ziele wurden die Features des validierten Prototyps ausgerichtet.

Tim rekapituliert nochmals die User Story Map, die das Team in den vergangenen Wochen entwickelt hat:

*Abbildung 69: Nach Validierung aktualisierte User Story Map der zukünftigen Leistungserfassung*

Aktivität: Leistungen erfassen

| Leistungserfassung starten | Überprüfen der erfassten Leistungen | Leistung erfassen | Leistungsvorlagen verwalten | Teammitglieder hinzufügen | Leistung ändern | Leistungen freigeben |
|---|---|---|---|---|---|---|
| Anmelden | Aktuelle Woche anzeigen | Leistung manuell erfassen | Leistung in Vorlage übernehmen | Leistungen von Teammitgliedern überprüfen | Leistung löschen | Leistungen freigeben |
| | Woche wechseln | Leistung mittels Vorlage erfassen | Leistung aus Vorlage löschen | Leistungen von Teammitgliedern übernehmen | Leistungstext oder Projekt ändern | |
| | Termine überprüfen | Leistung aus Terminen übernehmen | | Teammitglieder aus Leistung entfernen | Leistungszeitpunkt und -dauer ändern | |
| | Gemeinsame Leistungen überprüfen | Temporäre Leistung erfassen | | Teammitglieder zu Leistung hinzufügen | | |
| | Wochen- und Tagessumme überprüfen | Projektbudget überprüfen | | | | |
| | Urlaubsguthaben überprüfen | Abschreiben einer Leistung beantragen | | | | |
| | Überstunden überprüfen | | | | | |

Anschließend beginnt Tim damit, die in der User Story Map angesprochenen zukünftigen Features herauszuarbeiten. Diese will er nachfolgend gemeinsam mit dem Team priorisieren. Er identifiziert folgende Themen:

- *Kürzlich verwendete Leistungen übernehmen:* Damit spricht Tim die Möglichkeit an, Leistungen aus einer Liste kürzlich verwendeter Leistungen mittels *Drag & Drop* auf die Terminübersicht übertragen zu können.
- *Übernahme von Terminen:* Leistungen sollen direkt aus dem Terminkalender übernommen werden und so den Aufwand beim Eintragen verringern.
- *Gruppenleistungen:* Diese Funktion ermöglicht es Nutzenden, unter Kolleginnen und Kollegen abgestimmte Leistungseinträge zu erfassen.
- *Temporäre Projekte:* Mit dieser Funktion können Leistungen auch dann erfasst werden, wenn das eigentliche Projekt, auf das gebucht werden soll, in 4Service noch nicht angelegt ist.
- *Projektbudget:* Dieses Feature zeigt bei der Leistungserfassung direkt das aktuell noch vorhandene Projektbudget an.

Die Grundlage dieser Funktionen hatte das Team in den vergangenen Workshops erarbeitet, eingehend diskutiert, prototypisch umgesetzt und schließlich validiert. Tim platziert nun beschriftete Karten mit den Businesszielen und den weiteren angesprochenen Themen auf der Matrix an der Wand. Als Managementziele hat er »Mehr verrechenbare Stunden«, »Reduktionen von Reklamationen« und »Effiziente Erfassung« in die erste Spalte der Priorisierungsmatrix gepinnt. Er baut die Struktur der Matrix sukzessive auf und ergänzt Spalten und Zeilen zur Gewichtung von Nutzerzielen und zum technischen Umsetzungsaufwand (Abbildung 70).

*Abbildung 70: Vorlage für die Priorisierungsmatrix*
- Spalten: Gewichtung der Businessziele | Temporäre Projekte | Gruppenleistungen | Übernahme von Terminen | Kürzlich verwendete Leistungen | Projektbudget
- Zeilen: Gewichtung der Nutzerziele | Mehr verrechenbare Stunden | Reduktion von Reklamationen | Effiziente Erfassung | Zwischensumme | Aufwand | Gesamtpunkte

Tim erläutert die Ideen hinter einer Priorisierungsmatrix: »Mit der Spalte *Gewichtung der Businessziele* wird später das Management die Businessziele priorisieren können. Die Zeile *Gewichtung der Nutzerziele* dient der Festlegung des erwarteten Einflusses der Funktionen auf das Nutzungserlebnis: Wie stark unterstützt eine Funktion Nutzende bei der Erreichung ihrer Ziele? In der Zeile *Aufwand* tragen wir eine Abschätzung des Aufwands zur technischen Realisierung der Funktionen ein. Die Zeilen mit »Zwischensumme« und »Gesamtpunkte« brauchen wir später für die Berechnung der Gesamtbewertung – dies erläutere ich genauer, wenn wir diese Matrix gleich gemeinsam ausfüllen.«

Mittlerweile ist auch die Vertretung des Managements eingetroffen, Tim bittet sie um ihre Unterstützung: »Wir haben die Erstellung einer Priorisierungsmatrix zur Umsetzung von 4Service vorbereitet. Ich möchte Sie gerne bitten, die Businessziele, die Sie mit der neuen Version von 4Service verfolgen, zu gewichten. Damit Ihre Entscheidungen für uns alle sichtbar sind, vergeben Sie bitte gelbe Punkte für Ihre Einschätzung. Wir möchten es einfach halten: Drei Punkte stehen für die höchste und ein Punkt für die niedrigste Priorität.« Nach einer kurzen Diskussion liegt die Bewertung des Managements vor (Abbildung 71).

*Abbildung 71: Priorisierungsmatrix mit Gewichtungen*

| | Gewichtung der Businessziele | Temporäre Projekte | Gruppenleistungen | Übernahme von Terminen | Kürzlich verwendete Leistungen | Projektbudget |
|---|---|---|---|---|---|---|
| Gewichtung der Nutzerziele | | 2 | 2 | 2 | 3 | 1 |
| Mehr verrechenbare Stunden | 3 | | | | | |
| Reduktion von Reklamationen | 2 | | | | | |
| Effiziente Erfassung | 1 | | | | | |
| Zwischensumme | | | | | | |
| Aufwand | | 1 | 2 | 3 | 2 | 2 |
| Gesamtpunkte | | | | | | |

(Punkte: gelb = Gewichtung der Businessziele, grün = Gewichtung der Nutzerziele, blau = Aufwand)

Tim wendet sich an sein Team: »Jetzt ist es an uns, die vorgeschlagenen Themen aus Sicht der Nutzenden zu gewichten. Lasst uns ebenfalls drei Stufen »niedrig«, »mittel« und »hoch« unterscheiden und durch grüne Punkte symbolisieren. Bei der Bewertung ist es entscheidend, dass wir uns auf die Ergebnisse der Nutzerbeobachtungen und die Validierung der Vision stützen. Es geht hier nicht um unsere Meinung – wir sind ja nicht die direkten User von 4Service.« Tim verteilt zur Bewertung aus Sicht der Nutzenden Punkte an die Teammitglieder, die in der Nutzerforschung involviert waren.

Nun wendet sich Tim an die Personen aus der Entwicklung im Team: »Jetzt seid ihr an der Reihe. Bitte schätzt den erwarteten Aufwand zur Umsetzung der Themen ab. Auch euch stehen jeweils bis zu drei Punkte zur Verfügung.« Die Diskussion zwischen ihnen ist kurz, schnell ist eine Einigung erreicht und es werden Punkte für den erwarteten Aufwand vergeben (vgl. Abbildung 72).

Tim wendet sich an alle Anwesenden: »Jetzt wird es spannend – wir beginnen nun damit, die erwarteten Einflüsse miteinander in Beziehung zu setzen. Lasst uns zunächst für jedes Thema bestimmen, wie hoch dessen Einfluss auf die drei Businessziele ist. Ich möchte dies an einem Beispiel illustrieren: Wenn User die Möglichkeit haben, ihre Leistungen auf temporäre Projekte zu buchen, so können wir erwarten, dass es weniger nicht verrechnete Leistungen gibt. Ohne diese Möglichkeit haben Nutzende vielleicht vergessen, ihre Leistungen später nachzutragen. Nun kann eine Leistung auch dann erfasst werden, wenn ein Projekt noch gar nicht angelegt ist: Die erbrachten Leistungen gehen für die Rechnungsstellung nicht verloren. Deshalb gewichte ich dies hoch und vergebe für die Zelle im Schnittpunkt von *Mehr verrechenbare Stunden* und *Temporäre Projekte* drei Punkte (Abbildung 72).« Tim verwendet zur Unterscheidung rote Punkte. Mit den Punkten bestimmen wir also, wie stark sich ein Thema aus unserer Sicht auf die Erreichung eines Businessziels auswirkt. Oder anders formuliert: Wie stark zahlt das Thema auf die Erreichung des Businessziels ein?«

*Abbildung 72: Ergänzte Priorisierungsmatrix mit erster Gewichtung*
- Wie Abbildung 71, zusätzlich drei rote Punkte im Schnittpunkt von *Mehr verrechenbare Stunden* und *Temporäre Projekte*.

»Am geringsten sehe ich«, fährt Tim fort, »den Einfluss dieses Themas auf die Anzahl der Kundenreklamationen. Kunden sind wohl nicht unglücklich, wenn Leistungen vergessen wurden und ihre Rechnung damit niedriger ausfällt. Wenn ein fairer Kunde jedoch feststellt, dass Leistungen vergessen wurden, wird er den Dienstleister darauf aufmerksam machen – der Dienstleister steht dann schon als etwas nachlässig da. Ich sehe den Einfluss dieser Funktion auf das Businessziel *Reduktion von Kundenreklamationen* insgesamt als relativ gering an und vergebe einen Punkt.«

»Das Thema ›Temporäre Projekte‹ hat, denke ich, einen mittelgroßen Einfluss auf die Effizienz der Erfassung. Ohne dieses Thema buchen User die erbrachte Leistung häufig auf ein internes Projekt und übertragen sie später – oder vergessen diese Übertragung. Zu einem gewissen Mehraufwand kommt es in jedem Fall. Ich vergebe also in der entsprechenden Zelle zwei Punkte – seid ihr damit einverstanden?«, fragt Tim. In Abbildung 73 haben wir den Stand von Tims Ausführungen festgehalten.

»Die Zellen der Matrix stellen eine Verbindung zwischen Projektzielen und funktionalen Themen her. Wir bewerten damit also die Bedeutung der Features in Bezug auf deren Relevanz zur Zielerreichung«, erläutert Tim. »Ich denke, das Prinzip ist jetzt klar: Wir können nun gemeinsam die noch unbesetzten Zellen der Matrix bestimmen«, sagt Tim.

*Abbildung 73: Priorisierungsmatrix nach Gewichtung des Einflusses auf alle drei Businessziele*
- Wie Abbildung 71, zusätzlich rote Punkte in der Spalte *Temporäre Projekte*: Mehr verrechenbare Stunden 3, Reduktion von Reklamationen 1, Effiziente Erfassung 2.

In der nächsten halben Stunde ergeben sich intensive Diskussionen zwischen den Stakeholdern. Alle bringen ihre Perspektiven ein, Punkte werden vergeben und die Matrix sukzessive vervollständigt (Abbildung 74).

*Abbildung 74: Priorisierungsmatrix mit Abhängigkeiten*

| | Gewichtung der Businessziele | Temporäre Projekte | Gruppenleistungen | Übernahme von Terminen | Kürzlich verwendete Leistungen | Projektbudget |
|---|---|---|---|---|---|---|
| Gewichtung der Nutzerziele | | 2 | 2 | 2 | 3 | 1 |
| Mehr verrechenbare Stunden | 3 | 3 | 1 | | 1 | |
| Reduktion von Reklamationen | 2 | 1 | 3 | | | |
| Effiziente Erfassung | 1 | 2 | 2 | 3 | 3 | 2 |
| Zwischensumme | | | | | | |
| Aufwand | | 1 | 2 | 3 | 2 | 2 |
| Gesamtpunkte | | | | | | |

Als schließlich die einzelnen Bewertungen vorliegen, besteht der nächste Schritt in deren Zusammenführung. Schauen wir uns die zugrunde liegenden Verknüpfungen an einem Beispiel an. Für jede mit roten Punkten gefüllte Zelle bilden wir das Produkt aus der zugeordneten Zeilen- und Spaltengewichtung. Beginnen wir mit der ersten, mit roten Punkten versehenen Zelle oben links in der Matrix von Abbildung 75.

*Abbildung 75: Verknüpfung von Thema und Einfluss auf das Businessziel*
- Matrix wie Abbildung 74; die Zelle *Mehr verrechenbare Stunden* × *Temporäre Projekte* (drei rote Punkte) ist hervorgehoben, Pfeile führen von der Gewichtung der Nutzerziele (zwei grüne Punkte) und der Gewichtung des Businessziels (drei gelbe Punkte) zu dieser Zelle.

Das Thema *Temporäre Projekte* ist mit zwei Punkten gewichtet, der Einfluss auf das erste Businessziel mit drei Punkten und das erste Businessziel *(Mehr verrechenbare Stunden)* ebenfalls mit drei Punkten. Wir berechnen nun das Produkt aus den vergebenen Punkten, also: 2 × 3 × 3 = 18 Punkte (Abbildung 76).

*Abbildung 76: Resultierende Berechnung der Verknüpfung*
- Matrix wie Abbildung 75; in der hervorgehobenen Zelle *Mehr verrechenbare Stunden* × *Temporäre Projekte* steht »2 x 3 x 3 = 18«.

In Abbildung 77 ist die Berechnung zur Bewertung der Kombination *Effiziente Erfassung* und *Kürzlich verwendete Leistungen* als weiteres Beispiel dargestellt.

*Abbildung 77: Priorisierungsmatrix mit Berechnung*
- Matrix wie Abbildung 74; die Zelle *Effiziente Erfassung* × *Kürzlich verwendete Leistungen* (drei rote Punkte) ist hervorgehoben, Pfeile führen von der Gewichtung der Nutzerziele (drei grüne Punkte) und der Gewichtung des Businessziels (ein gelber Punkt) zu dieser Zelle; Berechnung »1 x 3 x 3 = 9«.

Für leere Zellen legen wir eine Besetzung mit null Punkten fest, entsprechend resultiert als Produkt mit solchen Zellen jeweils insgesamt eine Bewertung mit null Punkten. Abbildung 78 zeigt den Zustand der Matrix nach Durchführung aller Berechnungen.

*Abbildung 78: Priorisierungsmatrix mit Berechnungen*

| | Gewichtung der Businessziele | Temporäre Projekte | Gruppenleistungen | Übernahme von Terminen | Kürzlich verwendete Leistungen | Projektbudget |
|---|---|---|---|---|---|---|
| Gewichtung der Nutzerziele | | 2 | 2 | 2 | 3 | 1 |
| Mehr verrechenbare Stunden | 3 | 18 | 6 | 0 | 9 | 0 |
| Reduktion von Reklamationen | 2 | 4 | 12 | 0 | 0 | 0 |
| Effiziente Erfassung | 1 | 4 | 4 | 6 | 9 | 2 |
| Zwischensumme | | | | | | |
| Aufwand | | 1 | 2 | 3 | 2 | 2 |
| Gesamtpunkte | | | | | | |

Vor der Berücksichtigung des Umsetzungsaufwands bildet Tim die Spaltensummen des kombinierten Einflusses von Themen auf Business- und Nutzerziele als Zwischenergebnis (Abbildung 79).

*Abbildung 79: Priorisierungsmatrix mit Zwischensummen*
- Matrix wie Abbildung 78, ergänzt um die Zeile *Zwischensumme*: Temporäre Projekte 18 + 4 + 4 = 26, Gruppenleistungen 22, Übernahme von Terminen 6, Kürzlich verwendete Leistungen 18, Projektbudget 2.

Zur Berücksichtigung des Umsetzungsaufwands müssen wir das Zwischenergebnis zum erwarteten Einfluss der Themen mit einer Schätzung des Aufwands zur technischen Umsetzung in Beziehung setzen. Hierzu benötigen wir eine Art Faustregel: Tim regt aus seinen Erfahrungen an, die nun vorliegende Zwischensumme durch den geschätzten Umsetzungsaufwand zu dividieren (Abbildung 80). Ein höherer Realisierungsaufwand resultiert dann bei sonst gleichen Zwischensummen des Einflusses von Business- und Nutzerzielen in entsprechend niedrigeren Scores in den Zellbesetzungen der Zeile »Gesamtpunkte«.

*Abbildung 80: Vollständige Priorisierungsmatrix*

| | Gewichtung der Businessziele | Temporäre Projekte | Gruppenleistungen | Übernahme von Terminen | Kürzlich verwendete Leistungen | Projektbudget |
|---|---|---|---|---|---|---|
| Gewichtung der Nutzerziele | | 2 | 2 | 2 | 3 | 1 |
| Mehr verrechenbare Stunden | 3 | 18 | 6 | 0 | 9 | 0 |
| Reduktion von Reklamationen | 2 | 4 | 12 | 0 | 0 | 0 |
| Effiziente Erfassung | 1 | 4 | 4 | 6 | 9 | 2 |
| Zwischensumme | | 26 | 22 | 6 | 18 | 2 |
| Aufwand | | 1 | 2 | 3 | 2 | 2 |
| Gesamtpunkte | | **26** | 11 | 2 | 9 | 1 |

Die Priorisierungsmatrix in Abbildung 80 fasst das Ergebnis der numerischen Gewichtung von Business-, Nutzer- und Aufwandsabwägungen zu den betrachteten Themen zusammen. Im vorliegenden Fall sind die numerischen Unterschiede recht ausgeprägt und das Ergebnis deutlich: »Auch wenn wir die aus einer Priorisierungsmatrix resultierenden Ergebnisse vorsichtig als grobe, heuristische Empfehlungen ansehen sollten – wir haben klare Evidenz dafür, dass wir das Thema *Temporäre Anlage von Projekten* auf jeden Fall angehen sollten – und zwar mit vordringlicher Priorität«, folgert Tim. »Auch die technische Realisierung der Themen *Gruppenleistungen übernehmen* und *Kürzlich verwendete Leistungen* sollten wir berücksichtigen. Die Themen *Übernahme von Terminen* und *Berechnung des Projektbudgets* können wir nach dieser Betrachtung hingegen in späteren Releases anbieten«, schließt Tim seine Ausführungen.

## Roadmap

Daniela, die Produktmanagerin, verfolgte die Argumentation zur Priorisierungsmatrix aufmerksam: »Also Tim, wenn ich dich richtig verstehe, planst du mit drei Releases. Das erste Release bietet die *Anlage temporärer Projekte,* im zweiten kommen *Gruppenleistungen übernehmen* und *Kürzlich verwendete Leistungen* hinzu. Das dritte Release wird dann durch die Themen *Übernahme von Terminen* und *Berechnung des Projektbudgets* charakterisiert sein. Habe ich dich richtig verstanden?«

Tim antwortet etwas zögerlich: »Hmm, grundsätzlich hast du recht, aber lasst uns das differenziert betrachten. Wenn wir uns die Priorisierungsmatrix noch einmal im Detail anschauen, so können wir daraus prüfbare Hypothesen ableiten. Die *Anlage temporärer Projekte* ist offensichtlich ganz wesentlich für das Erreichen des ersten Businessziels verantwortlich. Die anderen Themen können wir hier fast vernachlässigen. Welche Konsequenzen würden sich ergeben, wenn entsprechende Features verfügbar wären? Ich stelle eine erste quantitative Hypothese auf: Wenn Leistungen auch erfasst werden, obwohl das entsprechende Projekt noch nicht angelegt ist, so wird sich die Anzahl der fakturierbaren Stunden um etwa 10 % erhöhen.

Daniela versteht die Argumentation von Tim: »Ah – du meinst, die Priorisierungsmatrix ist auch sehr hilfreich, um über Wirkungszusammenhänge nachzudenken und Hypothesen abzuleiten. Und ja, auf dieser Grundlage können wir zumindest über grobe quantitative Ausprägungen der vermuteten Wirkung nachdenken.«

Kurz ist es still, offensichtlich wird angestrengt darüber nachgedacht, was aus der aufgestellten Priorisierungsmatrix weiter herausgelesen werden kann – dann schaltet sich Andrea ein: »Wenn ich diesen Ansatz konsequent weiterdenke, so sehe ich die folgenden Releases: Ein MVP, mit dem wir Grundfunktionen für die Kalenderansicht zur Verfügung stellen. Die Kalenderansicht bietet gegenüber der heutigen Lösung bereits eine spürbare Verbesserung. Ein zweites Release mit der zusätzlichen Funktionalität *Auf temporäre Projekte buchen,* ein drittes Release, das es erlauben wird, *Gruppenleistungen* zu übernehmen, und ein viertes Release für *Kürzlich verwendete Leistungen.* Wir können dann jeweils sehen, wie gut sich die späteren Releases gegenüber unserem MVP auf dem Markt schlagen.«

Sarah schaut Andrea verwundert an: »Wie kommst du denn genau auf diese Releases?« Andrea zeigt auf die Priorisierungsmatrix und erläutert: »Schaut euch die Bewertung der Funktionalitäten an. Mit Abstand die meisten Punkte hat die Erfassung auf temporäre Projekte bekommen. Damit wir den Einfluss dieser Funktionalität messen zu können, würde ich dennoch vorschlagen, zuerst die Grundfunktionalität eines Kalenders zu lancieren. Das gibt uns die Möglichkeit zur Messung einer Art Grundlinie als Ausgangswert – an dieser können wir zukünftige Releases messen. Die zweitmeisten Punkte hat das Thema *Gruppenleistungen,* danach folgt die Übernahme der *Kürzlich verwendeten Leistungen.*«

Tim meldet sich zu Wort: »Das erscheint mir ebenfalls sinnvoll – die Releases müssen wir aber noch weiter konkretisieren. Wir haben ja mit der User Story Map eine sehr genaue Beschreibung als Fundament unserer Überlegungen. Auf dieser Basis können wir festlegen, welche User Stories wir mit welchen der obigen Funktionalitäten verbinden. Damit können wir den Inhalt der unterschiedlichen Releases dann genau festlegen. Lasst uns zunächst die User Stories bestimmen, die für das MVP relevant sind.«

Die nun folgenden Aktivitäten basieren auf der ursprünglichen User Story Map – nun aber geht es im Wesentlichen darum, Karten wegzunehmen: Das MVP wird konkret.

*Abbildung 81: MVP mit essenziellen Merkmalen*

Aktivität: Leistungen erfassen – Release 1 (MVP):

| Leistungserfassung starten | Überprüfen der erfassten Leistungen | Leistung erfassen | Teammitglieder hinzufügen | Leistung ändern | Leistungen freigeben |
|---|---|---|---|---|---|
| Anmelden | Aktuelle Woche anzeigen | Leistung manuell erfassen | | Leistung löschen | Leistungen freigeben |
| | Woche wechseln | Abschreiben einer Leistung beantragen | | Leistungstext oder Projekt ändern | |
| | Wochen- und Tagessumme überprüfen | | | Leistungszeitpunkt und -dauer ändern | |

Tim geht noch einen Schritt weiter: »Wenn wir dem Vorschlag von Andrea folgen, sollten wir bereits das darauffolgende Release definieren: In dessen Mittelpunkt wird die Erfassung auf temporären Projekten stehen. Daneben könnten wir einige kleinere Funktionen zur Unterstützung integrieren.« Abbildung 82 zeigt das Folgerelease 2:

*Abbildung 82: MVP und Release 2*
- Release 1 (MVP): wie Abbildung 81
- Release 2 »Termporäre Leistung« [sic]: Urlaubsguthaben überprüfen, Überstunden überprüfen (unter *Überprüfen der erfassten Leistungen*); Temporäre Leistung erfassen (unter *Leistung erfassen*)

Nach weiteren Diskussionen hat das Team schließlich die erste Roadmap in Abbildung 83 entwickelt: Ein wesentlicher Meilenstein ist erreicht.

*Abbildung 83: Vollständige Roadmap*

| Release | Leistungserfassung starten | Überprüfen der erfassten Leistungen | Leistung erfassen | Teammitglieder hinzufügen | Leistung ändern | Leistungen freigeben |
|---|---|---|---|---|---|---|
| Release 1 – MVP | Anmelden | Aktuelle Woche anzeigen; Woche wechseln; Wochen- und Tagessumme überprüfen | Leistung manuell erfassen; Abschreiben einer Leistung beantragen | | Leistung löschen; Leistungstext oder Projekt ändern; Leistungszeitpunkt und -dauer ändern | Leistungen freigeben |
| Release 2 – Temporäre Leistung | | Urlaubsguthaben überprüfen; Überstunden überprüfen | Temporäre Leistung erfassen | | | |
| Release 3 – Gruppenleistungen | | Gemeinsame Leistungen anzeigen | | Leistungen von Teammitgliedern überprüfen; Leistungen von Teammitgliedern übernehmen; Teammitglieder aus Leistung entfernen; Teammitglieder zu Leistung hinzufügen | | |
| Release 4 – Kürzlich verwendete Leistungen übernehmen | | | Kürzlich erfasste Leistung übernehmen | | | |
| (unterhalb von Release 4, ohne Releasebezeichnung) | | Termine anzeigen | Leistung aus Terminen übernehmen; Projektbudget überprüfen | | | |

## Metrikenboard

Eine erste Roadmap liegt nun vor. Damit wir feststellen können, ob die Releases eines Produkts erfolgreich und unsere Hypothesen angemessen sind, benötigen wir Metriken und Methoden zu ihrer Messung: Je nach Ergebnis der erhaltenen Resultate können wir entscheiden, ob es Gründe zur Abweichung von der zuvor aufgestellten Roadmap gibt. Tim argumentiert: »Lasst uns Metriken definieren, anhand derer wir eine zuverlässige Aussage zum Erfolg unseres Produkts treffen können. Wir müssen uns auch darüber klar werden, welche Daten wir hierzu brauchen und wie wir diese Daten erheben können.«

Tim beginnt mit der Erstellung eines Metrikenboards, das die folgenden Komponenten umfasst: die Definition einer geeigneten UX-Metrik und einer Methode zu ihrer quantitativen Erfassung; eine Festlegung dazu, welche Persona und welches Szenario zur Bestimmung der Metrik herangezogen werden; einen Ausgangswert, der wiedergibt, welche quantitative Ausprägung die gewählte Metrik bei einem gegebenen System (aktuell) aufweist; und schließlich die Festlegung von intendierten Zielwerten, die über die kommenden Releases erreicht werden sollen. Abbildung 84 zeigt das Grundgerüst eines solchen Metrikenboards.

*Abbildung 84: Grundgerüst eines Metrikenboards*

| UX-Metrik | Messmethode | Persona | Szenario | Ausgangswert | Zielwert MVP | Zielwert Release 2 |
|---|---|---|---|---|---|---|

Die Auswahl aussagekräftiger Metriken fällt im Lichte der definierten Projektziele nicht schwer, Tim legt in der Diskussion aber großen Wert darauf, dass neben Performanzmetriken, die die Effizienz (zeitliche Dauer der Leistungserfassung) und Effektivität (verrechenbare Stunden) der Arbeit mit 4Service reflektieren, auch Indikatoren zum subjektiven Eindruck von Nutzenden mit in das Metrikenboard zu 4Service aufgenommen werden. Er schlägt hierzu den Einsatz der *System Usability Scale (SUS)* vor, eines kompakten Fragenbogens, bei dem Nutzende ihre Zustimmung zu zehn Fragen auf jeweils fünf Stufen angegeben können.

»Lasst uns zur Messung des subjektiven Eindrucks der Gebrauchstauglichkeit von 4Service die System Usability Scale heranziehen – wir haben im letzten Jahr bereits eine Erhebung für 4Service mit der SUS gemacht. Damals hatten wir einen Durchschnittswert von 62 Punkten erreicht. Zur SUS liegen viele Studien mit publizierten Benchmarkwerten vor, daher wissen wir, dass unser SUS-Score von 62 leider kein tolles Ergebnis ist.« Die anderen Teammitglieder stimmen zu – und ergänzen das in Abbildung 85 dargestellte Metrikenboard. Mit diesem Board liegt eine quantitative Zielvorstellung für die kommenden Releases vor.

*Abbildung 85: Ausgefülltes Metrikenboard*

| UX-Metrik | Messmethode | Persona | Szenario | Ausgangswert | Zielwert MVP | Zielwert Release 2 |
|---|---|---|---|---|---|---|
| Subjektive Beurteilung | SUS-Befragung | Marie Beraterin | Erfassen der Tagesleistungen | 62 | 70 | 72 |
| Effizienz | Zeitmessung mit Log | Marie Beraterin | Erfassen der Tagesleistungen | 14 Min | 13 Min | 12 Min |
| Effektivität | Anteil verrechenbare Stunden pro Tag | Marie Beraterin | Erfassen der Tagesleistungen | 70% | 71% | 73% |
| Fehlerrate der Leistungseinträge | Anzahl Reklamationen pro Kunde | Marie Beraterin | Erfassen der Tagesleistungen | 4,2 / Monat | 4,2 / Monat | 3,5 / Monat |

Peter nickt anerkennend: »Das Board ist wirklich hilfreich. Damit setzen wir für jedes Release klare, messbare Ziele und können direkt überprüfen, ob wir sie erreicht haben. Ein Metrikenboard fasst zusammen, welche Metriken wir in welcher Ausprägung in welchem Release erreichen wollen – aus der Priorisierungsmatrix konnten wir die vermuteten Wirkzusammenhänge von Features als grundlegende Hypothesen hierzu ableiten. In gewisser Weise sind unsere Releases damit Experimente, in denen wir dieses vermutete Wirkgefüge prüfen – auch wenn wir natürlich nicht streng alle relevanten Variablen wie in einem wissenschaftlichen Experiment kontrollieren können.«

## Zusammenfassung Roadmap

In diesem Workshop erarbeitete das Team eine konkrete Roadmap für die Releaseplanung von 4Service. Diese beschreibt, welche Releases in welcher Abfolge ausgeliefert werden sollen. Features mit dem größten Nutzen für alle Stakeholder sollten priorisiert ausgeliefert werden. Um diese zu identifizieren, arbeitete das Team mit einer Priorisierungsmatrix. In einem Metrikenboard wurden anschließend relevante Metriken definiert und Messmethoden zu ihrer Erhebung bestimmt. Das Metrikenboard bildet die Grundlage zur Planung abgestimmter Studien zur Erfolgskontrolle von Releases.

## Literatur

Eine Einführung in quantitative Methoden, die insbesondere im Umfeld von User Experience Design relevant sind, liefern Jeff Sauro und James Lewis:

- [Sauro & Lewis 2016] Sauro, Jeff; Lewis, James: *Quantifying the User Experience: Practical Statistics for User Research.* Waltham: Elsevier, 2016.

Von Jeff Sauro stammt auch eine lesenswerte Arbeit zum Einsatz und zu Benchmarks der System Usability Scale:

- [Sauro 2011] Sauro, Jeff: *A Practical Guide to the System Usability Scale.* Denver: Measuring Usability LLC, 2011.

Rex Hartson und Pardha Plya beschreiben die Grundlagen zu Metrikenboards in dem sehr lesenswerten UX-Lehrbuch:

- [Hartson & Pyla 2019] Hartson, Rex; Pyla, Pardha: *The UX Book. Agile UX Design Process and Guidelines for a Quality User Experience.* Amsterdam: Elsevier, 2019.
