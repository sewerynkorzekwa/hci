# Workshop: Konzept

> **Hinweis:** Die Titelseite und der Überblick dieses Kapitels (S. 138-139) wurden nicht fotografiert. Die Transkription beginnt ab Seite 140.

---

## Szenario

> **Szenario:** Beschreibungen in Szenarien fokussieren in narrativer Form auf das Erreichen von Nutzerzielen und betten diese anschaulich in einen konkreten, situativen Kontext ein. Sie abstrahieren von gestalterischen Details und implementationstechnischen Merkmalen einer späteren Umsetzung. Betrachten wir hierzu ein Beispiel: Es ist Montagabend, 19 Uhr. Patricia war den ganzen Tag über bei einem Kunden. Sie fährt nun mit dem Zug nach Hause, hierfür wird sie knapp eine Stunde benötigen. Alle Sitzplätze im Zug sind besetzt – Patricia muss stehen. Dennoch möchte sie die Fahrzeit nutzen, um ihre heutigen Arbeitsleistungen für eine spätere Rechnungsstellung in einer App auf ihrem Smartphone einzutragen. Es gibt zwei Leistungen, die sie einträgt: Sie nahm über den ganzen Vormittag, zusammen mit einer Kollegin, an einem Workshop teil. Der Workshop begann um 9 Uhr und endete pünktlich um 12 Uhr. Ihre Anreise zum Workshop betrug 60 Minuten. Am Nachmittag blieb sie vor Ort und dokumentierte die Ergebnisse des Workshops allein.
>
> Dieses Szenario enthält ein klares Nutzerziel und beschreibt den situativen Zusammenhang, in dem die Persona das Nutzerziel erreicht. Das Szenario ist konkret – wir verstehen inhaltlich, warum Patricia die Leistungserfassung vornehmen möchte. Die narrative Formulierung des Szenarios ist dabei vollständig lösungsoffen: Es geht aus der Szenariobeschreibung nicht hervor, wie die Leistungserfassung genau durchgeführt wird. Wir erfahren, wer handelt (Patricia), wir kennen das Ziel (die Leistungserfassung) und den Kontext (im Zug) – über das konkrete WIE des Prozesses schweigen wir uns hingegen (bewusst) aus.

Wo stehen wir jetzt? In unserem Team wurden Lösungsideen zur Leistungserfassung mit 4Service entwickelt, einander gegenübergestellt und priorisiert. Inwieweit diese Ideen auch im Zusammenspiel tragfähig sind, hat das Team mithilfe eines morphologischen Kastens erkundet. Die dort gewählte Kombination soll im Folgenden weiter detailliert werden. Die Formulierung von *Szenarien* helfen uns beim Durchspielen konkreter, zielgerichteter Nutzungssituationen.

Der fünfte Workshop kann beginnen, Tim moderiert ihn an: »Wir haben im Synthese-Workshop die Persona Marie Beraterin ausgearbeitet – wir starten mit ihr als handelnder Person in den von uns nun zu definierenden Szenarien. Lasst uns zunächst nochmals die Eigenschaften der Persona von Marie Beraterin, die identifizierten Opportunity Areas der Ist-Journey und die gewonnenen Lösungsideen als Ausgangspunkte vergegenwärtigen.«

Das Team betrachtet die UX-Artefakte, die in den vergangenen Workshops entstanden sind, und ist nun bereit für die Formulierung eines ersten Szenarios.

Sarah ergreift die Initiative: »Lasst uns ein *Soll-Szenario* für die Erfassung von Leistungen formulieren. In einem Soll-Szenario beschreiben wir unsere zukünftige Lösungsvision. Wir formulieren eine tragfähige Zielperspektive, arbeiten sie sukzessive aus und validieren sie. Eine passende Roadmap zu ihrer schrittweisen Umsetzung werden wir zu einem späteren Zeitpunkt erstellen.«

Daniela öffnet ihr Laptop, schließt es an den Beamer an und beginnt damit, einen Text zum Soll-Szenario zu schreiben. Sie liest die Passagen, während sie sie schreibt, laut vor:

»Es ist früher Abend, Marie sitzt an ihrem Schreibtisch, sie hat den ganzen Tag im Büro gearbeitet. Sie meldet sich bei 4Service an und kann ohne Umwege ihre Leistungen erfassen.

Marie überprüft, wann sie ihre Leistungen zuletzt erfasst hat. Sie betrachtet die aktuelle Woche und erkennt, dass die letzten protokollierten Leistungen von gestern Abend stammen. Konkret hat sie am gestrigen Tag 8 h und 30 min gearbeitet.

Die Leistungserfassung zeigt direkt die heutigen Termine in ihrem Kalender an. Sie bestätigt die Durchführung des angezeigten Termins von 10 bis 12 Uhr. Das diesem Termin zugeordnete Projekt wird automatisch korrekt erkannt. Der Titel des Termins ›Kick-off Marketing‹ wird ohne weiteres Zutun in den Beschreibungstext übernommen.

Marie weiß, dass ihr Arbeitstag an diesem Tag bereits um 8 Uhr startete: Sie hat am Designkonzept ihres aktuellen Projekts gearbeitet. Sie übernimmt die Eckdaten aus einer Übersicht der kürzlich erfassten Leistungen.

Marie kann zu jedem Zeitpunkt das aktuelle Restbudget auf dem Projekt einsehen – sie mag diese Transparenz, dies gibt ihr Sicherheit bei der Einhaltung von Budgets.

Den ganzen Nachmittag verbrachte Marie damit, sich in die Dokumentation für ein neues Projekt einzulesen. Einen zugeordneten Eintrag für dieses Projekt gibt es offensichtlich noch nicht.«

Tim unterbricht: »Daniela, die bisher von dir ausgeführte Formulierung des Szenarios bildet gut unsere Ideen ab und berücksichtigt auch die erkannten Opportunity Areas. Nun aber scheinst du gerade auf einen *Edge Case*, also eine Art Sonderfall, einzugehen. Lass uns doch zunächst einen ganz typischen Fall beschreiben, also einen *Happy Case*. Einverstanden?«

Daniela löscht den letzten Absatz und beginnt ihn neu: »Marie erfasst eine neue Leistung von 13.00 bis 18.00 Uhr und weist diese der Projektaufgabe ›Quality Review‹ zu. Als Beschreibungstext gibt sie ›Einarbeitung: Desk Research‹ an.

Marie möchte wissen, für wie viele Stunden des Arbeitstages sie bis hierhin Leistungen erfasst hat. Es sind bereits neun – schon wieder ein Tag mit Überstunden. Sie betrachtet zur Überprüfung alle Leistungen dieses Tages und kontrolliert die zugehörigen Beschreibungen.

Marie bestätigt nun die durchgeführte Leistungserfassung und gibt damit die eingetragenen Leistungen zur weiteren Verarbeitung frei.«

---

## Theorie: User Story Mapping

Ein Szenario beschreibt eine handelnde Person, ihr Ziel und den Kontext, in dem dieses Ziel erreicht werden soll. Aus dem Szenario können die notwendigen Funktionalitäten der zukünftigen Lösung abgeleitet werden.

Im von uns betrachteten Fallbeispiel lassen sich unterschiedliche Varianten der Bearbeitung des Ziels »Leistungserfassung« unterscheiden: Vielleicht möchte eine Nutzerin Leistungen erfassen, aber das relevante Projekt ist noch nicht angelegt? Vielleicht gibt sie unmittelbar nach der Erfassung der Leistungen jeden Tag ihren Zeitreport direkt frei? Oder sie tut dies erst am Ende einer Woche? Vielleicht greift ein Nutzer bei der Leistungserfassung auf eine Projektvorlage zurück, damit er seine Leistungen effizienter erfassen kann?

In einer User Story Map visualisieren wir die Aufgaben, die User bei der Erreichung ihrer Ziele in den wesentlichen Szenarien bewältigen. Durch die Erstellung einer User Story Map gewinnen wir somit einen Überblick über die relevanten Aufgaben in einem betrachteten Anwendungszusammenhang.

Für unser Team ist ein solcher Überblick zu diesem Zeitpunkt im Projektverlauf besonders wichtig: Damit das Konzept eines User Interface umfassend überzeugen kann, müssen alle zentralen Nutzungsziele der Nutzenden berücksichtigt und effizient unterstützt werden. Erst auf der Grundlage eines vollständigen Überblicks über alle durchzuführenden Aufgaben kann eine kohärente Lösung gefunden werden, die eine hinreichende Flexibilität bietet. Eine User Story Map stellt in anschaulicher Form zielorientierte Aufgaben in ihrer typischen Reihenfolge und Priorisierung dar.

User Story Maps bauen auf sogenannten *User Stories* auf. Eine User Story verweist in ein oder zwei alltagssprachlich formulierten Sätzen auf konkrete Arbeitsaufgaben, die User bei der Erreichung ihrer Ziele durchführen. »Anmeldung« ist ein Beispiel für eine solche Aufgabe bei der Erreichung des übergeordneten Ziels »Leistungserfassung«. Bei der konkreten Durchführung der Anmeldung können bei Bedarf unterschiedliche Alternativaufgaben angegeben werden. Oft wird auch erläutert, *warum* eine Aufgabe notwendig ist. Die folgende allgemeine Form einer User Story hat sich im Projektzusammenhang bewährt: »Als ›Persona‹ muss ich bei der ›Zielerreichung‹ eine ›Aufgabe‹ durchführen, weil ›Begründung‹.«

In einer User Story Map ordnen wir User Stories auf zwei Achsen an: Auf der horizontalen Achse der User Story Map beschreiben wir den sequenziellen Ablauf einer Interaktion im Sinne der Aufeinanderfolge einzelner Arbeitsaufgaben (vgl. Abbildung 43).

Auf der vertikalen Achse beschreiben wir ein Ziel und differenzieren einzelne Aufgaben zu dessen Erreichung. In einer weiteren Detaillierung zerlegen wir Aufgaben in »Teilaufgaben« mit höherer Auflösung und geben gegebenenfalls alternative (Teil-)Aufgaben an (in der Abbildung mit User Story bezeichnet). Die Höhe der Platzierung einer Teilaufgabe in einer User Story Map reflektiert deren zu berücksichtigende Priorisierung. Die Struktur einer User Story Map liefert auf diese Weise bereits erste Hinweise zur Relevanz von Funktionen, die die Arbeitsschritte von Nutzenden unterstützen.

Die Menge der erstellten User Stories bildet eine Art Checkliste für Funktionen, die die damit definierten Aufgaben adressieren. User Stories helfen einem Produktteam, an alle Funktionen zu denken, dienen als Kommunikationsgrundlage zur Diskussion ihrer Details sowie zur Einplanung von Ressourcen für ihre technische Realisierung. User Stories ergänzen wir oft durch Stichworte für Testfälle oder annotieren sie durch erste grobe Aufwandsschätzungen zum erwarteten Implementierungsaufwand. Mehr zu User Stories findet sich im Kapitel »Ausblick: Delivery« dieses Buches.

*Abbildung 43: Abstrakte Darstellung einer User Story Map*

- Oberste Zeile: eine Karte »Zielsetzung« (grün)
- Darunter: sechs Karten »Aufgabe« nebeneinander (rot)
- Darunter je Aufgabe eine Spalte mit Karten »User Story« (gelb): Spalte 1: 1, Spalte 2: 2, Spalte 3: 3, Spalte 4: 2, Spalte 5: 2, Spalte 6: 1

---

## User Story Map

Kehren wir wieder zu unserem Team zurück. Ziel ist nun die Identifikation von Funktionalitäten, die das erste Szenario betreffen.

Sarah nimmt sich einige Karten und beginnt mit dem Erstellen einer User Story Map zur Leistungserfassung. Sarah liest den Anfang des Szenarios nochmals vor: »Es ist früher Abend, Marie sitzt an ihrem Schreibtisch, sie hat den ganzen Tag im Büro gearbeitet. Sie meldet sich bei 4Service an und kann ohne Umwege ihre Leistungen erfassen. Marie überprüft, wann sie ihre Leistungen zuletzt erfasst hat. Sie betrachtet die aktuelle Woche und erkennt, dass die letzten protokollierten Leistungen von gestern Abend stammen. Konkret hat sie am gestrigen Tag 8 h und 30 min gearbeitet.«

Tim antwortet: »Wir erkennen folgende Schritte, die wir durch unterstützende Funktionen adressieren können:

- Sie meldet sich an,
- sie betrachtet die aktuelle Woche,
- sie überprüft die Termine und
- sie will die Gesamtsumme des Tages wissen – wobei sie sicher auch an der Gesamtsumme der Woche interessiert ist.«

Sarah hat damit begonnen, Karten zu schreiben und an die Wand zu heften.

*Abbildung 44: Die ersten Schritte einer User Story Map*

- Zielsetzung: Leistungen erfassen
  - Leistungserfassung starten: Anmelden
  - Überprüfen der erfassten Leistungen: Aktuelle Woche anzeigen / Wochen- und Tagessumme überprüfen / Termine überprüfen

Schritt für Schritt liest Tim nun den weiteren Verlauf des Szenarios vor. Unterstützt durch das Team füllt Sarah dabei die User Story Map mit den identifizierten Funktionalitäten aus.

*Abbildung 45: Weitere Schritte einer User Story Map*

- Zielsetzung: Leistungen erfassen
  - Leistungserfassung starten: Anmelden
  - Überprüfen der erfassten Leistungen: Aktuelle Woche anzeigen / Wochen- und Tagessumme überprüfen / Termine überprüfen
  - Leistung erfassen: Leistung manuell erfassen / Leistung mittels Vorlage erfassen / Leistung aus Terminen übernehmen
  - Leistung ändern: Leistungszeitpunkt und -dauer ändern
  - Leistungen freigeben: Leistungen freigeben

In Abbildung 45 ist das erste Szenario erfasst, die ersten Schritte in Richtung einer umfassenden User Story Map sind damit gemacht. Doch wie können die identifizierten Funktionen für dieses Szenario in der Integration in einem User Interface zusammenspielen? Für die erste Skizze einer möglichen Lösung bietet sich der Einsatz von Wireflows an.

---

## Sketchen von Wireflows

Tim erläutert die Idee hinter Wireflows: »Mit einem Wireflow können wir die in einem Szenario beschriebenen Interaktionen in Form von miteinander verknüpften Wireframes visualisieren.«

Er fährt weiter fort: »Wir zeigen die involvierten Screens, geben die notwendigen Aktionen an, die einen Nutzer oder eine Nutzerin dem Ziel einen Schritt näherbringen, und bestimmen, wie sich der Zustand des Interface nach Anwendung dieser Funktionen ändert. Hierbei gehen wir nun die einzelnen Schritte des Soll-Szenarios durch.«

> **Wireflow:** Ein Wireflow visualisiert zu einem frühen Zeitpunkt in einem Projekt den Fluss von Interaktionen durch einzelne Screens oder Dialoge einer zukünftigen Anwendung. Dargestellte Screens und Dialoge werden als Wireframes dargestellt, ihre Verbindungen und auslösende Aktionen beschrieben.

»Wir teilen uns nun wieder auf«, läutet Tim die nächsten Aktivitäten ein. »Lasst uns eine Variante des Design Studios durchführen. Nun geht es allerdings nicht mehr um das Erzeugen von Vielfalt. Ich bitte jeden von euch um die Erstellung von nur einem Entwurf. Danach werden wir einander die entstandenen Sketches wechselseitig präsentieren. Wir werden uns auf die besten Aspekte der Entwürfe einigen und versuchen, ihre vielversprechendsten Attribute anschließend in einem konsolidierten Entwurf zusammenzuführen.« Die Teammitglieder statten sich mit Papier, Bleistift, Marker, Radiergummi und Spitzer aus und ziehen sich in eine bequeme Ecke zurück. Dieses Mal steht etwas mehr Zeit zur Verfügung – beim Sketching ist Reflexion und Sorgfalt wichtig.

Tim gibt ihnen für die Sketching-Session weitere Tipps: »Betrachtet den Fluss eines Szenarios. Beginnt damit, den Ablauf zu segmentieren und die Inhalte von Screens und Screen-Zuständen abzubilden. Skizziert die Screens erst einmal nur grob. Gezeichnete Screen-Miniaturen sind hinreichend: Sie brauchen zunächst lediglich anzudeuten, welche Inhalte jeweils auf ihnen zu finden sind. Annotiert dann die beschriebenen Inhalte mit den zugehörigen Schritten des Szenarios, sodass die Schritte in den Übergängen zwischen Screens für alle Beteiligten verständlich sind.«

Tim begleitet die Arbeit des Teams und schaut sich die entstehenden Sketches an. Er achtet darauf, dass die in der Ideation-Phase erarbeiteten Ideen auch tatsächlich einfließen, und weist auf die Berücksichtigung der Anforderungen der Personas hin. Auch dafür sind die UX-Artefakte im Raum nützlich: Ideenwand und Personas sind immer präsent.

Nach 30 Minuten trifft sich das Team wieder. Alle Sketches werden an die Wand gehängt, die Teammitglieder stellen nacheinander ihre Skizzen vor. Tatsächlich sind die erstellten Skizzen auf den ersten Blick recht ähnlich, beinhalten aber in der detaillierten Ausgestaltung durchaus unterschiedliche Ideen. Tim verteilt wieder Bewertungspunkte, die die Teammitglieder zur Auszeichnung der besten Umsetzungsideen vergeben. Sie kleben die Punkte direkt auf die Sketches. Die in Abbildung 46 gezeigte Variante eines Wireflows zusammen mit der Beschreibung des Szenarios versammelt schließlich die meisten Bewertungspunkte auf sich:

*Abbildung 46: Wireflow mit der Szenariobeschreibung*

Acht durch Pfeile verbundene Screen-Skizzen (zuerst ein Anmeldescreen mit zwei Eingabefeldern und zwei Buttons, danach jeweils eine Wochenansicht Mo–Fr mit Liste links, Teammitgliedern unten links und Tagessummen unter den Spalten, z. B. 8:30 / 4:00 / 9:00; ein ausgewählter Eintrag zeigt das Restbudget »28h«, in späteren Screens öffnet sich ein Detaildialog, im letzten Screen führt der Pfeil zu einem Button oben rechts). Daneben der Szenariotext:

1. Es ist früher Abend, Marie sitzt an ihrem Schreibtisch, sie hat den ganzen Tag im Büro gearbeitet. Sie meldet sich bei 4Service an und kann ohne Umwege ihre Leistungen erfassen.
2. Marie überprüft, wann sie ihre Leistungen zuletzt erfasst hat. Sie betrachtet die aktuelle Woche und erkennt, dass die letzten protokollierten Leistungen von gestern Abend stammen. Konkret hat sie am gestrigen Tag 8 h und 30 min gearbeitet. Die Leistungserfassung zeigt direkt die heutigen Termine in ihrem Kalender an. Sie bestätigt die Durchführung des angezeigten Termins von 10 bis 12 Uhr. Das diesem Termin zugeordnete Projekt wird automatisch korrekt erkannt. Der Titel des Termins »Kick-off Marketing« wird ohne weiteres Zutun in den Beschreibungstext übernommen. *(zwei Screens)*
3. Marie weiß, dass ihr Arbeitstag an diesem Tag bereits um 8 Uhr startete: Sie hat am Designkonzept ihres aktuellen Projekts gearbeitet. Sie übernimmt die Eckdaten aus einer Übersicht der kürzlich erfassten Leistungen.
4. Marie kann zu jedem Zeitpunkt das aktuelle Restbudget auf dem Projekt einsehen — sie mag diese Transparenz, dies gibt ihr Sicherheit bei der Einhaltung von Budgets.
5. Marie erfasst eine neue Leistung von 13.00 bis 18.00 Uhr und weist diese der Projektaufgabe »Quality Review« zu. Als Beschreibungstext gibt sie »Einarbeitung: Desk Research« an.
6. Marie möchte wissen, für wie viele Stunden des Arbeitstages sie bis hierhin Leistungen erfasst hat. Es sind bereits neun — schon wieder ein Tag mit Überstunden. Sie betrachtet zur Überprüfung alle Leistungen dieses Tages und kontrolliert die zugehörigen Beschreibungen.
7. Marie bestätigt nun die durchgeführte Leistungserfassung und gibt damit die eingetragenen Leistungen zur weiteren Verarbeitung frei.

---

## Theorie: Sketching

Zeichnen kann jeder von uns – anfangs brauchen wir hierzu vielleicht ein wenig Mut, aber wir alle haben von Kindesbeinen an Übung im Umgang mit Stiften und Papier. Mit einigen einfachen Tricks fällt uns das Skizzieren, auch *Sketching* genannt, leichter und führt zu immer überzeugenderen Ergebnissen. Die Beachtung einiger Tipps unterstützt hierbei:

- Sketche mit Bleistiften. Die verwendeten Bleistifte sollten eher weich sein. Wir verwenden am liebsten den Härtegrad 2B oder 4B.
- Halte den Bleistift nicht zu weit vorne. Halte ihn etwa bei einem Drittel der Bleistiftlänge.
- Verwende bei längeren geraden Strichen den ganzen Arm beim Zeichnen. Bewege nicht nur das Handgelenk.
- Beginne eine Interface-Skizze mit den großen Formen eines Screens. Zeichne beispielsweise zuerst das Fenster eines Screens, unterteile anschließend das Fenster. Gehe erst dann zu den Details über.
- Beginne zunächst fein zu zeichnen, am Anfang müssen wir die Silhouette nur erahnen können. Danach, wenn wir wissen, dass Form und Dimensionen passen, können wir sie stärker nachzeichnen.
- Verschiedene Grauabstufungen mit dem Bleistift sind oft hinreichend, um Flächen oder Elemente hervorzuheben und Hierarchien anzudeuten.
- Reserviere eine Signalfarbe zur Lenkung der Aufmerksamkeit – etwa, um ausgewählte Navigationspunkte zu markieren.
- Belasse es nicht bei einem einzelnen Entwurf: Gerade in frühen Phasen ist das umfassende Erkunden des Lösungsraums wichtig.

Oft neigen wir dazu, bereits mit dem Erstellen einer ersten für uns akzeptablen Lösung weitere Bemühungen einzustellen. Wir müssen lernen, dieser Neigung zu widerstehen. Wenn wir verschiedene Lösungen ausarbeiten, erfahren wir nicht nur mehr über die Weite des Lösungsraums. Wir erschaffen uns auch eine wichtige weitere Option: Wir können die Vorzüge und Nachteile unterschiedlicher Lösungsalternativen einander gegenüberstellen und miteinander vergleichen. Wir müssen zu diesem Zeitpunkt nicht bereits die eine – vermeintlich beste – Alternative auswählen: Oft lässt sich erkennen, dass sich die Vorzüge einzelner Alternativen kombinieren lassen – oder wie ihre Nachteile kompensiert oder vermieden werden können.

Sketches haben einen hohen kommunikativen Wert: Wir veranschaulichen unsere Ideen und geben anderen Stakeholdern so die Möglichkeit, sie zu verstehen und nachfolgend gemeinsam zu verbessern. Wir vermeiden Missverständnisse und decken durch die beim Sketching notwendige Konkretheit immer wieder neue Fragen auf.

Wenn digitale Produkte gestaltet werden, so erleben wir häufig eine etwas zu zügige Nutzung digitaler Werkzeuge. Softwaretools haben unbestrittene Vorzüge, weil wir mit ihnen schnell eine Idee veranschaulichen können. Dies gelingt, weil viele Tools vorgegebene Elemente anbieten, aus denen wir nur noch auszuwählen brauchen. Doch genau hierdurch schränkt die Nutzung dieser Tools unsere Kreativität ein: Wir erkennen eine angebotene Schablone für ein Interface Control als (mehr oder weniger) passend und ziehen sie einfach auf die Arbeitsfläche.

Wenn wir sketchen, gibt es keine vorgegebenen Elemente – wir können (und müssen) uns ganz frei mit der Lösungsfindung beschäftigen. Vielleicht fällt uns hierbei ein individuelles Bedienelement ein, das für Nutzende bei einer gegebenen Aufgabe einen wesentlichen Effizienzvorteil bietet und gleichzeitig für Personen aus der Entwicklung mit vertretbarem Aufwand realisierbar ist.

Sketching bietet Freiheitsgrade und Geschwindigkeit: Wir können unsere Ideen in wenigen Augenblicken grob skizzieren und sie so anderen und auch unserer eigenen Reflexion zugänglich machen.

Sketchen funktioniert auch gut in Zweierteams, dies hatten wir bereits bei der Vorstellung der Methode Design Studio angesprochen. Das folgende Vorgehen hat sich in unserer Praxis bewährt: Eine Person zeichnet aktiv *(Konzepter)*. Die andere Person nimmt eine reflektierende, etwas distanziertere Haltung ein *(Reviewer)*. Der Konzepter führt das Sketching. Er sollte laut denken und erklärende Gedankengänge äußern. Die hinter den Zeichenstrichen von Konzeptern stehenden Gedanken werden so für Reviewer nachvollziehbar. Ein Reviewer hat Zeit zu überlegen, Ideen einzubringen und kritische Fragen zu stellen. Typischerweise wechseln sich die Rollen Konzepter und Reviewer ab. Sie nehmen sich eine Fragestellung nach der anderen vor. Nachdem eine Fragestellung beantwortet ist, übernimmt die andere Person.

---

## Vervollständigen der User Story Map

Sarah blickt in die Runde: »Welches Szenario betrachten wir als Nächstes?« Daniela schaut auf den Ideenkatalog und antwortet: »Marie, unsere Persona, war bei einem externen Kundentermin, sie hat gemeinsam mit einer Kollegin einen Workshop durchgeführt und erfasst deshalb den Eintrag gleich für beide Mitarbeiterinnen gemeinsam. Sie befindet sich gerade auf dem Heimweg.« »Okay«, antwortet Sarah, »hier ist klar, welche Funktion für Marie eine wirklich gute Unterstützung böte.« Sarah geht zur Wand und ergänzt die User Story Map um einen weiteren Bearbeitungsschritt: »Kollegin hinzufügen«.

Nun meldet sich Daniela zu Wort: »Wir haben doch darüber gesprochen, dass User Leistungen direkt aus Vorlagen einfügen möchten.« Sarah schaut auf die Karten und ist unsicher: »Ist dies ein eigener Schritt?« Tim antwortet: »Nein, ich denke nicht. Es ist eine Variante des Schrittes ›Leistung erfassen‹. Auf dieser Basis können wir aber beginnen, weitere Details zu den Schritten hinzuzufügen. Mit den Vorlagen können wir folglich zwei Varianten der Erfassung von Leistungen unterscheiden.« Tim schreibt eine gelbe Karte »Leistung aus Vorlage erfassen«.

Schritt für Schritt ergänzen die verschiedenen Teammitglieder die Details der User Story Map und diskutieren aufkommende Lösungsideen. Nacheinander spielt das Team weitere Szenarien durch. Tim greift nur dann in die Diskussion ein, wenn die Teilnehmenden nicht mehr über die fachliche Konkretisierung der Schritte in der User Story Map, sondern bereits über deren gestalterische Details oder die technische Umsetzung reden: »Wie wir das genau gestalten oder umsetzen, damit beschäftigen wir uns später. Lasst uns davon abstrahieren – im Moment geht es noch um das Konzept.«

*Abbildung 47: Ausgearbeitete User Story Map*

- Zielsetzung: Leistungen erfassen
  - Leistungserfassung starten: Anmelden
  - Überprüfen der erfassten Leistungen: Aktuelle Woche anzeigen / Woche wechseln / Termine überprüfen / Gemeinsame Leistungen überprüfen / Wochen- und Tagessumme überprüfen / Urlaubsguthaben überprüfen / Überstunden überprüfen
  - Leistung erfassen: Leistung manuell erfassen / Leistung mittels Vorlage erfassen / Leistung aus Terminen übernehmen / Temporäre Leistung erfassen / Projektbudget überprüfen / Abschreiben einer Leistung beantragen
  - Leistungsvorlagen verwalten: Leistung in Vorlage übernehmen / Leistung aus Vorlage löschen
  - Teammitglieder hinzufügen: Leistungen von Teammitgliedern überprüfen / Leistungen von Teammitgliedern übernehmen / Teammitglieder aus Leistung entfernen / Teammitglieder zu Leistung hinzufügen
  - Leistung ändern: Leistung löschen / Leistungstext oder Projekt ändern / Leistungszeitpunkt und -dauer ändern
  - Leistungen freigeben: Leistungen freigeben

Tim achtet darauf, dass Details, die als weniger kritisch angesehen werden, in der Map weiter unten platziert werden. Zur Begründung der Priorisierung werden immer wieder neue Argumente ausgetauscht.

---

## Exkurs: Definieren eines Frameworks

An diesem Punkt ist es oft zielführend, die ersten groben Skizzen der Abläufe nochmals zu überdenken und ein grobes Framework zu entwerfen, in dem wir Inhalte und Funktionalitäten einzelnen Screens zuordnen. Basis des Frameworks ist die gesamte, in der User Story Map festgehaltene Funktionalität. Bei der Zuordnung ist es ausreichend, vorgeschlagene Screens lediglich klein und ohne Details zu skizzieren. Keyscreens werden erst im nächsten Schritt konkret ausgearbeitet (siehe nächster Abschnitt). Sind unterschiedliche Endgeräte mit verschiedenen Auflösungen vorgesehen, so bietet es sich an, die jeweiligen Keyscreens zu sketchen und zum Vergleich nebeneinander zu platzieren.

Bei der Beschreibung von Szenarien, eines Frameworks und der Keyscreens sind gegenseitige Abhängigkeiten zu berücksichtigen. Szenarien können dabei als validierende Komponente genutzt werden, in der die Auswirkungen einer Änderung im Framework unmittelbar in einem konkreten Nutzungsablauf durchdacht werden können.

Die Gestaltung des Frameworks macht es nicht nur erforderlich, über die Aufteilung der Inhalte und Funktionen in unterschiedlichen Interaktionskontexten zu entscheiden, sondern auch über die Wahl geeigneter Design Patterns zur Navigation und zur Darstellung und Bearbeitung von Daten. Hierzu sind Kenntnisse über Patterns und Prinzipien guten Interaktionsdesigns sehr hilfreich. Gerne verweisen wir an dieser Stelle auf das lesenswerte Buch von Jenifer Tidwel, Charles Brewer und Aynne Valencia [Tidwel et al. 2019].

In den Diskussionen in unserem Team werden zwei unterschiedliche Patterns für mögliche Bearbeitungsmodi besprochen: ein an Kalendern orientiertes Pattern und ein Spreadsheet-ähnlicher Modus, mit dem insbesondere die Bedürfnisse von Mitarbeitenden aus der Administration adressiert werden können (vgl. Abbildung 48).

*Abbildung 48: Framework für die Leistungserfassung*

- Anmeldescreen → Wochenansicht als Kalender (Spalten Mo–Fr, Liste links, Teammitglieder unten links, Tagessumme 8:30)
- Kalenderansicht ↔ Spreadsheet-ähnliche Tabellenansicht (Zeilen je Leistung: Mo, Mo, Mo, Di, Di, Di, Di)
- Kalenderansicht ↕ Kalenderansicht mit geöffnetem Detaildialog zu einer Leistung (Restbudget 28h, Tagessummen 8:30 / 9:00)

---

## Definieren von Keyscreens

Mit der Festlegung von Keyscreens konkretisieren wir das Interface-Konzept des zukünftigen Moduls zur Leistungserfassung: Nun geht es um die Ausarbeitung von Details einzelner Screens.

Bei der Identifikation von Keyscreens bietet wieder der Rückgriff auf Szenarien wertvolle Unterstützung. Schnell wird die zentrale Rolle der Wochendarstellung für die Leistungserfassung deutlich: Wie sollte ein Keyscreen, der die Wochendarstellung umfasst, aussehen?

Tim versucht es mit einer abstrakten Skizze für die Wochendarstellung auf einem Flipchart und hängt das Ergebnis an die Wand. Er wendet sich an das Team: »Im nächsten Schritt möchte ich die wichtigsten Screens weiter ausarbeiten. Ich habe mal mit einer Skizze des Screens zur Wochenerfassung begonnen und ausgehend von der User Story Map auch die unterschiedlichen Informationen und Funktionen benannt, die angezeigt werden sollen. In welchen Bereichen des Screens würdet ihr bedeutsame Daten und Funktionen platzieren?«

Sukzessive werden die unterschiedlichen Bereiche festgelegt, Tim ergänzt die Zeichnung jeweils mit passenden Karten, die er jeweils beschriftet (vgl. Abbildung 49).

Tim richtet sich wieder an das Team: »Nun haben wir eine grobe Screen-Aufteilung – sollten wir feststellen, dass der Grundaufbau des Screens doch nicht passt, ändern wir ihn einfach wieder. Diese Flexibilität ist ein großer Vorteil des Arbeitens mit Papierskizzen. Wir können uns mit diesem Grundaufbau den konkreten Daten und Funktionen zuwenden, die in den unterschiedlichen Bereichen lokalisiert sind. Für Details zu Funktionen hilft uns die User Story Map, in ihr finden wir ein Verzeichnis mit allen funktionalen Anforderungen.«

*Abbildung 49: Keyscreens mit ausgewählten Elementen*

Skizze einer Wochenansicht (Spalten Mo–Fr, Tagessummen 8:30 / 9:00) mit beschrifteten Karten an den Bereichen:

- Gewählte Woche (oben)
- Arbeitszeiten (oben rechts)
- Liste mit vorbereiteten Leistungen (links)
- Liste mit Kolleginnen (unten links)
- Leistung (Eintrag im Kalender)
- Summen (unten)

> **Wireframe:** Ein Wireframe zeigt den konzeptionellen Entwurf eines Screens als konkretisierte Layoutdarstellung: Größe, Position und räumliche Bezüge der zentralen Bereiche sowie Interaktions- und Navigationselemente sind festgelegt. Im Mittelpunkt eines Wireframes steht die Struktur eines Screens; von dessen detaillierter visuell-ästhetischer Ausgestaltung wird abstrahiert. Auch wenn typografische Überlegungen zunächst nachgeordnet sind, sollte bei Wireframes kein Blindtext, sondern inhaltlich aussagekräftige Bezeichner (Labels) verwendet werden, um deren Verständlichkeit – aber auch den Platzbedarf für die jeweiligen Labels – evaluieren zu können.

Die Artefakte im Projektraum machen das Arbeiten leicht: Nach und nach ergänzen die Teammitglieder die beschrifteten Karten auf der Skizze mit grünen Karten für die vorgesehenen Daten und gelben Karten für die unterschiedlichen Funktionen, die das Interface umfassen soll (vgl. Abbildung 50).

Die in Abbildung 50 angereicherte Skizze fasst alle Informationen zusammen, die zur Anfertigung von Wireframes notwendig sind (Abbildung 51). Mit Wireframes repräsentieren wir das Grundlayout eines Screens, visualisieren angezeigte Daten und Funktionen in ihrem räumlichen Zusammenhang und bieten so einen ersten Blick auf das zukünftige Interface. Wir werden uns im nächsten Kapitel eingehender mit Wireframes beschäftigen.

*Abbildung 50: Mit Details ergänzter Keyscreen: Grüne Karten beschreiben die Daten, gelbe Karten die Funktionalitäten.*

| Bereich (blaue Karte) | Daten (grün) | Funktionen (gelb) |
|---|---|---|
| Gewählte Woche | Wochennummer, Wochentag, Datum | Nächste Woche zeigen, Letzte Woche zeigen, Aktuelle Woche zeigen |
| Arbeitszeiten | Wochenzeit, Überstunden, Wochen-Sollzeit, Urlaubsguthaben | – |
| Liste mit vorbereiteten Leistungen | Kunde, Projektbezeichnung, Tätigkeit | Leistung entfernen |
| Liste mit Teammitgliedern | Foto, Name | Teammitglied hinzufügen |
| Leistung | Projekt, Kunde, Status: Kalender, Status: Gruppentermin | Bearbeiten, Kopieren, Löschen, Verschieben, Beginn ändern, Start ändern |
| Summen | Sollzeit, Summe | – |

*Abbildung 51: Wireframe der Kalenderansicht*

- Kopfzeile: »Oktober 2023 - W40« mit Pfeilen zum Wochenwechsel und Kalendersymbol; rechts Kennzahlen Woche -42h, Monat -142h, Urlaub 12 Tage
- Linke Spalte »Projekte«: Kunde 1 – UX Design, Kunde 2 – UX Design, Kunde 3 – UX Design, Kunde 4 – UX Design
- Linke Spalte »Teammitglieder«: Mitarbeiter\*in 1, Mitarbeiter\*in 2, Mitarbeiter\*in 3 (jeweils UX Designer)
- Kalenderraster Mo 2.10, Di 3.10, Mi 4.10, Do 5.10, Fr 6.10 mit Zeitachse 08:00–17:00; am Montag Einträge »Kunde 4 – UX Design, 09:00-10:00« und »Kunde 3 – UX Design, 10:00-11:00« (jeweils mit Gruppensymbol)
- Tagessummen: Mo 2h, Di 0h, Mi 0h, Do 0h, Fr 0h

---

## Zusammenfassung Konzept

Ausgehend von zuvor erarbeiteten Lösungsideen haben wir im Konzept-Workshop das Ziel verfolgt, das Fundament zur Gestaltung eines User Interface zu legen und dessen wichtigste Interaktionskontexte schrittweise detaillierter auszugestalten.

Hierzu haben wir eine User Story Map entwickelt, in der wir Anforderungen von Nutzenden zur Ableitung konkreter Funktionen abbildeten. Mit der Definition eines Frameworks haben wir relevante Interaktionskontexte festgelegt.

Bei der Definition der Keyscreens haben wir bislang visuelle Aspekte des zukünftigen Interface kaum betrachtet. Vielmehr lag unser Fokus darauf, herauszufinden, wie die Interaktionskontexte segmentiert werden können und welche Daten und Funktionen sie enthalten sollten, damit zukünftige Nutzerinnen und Nutzer erfolgreich damit arbeiten können.

Anschließend arbeitete das von uns im Fallbeispiel begleitete Team erste Interaktionskontexte als Wireframes aus. Mit der Ausgestaltung von Wireflows, dem Framework und wesentlicher Keyscreens liegt nun ein Designkonzept für das User Interface zur Leistungserfassung in 4Service vor.

---

## Literatur

Ein Buch, das eine tragfähige Brücke zwischen UX Design und agilen Entwicklungsansätzen geschlagen hat, ist das Werk »User Story Mapping« von Jeff Patton. Es ist inspirierend geschrieben und als Lektüre sehr empfehlenswert. Der im vorliegenden Buch dargestellte Ansatz vom User Story Mapping basiert weitgehend auf dem in Jeff Pattons Buch geschilderten Modell:
[Patton 2014] Patton, Jeff: *User Story Mapping, Discover the Whole Story, Build the Right Product*. Sebastopol: O'Reilly, 2014.

Das Buch von Bill Buxton beschreibt den kreativen Prozess des Sketchings in anschaulicher Form:
[Buxton 2010] Buxton, Bill: *Sketching User Experiences: Getting the Design Right and the Right Design*. Burlington: Morgan Kaufmann, 2010.

Avi Parush stellt in seinem Buch den Prozess des konzeptionellen Designs vor:
[Parush 2015] Parush, Avi: *Conceptual Design for Interactive Systems: Designing for Performance and User Experience*. Burlington: Morgan Kaufmann, 2015.

Ein kurzgefasster Überblick zu Wireflows findet sich bei Page Laubheimer:
[Laubheimer 2016] Laubheimer, Page: *Wireflows: A UX Deliverable for Workflows and Apps*. 2016. Online: *www.nngroup.com/articles/wireflows/*.

Auch in der dritten Auflage bleibt das folgende Werk eine hilfreiche Referenz zum Thema Interface Design Patterns:
[Tidwel et al. 2019] Tidwel, Jenifer; Brewer, Charles; Valencia, Aynne: *Designing Interfaces: Patterns for Effective Interaction Design*. Sebastopol: O'Reilly, 2019.
