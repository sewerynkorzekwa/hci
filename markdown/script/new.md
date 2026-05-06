# Klausur-Fragen

## Gruppe A

### 1. Was ist Chunking

**Psychologische Grundlage: Subitizing und parallele Wahrnehmung (Folien 464–469)**

**Parallele Wahrnehmung (Folie 464–467):**
- Bei **wenigen Objekten** (~3–4): sofortiges Erfassen ohne Zählen möglich
- Bei **vielen ungeordneten Objekten** (10+): Zählen nötig — lineare, sequenzielle Verarbeitung
- Bei **geordneten Objekten** (Raster, Reihen): deutlich weniger Objekte wahrgenommen → Komplexität reduziert

**Lineare vs. parallele Wahrnehmung (Folie 468):**
- Bis ~4 Objekte: Reaktionszeit konstant ca. **500 ms** (parallele Wahrnehmung)
- Ab 5–9 Objekte: Reaktionszeit steigt stark auf ca. **2000 ms** (lineare, zählende Wahrnehmung)

**Subitizing (Folie 469):**
> Beim Zählen steigt die Reaktionszeit drastisch zwischen 4 und 6 Objekten.

- Von 2 bis 4 Objekte: **50 ms pro Objekt** (nahezu automatisch)
- Ab 6 Objekte: **250–300 ms pro Objekt** (bewusstes Zählen nötig)

**Konsequenz für UI-Design:**
> Gruppen von maximal **4–5 Elementen** ermöglichen parallele (sofortige) Wahrnehmung — mehr Elemente erzwingen lineare, kognitive Zählarbeit.

**Reduktion der Komplexität durch Ordnung (Folie 471):**
- 16 in einem 4×4-Raster angeordnete Elemente → werden als **wenige Einheiten** wahrgenommen
- 16 ungeordnete Elemente → werden als **viele einzelne Objekte** wahrgenommen
- → Ordnung reduziert die wahrgenommene Komplexität drastisch

---

**Miller's Gesetz / Magic Number 7 (±2) (Folien 543–544):**

> „The average person can only keep 7 (plus or minus 2) items in their working memory."

Miller (1957): Menschen können **7 ± 2 Chunks** von Informationen für ca. **30 Sekunden** im Arbeitsgedächtnis halten.

**Chunking — Definition:**
> Fähigkeit zum inhaltlichen Clustern bedeutsamer Information bei der mentalen Repräsentation.

- Größe und Struktur von Chunks hängen vom **Vorwissen** ab
- Je mehr wir wissen, desto größer und effizienter können Chunks sein
- Memorieren wird umso einfacher, je mehr Vorwissen vorhanden ist

**Beispiele für Chunks (Folie 546–547):**

| Folge | Merkbarkeit | Warum |
|---|---|---|
| `3 8 4 7 5 3 9` | schwer | Zufällige Zahlen, keine Struktur |
| `3 1 4 1 5 9 2` | leichter | Beginnt mit Pi (3.14159…) |
| `1 3 5 7 9 11 13` | leicht | Ungerade Zahlen — Muster erkennbar |
| `town river corn string car shovel` | gut | Bekannte Substantive |
| `what is the meaning of life` | sehr gut | Bekannte Phrase = ein Chunk |
| `CSPBUSAIR` | schwer ohne Wissen | CS · PB · US AIR → 4 bekannte Marken = 4 Chunks |

**Schach-Experiment (Folien 548–549):**
- Schachspieler bekamen echte Spielpositionen vs. zufällig platzierte Figuren kurz gezeigt
- **Experten** erinnerten sich bei echten Positionen deutlich besser als Anfänger → Spielmuster sind als Chunks im Langzeitgedächtnis gespeichert
- Bei zufälligen Positionen: kein Vorteil für Experten (keine Chunks nutzbar)
→ Je mehr Vorwissen, desto effizienter das Chunking

**Gedächtnissystem als Grundlage (Folien 537–539):**

Drei strukturelle Systeme in Interaktion:

| System | Beschreibung |
|---|---|
| **Sensorisches Gedächtnis** | Kurzer Filter-Puffer (< 1 Sekunde); selektive Wahrnehmung entscheidet, was weiterverarbeitet wird |
| **Arbeitsgedächtnis** | Limitiert auf 7 ± 2 Chunks; FILO-Puffer (wird ständig erneuert); ca. 30 Sekunden |
| **Langzeitgedächtnis** | Semantisches Netzwerk + Prozedurales/Deklaratives Wissen; durch Wiederholung, Emotion, Motivation gefestigt |

**Drei Prozesse des Gedächtnisses (Folie 539):**
1. **Enkodierung**: Transformation sensorischer Stimuli zu mentalen Repräsentationen
2. **Speicherung**: Mentale Ablage enkodierter Repräsentationen im Gedächtnis
3. **Retrieval**: Abruf von Gedächtnisinhalten

Warum vergessen wir? Fehlschlagen der Enkodierung / Verlust gespeicherter Inhalte / Fehlschlagen des Abrufs.

**Vergessenskurve (Folie 541) — Behalten sinnfreier Silben:**
- Nach 20 min: ~55 % behalten
- Nach 1 h: ~45 %
- Nach 24 h: ~30 %
- Langfristig: ~15 %

**Serial Position Effect (Folie 550–551):**
> „Users have a propensity to best remember the first and last items in a series."

- **Primacy Effect**: Erste Elemente werden gut erinnert (in Langzeitgedächtnis überführt)
- **Recency Effect**: Letzte Elemente werden gut erinnert (noch im Arbeitsgedächtnis)
- Bei **verzögerter** Wiedergabe: Recency Effect verschwindet — nur Primacy bleibt
→ Wichtige Navigationspunkte gehören ans **Anfang oder Ende** einer Liste/Navigation

**Von Restorff Effect / Isolation Effect (Folie 552):**
> „The Von Restorff effect predicts that when multiple similar objects are present, the one that differs from the rest is most likely to be remembered."

→ Einzeln hervorstechendes Element wird am besten erinnert — Verbindung zum Pop-Out Effekt und Las Vegas Effect

**Verbindung Peak-End Rule (Folie 553):**
Serieller Positionseffekt + Von Restorff-Effekt → bilden die Gedächtnisbasis der Peak-End Rule (Kahneman)

**Konsequenz für UI-Design:**
- Maximal **7 ± 2 Menüoptionen** oder Navigationseinträge (besser: ≤ 5)
- Informationen in **logische Gruppen (Chunks)** unterteilen → Group Related Information
- Bekannte Strukturen und Muster nutzen → reduziert kognitive Last
- Wichtige Elemente an **Anfang oder Ende** platzieren (Serial Position Effect)
- Schlüsselelemente visuell hervorheben (Von Restorff Effect)

---

### 2. Formativer und summativer (Test / Evaluation)

**Quelle:** Folie 755 (UX Evaluation — Was ist das?)

**Definition — Usability Evaluation (Folie 755):**
> „Mit dem Begriff Usability Evaluation wird eine Sammlung von Methoden zur strukturierten Erfassung der Gebrauchstauglichkeit (Usability)/User Experience eines interaktiven Systems angesprochen."

**Zwei Hauptunterscheidungen:**

**1. Formative vs. Summative Evaluation:**

| | Formative Evaluation | Summative Evaluation |
|---|---|---|
| **Ziel** | Input für die **nächste Iteration** — was soll verbessert werden? | **Feststellung des Ist-Zustands** — wie gut ist das System aktuell? |
| **Zeitpunkt** | Während des Designprozesses (früh, iterativ) | Am Ende — nach Abschluss des Designs oder einer Phase |
| **Ergebnis** | Konkrete Verbesserungsvorschläge | Messung gegen Baseline/Standard |
| **Analogie** | Arzt behandelt Patient während Krankheit | Arzt stellt Diagnose nach Genesung |

**2. Analytische vs. Empirische Verfahren:**

| | Analytische Verfahren | Empirische Verfahren |
|---|---|---|
| **Benutzerbeteiligung** | **Benutzerfrei** — Experten evaluieren ohne echte User | **Benutzer involviert** — echte Nutzer testen das System |
| **Beispiele** | Heuristische Evaluation (Nielsen), Kognitive Walkthrough | Usability-Test, Befragung, Beobachtung |

**Wichtiger Hinweis — Wann evaluieren? (Folie 759):**
> „Möglichst früh evaluieren — nicht auf das GO! von Designern warten."

- Feedback zu **prinzipiellen Designentscheidungen** ist zentral — Detailausarbeitungen sollten nachgeordnet werden
- **Papierprototypen** statt High-Fidelity Design: frühe, günstige Erkenntnisse sind wertvoll
- Problem: Designer sehen (negatives) Feedback oft als **Kritik** → möchten möglichst perfektes Ergebnis vorlegen → dadurch verschleppen sie Evaluation
- Evaluationsergebnisse dokumentieren früh mögliche **Schwächen (aber auch Stärken)** eines Entwurfs

---

### 3. UX – Usability

**Usability** — ISO 9241-11 (2018):
> „The extent to which an **interactive system** can be used by **specific users** to achieve **specific objectives effectively, efficiently** and **satisfactorily** in a **specific context** of use."

- **Effektivität**: Werden die Ziele erreicht?
- **Effizienz**: Mit welchem Aufwand?
- **Zufriedenstellung** (neu 2018): Ausmaß der Übereinstimmung der physischen, kognitiven und emotionalen Reaktionen des Benutzers mit seinen Bedürfnissen und Erwartungen

**User Experience (UX)** — ISO 9241-210:
> „Person's perceptions and responses resulting from the **use and/or anticipated use** of a product, system or service." (Donald Norman)

UX umfasst alle Emotionen, Überzeugungen, Präferenzen, Wahrnehmungen — **vor, während und nach** der Nutzung.

**Verhältnis UX ↔ Usability:**

```
|←————————— USER EXPERIENCE ——————————→|
          |←— USABILITY —→|
  BEFORE       DURING          AFTER
  (Erwartung)  (Nutzung)       (Reflexion)
```

**Kernunterschied:** Usability misst die Qualität der Interaktion *während* der Nutzung (effektiv, effizient, zufriedenstellend). UX ist breiter und schließt auch Erwartungen vor der Nutzung und die Bewertung danach ein.

---

### 4. Service Design – UX Design

**Quelle:** Folie 5 (konzentrische Kreise-Diagramm), Folien 221–229

Die Disziplinen sind konzentrisch ineinander verschachtelt — von innen nach außen:

| Ebene | Inhalte |
|---|---|
| **UI** (innerster Kreis) | Color Theory, Typography, Design Patterns, Pixel-perfect, Accessibility |
| **UX** | Wireframe/Prototyping, User Research, Experiments, Target Groups, Information Architecture, Copywriting |
| **Product Design** | Product Strategy, Product Outcomes, Opportunities & Solutions, Prioritization, Project Output Management |
| **CX Design** | Market Research, Sales, Marketing, Branding, Customer Service, Touchpoints, Customer Research |
| **Service Design** (äußerster Kreis) | Business Strategy, Team Composition, Process Design, Business Processes |

**Unterschied:**
- **UX Design** fokussiert auf das direkte Nutzungserlebnis mit einem Produkt (Forschung, Prototyping, Informationsarchitektur)
- **Service Design** umfasst das gesamte Geschäftsökosystem — Prozesse, Teams, Strategie und alle Touchpoints — weit über das einzelne Produkt hinaus

**Service Design — vertiefende Definition (Folie 221–227):**

> „Service design applies design methods and craft to the definition and **orchestration of service experiences**."

> „Service design examines the products, communications, interactions, operations, culture, and structure of an organization for impact on **service experience**."

**Dienstleistung (Service) vs. Produkt:**

| | Produkt | Service |
|---|---|---|
| Art | Vorproduziertes, fertiges Objekt | Entsteht erst durch Interaktion während der Nutzung |
| Speicherbar | Ja | Nein |
| Besitz | Ja | Nein |
| Produziert | Vor der Nutzung | Gleichzeitig mit der Nutzung (Production = Consumption) |

Was wird durch Services erworben? Erlebnis/Erfahrung, Transport, Zugang, Wissen.

> „Services are everything that you cannot drop on your foot."

Bedeutung: 69,7 % der deutschen Bruttowertschöpfung (2023, Statista) — Wandel von Produktions- zur Dienstleistungsgesellschaft.

**UX vs. Service Experience:**

| | User Experience (UX) | Service Experience |
|---|---|---|
| Fokus | Experience zwischen Person und **einem** Touchpoint (meist digitales Produkt) | Orchestrierte Experience **aller** Teile eines Service (Menschen, Objekte, Orte, Interfaces) |

**Service Design — 5 Prinzipien der Methodologie (Folie 229):**

1. **Human-Centered** — Der Mensch steht im Mittelpunkt
2. **Co-Creation** — Stakeholder werden aktiv in den Gestaltungsprozess einbezogen
3. **Sequencing** — Services werden als zeitliche Abfolge betrachtet (Before / During / After)
4. **Evidencing** — Immaterielle Services werden durch physische Artefakte erlebbar gemacht
5. **Holistic** — Das gesamte System wird berücksichtigt

---

### 5. 6-3-5 / HMW / Opportunity Areas

**Quelle:** Folien 258–275 (Explore-Phase, Ideation)

**Kontext:** Diese drei Methoden gehören zur **Explore-Phase** im Collaborative UX Prozess. Ziel: Von Opportunity Areas zu konkreten Ideen kommen.

---

#### Opportunity Areas

> **Opportunity Areas sind Themenfelder, in denen Innovationspotenzial identifiziert wurde → Innovationsfelder.**

- Entstehen aus Herausforderungen, mit denen Kunden oder Nutzende konfrontiert sind
- Oder aus **nicht genutzten Chancen**, die sich aus: technischen / regulatorischen / prozessualen Bedingungen ergeben
- Verbinden den **Problem Space** mit dem **Solution Space**

**Prozessfluss:**
```
Journey → Initial Challenge → Opportunity Areas → Ideas → Concept → Use-Scenarios
```

**Insight Statements** (Folie 259):
- Bauen auf den Ergebnissen der User Research auf
- Identifizieren **key findings für die Produktentwicklung**
- Opportunity Areas fassen Findings zusammen → zeigen Bereiche für Produktchancen

---

#### How-Might-We (HMW) Fragen

> HMW-Fragen beschreiben eine **Aufgabenstellung zur Ideenfindung** in Form einer konkreten Frage.

- Frage: „Wie könnten wir ein **Problem überwinden**?"
- Nicht *eine* Lösung ist gefragt — der Lösungsraum soll **umfassend erkundet** werden

**Struktur:**

| Teil | Bedeutung |
|---|---|
| **HOW** | Reframing Insights (Schlüssel zum Problem) |
| **MIGHT** | Opportunities for Design (mögliche Wege) |
| **WE?** | Explore Together (gemeinsam im Team) |

**Beispiel:** „How might we create a moment in time that frees drug-users from threat?"

---

#### 6-3-5 Methode

**Ablauf:**
- **6** Teilnehmende, **3** Ideen, **5** Iterationen (Runden)
- Alle erstellen ein A4 Papier mit 3 Spalten und 6 Zeilen
- Startpunkt: eine (oder mehrere) **HMW-Frage(n)**

**Runde 1:**
- Jede:r generiert **3 Ideen** in die erste Zeile (1–2 Sätze pro Idee, 6–12 Worte)

**Runden 2–5:**
- Blatt wird **im Uhrzeigersinn** weitergegeben
- Vorherige Ideen werden **weiterentwickelt, konkretisiert, gechallenged oder angepasst**

**Hinweis:** Funktioniert auch mit weniger Personen → 534, 433, 322 (Zahl der Personen, Ideen, Iterationen)

**Prinzipien Ideation (Folie 272):**
- STEHLEN IST ERLAUBT!
- QUANTITÄT VOR QUALITÄT!
- ALLE BRINGEN SICH EIN!
- MANCHE DINGE SIND ALLEINE EFFIZIENTER!
- |: ARBEITEN, ITERIEREN! :|
- VISUALISIEREN!

---

### 6. Gestaltgesetz

**Psychologische Grundlage (Folien 382–401):**

Gestaltgesetze basieren auf der menschlichen Fähigkeit zur **visuellen Mustererkennung**. Das visuelle System konstruiert aktiv Bedeutung aus Rohinformation:
- **Bottom-up**: Reizverarbeitung von der Retina aufwärts
- **Top-down**: Vorannahmen aus Wissen, Erfahrung und Kontext

> „Wenn wir etwas sehen, so versucht unser kognitives System Sinn im Ganzen zu entdecken — und nicht alleine auf die individuellen Teile einer Szene zu fokussieren."

> „Gestalt Prinzipien beschreiben, wie Eigenschaften der individuellen Teile die Wahrnehmung einer gesamten Konfiguration beeinflussen."

**80 %** aller Menschen sehen in einem Baumfoto einen menschlichen Kopf (Beispiel Folie 401).

---

#### 1. Gesetz der Geschlossenheit / Closure (Folien 403–408)

> Bei der Betrachtung einer komplexen Struktur visueller Elemente identifiziert unser Gehirn nach **Muster**. Wahrnehmung füllt Lücken und ergänzt bei der Identifikation vollständiger, erkennbarer Muster.

**Beispiele:**
- Apple Logo (negative Fläche des Apfels wird als vollständige Form wahrgenommen)
- IBM Logo (aus horizontalen Strichen wird „IBM" gelesen)
- Toblerone Logo (im Berg ist ein Bär versteckt)
- Paris 2024 Logo (Flamme + Marianne-Gesicht = zwei Lesarten)
- WWF Panda (aus wenigen Flecken wird ein vollständiger Panda erkannt)

---

#### 2. Gesetz der Nähe / Law of Proximity (Folien 409–412)

> „Objects that are near, or proximate to each other, tend to be grouped together."

- The law of proximity allows us to group different clusters of content **at a glance**
- **Implication:** No need for surrounding boxes to group elements — räumliche Nähe genügt

**Interface-Beispiel:** Das Suchfeld der „Die Post"-Website — Nähe des Eingabefelds zum Suchbutton bestimmt die Gruppe, nicht eine Box.

---

#### 3. Gesetz der Ähnlichkeit / Law of Similarity (Folien 413–418)

> „The human eye tends to perceive similar elements in a design as a complete picture, shape, or a group, even if those elements are separated."

> „Elements that are similar to each other are more likely to be perceived as related to each other than elements that are different."

**Takeaways:**
1. Visuell ähnliche Elemente werden als zusammengehörig wahrgenommen
2. Farbe, Form, Größe, Orientierung und Bewegung signalisieren Gruppenzugehörigkeit
3. Links und Navigation müssen visuell von normalem Text differenziert sein

**Interface-Beispiel:** Navigation vs. Fließtext — visuelle Differenzierung (Farbe, Unterstrich) macht Interaktionselemente erkennbar.

**Nähe vs. Ähnlichkeit:** Ähnlichkeit ist mächtiger als Nähe bei der Herstellung von gruppierender Ordnung.

**Herkunft:** Gestalt Laws of Grouping (Gestaltpsychologen) — fünf Kategorien: Proximity, Similarity, Continuity, Closure, Connectedness.

---

#### 4. Law of Common Region (Folien 419–424)

> „Elements tend to be perceived into groups if they are sharing an area with a clearly defined boundary."

> „The principle of common region states that objects bounded in a close region, appear to be a single group."

**Umsetzungsmöglichkeiten:**
- Expliziter Rahmen (Border/Box)
- Hintergrundfarbe / Schattenbereich
- Trennlinie

**Interface-Beispiel:** Profilkarten (Foto + Name + Text in einem Rahmen). Foodpanda: **implizite** gemeinsame Region durch Symmetrie und Nähe — ohne expliziten Rahmen.

---

#### 5. Gesetz der Symmetrie (Folie 425)

Symmetrische Muster werden als Einheit wahrgenommen. Bei konkurrierenden Cues (Farbe/Nähe) kann Symmetrie die Gruppenbildung beeinflussen.

---

#### 6. Figur / Hintergrund Prinzip (Folien 426–430)

> Erkennen von Objekten durch Fokussierung auf Figur oder Hintergrund.

**Zwei bestimmende Faktoren:**
- **Fläche**: Die kleinere überlappende Fläche zweier Objekte wird als Figur, die größere als Hintergrund gesehen (Beispiel: weißer Apple = Figur, schwarze Fläche = Hintergrund)
- **Konvexität**: Konvexe (gerundete) Muster werden eher als Figur gesehen

**Interface-Beispiele:**
- **Trivial:** Modal-Dialog (z. B. Airbnb Login) — Dialog ist Figur, abgedunkelter Hintergrund ist Background
- **Komplex:** Hörgeräte-Software Rexton — fehlende Figur/Hintergrund-Trennung macht das Interface schwer navigierbar (schlechtes Beispiel)

---

#### 7. Law of Prägnanz (Folie 431)

> „People will perceive and interpret ambiguous or complex images as the **simplest form possible**, because it is the interpretation that requires the **least cognitive effort** of us."

Menschen bevorzugen die einfachste mögliche Interpretation.

---

#### 8. Pop-Out Effekt / Merkmalswahrnehmung (Folien 432–438)

> **Gesetz der Prägnanz in der Praxis:** Wir achten besonders auf jene Elemente, die sich von der Umgebung abheben — **Pop-Out Effekt**.

Ein Element, das sich von den anderen unterscheidet, wird sofort fokussiert (saliente Information).

**Pop-Out-Merkmale (parallele Suche, unabhängig von Elementanzahl):**
| Merkmal | Beispiel |
|---|---|
| Farbe | Rotes Quadrat unter schwarzen Kreisen |
| Position & Alignierung | Versetztes Element |
| Sättigung | Helles Element in dunkler Menge |
| Größe | Größeres Element |
| Helligkeit | Leuchtendes Element |
| Orientierung | Gedrehtes Element |
| Textur | Anderes Muster |
| Form | Anderer Shape |
| Animation | Bewegendes Element |

**Reijnen & Wallach (2008):** Pop-Out = parallele Suche (Reaktionszeit bleibt konstant, egal wie viele Elemente). Kombinierte Merkmale = serielle Suche (Reaktionszeit steigt).

**⚠️ Las Vegas Effect / Hervorhebung (Folien 437–438):**
> Gibt es viele Elemente mit auffälligen Merkmalen, sticht ein einzelnes Element **nicht mehr hervor**.

→ Wenn alles hervorgehoben ist, ist nichts hervorgehoben. Zu viele Pop-Out-Reize neutralisieren sich gegenseitig.

**Anwendung — Farbe zur Aufmerksamkeitssteuerung (Folien 441–447):**

**Design in Greyscale First:**
> Durch das Designen in Graustufen wird man gezwungen, **Spacing, Kontrast und Größe** zur Klärung des Layouts zu nutzen → klares Interface mit starker Hierarchie. Farbe wird danach gezielt zur Lenkung der Aufmerksamkeit eingesetzt.

**Principle of Focal Point (Folie 443–446):**
> Das Auge fokussiert auf Elemente, die sich von der Umgebung abheben — in einem monochromen Interface ist der einzige farbige Button der **Focal Point**.

- Interface-Beispiel: Uber-Homepage (S/W-Foto) — nur der „SIGN UP FOR UBER"-Button ist farbig hervorgehoben → sofort als Call-to-Action erkennbar
- Pop-Out-Beispiel: Tabelle mit Zahlen, zwei Werte (> 1.0) in Magenta → sofortige parallele Erkennung ohne Zählen

---

#### 9. Gesetz der Kontinuität / Law of Continuity (Folien 448–450)

> **Continuity:** Elemente, die in einer Linie oder Kurve angeordnet sind, werden als zusammengehörig wahrgenommen.

- Eine Reihe von Punkten in einer geraden Linie → als Gruppe wahrgenommen (Folie 448)
- Ungeordnete Punkte → nicht als Gruppe wahrgenommen
- Kontinuität: Ein sequenzielles Invertieren des jeweils rechten Elements wird als **kontinuierliche Bewegung** wahrgenommen (Folie 449)

**Interface-Implikation:** Elemente, die entlang einer gemeinsamen Linie ausgerichtet sind (z. B. Navigationsleiste, Menüpunkte in einer Reihe), werden als Einheit wahrgenommen — ohne expliziten Rahmen.

---

#### Zusammenfassung: Gestalt Principles in a Nutshell (Folie 450)

> „User Interface Design is (also) about the feelings of users. Gestalt principles help to give users a good feeling while using your design — **they make a bridge between the design and the emotion of users**."

| Prinzip | Kernaussage |
|---|---|
| **Closure** | Gehirn erkennt komplexe Strukturen basierend auf Erfahrung, auch wenn Teile fehlen |
| **Proximity** | Nahe beieinanderliegende Dinge erscheinen verwandter als entfernte |
| **Similarity** | Elemente mit gemeinsamen visuellen Eigenschaften erscheinen ähnlich |
| **Common Region** | In einer gemeinsamen Region gebundene Objekte erscheinen als eine Gruppe |
| **Figure-Ground** | Objekte durch Fokus auf Vorder- oder Hintergrund erkannt; Fläche + Konvexität bestimmen Figur |
| **Focal Point** | Das Auge erfasst Elemente, die sich von der Umgebung abheben |
| **Continuity** | In einer Linie/Kurve angeordnete Elemente erscheinen verwandter als ungeordnete |

---

### 7. Was ist Affordance

**Quelle:** Folien 302–308

**Definition:**
> „Affordance is a term we use to qualify the ability of an object or a product to communicate its function. **Affordances are what an object can do based on a user interaction.**"

→ Affordance beschreibt, was ein Objekt dem Nutzer signalisiert, was er damit tun kann.

**Signifier:**
> Ein Signifier ist ein Indikator (physisch oder digital), der bedeutungsvoll interpretiert werden kann — er verstärkt die Affordance eines Objekts.

Beispiel: Die kleine LED am Monitor ist ein **Signifier** (weiß = an, rot = aus mit Strom, aus = kein Strom). Die Farbe ist das **Feedback**.

**Vier Signifier eines Login-Buttons (Folie 303):**
| Signifier | Wirkung |
|---|---|
| **Der Button selbst** | Erfahrene Nutzer:innen erkennen ihn als klickbar |
| **Farbwechsel beim Hover** | Zeigt, dass man darauf klicken kann |
| **Cursor-Wechsel** (Pfeil → Zeigefinger) | Verstärkt die Klick-Affordance |
| **Text auf dem Button** | Zeigt, was die Aktion bewirkt |

**Inherited Affordance (Folie 308):**
Umliegende Elemente verstärken die Affordance eines Buttons — z. B. das Muster „username input → password input → login button" ist so bekannt, dass der Button automatisch als klickbar wahrgenommen wird.

**Typen von Signifiern in Mobile Design:**
- **Basic**: Icon + Label (2 Signifier)
- **Complex**: Remove/Add-Symbol + Label + Draggable-Handle (3 Signifier)
- **Hidden**: Affordance erst durch Interaktion entdeckbar (z. B. Swipe → Delete)

---

### 8. Prototyp – MVP

→ Vollständige Vergleichstabelle: Gruppe B, Frage 2

**Quelle:** Folien 831–837

**MVP — Definition (Folie 834):**
> „The smallest possible thing we can build to fulfill the **basic narrative** and **delight the users**."

- **Narrative-complete, not feature-complete** — nicht alle Features, aber eine vollständige Story
- Ziel: Marktfeedback einholen, implizite Annahmen validieren, Features priorisieren

**MVP Pyramide (Folie 832) — von unten nach oben:**
```
BEDEUTUNGSVOLL
BEGEISTERND
PRAKTISCH
BENUTZBAR
ZUVERLÄSSIG
FUNKTIONAL  ← MVP = Core Features Done Right
```
→ MVP ≠ „Lots of Features Done Poorly" → MVP = „Core Features Done Right"

**MVP vs. Prototyp (Folie 837):**

| | Prototyp | MVP (= Erstes Release eines Produktes) |
|---|---|---|
| **Zweck** | Schnell & günstig, erlebbar, anschaulich, inspirierend, Identifikation von Usabilitybarrieren, kommunikativ | Erhebung von Kundenfeedback, Validieren (impliziter) Annahmen, Priorisierung von Features, technische + wirtschaftliche Produktvalidierung, Überprüfung von Marktreaktionen |
| **Vollständigkeit** | Bewusst unvollständig — kein echter Release | Minimal vollständig — erster Release des Produkts |
| **Zielgruppe** | Testnutzer im kontrollierten Rahmen | Echte Kunden im Markt |

**Richtige MVP-Analogie (Folie 835):**
- Falsch: Reifen → Fahrgestell → Karosserie → Auto (nie nutzbar während der Entwicklung)
- Richtig: Skateboard → Roller → Fahrrad → Motorrad → Auto (in jeder Stufe nutzbar und Feedback liefernd)

**Minimum Viable vs. Minimum Lovable (Folie 836):**
- MVP = Kuchen ohne Dekoration (funktional, aber nicht verführerisch)
- MLP (Minimum Lovable Product) = liebevoll dekorierter Cupcake (minimal, aber begeisternd)

---

### 9. Contextual Inquiries mit Beispiel

**Quelle:** Folien 153–160 (User Research Kapitel)

**Definition:**
> „Contextual inquiry is a type of ethnographic field study that involves in-depth observation and interviews of a small sample of users to gain a robust understanding of work practices and behaviors."

**Kernprinzip:** *Inquiry in Context* — Forschung findet in der natürlichen Umgebung der Nutzer statt.

**Zwei Komponenten (Site Visits):**
- **Observation**: Forscher beobachtet Nutzer bei der Arbeit in ihrer gewöhnlichen Umgebung (Büro, Zuhause, …)
- **Interview**: Forscher fragt nach, um zu verstehen wie und warum Nutzer das tun, was sie tun

**Wofür besonders geeignet:** Komplexe Systeme, tiefe Prozesse, Expertenperspektive

**Job Shadowing:** Spezialform — Forscher wird zum „Schatten" des Nutzers und begleitet ihn bei der Arbeit (GOOB = Get Out Of The Building!). Beobachtet: Wo findet Arbeit statt, welche technische Infrastruktur, Workarounds, Arbeitsschritte, Ablenkungen, Fachbegriffe, Zeitdruck, Rolleninteraktionen.

**Einbettung in User Research:**
- Ziel: aktuelle Situation von Nutzern durch Beobachtungen + Interviews erheben, Annahmen validieren
- Andere Methoden: Tagebücher, Befragungen, Interviews
- **Annahmen-Map** (vorher): zeigt Impact und Unsicherheit von Annahmen → priorisiert, welche Annahmen im Contextual Inquiry geklärt werden müssen (Fokus: hohe Auswirkung + hohe Unsicherheit)

**Beispiel:** Forscher begleitet einen Fabrikarbeiter an einer CNC-Maschine — beobachtet, welche Tastenkombinationen er sucht, welche Workarounds er entwickelt hat, wann er unter Zeitdruck arbeitet → versteht Nutzer:in ↔ Kontext ↔ Ziel

**Hartson & Pyla (2020):** „Getting your nose in the customer's tent"

**Filter-Problem (Folie 165):** Zwischen Forscher und Nutzer wirken 4 Filter, die Daten verfälschen:
1. **Nicht erinnern** — Nutzer hat vergessen, was passiert ist
2. **Nicht für relevant halten** — Nutzer denkt, das sei unwichtig (Expertise-Blindheit)
3. **Nicht sagen wollen** — Nutzer verschweigt aus sozialer Erwünschtheit
4. **Nicht, oder falsch fragen** — Forscher stellt die falsche oder führende Frage
→ Deshalb: Beobachtung **vor** dem Interview! ("Observe before the interview!")

**Interview-Typen (Folie 166):**
| Typ | Beschreibung |
|---|---|
| **Free Interviews** | Offen, kein festes Schema |
| **Structured Interviews** | Strikter Fragenkatalog, keine Abweichung |
| **Semi-Structured Interviews** | Leitfaden als Orientierung, aber flexibel |

**Master-Apprentice Model (Folie 167):**
- Interviewer behandelt den Nutzer als **Master**, sich selbst als **Apprentice**
- Ziel: Nutzerziele und -aufgaben verstehen, wie ein Lehrling lernt
- **Typische Fehler:** Unterbrechen des Masters, Beeinflussen, Anzweifeln oder korrigieren, Checkliste zum Steuern statt zum Orientieren nutzen

**Fragetypen im Interview:**
- **Open Question**: gibt keine Indikation über Format oder Inhalt der Antwort (bevorzugt!)
- **Closed Question**: erfordert Antwort aus vorgegebenen Alternativen (z. B. Ja/Nein)
- **Neutral Question**: keine eingebauten Annahmen, kein Frame — z. B. „What happened?", „What do you mean by that?"

**Best Practices (Folie 176):**
- Beobachten, möglichst offene Fragen
- Nach kürzlichen Ereignissen fragen (nicht abstrakte Zukunft)
- Einem Beispiel folgen, keine Synthesen verlangen
- Haltung eines „Lernenden" einnehmen
- Lösungen nicht ohne konkretisierenden Prototyp diskutieren

**Jakob Nielsen — First Rule of Usability:** „Don't Listen!" → Schau, was Nutzer **tun**, nicht was sie sagen. Self-reported claims sind unzuverlässig (Beispiel: Telefon-Hörer — Nutzer sagt „Gewicht ist genau richtig", wählt aber bei Prototypen das halb so schwere Gerät).

**Anzahl Interviews (Folie 200):** Typisch 3–6 Beobachtungen/Interviews pro Rolle; max. 2 Stunden pro Interview.

**Don't wait with analysis! (Folie 201):** Protokolle und Aufzeichnungen sollten **innerhalb von 24 Stunden** nach dem Interview ausgewertet werden. Screenshots, Notizen, Videos, Fotos und Audioaufnahmen sind die wichtigsten Gedächtnisstützen.

**Confirmation Bias (Folie 202):**
> „The tendency to interpret new evidence as confirmation of one's existing beliefs or theories."

User Research darf **nicht nur** darauf abzielen, Annahmen zu bestätigen — es muss aktiv geprüft werden, ob es Belege gibt, die Annahmen zu **widerlegen**. Sonst entsteht ein Confirmation Bias, der zu falschen Designentscheidungen führt.

---

### 10. Vorgehensmodell – menschzentriert / ISO – Gemeinsamkeiten und Unterschiede

**Erfordernisse und Nutzungsanforderungen (Folien 231–237) — Ergänzung zum ISO-Prozess:**

**Root-Cause Analysis (Theodore Levitt):**
> „People don't want to buy a quarter-inch drill bit — they want a quarter-inch hole."

→ Ziel ist es, die **eigentlichen Nutzerziele** zu verstehen, nicht nur die Oberfläche. Das Aufdecken der echten Ziele kann ein bedeutsamer Innovationstreiber sein.

**Nutzungskontext (Folie 232) — Attribute:**
- Benutzergruppen
- Aufgaben
- Umgebungen
- Ausrüstung
- Szenarien, die illustrieren, was im Nutzungskontext passiert

**Erfordernisse (Folie 233):**
> Erfordernisse sind **notwendige Voraussetzungen**, damit Nutzende in einem gegebenen Nutzungskontext ein Ziel erreichen können.

Formulierung: **Voraussetzung** (was der User wissen/können/haben muss) + **Ziel** (Aktivität, um etwas zu entscheiden oder zu tun).

**Beispiel Wecker:** Brillenträger wird nachts wach → muss wissen, wie lange er noch schlafen kann → entscheidet, ob er aufsteht.
Erfordernis: *„Der brillentragende Schlafende muss (auch ohne seine Brille aufzusetzen) wissen, wie lange er noch schlafen kann, um zu entscheiden, ob er auf die Toilette geht."*

**Von Erfordernissen zu Nutzungsanforderungen (Folie 235–237):**

> Nutzungsanforderungen beschreiben, was ein:e Nutzer:in am System **erkennen, eingeben oder auswählen** muss, während er/sie Ziele im gegebenen Nutzungskontext bearbeitet.

Drei Leitfragen:
1. Was müssen User **erkennen** können?
2. Was müssen User **eingeben** können?
3. Was müssen User **auswählen** können?

Abgeleitete Nutzungsanforderung (Beispiel):
> „Ein User muss am System — auch ohne seine/ihre Brille aufzusetzen — **erkennen** können, wie lange er/sie noch schlafen kann."

→ Aus solchen Nutzungsanforderungen ergeben sich **Opportunity Areas** (z. B. Wecker mit großer Leuchtziffernanzeige oder Sprachausgabe).

| Begriff | Zweck | Abgeleitet von |
|---|---|---|
| **Erfordernis** | Verstehen, was notwendig ist für Nutzerziele | Nutzungskontextbeschreibung |
| **Nutzungsanforderung** | Richtschnur für Design + Akzeptanzkriterien | Erfordernisse (möglichst aus Nutzungskontext) |

---

### 11. Was ist Mentales Design Modell

**Mentales Modell — Definition (Folie 566):**

> Subjektives Annahmengerüst über die Funktionsweise eines (interaktiven) Systems.
> Das Mentale Modell ist **handlungsleitend**, muss aber **nicht mit der Realität übereinstimmen** (Vereinfachungen, Fehlannahmen).

**Entstehung (Folie 567) — Mentale Modelle resultieren aus:**
- Erfahrungen, Trainings, Instruktionen
- (1) Interpretation von **Handlungskonsequenzen** und der **visuellen Struktur/Anmutung** des Systems
- (2) **Nutzungserfahrungen mit vergleichbaren Systemen** (Transfer)

**Funktion von Mentalen Modellen:**
- Erleichtern die zusammenhängende **Verankerung neuer Gedächtnisinhalte** im Langzeitgedächtnis
- Unterstützen das **Lernen** — neue Informationen werden an das bestehende Modell angeknüpft
- Liefern **Hypothesen** über mögliche Ursachen bei Systemfehlern

**Beispiel Textverarbeitung (Folie 566):**
- **Modell 1:** Änderungen werden immer und unmittelbar (ohne initierende Aktion) gespeichert
- **Modell 2:** Änderungen werden erst gespeichert, wenn User explizit „Save" selektiert
- → Die beiden Mentalen Modelle **resultieren in Handlungsunterschieden** mit Blick auf Systemcrashes

**Beispiel Heizung/Backofen (Folie 568):**
- Weit verbreitetes falsches Modell: Heizung auf Maximum stellen = wird schneller warm
- Realität: Thermostat schaltet ab, wenn Temperatur erreicht — Einstellung beeinflusst Zieltemperatur, nicht die Heizgeschwindigkeit
- Falles Modell: Backofen auf Maximum → Pizza wird schneller fertig (falsch bei Umluft-/Backofentypen)

**Mentale Modelle: Apple's Time Machine (Folie 569):**
- Räumlich-zeitliche Rückzugs-Metapher für Dateisystem-Backups: „Reise in die Vergangenheit" — Dateien als Schichten
- Das Interface kommuniziert ein mentales Modell von Backups als räumlicher Zeitreise → intuitiv verständlich

**Piktoriales (bildhaftes) Gedächtnis (Folien 561–564) — Ergänzung:**

**Mentale Rotation (Shepard & Metzler, 1977):**
- Frage: Können Objekte der unteren Reihe rotiert werden, um wie das Objekt oben auszusehen?
- Ergebnis: **Lineare Beziehung** zwischen Reaktionszeit und Rotationswinkel → ca. 1 Sek. pro 40°
- Schlussfolgerung: *„Visual images seem to reflect internal representations that operate in a way that is analogous to the functioning of the perception of physical objects"*

**Piktorielles Gedächtnis:**
- Instruktionen zur Generierung visueller Vorstellungsbilder verbessern die Behaltensleistung
- Gedächtnisleistung ist generell besser für **konkrete, „vorstellbare" Wörter** als für abstrakte Konzepte
  - Beispiel: „Piano" (vorstellbar) besser erinnert als „Kontext" (abstrakt)
  - Gilt auch für blinde Menschen (mentale Bilder ohne visuelle Erfahrung)
- Erklärung: Das generierte visuelle Vorstellungsbild wird als **„mentales Bild"** repräsentiert — **zusätzlicher Gedächtnispfad** (bildhafte + propositionale Repräsentation)

**Komplexeres Gedächtnismodell (Folie 564):**

```
Eingabe → Sensorischer Puffer
  Words → Ears → Sounds → Verbal Model  ──┐
  Pictures → Eyes → Images → Pictorial Model ─┤→ integrating → Prior Knowledge (LTM)
```
→ Sprache und Bild werden in **parallelen Kanälen** im Arbeitsgedächtnis verarbeitet und dann integriert.

**Zeigarnik-Effekt (Folie 572):**
> „People remember uncompleted or interrupted tasks better than completed tasks."

- Unfertige oder unterbrochene Tasks werden besser erinnert als abgeschlossene
- **Anwendung:** Progress Bars bei komplexen Tasks — visualisieren, dass die Task noch nicht abgeschlossen ist → erhöht die Wahrscheinlichkeit, dass die Aufgabe nicht vergessen wird

**Design-Implikationen für Gedächtnisgrenzen (Folie 573):**
- Organisation von Informationen in Chunks
- Kurze, lineare Sequenzen von Schritten: Memory Overload verhindern
- Bedeutsame Information **nicht nur temporär** anzeigen
- Messages (Zustandsinformationen, Feedback) als **externe Gedächtnisstützen** nutzen
- **Mehrfachkodierung** (Bild und Text: Icons und Labels) einsetzen
- Bildung handlungsadäquater Mentaler Modelle unterstützen
- Rekognition statt aktiver Erinnerung: Optionen visualisieren
- **Erwartungskonformität**: Organisation von Daten (z. B. Auto-Formatierung bei Telefonnummern)

---

**Kognitive Architektur als Grundlage (Folien 369–374):**

**Einfache Theorie menschlichen Verhaltens (Folie 369):**
```
Wissen ──────────────┐
(Angeboren /         │
 Erlernt /           ├──→ Rationalität ──→ Verhalten
 Wahrgenommen)       │
                     │
Ziele ───────────────┘
(Intrinsisch /
 Extrinsisch)
```
> Menschen wählen Handlungen, deren Durchführung — bei einem gegebenen Wissensstand, der auch die Handlungskosten berücksichtigt — die **Wahrscheinlichkeit einer Zielerreichung maximiert**.

**Cognitive Architecture (Folie 373):**
> Was vereint Einstein, eine Frau auf der Straße, einen Stammesangehörigen — und dich?

**Same cognitive architecture**: fixed mental structures that form the basis for running processes or «cognitive algorithms» — unabhängig von Kultur, Wissen und Intelligenz.

**Cognitive Psychology of Interaction Design (Folie 372, Peter Morville 2002):**
> „The design of good houses requires an understanding of both the **construction materials** and the **behavior of real humans**."

- construction materials → [Psychology] → **Cognitive Architecture**
- behavior of real humans → [Knowledge, Goals, Context] → **Contextual Inquiry**

**Cognitive re-engineering:**
> „Exploration of cognitive structures and processes as well as applying gained insights in system design"
- Überwindung von **Einschränkungen** menschlicher Kognition durch angemessene Systemunterstützung
- Berücksichtigung der **Stärken** menschlicher Kognition

*(Mentales Modell im engeren Sinne — Norman's Design Model vs. User's Mental Model — folgt auf späteren Seiten)*

---

## Gruppe B

### 1. Proto-Persona und Persona

**Quelle:** Folien 121–131

#### Persona

> **Fictional, archetypical user: needs and goals are representative for the target audience**

Eine Persona-Beschreibung umfasst:
- **Goals, personal backgrounds, depiction of behaviors, utilization patterns** relevant to an interactive system

**Warum Personas?**
- Consensus-building zwischen Stakeholdern — implizite Vorannahmen werden aufgedeckt
- Ziel: Software an Nutzerbedürfnisse anpassen (nicht umgekehrt)
- Gegengewicht zu **self-referential design** (Designerfokus statt Nutzerfokus)
- „Personas help to end feature debates" (Cooper, 2004)
- Keine abstrakten „elastic user concepts" — stattdessen konkrete Repräsentationen archtypischer Nutzer

**Primary vs. Secondary Persona:**
- **Primary Persona**: Eine Persona pro Interface — das Produkt soll primär auf sie ausgerichtet sein (ohne andere auszuschließen)
- **Secondary Persona**: Wäre vollständig zufrieden, wenn noch kleinere zusätzliche Attribute erfüllt wären; das Interface erfordert für sie zusätzliche Aktionen, ist aber für die Primary Persona leichter erlernbar

**Personas erstellen:** Durch Beobachtung und Interviews — Ziele, Aktivitäten, Tasks, Häufigkeit, Bildung, Computer-Affinität, Einstellung zur Technologie, Lernmotivation → Brainstorming mit Stakeholdern → Ableitung von Primary Personas

#### Proto-Persona

> **Modeled, archetypical users — based on assumptions and subjective perceptions of the development team**

- Repräsentiert **Annahmen** über hypothetische archetypische User für eine bestimmte Nutzergruppe
- Typisch in Rohform präsentiert
- Sammelt und strukturiert Annahmen über User — Validierung ist verschoben (aber darf nicht vergessen werden!)
- **Negative Personas**: machen deutlich, für wen man **nicht** designed

**Proto-Persona Template:**
| Bereich | Inhalt |
|---|---|
| Name, Quote | Kurzes Zitat |
| Person & Workplace | Alter, Experience level, Beruf, Job-Beschreibung, Computer-Erfahrung, Arbeitsplatz, Hardware |
| Tasks | Tägliche Aufgaben, typischer Workflow, Team/Kommunikation, Kontext anderer Tasks |
| Pain Points | Negative Aspekte, Workarounds, Wünsche/Anfragen |
| Goals & Needs | Ziele des Nutzers |

#### Proto-Persona vs. Validierte Persona

| | Proto-Persona | Validierte Persona |
|---|---|---|
| Basis | Annahmen, subjektive Wahrnehmung des Teams | Empirische Forschungsergebnisse |
| Realitätsbezug | Hypothetisch, Merkmale = temporäre Annahme | In der Realität verankert, glaubwürdig |
| Entstehung | Workshopbasiert (Entwurf) | Empirische Feldforschung + Gruppierung ähnlicher Proto-Personas |

**Wichtig (Prince Charles / Ozzy Osbourne Beispiel):** Zwei Personen können identische demografische Daten haben (Jahrgang 1948, England, verheiratet, reich, Kinder, mag Hunde) — aber völlig unterschiedliche Designanforderungen haben. → Auf **relevante Attribute** kommt es an, nicht auf demografische Ähnlichkeit!

---

### 2. Low-Fidelity / High-Fidelity erläutern und Unterschied Prototyp – MVP

**Quelle:** Folien 313–336 (Sketches, Wireframes, Progression)

**Fidelity** beschreibt den Detailgrad und die Realitätsnähe eines Designartefakts.

**Low-Fidelity (Lo-Fi):**
- Bewusst unfertig, abstrakt von Details
- Fokus auf Essenz, Struktur, Ideen
- Kein visuelles Design (keine Farben für Ästhetik)
- Beispiele: **Sketches** (Hand auf Papier), einfache Wireframes
- Ziel: Schnelles Iterieren, Sunk Cost Fallacy vermeiden
- „The whole point of designing in low-fidelity is to be able to move fast."

**High-Fidelity (Hi-Fi):**
- Realitätsnah, detailliert ausgearbeitet
- Beinhaltet Farben, Typografie, echte Inhalte, Animationen
- Wird im Rahmen von Usability-Tests oder für die Übergabe an Entwickler eingesetzt
- Beispiele: Figma-Mockups, interaktive Prototypen

**Formale Definitionen (Folie 729):**

> **Low-Fidelity Prototype:** „A low-cost, simple illustration of a design or concept used to gather user feedback at the very early stages of design."

> **High-Fidelity Prototype:** „A software prototype of the user interface to the interactive system that is being designed. A high-fidelity prototype resembles the finished interactive system and may or may not be interactive."

**Progression (Folie 322, 336):**
```
Sketches (Lo-Fi) → Wireframes (Lo-Fi/Mid) → Visual Design/Mockup (Hi-Fi)
```

**Wireframe als Zwischenstufe:**
- Skelettrahmen des Interfaces
- Legt Informationsarchitektur und Grid fest
- Kein visuelles Design — konzentriert sich auf Struktur und Controls

**Unterschied Prototyp vs. MVP:**

| | Prototyp | MVP (Minimum Viable Product) |
|---|---|---|
| **Zweck** | Validierung von Design-Annahmen / UX-Feedback | Marktvalidierung — echte Nutzung durch echte Nutzer |
| **Fertigungsgrad** | Kann Lo-Fi oder Hi-Fi sein — nicht notwendigerweise funktionsfähig | Einfachste, aber vollständig funktionsfähige Version |
| **Zielgruppe** | Testnutzer im kontrollierten Rahmen | Echte Kunden/Nutzer im Markt |
| **Ergebnis** | Design-Verbesserungen, Iterationsgrundlage | Marktfeedback, Business-Entscheidungen |
| **Fertigstellung** | Nicht fertig — bewusst unvollständig | Minimal fertig — auslieferbar |

→ Ein Prototyp ist ein Werkzeug zum **Lernen über Design**; ein MVP ist ein Werkzeug zum **Lernen über Märkte**.

**Formale Definitionen (Folie 837):**

**Prototyp (≠ Evolutionärer Prototyp):**
- Schnell & günstig, erlebbar, anschaulich, inspirierend
- Identifikation von Usabilitybarrieren
- Kommunikativ & aussagekräftig
- (Überzeugung von Stakeholdern)

**MVP (= Erstes Release eines Produktes):**
- Erhebung von Kundenfeedback
- Validieren (impliziter) Annahmen
- Priorisierung von Features
- Technische Produktvalidierung
- Wirtschaftliche Produktvalidierung
- Überprüfung von Marktreaktionen

**MVP Pyramide (Folie 832) — von unten nach oben:**
```
BEDEUTUNGSVOLL
BEGEISTERND
PRAKTISCH
BENUTZBAR
ZUVERLÄSSIG
FUNKTIONAL  ← MVP = Core Features Done Right
```
→ MVP ist nicht „Lots of Features Done Poorly" sondern „Core Features Done Right"

**MVP-Definition (Folie 834):**
> „The smallest possible thing we can build to fulfill the **basic narrative** and **delight the users**."
- Narrative-complete, not feature-complete
- Ziel: Marktfeedback einholen + implizite Annahmen validieren

**Richtige MVP-Analogie (Folie 835):**
- Falsch: Reifen → Fahrgestell → Karosserie → Auto (nie nutzbar während Entwicklung)
- Richtig: Skateboard → Roller → Fahrrad → Motorrad → Auto (immer nutzbar + Feedback liefernd)

---

### 3. Fitts'sches Gesetz mit Beispiel

**Quelle:** Folien 579–583

**Overview:**
> „The time to acquire a target is a function of the **distance** to and **size** of the target."

**Formel (Folie 581):**
```
Time (in msec) = a + b · log₂(D / W + 1)
```
- **D** = Distance zwischen Zeigegerät und Target
- **W** = Width/Size des Targets
- a = 0,230 sec, b = 0,166 sec (experimentell bestimmt)

**Kernaussage:** Je weiter das Target entfernt und je kleiner es ist, desto länger dauert es, es zu treffen — und desto höher ist die Fehlerrate.

**Drei Subprozesse der Mausbewegung (Folie 581):**

| Subprozess | Beschreibung |
|---|---|
| **Ballistische Bewegung** | Schnell, aber ungenau — Bewegung grob in Richtung Target |
| **Homing** | Mikromotorisches Adjustieren zum exakten Treffen des Targets |
| **Stop-Position** | Vorbereitung zum Klick |

> Homing-Bewegungen haben die **höchsten zeitlichen Kosten** — und sind für die meisten Fehler verantwortlich.

**Mac vs. Windows — Vertikale Endlosigkeit (Folie 582):**
- Das **Mac-Menü** positioniert sich an der **oberen Bildschirmkante** → die Trefferfläche wird effektiv "unendlich groß" (kein Cursor-Überfahren möglich)
- Der **Mac Dock** nutzt ebenfalls vertikale Endlosigkeit → schnellerer Zugriff als bei Windows-Taskbar
- **Quizantwort:** 5 Pixel-Targets ideal an den **4 Bildschirmecken + Bildschirmmitte** (Endlosigkeit in alle Richtungen)

**Implikationen für Interface Design (Folie 583):**

**Einsatz von großen Controls:**
- Größere Targets sind schneller und mit geringerer Fehlerwahrscheinlichkeit erreichbar

**Minimierung von Input:**
- Anbieten von effizienter Selektion aus Listen (**„Select vs. Type"**)
- Nutzen von **Default Selections** (häufigste Option vorausgewählt)
- Beachtung der Nutzungsfrequenz (User Research!)
- Unterstützung von Maus- und Tastaturinput

**Effiziente Texteingabe:**
- **Auto Complete** anbieten
- Synonyme akzeptieren, Fehlerkorrektur
- Strukturvorgaben zur Fehlervermeidung

**Beispiel:**
- Primärer CTA-Button (z. B. „Kaufen") groß und nahe am Cursor-Aktionsbereich → schneller und fehlerärmer erreichbar
- Kleines Schließen-X in Ecke = hohe Fehlerrate (klein + weit vom Aktionsbereich)

---

### 4. Usability und Metriken

**Quelle:** ISO 9241-11 (2018), Folien 778–786

**Die drei Kern-Usability-Metriken (ISO 9241-11):**

| Metrik | Definition | Beispiel-Messung |
|---|---|---|
| **Effektivität** | Werden Nutzerziele vollständig und korrekt erreicht? | Task Completion Rate (% erfolgreich abgeschlossener Aufgaben) |
| **Effizienz** | Mit wie viel Aufwand werden Ziele erreicht? | Time-on-Task, Fehleranzahl, Anzahl Klicks |
| **Zufriedenstellung** | Wie zufrieden sind Nutzende mit dem System? | SUS-Fragebogen, Likert-Skalen |

**UX Evaluation Methods Matrix (Folie 778, Rohrer 2014):**

|  | **Qualitativ** | **Quantitativ** |
|---|---|---|
| **Behavior** | Usability Testings, Walkthrough | A/B Testing, Analytics |
| **Opinion** | User Interviews | Questionnaire (Fragebogen) |

**Usability-Test — Definition (Folie 786):**
> Usability-Evaluation, bei der **repräsentative Benutzer:innen** bestimmte Aufgaben mit einem interaktiven System ausführen.

- Identifikation von UX-Barrieren anhand von Prototypen
- Aufdecken von Optimierungspotenzialen
- Messung von UX-Metriken: Effektivität, Effizienz, Zufriedenstellung
- Pro Interview ca. 45–60 Minuten; Interviews mit Möglichkeit zur Beobachtung durch Projektbeteiligte

**Setup (Folie 789):**
- **Userraum**: Testperson arbeitet allein am System
- **Observationsraum**: Beobachter sehen durch One-Way-Mirror zu — ohne die Testperson zu beeinflussen

**Thinking Aloud (Folie 790–791):**
> Prozessbegleitende Verbalisierungen von Ausschnitten des Arbeitsgedächtnisses

- Erfahren was Probanden bei der Bearbeitung durch den Kopf geht — nicht nur was, sondern auch warum
- Instruktion: „Tell me what you are thinking about as you work."
- Wichtig: Das System wird getestet, nicht der Nutzer
- Video liefert reichste Daten; Audio weniger; Notizen: schnell & effektiv

**Issue Map (Folien 799–800):**
- Struktur zur organisierten Erfassung von Findings im Usability-Test
- Neutral aufzeichnen was gesagt wurde (keine Interpretation)
- Nur der Moderator spricht; Note-Taker ist im Hintergrund
- Statements werden den jeweiligen Tasks und Screens zugeordnet

---

**Wie viele Teilnehmer? (Folien 801–803):**

- Häufige Empfehlung: ca. **5 Teilnehmende**
- Mit 5 Probanden werden **85% der Usability-Probleme** festgestellt
- Ab dem 6. Proband nimmt der **Lerneffekt ab** — es werden zunehmend dieselben Probleme entdeckt
- Nielsens eigentliche Empfehlung: **3 iterative Testings à 5 Teilnehmende** statt einmalig 15
- Anzahl hängt ab von: Ziel (Summativ vs. Formativ), Komplexität des Systems, Anzahl Nutzergruppen, Fehlertoleranz
- Mehr Nutzergruppen → mehr Teilnehmende nötig

**Onion Model — Mehrmals Testen (Folie 802):**
- Usability-Probleme können **einander verdecken**
- Erst wenn manche Probleme beseitigt sind, können andere entdeckt werden
- → Mit wenigen Probanden **mehrere Testings** stufenweise durchführen (nach Behebung von Problemen neu testen)

**Zeitplan (Folie 804):**
- Test-Session: **30–45 Minuten** Dauer
- Mindestens **15 Minuten Puffer** zwischen Sessions einplanen

**Rollen & Setup (Folie 805):**
- **Proband**: Testperson, arbeitet allein am System
- **Moderator**: Leitet die Session, stellt Aufgaben, interagiert mit Probanden
- **Note Taker**: Protokolliert im Hintergrund, spricht nicht mit Probanden
- Keine „prüfungsähnlichen" Situationen schaffen
- Reduziere unmittelbare Teilnehmende auf Proband + Moderator + Note Taker

**Geführter vs. Ungeführter Test (Folie 808):**

| | Geführter (moderierter) Test | Ungeführter (unmoderierter) Test |
|---|---|---|
| **Befragung** | Möglich — Gründe für Verhalten nachvollziehbar | Nicht möglich |
| **Hilfestellung** | Möglich | Nicht möglich |
| **Kosten** | Günstig (wenige Probanden reichen) | Teuer (hunderte Tests für repräsentative Ergebnisse) |
| **Forschungsfragen** | Gezielte Abfrage möglich | Keine situationsbedingte Befragung |

**Usability-Test in 3 Phasen (Folie 808):**

| Phase | Inhalte |
|---|---|
| **1. Vorbereitung** | Scoping & Analyse, Testaufgaben, Leitfaden/Moderationsskript, Teilnahmeerklärung, Issue Map, Pre-Test |
| **2. Durchführung** | Moderation, Beobachtung der Probanden, Protokollierung der Erkenntnisse |
| **3. Auswertung** | Konsolidierung & Digitalisierung der Erkenntnisse, Bewertung der Ergebnisse, Testbericht, Priorisierung von Optimierungsmöglichkeiten |

**Bewertung von Usability-Problemen — 5 Schwere-Klassen (Folien 811–812):**

**Drei Bewertungsfragen:**
1. Betrifft das Problem eine **kritische Aufgabe**? (wichtigste Aufgaben → betreffen meiste Benutzer:innen)
2. Ist das Problem **schwierig zu überwinden**? (schwer lösbar → Erfolgsrate sinkt, Ziele werden nicht erreicht)
3. Ist das Problem **persistent**? (Nutzer werden wiederholt gestört, auch wenn sie davon wissen)

**Fünf Klassen:**

| Klasse | Beschreibung |
|---|---|
| **Schwerwiegend** | Massives Problem, nachhaltig negative Konsequenzen, kann zu Bearbeitungsabbruch führen. **Dringend beseitigen.** |
| **Moderat** | Deutlich behindernd, steht positiver UX entgegen. **Prioritäre Behebung empfohlen.** |
| **Geringfügig** | Kosmetisches Problem. Behebung empfohlen, aber niedrige Priorität. |
| **Positiv** | Aspekte, die positiv aufgefallen sind und beibehalten werden sollen. |
| **Beobachtung** | Neutrale Erkenntnisse über System/Fachdomäne (z. B. typische Nutzeranforderungen, Konkurrenzlösungen). |

**Häufigkeit von Beobachtungen (Folie 813):**
- Usability Tests sind qualitative Methoden → keine statistische Signifikanz
- Häufigkeit wird symbolisch angegeben (nicht exakt): KEINE:R / EIN:E / EINIGE / VIELE / ALLE
- Bei der Priorisierung: **Schweregrad und Aufgaben-Wichtigkeit** stärker gewichtet als bloße Häufigkeit

**Heuristische Evaluation vs. Usability Testing — Vergleich (Folie 810):**

| | Heuristische Evaluation | Usability Testing |
|---|---|---|
| **Kosten** | Günstig & flexibel | Aufwändiger & teurer |
| **Geeignet für** | Einfache Domänen, frühe Stadien | Ausgereifte & komplexe Designs |
| **Probleme** | Weniger als beim UT | Mehr Probleme gefunden |
| **False Positives** | Gefahr der Überbewertung | Weniger False Positives |
| **Nutzer** | Keine echten Nutzer | Reale Nutzer — oft eine Überraschung |
| **Repräsentativität** | Nicht für echte Nutzer repräsentativ | Repräsentativ für reale User |
| **Wichtig** | KEIN ERSATZ FÜR USABILITY TESTING | — |

**Empfehlung (Folie 809):** Expert Review & Usability Testing kombinieren:
- Frühe Stadien → Expert Reviews (HE)
- Ausgereifte, komplexe Designs → Usability Testing mit repräsentativen Nutzern
- Expert Review als **Vorbereitung** des Usability Tests (Vorhersage möglicher Probleme → Auswahl von Tasks)

**Action Priority Matrix für Findings (Folie 822):**
→ Vollständig unter Gruppe B, Frage 9

---

### 5. Top und links und rechts Felder (Label-Alignment)

→ Vollständige Antwort: Aufgabe 6

**Abstandsregel (Folie 480 — „Mit Abständen arbeiten"):**

> Abstände **zwischen** Eingabefeldern sind größer als Abstände **zwischen** Labels und ihren zugehörigen Eingabefeldern.

- Das Label „klebt" näher am eigenen Feld als am nächsten Feld → Gesetz der Nähe (Proximity) erzeugt klare Label-Feld-Zuordnung
- Gruppe aus Label + Feld wird durch größeren Abstand zur nächsten Gruppe deutlich abgegrenzt

**Drei Alignment-Typen im Überblick (Folien 611–620):**

| Typ | Beste Situation | Nachteil |
|---|---|---|
| **Top-Aligned** | Bekannte Formulare, Geschwindigkeit wichtig | Mehr vertikaler Platzbedarf |
| **Right-Aligned** | Vertikaler Platz eingeschränkt | Weihnachtsbaumeffekt, Scannen schwerer |
| **Left-Aligned** | Unbekannte Formulare (unvertraute Labels) | Zuordnung Label↔Feld kann schwierig sein |

**Eye-Tracking-Fazit (Folie 619):**
- Top-Aligned: schnellste Verarbeitungszeit (Label + Feld in einer Fixation)
- Right-Aligned: halbe Fixationszeit vs. Left-Aligned
- Left-Aligned: größter Abstand Label↔Feld → höchste Verarbeitungszeit

---

### 6. Konsistenz-Prinzip

**Quelle:** Vorlesung, Interaction Design 7 Principles (Folie 67–70) + Folien 603–610

**Definition (Folie 604):**
> „The same information is presented in the same way throughout the **interactive system**, in accordance with the **user's** expectation."

Konsistenz stellt die **Einheitlichkeit** der Screens eines User Interfaces in Erscheinung und Verhalten der Elemente sicher.

**8 Konsistenz-Typen (Folie 605):**

| Typ | Bedeutung |
|---|---|
| **Consistency of groupings** | Elemente werden immer auf dieselbe Weise gruppiert |
| **Consistency of interactions** | Interaktionen und ihre Effekte sind durchgängig gleich |
| **Consistency of order sequence** | Reihenfolge von Optionen/Schritten bleibt konstant |
| **Consistency of identifiers** | Bezeichnungen für Elemente sind eindeutig und konsistent |
| **Consistency of controls** | Gleiche Controls (Buttons, Felder) verhalten sich überall gleich |
| **Consistency of terminology** | Gleiche Begriffe für gleiche Konzepte |
| **Consistency of icons** | Icons haben immer dieselbe Bedeutung |
| **Consistency of colors** | Farben kodieren Bedeutung konsistent |

**Vorteile (Folie 606):**
- User können Wissen von einer App auf andere übertragen
- **Learnability**: einmal gelerntes Muster überall anwendbar
- **Error reduction**: weniger Fehler durch vertraute Interaktionsmuster
- **Performance**: schnellere Aufgabenerledigung

**Problem: Was bedeutet „konsistent"? (Folie 606):**
- Konsistenz innerhalb der Applikation?
- Konsistenz mit früheren Versionen?
- Konsistenz mit Interface-Guidelines (welchen)?
- Konsistenz mit Nutzererwartungen?

**Beispiel OK/Cancel-Problem:**
- Windows: OK links, Cancel rechts
- Apple: Cancel links, OK rechts
→ Inkonsistenz zwischen Plattformen → Nutzende klicken falsch, Fehlklicks kosten mehrere Minuten.

**Radio-Buttons vs. Checkboxes — Konsistenz bei Controls (Folie 608):**

| Control | Verwendung |
|---|---|
| **Radio-Buttons** | User wählt aus einer Liste mit **mind. zwei sich gegenseitig ausschließenden** Optionen; Auswahl eines Buttons de-selektiert alle anderen |
| **Checkboxes** | User kann **beliebig viele** Elemente auswählen (0, 1, …, n); jede Checkbox ist unabhängig; eine einzelne Checkbox schaltet Option an/aus |

**Font-Dialog-Beispiel (Mac vs. Windows, Folie 609):**
- Beide zeigen „Font"-Dialog — aber unterschiedliche Struktur, Optionen-Reihenfolge und Terminologie
→ Keine Cross-Platform-Konsistenz: User muss neues mentales Modell aufbauen

---

### 7. Dimensionen des Interaction Design

**Quelle:** Folien 67–80 (7 Prinzipien) + Folie 299 (5 Dimensionen, Silver 2018)

---

#### 5 Dimensionen des Interaction Design (Silver, 2018) — Folie 299

| # | Dimension | Beschreibung |
|---|---|---|
| 1 | **Words** | Wörter (z. B. Button-Labels) sollen bedeutungsvoll und einfach verständlich sein — nicht zu viel Information |
| 2 | **Visual Representations** | Grafische Elemente: Bilder, Typografie, Icons — ergänzen die Worte |
| 3 | **Physical Objects or Space** | Womit interagiert der Nutzer physisch? (Laptop, Maus, Smartphone, Finger) — und in welchem Kontext? (Zug, Büro) |
| 4 | **Time** | Medien, die sich über die Zeit verändern (Animationen, Videos, Sounds); Fortschrittsverfolgung und Unterbrechbarkeit |
| 5 | **Behaviour** | Der Mechanismus des Produkts: Wie führen Nutzer:innen Aktionen aus? Wie reagiert das System? (emotionale Reaktionen, Feedback) |

---

#### 7 Prinzipien des Interaction Design — Folien 67–80

Die Vorlesung behandelt **7 Prinzipien** des Interaction Design (nicht die klassischen 5 Dimensionen nach Crampton Smith):

| # | Prinzip | Bedeutung |
|---|---|---|
| 1 | **Visibility** | Alle Funktionen/Optionen müssen für Nutzende sichtbar und verständlich sein |
| 2 | **Consistency** | Gleiche Designelemente durchgängig verwenden — reduziert Lernaufwand |
| 3 | **Mapping** | Beziehung zwischen Bedienelementen und ihren Aktionen muss logisch und intuitiv sein (z. B. Herdknöpfe zur Plattenanordnung) |
| 4 | **Feedback** | Das System muss auf jede Nutzerinteraktion reagieren (visuell, auditiv oder haptisch) — bestätigt Aktionen, reduziert Unsicherheit |
| 5 | **Constraints** | Einschränkungen verhindern Fehler und leiten Nutzende zu richtigen Aktionen (physisch, logisch, kulturell) |
| 6 | **Simplicity** | Einfache, intuitive Oberfläche — reduziert kognitive Last, vermeidet Clutter |
| 7 | **Flexibility** | Das Produkt muss sich an verschiedene Nutzerbedürfnisse anpassen (z. B. Touch-Gesten, Sprachbefehle, verschiedene Eingabemethoden) |

**⚠️ Widerspruch Simplicity vs. Visibility:** Ein einfaches Interface versteckt Funktionen; ein sichtbares Interface wirkt komplex — kein universeller Sweet Spot, kulturelle Unterschiede spielen eine Rolle.

**Zusatzkonzept: Discoverability**
> „The degree of ease with which the user can find all the elements and features of a new system when they first encounter it."
Discoverability ist eine Komponente von Learnability. Beispiel: Viele iOS-Gesten sind nicht offensichtlich (Benachrichtigungen, Apps löschen, Undo …).

---

### 8. Was versteht man unter Progressive Disclosure?

**Quelle:** Folien 599–600 (im Kontext von Hick's Law und Choice Overload)

**Hick's Law — Motivation für Progressive Disclosure (Folien 585–591):**

> „The time it takes to make a decision increases with the **number and complexity of choices**."

Das Hick'sche Gesetz besagt: Die Zeit für eine Entscheidungsfindung wächst als Funktion der verfügbaren Entscheidungsoptionen.

**Aufgaben als Sequenz von 4 Schritten:**
1. Identifikation eines Ziels (Was will ich?)
2. Bewertung der verfügbaren Optionen (Was kann ich tun?)
3. **Auswahl einer Option** (Was werde ich tun?) — hier wirkt Hick's Law
4. Umsetzung der Option

**Beispiele für Hick's Law:**
- Menüs: Zeit zur Auswahl eines Items steigt mit Anzahl der Einträge
- Bremsen im Auto: Entscheidungszeit steigt, wenn es eine Möglichkeit zum Umfahren gibt
- Device-Settings: Zeit zur Justierung steigt mit Anzahl verfügbarer Controls

**Einschränkung:** Hick's Law gilt vor allem für **einfache Entscheidungsaufgaben** (eindeutige Reaktion auf Stimulus). Bei komplexen Menüs mit langen Textbeschreibungen oder Submenüs nicht direkt anwendbar.

**Implikationen (Folie 591):**
- Mehr Entscheidungsoptionen = mehr Zeit
- Komplexe Aufgaben in kleinere **Subtasks** unterteilen
- **Highlighting empfohlener Optionen** → reduziert die wahrgenommene Komplexität

**Paradox of Choice (Schwarz, 2005; Iyengar & Lepper, 2000) — Folie 593:**
- Marmeladenstudie: 6 Sorten → 40% Besucher, 30% Käufer (12% Gesamtkauf) / 24 Sorten → 60% Besucher, **3% Käufer** (2% Gesamtkauf)
- *„An extensive array of options can at first seem highly appealing, yet can reduce their subsequent motivation to purchase."*
- **Choice Overload:** User erleben Überforderung → Analysis Paralysis + Buyer's Remorse

**Choice Overload bekämpfen (Folie 596):**
- Reduktion der Auswahl
- Angemessene Kategorisierung
- Highlighting von Optionen
- Unterstützung der Suche: Exklusion → Vergleich (Suchstrategie, Folie 597)

---

**Progressive Disclosure — Definition (Folie 599):**

> „Effective strategy for taming complexity: Only the **typically relevant information** is shown."

- Informationen werden in **Schichten** aufgeteilt — weniger wichtige Informationen werden **nur auf Aufforderung** angezeigt
- Screens bleiben übersichtlich → Clutter-Probleme werden vermieden
- Selten verwendete Informationen werden nur auf Aufforderung dargestellt (Folie 600)

**Vorteile:**
1. Screens bleiben klar und fokussiert
2. Lernbarkeit des Interfaces verbessert sich: User können mit einfacher Funktionalität beginnen, Komplexität steigt progressiv
3. Information, die der User nicht benötigt, ist **Noise** → wird ausgeblendet
4. Weniger Fehler und geringere Lernzeit

**Nachteile / Grenzen:**
- Funktionen können versteckt wirken → Discovery-Problem (Hidden Affordance)
- Mehr Interaktionsschritte nötig, um zur Information zu gelangen
- Nicht geeignet, wenn Nutzer schnellen Überblick über alle Optionen brauchen

**Wireframe-Beispiel (Folie 600):**
- Links: Zusatzliste wird **immer** dargestellt → Clutter
- Rechts: Zusatzliste wird **nur durch Anwählen eines Buttons** dargestellt → Progressive Disclosure

**Interface-Beispiele:**
- „Erweiterte Einstellungen"-Button (versteckt selten genutzte Parameter)
- „Mehr anzeigen" / „Details"-Toggle
- Onboarding-Flow: zunächst nur Kernfunktionen, erweiterte Features schrittweise freischalten
- **Drucker-Dialog (Folie 602):** Einfache Ansicht zeigt nur Kopien, Seiten, Ausgabe. „Details einblenden"-Button → erweiterte Optionen (Papierwahl, Qualität, Ausrichtung) werden sichtbar. Fokus auf **80%-Fälle** — Gelegenheitsnutzer werden nicht mit seltenen Optionen überflutet.

---

### 9. Priorisierungsmatrix

**Visuelle Priorisierung (Folien 484–488) — ergänzende Designprinzipien:**

**Priorisierung: Visuell (Folie 485):**
> Informationen visuell priorisieren — wichtigere Inhalte sollen stärker hervortreten.

**Priorisierung: Hierarchie (Folie 486):**
- Durch **Kontrast** (dunkle vs. helle Elemente), **Größe** und **Gewicht** (Schriftstärke)
- Wichtige Elemente: dunkel, groß, fett — unwichtigere Elemente: heller, kleiner, dünner

**Priorisierung: Auszeichnung (Folie 487–488):**
- Gezielter Farbeinsatz für die **wichtigsten Elemente** (z. B. kritischer Messwert im Dashboard)
- Ohne Priorisierung: alles gleichwertig — schwer zu lesen
- Mit Priorisierung: Schlüsselelement (roter Balken, roter Text) sofort erkennbar
- Verbindung zu Pop-Out Effekt (Gestalt) und Focal Point

---

**Action Priority Matrix — Priorisierung von Findings (Folie 822):**

> Nach einem Usability-Test werden Findings nach **Impact** (Wirkung) und **Effort** (Aufwand zur Behebung) eingeordnet.

**Vier Felder:**

| | **Hoher Impact** | **Geringer Impact** |
|---|---|---|
| **Hoher Effort** | **MUST HAVES (YES!)** — trotz Aufwand priorisieren | **MONEY PITS (NO!)** — vermeiden |
| **Geringer Effort** | **LOW HANGING FRUITS (YES!)** — sofort umsetzen | **QUICK WINS (MAYBE)** — optional |

→ **Low Hanging Fruits** (hoher Impact, geringer Aufwand) haben höchste Priorität.
→ **Money Pits** (geringer Impact, hoher Aufwand) sollen vermieden werden.

---

**Priorisierungsmatrix für MVP-Features (Folien 838–839):**

> Welche Features soll ein MVP haben?

**Drei Leitfragen (Folie 838):**
1. Welche **Businessziele** werden durch das Produkt unterstützt?
2. Welche **Nutzerziele** werden durch das Produkt unterstützt?
3. Mit welchem **Umsetzungsaufwand** rechnen wir?

Abgeleitet aus: Problemstatement, Konzeptideen, Aufwandsabschätzung.

**Aufbau der Matrix (Folie 839):**
- Zeilen: Features (z. B. „Mehr verwendbare Bundles", „Reduktion von Ablenkungen", „Effiziente Erfassung")
- Spalten: Kriterien (Gewichtung der Businessziele, Gewichtung Kundenneutzen, Gruppenleistungen, Übernahme von Formularen, Kürzlich verwendete Lösungen, Projektbudget)
- Zeilen-Summe: Punkte für Kundennutzen / Aufwand → Gesamtpunkte → Priorität

> **Hinweis:** „Die Priorisierungsmatrix gibt einen heuristischen Eindruck wieder!"

---

### 10. Nähe-Gesetz Definition mit Zeichnung

**Quelle:** Folien 409–412

**Definition:**
> „Objects that are near, or proximate to each other, tend to be grouped together."

Das **Gesetz der Nähe** (Law of Proximity) besagt: Elemente, die räumlich nah beieinander liegen, werden vom menschlichen Wahrnehmungssystem als Gruppe interpretiert — **ohne dass ein Rahmen oder eine Box nötig ist**.

**Implikation für Interface Design:**
- Kein Need für umrahmende Boxen zur Gruppierung von Elementen
- Whitespace kann Gruppen trennen; enger Abstand signalisiert Zusammengehörigkeit

**Zeichnung (schematisch):**
```
●  ●  ●    ●  ●  ●
●  ●  ●    ●  ●  ●
●  ●  ●    ●  ●  ●
  Gruppe 1      Gruppe 2
  (Nähe intern groß, Abstand zwischen Gruppen größer)
```
→ Vier enge Spalten werden als eine Gruppe wahrgenommen; werden zwei Spalten weiter beabstandet, entstehen zwei Gruppen.

**Interface-Beispiel (Folie 412 — „Die Post"):**
- Version 1: Suchfeld und Suchbutton haben gleichen Abstand zu Navigation → unklar, ob Suche zur Navigation gehört
- Version 2: Suchfeld direkt neben Suchbutton (enger Abstand) → wird klar als Sucheinheit wahrgenommen

→ Nähe allein reicht, um Elemente als Einheit zu kommunizieren.

---

### 11. Phasen und Artefakte im Collaborative UX Prozess

**Quelle:** Vorlesung, Folien 100–106 (Collaborative UX Design — Design Thinking | Lean UX | Agile Development | HCD)

**Grundstruktur: Double Diamond**
- **Problem Space** (1. Diamant): Research → Insights
- **Solution Space** (2. Diamant): Ideation → Prototypes

**3 Phasen im Collaborative UX Design:**

| Phase | Ziel | Workshops / Aktivitäten | Beispiel-Artefakte |
|---|---|---|---|
| **Understand** | User Needs verstehen, Chancen erkennen | Scoping, Research, Synthese | Proto-Problem Statement, Proto-Persona, Proto-Journey, Personas, Journey Map |
| **Explore** | User Interface Konzept entwickeln und validieren | Ideation, Konzept, Prototyping, Validierung | Sketches, Wireframes, Prototyp, Validierungsbefunde |
| **Deliver** | Screens für weitere Anwendungsfälle ausarbeiten — oft in Sprints | Spezifikation, Review, Detaildesign, Planung | Spezifikationen, Component Library, Sprint Backlog |

**Abgrenzung zum Wasserfallmodell:**
- Wasserfall = linear, sequentiell (Business → Designer → Engineer → User)
- Collaborative UX = iterativ, gegen den Wasserfall — kontinuierliches Feedback statt „fix it later"

**Von Research zur Synthese (Folie 203–204):**

| Stufe | Artefakte |
|---|---|
| **Proto-Problem-Statement** (Ausgangspunkt) | Proto-Problem Statement, Proto-Personas, Proto-Journey-Maps |
| **Research** (Feldforschung) | Beobachtung, Interviews, Fragebogen, Diaries |
| **Validiertes Problem-Statement** (Synthese) | Problem-Statement, Personas, Ist-Journey-Maps |

Research-Prozess im Detail: Proto-Artefakte → Forschungsfragen → Forschungsplan → Leitfaden → Interviews/Beobachtungen → Persona + Journey + Problem Statement

**Ideation in HCD — fehlende Phase (Folie 242):**
> In der ISO 9241-210 ist **Ideation explizit nicht enthalten** — der HCD-Prozess geht direkt von „Specify User Requirements" zu „Produce Design Solutions". Ideation ist eine eigenständige kreative Phase, die im Collaborative UX Prozess (Explore-Phase) ergänzt wird.

**Nutzungszenario / Use Scenario (Folie 266):**
- Beschreibt ein **konkretes Fallbeispiel** im kontextuellen Zusammenhang
- Enthält eine **Ausgangslage** und eine **Beschreibung des Ablaufs**
- Ist **nicht lösungsneutral** — abstrahiert noch von den Details der Interaktion
- Kann verschiedene Lösungsideen kombinieren
- Kann durch Skizzen oder ein Storyboard illustriert werden
- Beispiel: Sabine Frank erfasst Zeitrapporteinträge im Zug auf der Heimfahrt

**User Story Mapping (Folien 276–282):**
- User Stories aus der agilen Softwareentwicklung: benutzerzen­trierte Anforderungen statt technische Kriterien
- Formulierung: **„Als … (Rolle/Persona) möchte ich … (Ziel/Wunsch), um … (Nutzen)."**
- Bestandteile: Person (Nutzertyp/Rolle) + Ziel (Wunsch) + Nutzen (Intention)
- User Story Map: visualisiert Aufgaben nach **Priorität und Sequenz** — Überblick über relevante Aufgaben im Anwendungskontext

**Zweck (Folie 281):** Entwicklung eines holistischen Bildes über geplante Funktionalitäten + gemeinsames „Big Picture" im Team; Nutzer:innen im Mittelpunkt.

**Durchführung (Folie 282):**
1. User Stories aus Nutzerforschung vorliegen (keine bloßen Annahmen!)
2. Auf vertikaler Achse: **Ziel** oben → darunter **Aufgaben** nach Priorität (je höher die Aufgabe, desto wichtiger)
3. Aufgaben werden in **Teilaufgaben** gesplittet
4. Daraus: Priorisierung der wichtigsten Funktionen → nächste Maßnahmen ableiten

**Anmerkung:** Je mehr Stories gemappt werden, desto mehr Überschneidungen — diese helfen dabei, Key Features zu identifizieren.

**User/Customer Journey Map (Folien 205–218):**

> „Journey maps combine two powerful instruments — **storytelling and visualization** — in order to help teams understand and address customer needs."

Zweck: Die Interaktionen einer Zielgruppe mit einem Produkt oder Service **ganzheitlich** betrachten. Schafft einheitliches Verständnis der Nutzerziele, hilft Anforderungen zu definieren, entwickelt Empathie für Nutzer und zeigt Pain Points sowie Opportunity Areas auf.

**Customer Journey — Marketing-Phasen (Folie 206):**
1. **Awareness** — Bewusstsein für das Produkt wird geweckt
2. **Favorability** — Interesse wird verstärkt (Favorisierung)
3. **Consideration** — Kunde erwägt den Kauf (Wunsch)
4. **Intent to Purchase** — Kaufabsicht wird konkret (Anstoß)
5. **Conversion** — Das Produkt wird gekauft (Umsetzung)

**8 Elemente einer Journey Map (Folie 209–210):**

| # | Element | Beschreibung |
|---|---|---|
| 1 | **Who** | Persona |
| 2 | **What** | Scenario (+ Goals and Expectations) |
| 3 | **Phases** | Phasen der Journey |
| 4 | **Actions** | Was der Nutzer tut |
| 5 | **Thoughts** | Was der Nutzer denkt |
| 6 | **Emotional Experience** | Emotionale Kurve |
| 7 | **Opportunities** | Chancen für Verbesserungen |
| 8 | **Ownership** | Wer intern verantwortlich ist |

**3 Zonen:**
- **Zone A — The Lens:** Who (1) + What (2) — definiert Rahmen der Map
- **Zone B — The Experience:** Actions (4) + Thoughts (5) + Emotional Experience (6) — Herzstück
- **Zone C — The Insights:** Opportunities (7) + Ownership (8) — Erkenntnisse

**Journey Mapping Prozess (schrittweise, Folien 211–218):**
1. Persona + Scenario festlegen
2. Steps (Schritte der Journey) definieren
3. Details (Erkenntnisse aus Research) hinzufügen
4. Problems (Probleme) markieren
5. Insight Statements formulieren
6. Feelings (emotionale Kurve) einzeichnen
7. User Needs ergänzen
8. → **Opportunity Areas** ableiten

**Peak-End Rule (Folie 219, David Kahneman):**
> „A psychological heuristic in which people judge an experience largely based on how they felt **at its peak** (i.e., its most intense point) and **at its end**, rather than based on the total sum or average of every moment of the experience."

**5 Regeln für eine großartige Experience (Folie 220):**
1. Set expectations
2. Follow through
3. Reduce pain
4. **Wow strategically** (key moments!)
5. **End strong**

---

## Gruppe C

### 1. Sunk Cost Fallacy

**Quelle:** Folien 316–318

**Definition:**
> „Die Sunk Cost Fallacy bezeichnet die Tendenz, ein Projekt fortsetzen zu wollen, in das wir Geld, Mühe und Zeit investiert haben, **obwohl sich herausstellt, dass die laufenden Kosten in einem negativen Verhältnis zu den gewünschten Ergebnissen stehen.**"

Allgemeiner: Wir neigen dazu, mit einem Vorhaben fortzufahren, in das wir bereits viel investiert haben — auch wenn die Kosten den Nutzen bereits übersteigen.

**Sunk Cost Fallacy Loop:**
```
"We already spent so much time and money."
        ↓
"We need to stick to it and make it work."
        ↓ (zurück zum Start)
```

**Beispiel 1 — Concorde (klassisches Paradebeispiel):**
Im Januar 1976 hob die Concorde zu ihrem ersten kommerziellen Flug ab. Britische und französische Regierung hatten 2,8 Milliarden Dollar investiert. Als sich herausstellte, dass das Flugzeug nicht rentabel sein würde, pumpten die Investoren weitere 27 Jahre lang Geld in das gescheiterte Projekt.

**Beispiel 2 — Skireisen-Studie:**
Teilnehmende hatten versehentlich zwei Skireisen gebucht: Michigan (100 $) und Wisconsin (50 $). Zusatzinfo: Wisconsin macht mehr Spaß. Die Mehrzahl entschied sich trotzdem für Michigan — wegen der höheren Vorauszahlung.

**Relevanz für UX Design (Folie 316):**
> *„Thou shall not expend effort beyond the necessary — Start with raw sketches, don't use your computer!"*

Wer zu früh zu viel in Visual Design investiert, fällt in die Sunk Cost Fallacy Loop und kann Ideen nicht mehr loslassen. Deshalb: immer mit rohen Sketches beginnen — Lo-Fi ermöglicht schnelles Iterieren und verhindert emotionale Bindung an unfertige Konzepte.

---

### 2. Summative und formative

→ Vollständige Antwort: Gruppe A, Frage 2

**Kurzfassung (Folie 755 + 792):**

**Formative Evaluation:**
> Input für die **nächste Iteration** — was soll verbessert werden?

- Findet **während** des Designprozesses statt (früh, iterativ)
- Weniger Proband:innen nötig
- Ziel: Usability-Probleme erkennen und beseitigen
- **Analogie: Der Koch probiert die Suppe selbst** (→ kontrolliert laufenden Prozess)

**Summative Evaluation:**
> **Feststellung des Ist-Zustands** — wie gut ist das System?

- Findet am **Ende** (einer Phase oder Entwicklung) statt
- Höhere Anzahl von Proband:innen erforderlich (mehrere Nutzergruppen)
- Ziel: Messung gegen Baseline-Metriken
- **Analogie: Ein Gast probiert die Suppe** (→ Endbeurteilung)

---

### 3. Persona / Proto-Persona

→ Siehe Gruppe B, Frage 1 (vollständige Antwort dort)

**Kurzfassung:**
- **Proto-Persona**: Annahmenbasiert, hypothetisch, vom Team erstellt, Entwurfscharakter — basiert auf subjektiven Wahrnehmungen
- **Persona (validiert)**: Empirisch, auf echter Feldforschung basierend, in der Realität verankert

---

### 4. Heuristiken (2 erläutern)

→ Vollständige Liste aller 10 Heuristiken + psychologische Grundlagen: Aufgaben, Frage 4

**Überblick: Nielsens 10 Usability-Heuristiken (Nielsen & Molich, 1990):**
1. Sichtbarkeit des Systemstatus
2. Übereinstimmung von System und Wirklichkeit
3. Kontrolle und Freiheit für Nutzende
4. Beständigkeit und Standards
5. Fehlervermeidung
6. Wiedererkennen statt Erinnern
7. Flexibilität und Effizienz
8. Ästhetisches und minimalistisches Design
9. Unterstützung bei Erkennung, Diagnose und Behebung von Fehlern
10. Hilfe und Dokumentation

---

**Heuristik 1 — Sichtbarkeit des Systemstatus (Folie 764):**

> Nutzer:innen sollten stets wissen, wo sie sich im Prozess befinden und wie der aktuelle Systemstatus ist. Wird eine Aktion durchgeführt, wird eine unmittelbare Rückmeldung durch das System erwartet.

- Rückmeldung kann in Form von Ton, Animation oder Screenwechsel erfolgen
- Muss **unmittelbar**, **einfach verständlich** und **prägnant** sein
- **Beispiel:** Fortschrittsbalken beim Datei-Upload — Nutzer weiß in Echtzeit wie lange es noch dauert

**Psychologische Grundlage:** Foveales Sehen — Feedback muss dort platziert sein, wo der Nutzer gerade schaut (z. B. direkt beim Button, nicht oben auf der Seite)

---

**Heuristik 5 — Fehlervermeidung (Folie 769):**

> Gute Fehlermeldungen sind wichtig, aber ein sorgfältiges Design stellt sicher, dass Fehler erst gar nicht auftreten. Fehleranfällige Bedingungen sollen eliminiert oder zumindest durch Bestätigung gesichert werden.

- Zwei Fehlerkategorien:
  - **Ausrutscher** (Slips): Entstehen durch mangelnde Aufmerksamkeit
  - **Bewusste Fehler** (Mistakes): Entstehen durch Diskrepanz zwischen Nutzerverständnis und System
- **Beispiel:** Küchenschränke mit Stickern — vermeidet, dass Personen versuchen, Schränke von der falschen Seite zu öffnen (physisches Constraint-Design)
- Interface-Beispiel: Löschen-Aktion erfordert explizite Bestätigung (Confirmation Dialog)

---

### 5. Fitts'sches Gesetz

→ Vollständige Antwort: Gruppe B, Frage 3

**Kurzfassung:**
> „The time to acquire a target is a function of the distance to and size of the target."

- Formel: **T = a + b · log₂(D/W + 1)**
- Je größer und näher das Target, desto schneller erreichbar und fehlerärmer
- Mac-Menü nutzt vertikale Endlosigkeit → effektiv unbegrenzte Trefferfläche
- Implikation: Wichtige Buttons groß und nahe am Aktionsbereich positionieren

---

### 6. Gestaltungsgesetz und Interface-Beispiel

→ Vollständige Antwort: Gruppe A, Frage 6 (alle Gestaltgesetze mit Beispielen).

**Kurzfassung für Klausur — zwei Gesetze mit Interface-Beispiel:**

**1. Gesetz der Nähe:**
> Objekte, die räumlich nah beieinander sind, werden als Gruppe wahrgenommen.
- Interface-Beispiel: Suchfeld + Suchbutton direkt nebeneinander → klar als Sucheinheit erkannt. Kein umgebender Rahmen nötig.

**2. Gesetz der Ähnlichkeit:**
> Visuell ähnliche Elemente werden als zusammengehörig wahrgenommen.
- Interface-Beispiel: Alle Navigationspunkte in gleicher Farbe und Schriftart → werden als Navigation erkannt. Links visuell (Farbe, Unterstrich) von Fließtext unterschieden.

**3. Law of Common Region (Bonus):**
> Elemente innerhalb einer gemeinsamen Region (Rahmen, Hintergrundfarbe) werden als Gruppe wahrgenommen.
- Interface-Beispiel: Profilkarte (Foto + Name + Beschreibung in einer Card) → wird als Einheit gelesen.

**4. Continuity (Bonus):**
> Elemente, die in einer Linie oder Kurve angeordnet sind, werden als zusammengehörig wahrgenommen.
- Interface-Beispiel: Navigationsleiste — alle Items in einer horizontalen Linie → sofort als Einheit erkannt.

**5. Focal Point (Bonus):**
> Das Auge erfasst jene Elemente, die sich von der Umgebung abheben.
- Interface-Beispiel: Einziger farbiger Button auf monochromem Hintergrund → wird sofort als primäre Aktion erkannt (z. B. Uber „SIGN UP"-Button).

---

### 7. Progressive Disclosure

→ Vollständige Antwort: Gruppe B, Frage 8

**Kurzfassung:**
> Nur die typischerweise relevante Information wird angezeigt. Weniger wichtige Information wird in Schichten aufgeteilt und nur auf Aufforderung dargestellt.

**Vorteile:** Screens bleiben übersichtlich, Lernbarkeit verbessert, weniger Fehler.
**Nachteile:** Funktionen können versteckt wirken (Discovery-Problem), mehr Klicks nötig.
**Beispiel:** „Erweiterte Einstellungen"-Button — versteckt selten genutzte Parameter.

---

### 8. Euro-in-Dollar-Interface effizient erstellen

---

### 9. UX-Metriken und ihre Bedeutung

→ Vollständige Metriken-Tabelle: Gruppe B, Frage 4

**Quelle:** ISO 9241-11, Folien 778–786

**Die drei Kern-UX-Metriken (ISO 9241-11, 2018):**

| Metrik | Beschreibung | Messung |
|---|---|---|
| **Effektivität** | Werden Nutzerziele vollständig und korrekt erreicht? | Task Completion Rate |
| **Effizienz** | Mit wie viel Aufwand werden Ziele erreicht? | Time-on-Task, Fehleranzahl |
| **Zufriedenstellung** | Wie zufrieden sind Nutzende? | SUS, Likert-Skalen, Interviews |

**UX Evaluation Methods Matrix (Folie 778):**

|  | Qualitativ | Quantitativ |
|---|---|---|
| **Behavior** | Usability Testing, Walkthrough | A/B Testing, Analytics |
| **Opinion** | User Interviews | Questionnaire |

**Thinking Aloud (Folie 790):**
- Probanden verbalisieren, was ihnen bei der Aufgabe durch den Kopf geht
- Gibt Aufschluss über Denkprozesse und emotionale Reaktionen

---

### 10. System Usability Scale (SUS)

**Quelle:** Folien 815–819 (Brooke, 1996; Sauro, 2011)

**Definition:**
> Die System Usability Scale (SUS) ist ein branchenweit etablierter, standardisierter Fragebogen zur Messung der subjektiv wahrgenommenen Usability eines interaktiven Systems.

**Eigenschaften:**
- **10 Items** (Aussagen), die auf einer 5-Punkte-Likert-Skala bewertet werden (Stimme gar nicht zu → Stimme voll zu)
- **Technologieunabhängig** — kann bei jedem System (Software, Hardware, Web, App) eingesetzt werden
- **Robust bei kleinen Stichproben** — funktioniert auch bei wenigen Probanden
- **Kann bei jedem Reifegrad** des Systems verwendet werden

**Skalierung:**
- SUS-Score zwischen **0 und 100**
- **68** gilt als **Mittelwert** / Benchmark (basierend auf umfassenden Benchmark-Daten, Sauro 2011)

**Interpretation der Werte (Folie 817):**

| Bereich | Bewertung | Akzeptabilität |
|---|---|---|
| 0–51 | Sehr schlecht / Schlecht | Nicht akzeptabel |
| 51–68 | Okay | Grenzwertig |
| 68–80 | Gut | Akzeptabel |
| 80–90 | Exzellent | Akzeptabel |
| 90–100 | Perfekt | Akzeptabel |

**Beispiel (Folie 817):**
- Mobile-Variante: SUS-Score **74** (SD=10,3, n=4) → **gut** eingestuft, über Benchmark
- Desktop-Variante: SUS-Score **85,6** → **exzellent**

**Alternative: UMUX-Lite (Folien 818–819):**
> Kürzere Alternative zum SUS — nur **2 Fragen** statt 10.

- Geeignet für **Online-Befragungen** oder als Ergänzung zu anderen Fragebögen
- Hohe **Korrelation zum SUS** (r = 0,83) → erlaubt potentiellen SUS-Wert vorherzusagen
- Misst zwei Dimensionen separat: **Usefulness** und **Usability**
- Beispiel: UMUX-Lite Score 80,09 → vorhergesagter SUS-Wert: 74 → „gut"

**Einordnung in UX Evaluation Methods Matrix:**
- SUS / UMUX-Lite = **Opinion + Quantitativ** (Questionnaire-Zelle in der Matrix)
- Typisch kombiniert mit Usability Testing (Behavior + Qualitativ) → **Triangulation**

---

## Aufgaben

### 1. Progressive Disclosure (Vorteile / Nachteile / eigenes Beispiel)

→ Vollständige Definition und Kontext: Gruppe B, Frage 8

**Definition:**
> Nur die typischerweise relevante Information wird angezeigt. Weniger wichtige Information ist in Schichten aufgeteilt und wird nur auf Aufforderung dargestellt.

**Kontext: Hick's Law + Choice Overload**
- Mehr Optionen = mehr Entscheidungszeit (Hick's Law)
- Zu viele Optionen können zur Analysis Paralysis führen (Paradox of Choice)
- Progressive Disclosure ist eine direkte Antwort auf dieses Problem

**Vorteile:**
1. Interface bleibt übersichtlich → Clutter vermieden
2. Lernbarkeit verbessert: User beginnen einfach, lernen schrittweise mehr
3. Informationen, die der User nicht braucht, sind Noise → werden ausgeblendet
4. Weniger Fehler, kürzere Lernzeit

**Nachteile:**
1. Funktionen können schwer findbar sein (Hidden Affordance)
2. Mehr Interaktionsschritte nötig, um zur versteckten Information zu gelangen
3. Power-User müssen sich durch mehrere Schichten klicken

**Eigenes Beispiel:**
- **E-Mail-Client (z. B. Gmail):** Standard-Ansicht zeigt nur To, Subject, Body. „CC / BCC" erscheinen erst nach Klick → Gelegenheits-User werden nicht überfordert, Power-User finden CC trotzdem.
- **Formular mit „Erweiterte Einstellungen":** Basis-Einstellungen immer sichtbar; selten genutzte Parameter erst nach Klick auf Button — reduziert initiale Komplexität ohne Funktionsverlust.

---

### 2. Bild bewerten (z. B. Ticketautomat)

**Quelle:** Fallstudie „Fixing a UI design in 16 steps" (Dannaway, 2023), Folien ~662–680

Beim Bewerten eines Interface-Bilds systematisch vorgehen — die folgenden Fragen/Kriterien anwenden:

---

#### Bewertungsrahmen: 8 Leitfragen

**1. Gruppierung (Use space to group related elements)**
> Werden zusammengehörige Elemente durch Abstände/Container klar gruppiert?
- Problem: Alles gleich weit entfernt → keine Struktur erkennbar
- Lösung: Abstand zwischen Gruppen > Abstand innerhalb einer Gruppe (Proximity)

**2. Konsistenz (Be consistent)**
> Sehen ähnliche Elemente gleich aus und verhalten sich gleich?
- Problem: Icons teils gefüllt, teils nicht → suggeriert falschen „Selected"-State
- Lösung: Einheitlicher Stil (z. B. alle Icons mit 2pt Strich, einheitliche Ecken)
- Text Labels zu Icons hinzufügen → Screen-Reader-Zugänglichkeit

**3. Gleich aussehen = gleich funktionieren (Similar looking = function similarly)**
> Sehen nur interaktive Elemente interaktiv aus?
- Problem: Icon-Container hat denselben visuellen Stil wie ein Button → wirkt interaktiv, ist es aber nicht
- Lösung: Nicht-interaktive Elemente ohne Button-Styling; Farbe nur für tatsächlich klickbare Elemente

**4. Visuelle Hierarchie (Create a clear visual hierarchy)**
> Sticht das Wichtigste hervor?
- Problem: Alle Textelemente gleich prominent — kein Call-to-Action erkennbar
- Lösung: Größe, Kontrast, Gewicht (fett/dünn), Farbe gezielt zur Priorisierung einsetzen
- Primäre Aktion = prominentestes Element

**5. Squint Test (als Methode)**
> Augen zusammenkneifen oder Design unscharf stellen: Was sieht man zuerst?
- Der primäre Call-to-Action sollte auch beim unscharfen Sehen sofort hervorstechen
- Wenn mehrere Elemente gleich stark konkurrieren → Hierarchie fehlerhaft

**6. Unnötige Stile entfernen (Remove unnecessary styles)**
> Gibt es Linien, Rahmen, Hintergründe, die keine Information tragen?
- Problem: Rahmen um Bilder, Whitespace-Elemente ohne Funktion → erhöhen cognitive load
- Lösung: Alles entfernen, was nicht zur Informationsübermittlung oder Gruppierung beiträgt (→ Tufte)

**7. Farbe gezielt einsetzen (Use colour purposefully)**
> Wird Farbe zur Bedeutungsvermittlung genutzt oder nur dekorativ?
- Problem: Blauer Titel wirkt wie ein Link → nicht interaktiv, also nicht blau
- Lösung: Markenfarbe nur für interaktive Elemente (Links, Buttons); nicht-interaktive Elemente neutral

**8. Kontrast (WCAG 2.1 Level AA)**
> Sind Kontrastverhältnisse ausreichend?
- Interface-Elemente (Buttons, Felder, Icons): mind. **3:1** Kontrastverhältnis
- Text (klein ≤18px): mind. **4.5:1** Kontrastverhältnis
- Großtext (>18px regulär oder >14px fett): mind. **3:1**
- Problem: Pfeil-Icon auf Foto → zu wenig Kontrast → mit weißem Hintergrundkreis verstärken

---

#### Fortsetzung: Typografie und Barrierefreiheit (Seiten 341–354, Fallstudie Dannaway)

**9. Textkontrastwert sicherstellen (Seite 341)**
> „Ensure text has a 4.5:1 contrast ratio"
- Auch dünne Schriftgewichte mit ausreichendem Helligkeitskontrast verwenden
- Dunklere Grautöne für Body-Text wählen, um Mindest-Kontrastverhältnis zu erreichen

**10. Nicht allein auf Farbe verlassen (Seite 342)**
> „Don't rely on colour alone as an indicator"
- Links nur durch Farbe (z. B. blau) zu kennzeichnen reicht nicht — Farbfehlsichtige können den Link nicht erkennen
- Lösung: **Redundante Kodierung** = Unterstreichung + Farbe
- Gilt für alle bedeutungstragenden Elemente: immer mindestens zwei unabhängige Kanäle nutzen

**11. Eine einzige Sans-Serif-Schrift verwenden (Seite 343)**
> „Use a single sans serif typeface"
- Sans-Serif-Schriften sind lesbarer, neutraler, einfacher als Serif-Schriften
- Serifs können für manche Nutzer ablenken oder schwer lesbar wirken
- Maximal eine Schriftfamilie im Interface-Design verwenden

**12. Schriftart mit hoher x-height wählen (Seiten 344–345)**
> „Use a typeface with taller lower case letters"
- **x-Height** = Höhe der Kleinbuchstaben in einem Schriftschnitt
- Höhere x-Height → bessere Lesbarkeit bei kleinen Größen
- Beispiel: Inter (hohe x-Height) besser lesbar als League Spartan (niedrige x-Height)

**13. Großschrift einschränken (Seite 346)**
> „Limit the use of uppercase"
- Großschrift erzwingt buchstabenweises Lesen statt Worterkennung (→ Wortform monotone Rechtecke)
- Beim Lesen wird die **Form des Wortes** erkannt, nicht die einzelnen Buchstaben → All Caps verhindert das
- Statt ALL CAPS: Sentence case verwenden (nur erster Buchstabe + Eigennamen groß)

**14. Nur Regular und Bold verwenden (Seiten 348–349)**
> „Use regular and bold font weights only"
- Viele verschiedene Schriftgewichte = Noise und Clutter
- Designsystem einfach halten: Regular für Body-Text, Bold für Überschriften
- Sehr dünne (Light) oder sehr dicke Gewichte nur für Überschriften/großen Text

**15. Text linksbündig ausrichten (Seiten 350–351)**
> „Left align text"
- Englisch (und Deutsch) wird links-nach-rechts gelesen → linksbündige Ausrichtung optimal
- Zentrierter Text bei langen Absätzen schwer lesbar: Zeilenbeginn wechselt ständig, Auge muss suchen
- Zentrierte Ausrichtung nur für Überschriften und kurze Texte akzeptabel

**16. Mindestens 1,5-facher Zeilenabstand (Seiten 352–353)**
> „Use at least 1.5 line height for body text"
- **Line Height** = vertikaler Abstand zwischen zwei Textzeilen
- Zu geringer Abstand → Nutzer liest dieselbe Zeile mehrfach
- Empfehlung: Line-Height 1.5–2.0 (150–200 %) für Fließtext

---

#### Zusammenfassung: Typische Mängel und ihre Ursachen

| Mangel | Ursache | Lösung |
|---|---|---|
| Kein klarer Fokuspunkt | Fehlende Hierarchie | Größe/Kontrast/Gewicht gezielt einsetzen |
| Gruppenunklarheit | Gleiche Abstände überall | Proximity-Regel (Abstand zwischen > innerhalb Gruppen) |
| Inkonsistente Elemente | Keine Designsprache | Einheitlichen Stil für alle gleichen Elemente |
| Überladenheit / Clutter | Zu viele Stile und Rahmen | Unnötige Stile entfernen (Tufte) |
| Farbverwirrung | Farbe nicht bedeutungstragend | Farbe nur für interaktive Elemente |
| Zugänglichkeitsprobleme | Zu geringer Kontrast | 3:1 (UI) / 4.5:1 (Text) sicherstellen |
| Schlechte Lesbarkeit | All Caps, schlechte x-Height, zu viele Gewichte | Sans-Serif, hohe x-Height, nur Regular+Bold, Sentence Case |
| Unlesbarer Fließtext | Zentriert oder Zeilenabstand < 1.5 | Linksbündig + Line-Height ≥ 1.5 |

---

### 3. Noise vs. Clutter im Interface Design

**Quelle:** Folien 348–352

**Visual Noise (Folie 349):**
> Unnötige visuelle Elemente — Ablenkung von visuellen Elementen, die **Funktionalität und Verhalten** einer Anwendung kommunizieren.

→ Noise stört die Wahrnehmung relevanter Inhalte.

**Leitsatz (Antoine de Saint-Exupéry):**
> „Perfektion ist dann erreicht, wenn nichts mehr weggenommen kann — nicht, wenn nichts mehr hinzugefügt werden kann."

→ Gutes UI-Design bedeutet **Reduktion auf das Wesentliche**, nicht das Hinzufügen von immer mehr Elementen.

**Cluttered Interfaces (Folie 350):**
- Exzessives Drängen von Informationen in zu kleinen **Screen Real Estate**
- Resultat: **Interferieren von UI-Elementen** — Elemente konkurrieren miteinander, statt zu unterstützen

**Noise vs. Clutter — Unterschied:**
| Begriff | Bedeutung |
|---|---|
| **Visual Noise** | Überflüssige Elemente, die keine Information transportieren (Dekoration, übermäßige Linien, Hintergründe) |
| **Clutter** | Zu viele relevante Elemente auf zu wenig Raum — erzeugt Überlastung, obwohl jede Info relevant sein könnte |

**3D in Visualisierungen (Folie 352):**
> „3D can make visualizations harder to understand."
→ 3D fügt visuelle Komplexität hinzu, ohne Informationswert zu erhöhen — klares Beispiel für unnötigen Noise.

**5 Grand Principles of Data Visualization (Edward Tufte, Folien 355–358):**
1. **Above all else show the data** — Betrachter soll über den Inhalt nachdenken, nicht die Form
2. **Maximize the data-ink ratio** — Data-ink = Tinte, die tatsächlich Daten zeigt; Verhältnis data-ink / total ink maximieren
3. **Erase non-data-ink** — Alle unnötigen Nicht-Daten-Elemente eliminieren (z. B. übermäßige Gitternetzlinien, Rahmen)
4. **Erase redundant data-ink** — Jede Tinte entfernen, die dieselbe Information doppelt zeigt
5. **Revise and edit** — Erste Version durch Überarbeitung klären

**Praxisbeispiel Tufte (Folien 359–364) — schrittweise Vereinfachung:**
1. Ausgangszustand (mit Hintergrund, Rahmen, Gitternetz)
2. Eliminierung des Hintergrunds
3. Eliminierung des Rahmens
4. Einführen strukturierender Segmente (dezente Hilfslinien)
→ Jeder Schritt reduziert non-data-ink, ohne Erkennbarkeit zu verlieren.

**Zu wenig des Guten? (Folie 364):**
Tufte zeigt auch die untere Grenze: Werden Balken durch bloße vertikale Linien ersetzt, entsteht neue Unleserlichkeit. Reduktion muss enden, wenn die Wahrnehmbarkeit der Datenmuster leidet. Ziel: **minimale, aber ausreichende Datendarstellung**.

**Tufte-Anwendung: Tabellen-Design (Folien 625–631)**

Schrittweise Vereinfachung einer Datentabelle — Tufte-Prinzipien in der Praxis:

| Schritt | Maßnahme | Begründung |
|---|---|---|
| Ausgangslage | Vollständige Tabelle mit Rahmen + vertikalen Linien | Viel non-data-ink |
| Schritt 1 | Vertikale Linien entfernen | Nicht notwendig — Spalten-Abstände reichen zur Trennung |
| Schritt 2 | Äußeren Rahmen entfernen | Nicht notwendig — Whitespace trennt Tabelle von Umgebung |
| Schritt 3 | Horizontale Linien zurücknehmen | Nur Trennlinie unter Kopfzeile nötig |
| Schritt 4 | **Ähnlichkeitsgesetz** für Kopfzeile: Fettschrift | Header hebt sich durch Gewicht ab — Gesetz der Ähnlichkeit |

**Erkennen vor Erinnern — Gruppierungen (Folien 631–632):**

> User können sich bei langen Listen besser zurechtfinden, wenn sinnvolle Gruppen vorhanden sind.

- Ungruppierte Liste (18 Getränke): User muss alles zählen und merken — Recall-intensive Aufgabe
- Mit Abständen zwischen Kategorien: sofortiges Erkennen von Gruppen (z. B. Limonaden, Milchprodukte, Wein, Bier, Tee) → Recognition statt Recall
- Noch hilfreicher: **Kategorie-Labels** (Überschriften) — User betrachtet zuerst Hauptbegriff, dann Details der Gruppe

→ Verbindung zur Nielsen-Heuristik „Recognition rather than Recall" + Hick's Law (Kategorisierung reduziert wahrgenommene Optionsanzahl)

---

### 4. Heuristiken (Nielsen) mit psychologischen Grundlagen

**Nielsens 10 Usability-Heuristiken — Vollständige Liste (Folien 763–774):**

| # | Heuristik (DE) | Heuristik (EN) |
|---|---|---|
| 1 | Sichtbarkeit des Systemstatus | Visibility of System Status |
| 2 | Übereinstimmung von System und Wirklichkeit | Match Between System and the Real World |
| 3 | Kontrolle und Freiheit für Nutzende | User Control and Freedom |
| 4 | Beständigkeit und Standards | Consistency and Standards |
| 5 | Fehlervermeidung | Error Prevention |
| 6 | Wiedererkennen statt Erinnern | Recognition Rather Than Recall |
| 7 | Flexibilität und Effizienz | Flexibility and Efficiency of Use |
| 8 | Ästhetisches und minimalistisches Design | Aesthetic and Minimalist Design |
| 9 | Unterstützung bei Erkennung, Diagnose und Behebung von Fehlern | Help Users Recognize, Diagnose, and Recover from Errors |
| 10 | Hilfe und Dokumentation | Help and Documentation |

**Entstehung:** Entwickelt von Jakob Nielsen und Rolf Molich in den 90ern. Aufbauend auf Heuristiken, die aus einer empirischen Analyse von **249 Usability-Problemen** destilliert wurden (Folie 761).

---

**Psychologische Grundlage: Visuelle Wahrnehmung und foveales Sehen (Folien 382–391)**

**Visuelle Wahrnehmung — dominanter menschlicher Kanal:**
- Beschäftigt grob **50 % des menschlichen Cortex**
- Ca. **70 % der sensorischen Rezeptoren** entfallen auf den visuellen Apparat
- **80 % der aufgenommenen Information** wird über den visuellen Kanal verarbeitet
- Intelligentes Verhalten greift auf die menschliche Fähigkeit zur **Mustererkennung** zurück

**Foveales Sehen (Folie 384):**
- Vom Zentrum des schärfsten Sehens (**Fovea**) nimmt die Auflösung zur Peripherie ab
- Das foveale Sehen ist auf eine eng gefasste Fläche limitiert: **ca. Daumennagel bei ausgestrecktem Arm**
- Farbwahrnehmung ebenfalls: Im Zentrum zuverlässig, nach außen nur noch Dunkel/Hell-Unterscheidung

**Klassisches Experiment (Clark, 1998, Folie 386):**
- Eye-Tracker bestimmt fovealen Fokus einer lesenden Person
- Alle Buchstaben außerhalb des Fokus werden zu zufälligen Zeichen konvertiert
- **„Participants do not notice the manipulation"** → Wir lesen in Wahrheit nur einen kleinen Bereich scharf

**Abgeleitete Guideline: Lokales Feedback (Folien 389–391):**
> „Show the user where the error occurred and provide a reason." (**Specify errors inline**)

- Eine oben platzierte Erfolgsmeldung (z. B. „Daten gespeichert") kann leicht übersehen werden
- Im Moment des Button-Drückens liegt der visuelle Fokus **auf dem Button** — daher: Feedback direkt beim Button platzieren → wird sofort foveal wahrgenommen
- Psychologische Grundlage: foveales Sehen, nicht periphere Wahrnehmung

**Periphere Wahrnehmung (Folie 392):**
- Liefert niedrig aufgelöste Hinweise zur schnellen **Orientierung der fovealen Wahrnehmung**
- Erkennt Bewegung → Einsatz bei animierten Bannern (bewusst oder unbewusst ablenkend!)

**Sehen als aktiver Konstruktionsprozess (Folie 393):**
- **Sehen ≠ Spiegel der Umwelt** — das Gehirn konstruiert aktiv eine Interpretation
- **Bottom-up**: Verarbeitung von Rohdaten der Retina nach oben
- **Top-down**: Vorannahmen aus Wissen und Zielen beeinflussen Wahrnehmung
- Abhängig von: **Erfahrungen/Wissen** (Vergangenheit) · **Ziele** (Zukunft) · **Kontext** (Gegenwart)
- Beispiel Kontext: „1N73LL1G3NC3" wird als „INTELLIGENCE" gelesen — Kontext ermöglicht das

**Nielsen-Heuristik: Ästhetisches und minimalistisches Design (Folien 472–480)**

> Dialoge sollen keine irrelevanten oder selten benötigten Informationen enthalten. Jede zusätzliche Information steht in Konkurrenz zu relevanten Informationen und vermindert deren relative Sichtbarkeit.

**Psychologische Grundlage: Subitizing + Parallele Wahrnehmung (Folien 464–469)**

Die Heuristik ist direkt aus der menschlichen Wahrnehmungspsychologie abgeleitet:
- Parallele Wahrnehmung funktioniert nur bei ~4 Elementen → mehr Elemente = kognitive Überlast
- Subitizing: Bis 4 Objekte sofort erfassbar (50ms/Obj.), ab 6 Objekte zählen nötig (250-300ms/Obj.)

**Gruppierung und Abstände — Praktische Anwendung (Folien 472–480):**

| Designregel | Wirkung |
|---|---|
| Elemente durch Abstände gruppieren (Proximity) | Einheiten werden sofort wahrgenommen |
| Abstände **zwischen** Feldern > Abstände **zwischen** Label und Feld | Label gehört zum Feld; Felder sind klar getrennt |
| Zu große Abstände = keine Gruppenbildung | Interface wirkt unnötig komplex, alles wirkt singular |
| Farbe als Hintergrund für Gruppen nutzen | Drastische Reduktion wahrgenommener Objekte — Interface wirkt weniger komplex |

**Konkrete Abstandsregel (Folie 480 — „Mit Abständen arbeiten"):**
- Abstand **zwischen Eingabefeldern** > Abstand zwischen Label und zugehörigem Eingabefeld
- → Label wird dem Feld eindeutig zugeordnet
- → Gruppe (Label + Feld) wird durch größeren Abstand zum nächsten Label-Feld-Paar deutlich

**Farbkonventionen (kognitive Ebene, Folie 505–507):**

> „Eine (kognitive) Ebene höher: Farbkonventionen"

Gelernte Farbkonventionen beeinflussen, **wie Nutzer Interfaces interpretieren** — unabhängig von Gestaltgesetzen:
- **Grün = OK / Erfolg**, **Rot = Fehler / Gefahr** (westliche Konvention)
- Gegenbeispiel (Folie 505): Dialog „Delete All Records" — Yes-Button = grün, No-Button = rot
  → Grün suggeriert „alles gut" — aber die Aktion ist destruktiv. Konvention widerspricht Intention!
- Weitere Beispiele:
  - Fehlermeldung in gelbem Banner + Ausrufezeichen → wirkt wie Warnung, nicht Fehler
  - Grüner Haken + grüner Text → wird als Erfolg erkannt → beste Kommunikation

**Regeln für Farbzurückhaltung (Folie 520):**
- **Wenige Farben** — Signalfarben reservieren für wichtige Aufmerksamkeitssteuerung
- **Vorsicht mit Rot+Blau**: diametrale Pole des Farbspektrums — gleichzeitige Lesbarkeit anstrengend
- **Blauer Text**: ca. **4× mehr Lesefehler** als schwarz/weiß (1 vs. 4/1000 bei grün/weiß vs. blau/weiß)
- **Kulturabhängig**: Farben haben je nach Kulturraum verschiedene Bedeutungen
- Allgemein: **„Design in monochrome first"** (bestätigt Greyscale-First-Prinzip)

**Nielsen-Heuristik: Recognition rather than Recall (Folie 557)**

> „Minimize the user's memory load by making objects, actions, and options visible. The user should not have to remember information from one part of the dialogue to another."

- **Recall**: Ungestützter Zugriff auf Gedächtnisinhalte (User muss sich eigenständig erinnern)
- **Recognition**: Wiedererkennen von (externen) Stimuli aus einer vorgegebenen Auswahl
- **Recognition ist Recall typischerweise deutlich überlegen**

Interface-Beispiel:
- Kommandozeile: `copy doc1 doc2` → User muss Befehl **erinnern** (Recall) — hohe kognitive Last
- GUI-Menü: Auswahl aus Liste → User **erkennt** den richtigen Menüeintrag (Recognition) — niedrige kognitive Last
→ Das WIMP-Paradigma (Windows, Icons, Menus, Pointer) basiert auf Recognition statt Recall

**Lesen — Fixationen und Sakkaden (Folie 523):**

**Fixationen:**
- Dauer: ~200–300 ms
- In dieser Zeit findet die eigentliche **Aufnahme von Information** statt

**Sakkaden:**
- Extrem schnelle Augenbewegungen zur räumlichen Sequenzierung der Fixation (~50 ms)
- Gerade Linien = Vorwärtssakkaden; Bögen = Regressions-Sakkaden (Rücksprünge)

**Stroop-Effekt — Lesen als automatisierte Fertigkeit (Folien 524–526):**
> Lesen ist eine so stark automatisierte Fertigkeit, dass sie schwerer zu unterdrücken ist als die Wahrnehmung von Farbe.

Experiment: Farbwörter in falscher Farbe benennen (z. B. „ROT" in blau geschrieben → Farbe = blau nennen)
- **Average Stroop**: ~40 Sekunden für 30 Wörter (kognitiver Konflikt durch Interferenz)
- **Average Matching**: ~17 Sekunden (Wortfarbe stimmt mit Inhalt überein)
→ Konsequenz: Farbkodierung im Interface darf nicht im Widerspruch zu konventionellen Bedeutungen stehen (→ Delete-Dialog-Problem)

**All Caps / Großschrift (Folien 527–528):**
- Lesbarkeit hängt von der **oberen Hälfte** der Buchstaben ab
- Großschrift erzeugt **monotone Rechtecke** — Wortformen sind nicht unterscheidbar
- Gemischte Groß-/Kleinschrift: Wortformen klar erkennbar → deutlich besser lesbar
→ Längere Texte nie in ALL CAPS setzen

**Scannability und F-Pattern (Folien 534–535):**

> „Scannable content gestattet Nutzenden einen schnellen Überblick: Was interessiert sie, was soll gelesen werden?"

- Nutzer **lesen** Webseiten nicht vollständig — sie **scannen** zunächst
- **Nielsen's F-Pattern**: Nutzer schauen zuerst horizontal oben, dann kürzer horizontal in der Mitte, dann vertikal links hinunter → F-Form im Eye-Tracker
- Strukturierter Text (Überschriften, Absätze) wird schneller erfasst als Fließtextblöcke

**Interferenz (Folie 559–560) — Konsistenz und Lernbarkeit:**

> Design A, B oder C: Was ist am Besten erlernbar?

Beispiel Keyboard Shortcuts für einen Document Editor:
- **Design A**: Gleiche Shortcuts (CTRL-X / CTRL-V) für alle Objekttypen (Text, Sketch, Table, Image, Video) — **konsistent**
- **Design B/C**: Unterschiedliche Shortcuts je Objekttyp — hohe Interferenz, schwer zu lernen

→ Konsistenz (Interaction Design Prinzip) reduziert Interferenz im Arbeitsgedächtnis — einmal Gelerntes muss nicht überschrieben werden
→ Verbindung zum Konsistenz-Prinzip (Interaction Design, Folie 69)

**Unterscheidbarkeit (Folien 621–624)**

> „Unterschiedliche Elemente werden auch **deutlich unterschiedlich** dargestellt."

- Elemente, die sich in ihrer Funktion unterscheiden, müssen sich **visuell klar unterscheiden**
- Problem-Beispiel: Eingabefelder und Buttons sehen identisch aus → User weiß nicht, was anklickbar ist und was eingegeben werden soll
- Problem-Beispiel 2: Labels und Feldinhalt in gleicher Schriftgröße/Farbe → nicht unterscheidbar (View vs. Edit Mode)

**Praxis-Beispiele (Folien 623–624):**
- Adressverwaltungs-Interface: Alle Felder gleich grau → Buttons und Eingabefelder visuell kaum differenzierbar (schlecht)
- Ohne visuelle Unterscheidung: User kann „Speichern"-Button nicht von Eingabefeld unterscheiden

**Lösung:**
- Eingabefelder: umrandet, weißer Hintergrund
- Buttons: gefüllte Farbe, klare Beschriftung, andere Form
- Labels: grauere, kleinere Schrift → vom Inhalt der Felder unterscheidbar

---

**Nielsen-Heuristik: Flexibilität und Effizienz der Nutzung (Flexibility and Efficiency of Use)**

> „Accelerators — unseen by the novice user — may often speed up the interaction for the expert user such that the system can cater to both inexperienced and experienced users."

- Experten-Nutzer können schneller arbeiten, wenn das System Abkürzungen bietet, die für Anfänger unsichtbar sind
- Das System muss beide Nutzertypen unterstützen

**Beispiel — Keynote vs. PowerPoint (Folie ~658):**
- **Keynote (gut):** Nach dem Start werden sofort die **zuletzt genutzten Vorlagen** angezeigt — der häufigste Anwendungsfall ist sofort zugänglich
- **PowerPoint:** Zeigt nach dem Start direkt die **zuletzt genutzten Dateien** an — noch näher am typischen Nutzungsfluss
- → „Zuletzt verwendete Objekte anbieten" = Accelerator für erfahrene Nutzer; reduziert Schritte zur Zielerreichung

**Weitere Acceleratoren im Interface:**
- Keyboard Shortcuts (sichtbar im Menü, aber primär für Experten)
- Default-Auswahlen vorbelegen (häufigste Option)
- Auto-Complete für Texteingaben
- Zuletzt verwendete Objekte / Dokumente anbieten

---

**Logischer Fluss (Achten Sie auf einen logischen Fluss — Folie ~660)**

> „Good logical flow: Eye movements match the path through the interface."
> „Bad logical flow: Everything is all over the place."

- Augenbewegungen des Nutzers sollten dem natürlichen Lesefluss (oben-links → unten-rechts) folgen
- Schlechtes Design zwingt Augen zu springen: hohe kognitive Last, Orientierungsverlust
- Verbindung zur Nielsen-Heuristik „Ästhetisches und minimalistisches Design": klare Hierarchie = logischer Fluss

---

**Buttons im korrekten State (Folie ~635)**

> Buttons müssen den aktuellen Systemstatus widerspiegeln — interaktiv wenn möglich, deaktiviert wenn nicht.

- **Greyed-out Buttons** (deaktiviert): wenn keine Aktion möglich ist (z. B. „Speichern" ohne Änderungen)
- **Aktive Buttons** (farbig, klickbar): wenn eine Aktion ausführbar ist
- Verbindung zu Nielsen-Heuristik: Visibility of System Status + Constraints (physische/logische Einschränkungen)
- Beispiel: Adress-Interface — „Abbrechen" und „Speichern" sind grau wenn kein Edit-Modus aktiv; sobald User etwas ändert, werden Buttons aktiv

---

**Squint Test — Methode zur Hierarchieprüfung (Folie ~672)**

> „Simply squint your eyes and look at your design."

- Augen zusammenkneifen, zurücktreten oder Design unscharf stellen
- Man sollte noch erkennen können: a) was das wichtigste Element ist, b) wofür das Interface ist
- **Problem-Indikator:** Wenn mehrere Elemente gleich stark hervorstechen, fehlt eine klare Hierarchie
- **Der primäre Call-to-Action** sollte auch unscharf sofort sichtbar sein: hoher Kontrast-Hintergrund + fette Schrift
- Verbindung zu: Visual Hierarchy, Focal Point, Priorisierung

---

**Kontrastwerte: WCAG 2.1 Level AA (Folien ~678–680)**

| Typ | Mindest-Kontrast |
|---|---|
| **Interface-Elemente** (Buttons, Felder, Icons) | **3:1** |
| **Kleiner Text** (≤18px oder ≤14px fett) | **4.5:1** |
| **Großer Text** (>18px regulär / >14px fett) | **3:1** |

- Kontrast = wahrgenommene Helligkeitsdifferenz zwischen zwei Farben, ausgedrückt als Verhältnis (1:1 bis 21:1)
- Schwarz auf Weiß = 21:1 (höchster Kontrast)
- Schwarz auf Schwarz = 1:1 (kein Kontrast)
- **Figma-Plugins** helfen beim Messen des Kontrastverhältnisses
- Kontrast erhöhen: weißen Hintergrundkreis hinter Icon, Opazität des Containers erhöhen, Textschatten hinzufügen

---

**Heuristik 2 — Übereinstimmung von System und Wirklichkeit (Folie 765)**

> Das System sollte die Sprache der Benutzenden sprechen, mit Worten, Sätzen und Konzepten, die ihnen bereits vertraut sind. Auf systemorientierte oder technische Begriffe sollte verzichtet werden.

- In der digitalen Welt helfen Bezeichnungen oder Modelle, die der analogen Welt entsprechen → **Mentale Modelle**
- **Beispiel:** Windows-Taschenrechner — Design ist dem physischen Taschenrechner aus der realen Welt nachempfunden (Layout, Tasten, Funktion)
- **Negativbeispiel:** Apple App Store Keyword-Feld → technische Fehlermeldung „Keywords for German cannot be longer than 100 bytes" — Nutzer denkt in Zeichen, nicht Bytes

---

**Heuristik 3 — Kontrolle und Freiheit für Nutzende (Folie 767)**

> Nutzer:innen sollen jederzeit die Kontrolle darüber haben, eine Systemfunktion zu verlassen oder eine getätigte Aktion rückgängig zu machen.

- Hierzu gehört der Überblick, wo man sich im Prozess befindet, und die Möglichkeit, den Prozessschritt einfach zu wechseln
- Wurde fälschlicherweise ein Item ausgewählt oder hinzugefügt, sollte es wieder abgewählt oder gelöscht werden können
- **Beispiel:** Gmail „Nachricht gesendet" — das System bietet für wenige Sekunden die Option an, die Sendung rückgängig zu machen

---

**Heuristik 4 — Beständigkeit und Standards (Folie 768)**

> Wörter, Interaktionselemente oder Navigationselemente sollten stets konsistent sein. Die Definition von Standards über das gesamte System ist dafür unabdingbar (z. B. Content Guidelines, Styleguides). Auch systemübergreifende Standards sollen berücksichtigt werden.

- **Beispiel:** Buttons aus Plattform-Libraries (z. B. Google Material Design) haben in verschiedenen Systemen stets dieselbe Funktion → systemübergreifende Konsistenz

---

**Heuristik 9 — Unterstützung bei Erkennung, Diagnose und Behebung von Fehlern (Folie 772)**

> Fehlermeldungen sollten in einer einfachen und prägnanten Sprache verfasst sein. Sie erklären das Problem und schlagen konstruktive Lösungen vor.

- Erhalten wir eine Fehlermeldung, möchten wir direkt die Ursache und Lösung sehen — keinen kryptischen Error-Code
- Auch der Zeitpunkt, wann die Fehlermeldung erscheint, ist relevant für die Nutzendenerfahrung
- **Beispiel:** Passwortfeld — schon während der Eingabe erhalten wir Feedback, welche Passwortregeln bereits erfüllt sind und welche noch ausstehen (Inline-Validierung, Folie 772)

---

**Heuristik 10 — Hilfe und Dokumentation (Folie 773)**

> Ein System sollte in seiner Anwendung möglichst selbsterklärend sein. Sollten Dokumentationen oder FAQs notwendig sein, sollen sie in verständlicher Sprache geschrieben und einfach auffindbar sein.

- Kommt man bei einer Aufgabe nicht weiter und muss sie erledigen, so werden Lösungen in einer Dokumentation oder beim Support-Dienst gesucht
- **Beispiel:** Microsoft Word — bietet Hilfe, Feedback, Schulung, Neuigkeiten im Hilfe-Menü an

---

**Heuristische Evaluation — Methode und Phasen (Folien 761–776)**

> Entwickelt von Jacob Nielsen und Rolf Molich in den 90ern. Basierend auf einer empirischen Analyse von **249 Usability-Problemen** destillierte Designrichtlinien als „Usability-Faustregeln".

**3 Phasen der Heuristischen Evaluation (Folie 762):**

| Phase | Beschreibung |
|---|---|
| **Phase 1: Einführung** | Evaluatoren werden auf Grundlage eines vorbereiteten Scripts in Ziele der HE eingeführt und geeignete Heuristiken vorgestellt |
| **Phase 2: Durchführung der Inspektion** | Experten inspizieren jeweils **alleine** das System auf Basis der Heuristiken — 2 Schritte: (1) Überblick gewinnen, (2) eigentliche Inspektion mit Protokollierung der Findings |
| **Phase 3: Ergebniskonsolidierung** | Gemeinsame Diskussion, Priorisierung der Findings (Schweregrade bestimmen), Erarbeitung von Lösungen + Was soll beibehalten werden? |

**Vorteile & Nachteile — Heuristic Analysis (Folie 775):**

| Vorteile | Nachteile |
|---|---|
| Keine Testnutzer notwendig (kein Recruiting) | Rekrutierung von Doppelexperten (Usability + Fachdomäne) schwierig |
| Kein spezifisches Equipment/Labor nötig | Findet Sequenzierungs- und Workflow-Probleme nur bedingt (Hartson & Pyla, 2012) |
| Zeitlich und örtlich flexibel | Für Nutzer relevante Probleme werden oft nicht gefunden |
|  | Triviale Probleme werden oft überschätzt |

**Evaluationserfolg: Expertise ist zentral (Folie 776):**
- Task & Usability Experts finden deutlich mehr Probleme als Regular Evaluators oder Novice Evaluators
- Bei komplexen Domänen sind **Doppelexperten** (Usability-Expertise + Domänenwissen) zwingend notwendig

---

### 5. Redundante Kodierung (z. B. für Farbfehlsichtigkeit)

**Quelle:** Folie 454 (Euro vs. Schweizer Franken), Folien 441–442 (Design in Greyscale First), Folien 490–496

**Biologische Grundlage: Farbfehlsichtigkeit (Folien 490–492)**

**Stäbchen und Zäpfchen:**
- **Zäpfchen** (Cones): konzentriert in der Fovea — zuständig für **Farbsehen** (3 Typen: S=420nm blau, M=534nm grün, L=564nm rot)
- **Stäbchen** (Rods): peripher verteilt — zuständig für **Hell/Dunkel-Unterscheidung** (kein Farbsehen)

**Farbfehlsichtigkeit:**
> Unvermögen, Farben korrekt zu benennen / Farben differenzieren zu können.

- **Rot/grün-Fehlsichtigkeit** in westlichen Ländern weit verbreitet:
  - **8 % der Männer**, ca. **0,4 % der Frauen**
  - Ursache: Zäpfchen ohne/mit eingeschränkter Funktionstüchtigkeit
  - Angeboren: Das **X-Chromosom** ist für gesundes Farbsehen von großer Bedeutung (XX vs. XY)

**Definition:**
> Redundante Kodierung bedeutet, dass **dieselbe Information über mehrere unabhängige Kodierungskanäle** gleichzeitig vermittelt wird — z. B. Farbe + Form + Beschriftung.

Warum: Fällt ein Kanal aus (z. B. Farbfehlsichtigkeit, S/W-Druck, schlechte Beleuchtung), bleibt die Information über andere Kanäle wahrnehmbar.

**Beispiel: Euro-Schein vs. Schweizer Franken (Folie 454)**

| Merkmal | Euro (10€) | Schweizer Franken (10 CHF) |
|---|---|---|
| **Farbe** | Einheitlich orange-braun (eindeutig) | Komplexe Farbmischung, weniger eindeutig |
| **Zahl** | Große „10" mehrfach vorhanden | Zahl vorhanden |
| **Schrift** | „EURO / ΕΥΡΩ / ЕВРО" — mehrsprachig | Mehrsprachig |
| **Architekturmotiv** | Klares Motiv | Porträt (Le Corbusier) |
| **Redundante Kanäle** | Farbe + Zahl + Text + Motiv + Sterne + Sicherheitsstreifen | Weniger klare Hierarchie |

→ Der Euro nutzt **redundante Kodierung** konsequent: Selbst Farbfehlsichtige können die Banknote anhand von Zahl, Motiv und Struktur unterscheiden.

**Beispiel: Ampel-Icons (Folie 495)**

| Ebene | Ohne Red. Kodierung | Mit Red. Kodierung |
|---|---|---|
| Normales Sehen | Grüne Kugel = OK, rote Kugel = Fehler | Grüner Haken, rotes X |
| Bei Farbblindheit | Beide Kugeln grau → **nicht unterscheidbar** | Haken vs. Kreuz bleibt erkennbar |

→ Form (Haken/Kreuz) + Farbe (grün/rot) + ggf. Text = drei unabhängige Kanäle.

**Beispiel: Metriken-Dashboard (Folie 496) — „Don't rely on color alone"**
> „With this design, someone who suffers from impaired color vision can't easily tell if a metric has gotten better or worse."

- Bei normalem Sehen: Pfeil + Zahl grün = Anstieg; rot = Rückgang
- Bei Rot-Grün-Blindheit: beide Zahlen identisch grau → keine Information übermittelt
- Lösung: Pfeil-Icon (↑/↓) + Farbe = redundante Kodierung

**Kernregel (Folie 497):**
> „Always use color to support something that your design is already saying; **never use it as the only means of communication.**"

**Kontrast statt Farbe (Folie 497):**
> Es ist für Farbblinde wesentlich leichter, zwischen Hell und Dunkel zu unterscheiden als zwischen zwei Farben. → **Kontrast als primärer Differenzierungskanal** nutzen.

**Anwendung im Interface Design:**

1. **Farbe allein reicht nicht** — niemals ausschließlich Farbe zur Übermittlung kritischer Informationen nutzen (ca. 8% der Männer sind rot-grün-blind)
2. **Redundante Signale:** Fehlermeldung = roter Rahmen + Ausrufezeichen-Icon + Fehlermeldungstext (3 Kanäle)
3. **Design in Greyscale First (Folie 441):** Zwingt dazu, Spacing, Kontrast und Größe zur Kommunikation von Hierarchie zu nutzen — Farbe verstärkt danach nur noch

**Weitere Beispiele für Redundante Kodierung:**
- Verkehrszeichen: Farbe (rot = Verbot) + Form (Achteck für Stop) + Text (STOP)
- Button: Farbe + Label-Text + Icon + Hover-Effekt
- Tabelle mit kritischen Werten: Hervorhebung durch Farbe + Fettschrift + Icon

---

### 6. Links/Rechts/Top-Alignment — wann was sinnvoll

**Abstandsregel als Grundprinzip (Folie 480):**
- Label immer näher am eigenen Eingabefeld als an anderen Feldern — unabhängig von Alignmenttyp
- Größerer Abstand zwischen Label-Feld-Gruppen als innerhalb einer Gruppe

**Group Labels with their Inputs (Folie 481):**
- Label und Input **close together** präsentieren — Gesetz der Nähe (Proximity) erzeugt klare Label-Feld-Zuordnung
- **Ausreichend Höhe zwischen den Feldern** — sonst verwechseln User, zu welchem Feld ein Label gehört
- Do: enger Abstand Label→Feld, größerer Abstand Feld→nächstes Label
- Don't: gleichmäßige Abstände überall — Label „klebt" am falschen Feld

**Group Related Information (Folie 482–483):**
> „Users think in batches, and long forms can feel overwhelming."
> „By creating logical groups the user will make sense of the form much faster."

- Lange Formulare in **logische Abschnitte** unterteilen (z. B. „Personal / Account / Contact")
- Trennmethoden: Whitespace, Linie (Separator), gemeinsame Region (Hintergrundfarbe / Common Region)
- Slider-Beispiel (Folie 483): RGB-Werte direkt beim Slider-Control platzieren, nicht oben — sonst Proximity-Verletzung

---

**TOP-ALIGNIERUNG (Folien 612–614)**

> Label steht **direkt über** dem Eingabefeld — beide in einer vertikalen Einheit.

**Vorteile:**
- Einsatz bei **bekannten Datenfeldern** (User kennt das Formular → schnelles Ausfüllen)
- **Minimale Bearbeitungszeit** — schnellste Verarbeitungszeit aller drei Typen
- **Sehr einfache Lokalisierung** (Übersetzungen verlängern Labels → kein Layout-Problem da Label oben)
- **Flexibel bei komplexen Eingaben** (z. B. lange Label-Texte passen gut)
- Label und Feld können in **einer einzigen Fixation** wahrgenommen werden (Eye-Tracking)
- → „Rapid Processing": Auge wandert direkt von Label zu Feld, ohne horizontale Sprünge

**Nachteile:**
- **Höherer vertikaler Platzbedarf** (mehr Screen Real Estate benötigt)
- Abstände oder Kontrast notwendig, um effizientes Scannen zu unterstützen

**Interface-Beispiel:** Amazon Checkout „Enter Shipping Address" (Folie 613) — alle Labels direkt über den Feldern, schnelles Ausfüllen für bekannte Adressfelder.

---

**RECHTS-ALIGNIERUNG (Folien 615–616)**

> Label steht **rechts-bündig links neben** dem Eingabefeld.

**Vorteile:**
- **Klare Zuordnung** von Label und Feld (enger visueller Abstand)
- **Geringer vertikaler Platzbedarf** (Label neben Feld, nicht darüber)
- **Schnelle Bearbeitungszeit** — jedoch höher als bei Top-Alignierung

**Nachteile:**
- **Scannen der Labels aufwendiger** — Labels enden an unterschiedlichen horizontalen Positionen (je nach Label-Länge)
- **„Weihnachtsbaumeffekt"**: unregelmäßige linke Kante der Labels erzeugt unruhiges Layout

**Interface-Beispiel:** Amazon-Checkout (ältere Version, Folie 616) — rechts-ausgerichtete Labels neben Eingabefeldern.

---

**LINKS-ALIGNIERUNG (Folien 617–618)**

> Label steht **links-bündig links neben** dem Eingabefeld.

**Vorteile:**
- **Vorteilhaft bei unbekannten Formularen** — User können Labels sehr einfach von oben nach unten scannen (klare linke Kante)
- **Geringer vertikaler Platzbedarf**

**Nachteile:**
- **Zuordnung Label↔Feld kann problematisch sein** — abhängig vom Unterschied zwischen längstem und kürzestem Label (großer Leerraum zwischen Label und Feld)
- **Änderungen der Labels können das Layout beeinträchtigen** → Vorsicht bei Lokalisierungen

---

**EYE-TRACKING-DATEN (Folie 619)**

| Alignment | Fixationsaufwand | Verarbeitungszeit |
|---|---|---|
| **Left-Aligned Labels** | Kein Zuordnungsproblem, aber **großer Abstand** Label↔Feld → höhere Verarbeitungszeit | Langsamste |
| **Right-Aligned Labels** | Fixationen auf fast **halbiertem** Niveau im Vergleich zu Left-Aligned | Mittel (~halbe Verarbeitungszeit vs. Left) |
| **Top-Aligned Labels** | Label + Feld in **einer Fixation** wahrnehmbar | **Schnellste** |

---

**EMPFEHLUNG (Folie 620)**

| Alignment | Empfohlener Einsatz |
|---|---|
| **Links-alignierte Labels** | Wenn Formulare dem User **nicht vertraut** sind (unbekannte Felder → Labels müssen gut gescannt werden) |
| **Rechts-alignierte Labels** | Wenn **vertikaler Platz eingeschränkt** ist |
| **Top-alignierte Labels** | Wenn **Geschwindigkeit** wichtig ist (und bekannte Formulare vorliegen) |

---

### 7. Zwei beliebige Usability-Metriken (z. B. Time-to-Task, SUS)

→ Vollständiger Kontext: Gruppe B, Frage 4

**Quelle:** ISO 9241-11, Folien 778–792

**Metrik 1 — Time-on-Task (Effizienz):**
> Misst, wie lange ein Nutzer benötigt, um eine definierte Aufgabe erfolgreich abzuschließen.

- Kurze Zeit = effizientes Interface; lange Zeit = Hinweis auf Usability-Problem
- Gemessen im Usability-Test: Start-Zeitpunkt (Aufgabe gestellt) → End-Zeitpunkt (Aufgabe abgeschlossen)
- Gehört zur ISO-Metrik **Effizienz**

**Metrik 2 — Task Completion Rate (Effektivität):**
> Anteil der Probanden, die eine Aufgabe erfolgreich abgeschlossen haben (in %).

- 100% = alle Probanden lösen die Aufgabe; < 70% = kritisches Usability-Problem
- Wird im formativen Usability-Test erhoben; auch Basis für summative Baseline-Messung
- Gehört zur ISO-Metrik **Effektivität**

**Ergänzend: Zufriedenstellung — SUS (Folien 815–817)**
- Wird mit dem **SUS (System Usability Scale)** gemessen — standardisierter 10-Item-Fragebogen (Brooke, 1996)
- Skala: **0–100**, Benchmark-Mittelwert: **68**
- < 51: schlecht / nicht akzeptabel; 68–80: gut / akzeptabel; > 80: exzellent
- Technologieunabhängig, robust bei kleinen Stichproben, bei jedem Reifegrad einsetzbar
- Alternative: **UMUX-Lite** (2 Fragen, Korrelation r=0,83 zum SUS) für Online-Befragungen

**UX Evaluation Methods Matrix (Folie 778):**

|  | Qualitativ | Quantitativ |
|---|---|---|
| **Behavior** | Usability Testing, Walkthrough | A/B Testing, Analytics |
| **Opinion** | User Interviews | Questionnaire (z. B. SUS) |

**Thinking Aloud als qualitative Ergänzung (Folie 790):**
- Erklärt das **Warum** hinter Metriken
- „Tell me what you are thinking about as you work."
- Kombiniert mit quantitativen Metriken = Triangulation (Mixed Methods)

---

### 8. UX Workshop Ablauf und jeweils ein Artefakt

**Quelle:** Folien 100–106 (Collaborative UX), Folien 203–240 (Research + Synthese + Explore)

Der Collaborative UX Design Prozess besteht aus 3 Phasen mit je eigenen Workshops:

| Phase | Workshop | Artefakt (Beispiel) |
|---|---|---|
| **Understand** | Scoping-Workshop | Proto-Problem Statement |
| **Understand** | Research-Workshop (User Research) | Proto-Persona, Proto-Journey-Map |
| **Understand** | Synthese-Workshop | Persona (validiert), Ist-Journey-Map, Problem Statement |
| **Explore** | Ideations-Workshop | Sketches, Konzepte |
| **Explore** | Konzept-Workshop | Wireframes, Screen Flow |
| **Explore** | Prototyping-Workshop | Prototyp (Lo-Fi oder Hi-Fi) |
| **Explore** | Validierungs-Workshop | Validierungsbefunde, Testprotokolle |
| **Deliver** | Requirements-Workshop | Spezifikationen, Sprint Backlog |
| **Deliver** | Planning-Workshop | User Story Map, Domain Model |
| **Deliver** | Review-Workshop | Component Library, Prüfbericht |

**Beispiel-Ablauf Scoping-Workshop (Understand):**
1. Proto-Problem Statement formulieren
2. Proto-Personas erstellen
3. Proto-Journey-Maps skizzieren
→ Artefakt: **Proto-Persona** (archetypischer Nutzer basierend auf Team-Annahmen)

**Beispiel-Ablauf Synthese-Workshop (nach Research):**
1. Rohdaten aus Interviews/Beobachtungen sichten (Sighting)
2. Klassifizieren (Classify) und auf Post-its extrahieren
3. Gruppieren und thematisch ordnen (Organize & Group)
4. Insights ableiten → Journey Map erstellen
→ Artefakt: **Ist-Journey-Map** (aus echten Forschungsdaten, zeigt Pain Points + Opportunities)

**Beispiel-Ablauf Ideations-Workshop (Explore):**
1. Opportunity Areas aus Journey Map ableiten
2. HMW-Fragen formulieren (How Might We)
3. 6-3-5 Methode durchführen (6 Personen × 3 Ideen × 5 Runden)
4. Ideen sichten, clustern und priorisieren
5. Konzept ableiten + als Nutzungszenario beschreiben
→ Artefakt: **Nutzungszenario / Use Scenario** (konkretes Fallbeispiel, nicht lösungsneutral, kombiniert Ideen)

---

### 9. Contextual Inquiries mit Beispiel

→ Siehe Gruppe A, Frage 9 (vollständige Antwort dort)

**Zusatz für Aufgabe:** Typisches Beispiel aus Vorlesung — Forscher begleitet Fabrikarbeiter an CNC-Maschine und beobachtet echte Arbeitsabläufe, Workarounds und Nutzungsmuster (Job Shadowing / GOOB = Get Out Of The Building).

**Vorbereitung (Folie 165):** Von Scoping zu Research — drei Artefakte vorbereiten: Annahmen-Board (Auswirkung × Wissen), Interview-Fragen, Beobachtungs-Fragen.

**Durchführung (Folien 173–176):**
- Beobachtung **vor** dem Interview
- Offene und neutrale Fragen, keine führenden Fragen
- Interviews zu zweit (Interviewer + Note-Taker)
- Exakte Aufzeichnung der Antworten (keine Korrekturen, keine „Verbesserungen")

**Auswertung (Folien 179–185):**
1. **Sighting** — Protokolle sichten und markieren
2. **Classify** — Protokolle klassifizieren (farblich)
3. **Extraction and Compacting** — Extrahieren auf Post-its
4. **Organize and Group** — Post-its gruppieren und thematisch ordnen
5. → **Insights** gewinnen (Interpretation der Rohdaten)

---

### 10. Unterschied Sketches und Wireframes

**Quelle:** Folie 313 (Sketches), Wireframes folgen auf Seiten 161+

#### Sketches (Folie 313)

> „Sketches are hand-drawn visualizations of a future interface — or parts of it."

**Eigenschaften:**
- **Low-fidelity by intention** — bewusst unfertig
- **Abstract from details** — abstrahieren von Details
- **Focus on the essence** — Fokus auf das Wesentliche
- Verwenden typischerweise **keine Farben** für visuelle Ausarbeitung — Farben nur zur Lenkung der Aufmerksamkeit

**Warum Sketches zuerst?**
> *„The whole point of designing in low-fidelity is to be able to move fast — so you can build the right thing AND build it right."*

Sketches verhindern die **Sunk Cost Fallacy**: Wer zu früh in Pixelarbeit investiert, kann Ideen nicht mehr verwerfen.

#### Wireframes (Folie 334–336)

> „A wireframe represents the skeletal framework of an interface."

**Eigenschaften:**
- Dictates an interface's **information architecture**
- Lays out a **consistent way of presenting information**
- Helps to **prioritize content in a consistent grid**
- „Wireframes are like floor plans" — sie zeigen Struktur, nicht visuelle Ausarbeitung

**Wann Wireframes?**
> „The minute you turn on the screen, you're not generating. You're editing." (Harris, 2018)

→ Wireframes kommen **nach** Sketches, **vor** Visual Design. Erst im Wireframe wird aus der freien Skizze eine strukturierte Darstellung der Informationsarchitektur.

**Progression: Von grob zu fein (Folie 336):**
1. Breite Erkundung des Lösungsraums durch **Scribbles/Sketches**
2. Bewertung von alternativen Lösungsoptionen
3. Reduktion auf aussichtsreiche Lösungskonzepte
4. **Elaboration in Wireframes** (Struktur, Grid, Controls)
5. Bewertung und Reduktion
6. **Visuelle Ausarbeitung** von Zielkonzepten (Hi-Fi, Visual Design)

**Design Funnel — Elaborate & Reduce (Folie 321):**
- Iterativer Prozess: Concepts generation → Iteration 1 (Coarse) → Iteration 2 (Medium) → Iteration 3 (Fine) → Concept selected
- Granularität: General → Coarse (significant alternatives) → Medium (intermediate development) → Fine (detailed refinement)
- In jeder Iteration: Elaboration (neue Ideen) und Reduction (Einschränkung) wechseln sich ab

**Strukturstudie: Tullis (1987, Folie 332):**
- Screen 1 (ohne Struktur, alles lesen): Ø 5,5 Sek. Suchzeit
- Screen 2 (mit vertikalen Kategorien): Ø 3,2 Sek. Suchzeit
- → Klare Struktur und Whitespace reduzieren kognitiven Aufwand erheblich

| | Sketch | Wireframe | Visual Design (Mockup) |
|---|---|---|---|
| Fidelity | Low (by intention) | Low–Mid | High |
| Fokus | Ideen, Essenz | Struktur, IA, Grid | Farben, Typografie, Pixel |
| Werkzeug | Papier, Stift | Tool (z. B. Figma) oder Papier | Design-Tool |
| Wann | Ideation | Vor Visual Design | Deliver-Phase |

---

### 11. Unterschied Stakeholder und User

**Quelle:** ISO 9241-11 (2018), ISO 9241-210, Vorlesung Iteration 2 (Folien 41–80)

**User (Nutzer:in):**
> Person, die direkt mit dem interaktiven System interagiert — das System bedient, steuert oder nutzt.

- Steht im Mittelpunkt der **Usability-Definition** (ISO 9241-11): „specific users"
- Hat konkrete **Aufgaben** (Tasks), die mit dem System erledigt werden
- Erlebt Effektivität, Effizienz und Zufriedenstellung direkt bei der Nutzung
- Beispiel: Die Buchhalterin, die eine Zeiterfassungs-App nutzt

**Stakeholder:**
> Jede Person oder Gruppe, die ein Interesse am System hat oder von ihm betroffen ist — unabhängig davon, ob sie das System direkt nutzt.

- Kann **Nutzer:innen einschließen**, ist aber weiter gefasst
- Umfasst auch: Auftraggeber, Geschäftsführung, Projektbeteiligte, Entwickler, Regulierungsbehörden, indirekt Betroffene
- Hat **eigene Ziele** (Geschäftsziele, wirtschaftliche Interessen, Compliance-Anforderungen), die sich von Nutzerzielen unterscheiden können

**Unterschied (Tabelle):**

| Merkmal | User | Stakeholder |
|---|---|---|
| **Direkter Kontakt mit dem System** | Ja — interagiert unmittelbar | Nicht zwingend |
| **Primäres Interesse** | Aufgaben effizient erledigen | Businessziele, wirtschaftlicher Erfolg, Compliance |
| **Einfluss auf Design** | Zentral (User Research, Testing) | Wesentlich (Auftraggeber, Anforderungen) |
| **Beispiele** | Endnutzer, Sachbearbeiterin, Kunde | CEO, Produktmanager, Rechtsabteilung, Investoren |

**ISO 9241-11 (2018) — Neuerung: Stakeholder-Ziele:**
> Die 2018er Revision erweiterte die Usability-Definition explizit um **Stakeholder-Ziele** — nicht nur Nutzerziele, sondern auch organisationale und gesellschaftliche Ziele werden berücksichtigt.

**Warum der Unterschied relevant ist:**
- Nutzer wollen **einfache, effiziente Nutzung**
- Stakeholder wollen **Geschäftsziele erfüllen** (z. B. Umsatz, Compliance, Kosten)
- **Zielkonflikte** sind möglich: Was für Stakeholder vorteilhaft ist (z. B. Datenerhebung), kann die User Experience beeinträchtigen
- Gutes UX Design balanciert: **User ↔ Technik ↔ Ökonomie ↔ Ökologie**
- „Nutzerzentrierung is a lie" → echter Anspruch: **Menschzentrierte Gestaltung** (human-centered), die alle betroffenen Parteien einbezieht

---

### 12. (offen)

---

### 13. Arten von Prototypen und wann welche zum Einsatz

**Quelle:** Folien 721–750 (Prototyping-Kapitel)

**Grunddefinition:**
> „A prototype is anything that move the process forward." (Marty Thaler)

> „Prototypes are tools to traverse design spaces."

> „Prototypes help to generate, communicate and evaluate design ideas – allowing informed decisions."

> „Find the cheapest way to relevant insights! It's all about informative prototypes."

---

**Typen von Prototypen (Folie 721):**

| Typ | Beschreibung |
|---|---|
| **Paper Prototyp** | Handgezeichnete Skizzen, schnellste und günstigste Methode |
| **Wireframes / „Klick"-Dummy** | Digitale Skelett-Struktur ohne visuelles Design |
| **Mixed / Augmented Reality Prototyp** | Überlagerung digitaler und realer Welt (z. B. mit AR-Brille) |
| **Virtual Reality Prototyp** | Vollständig immersive digitale Umgebung |
| **Video Prototyp** | Filmische Simulation des Nutzungsszenarios |
| **Verbale Prototypen** | Beschreibung/Erklärung eines Konzepts durch Sprache |
| **Statische & Dynamische Simulatoren** | Hardware-basierte Nachbildung (z. B. Cockpit-Simulator) |
| **Wizard of Oz Prototyping** | Mensch simuliert Systemverhalten im Hintergrund (unsichtbar für Nutzer) |
| **Interaktive Prototypen** | Vollständig klickbares, digitales Interface (z. B. Figma-Prototyp) |

**Beispiel Wizard of Oz (Folie 731):** Elektrischer EQV + 43" TV — Testperson interagiert mit Display, dahinter steuert ein Mensch die Reaktionen.

---

**Fidelität — Realitätstreue (Folie 725):**

> „Realitätstreue", „Echtheitsgrad"

Skala: **LOW ←——→ HIGH**

**3 Komponenten nach Dahl et al. (2009):**
1. **Prototype Fidelity** — Detailgrad des Prototyps selbst
2. **Environment Fidelity** — Realitätsnähe der Testumgebung
3. **Psychological Fidelity** — Realitätsnähe des psychologischen Erlebens

**Richtige Fidelity zur richtigen Zeit (Folie 726):**
```
Paper Scribbles → Wireframes → Visual Design
```
Je nach Projektphase und Fragestellung variiert die benötigte Fidelity.

---

**Horizontale, vertikale und diagonale Prototypen (Folie 724):**

| Typ | Abdeckung | Tiefe |
|---|---|---|
| **Horizontal** | Viele Features | Wenig Tiefe je Feature |
| **Vertikal** | Ein Feature | Sehr tiefe Abdeckung |
| **Diagonal** | Kombination aus H + V | Selektive Tiefe bei Breite |

---

**Lo-Fi und Hi-Fi Definitionen (Folie 729):**

**Low-Fidelity Prototype:**
> „A low-cost, simple illustration of a design or concept used to gather user feedback at the very early stages of design."

**High-Fidelity Prototype:**
> „A software prototype of the user interface to the interactive system that is being designed. A high-fidelity prototype resembles the finished interactive system and may or may not be interactive."

---

**Bewertungsdimensionen von Prototypen (Folie 728):**
- **Fidelität** (Echtheitsgrad)
- **Zeitaufwand**
- **Kosten** (monetär)
- **Benötigte Fähigkeiten**
- **Umfang**

→ Kein Prototyp ist in allen Dimensionen optimal — es sind immer Trade-offs.

---

**Google Glass Beispiel — Tom Chi, Google (Folien 737–744):**

- **1 Tag** für den ersten visuellen Prototyp (augmentierte Erfahrung: Wie fühlt sich digitale Überlagerung an?)
- **45 Minuten** für gestenbasierte Interaktion mit der Brille

**3 Prototyping Rules:**

1. **Find the quickest path to experience.**
   → Nicht planen — so schnell wie möglich ein Erlebnis schaffen.

2. **Doing is the best kind of thinking.**
   → Handeln liefert Erkenntnisse, die Nachdenken allein nicht liefert.

3. **Build on the ideas of others.**
   → Ideen sind nicht privat — auf dem Aufgebautem anderer aufbauen.

---

**Bill Buxton (2007) — Folie 734:**
> „Everything is best for something and worst for something else. The trick is knowing what is what, for what, when, for whom, where, and most importantly, why."

**Mike Dodge (2019) — Folie 735:**
> **(WHAT × WHY × HOW / TIME SPENT) × WHEN × FOR WHOM × WHERE = IMPACT ON DESIGN**

---

**Fazit — Folie 736:**
> „Je nach Fragestellung und Kontext eignen sich andere Vorgehensweisen. Es gibt nicht den perfekten Prototypen oder das perfekte Tool. Erfolg und Effizienz werden stattdessen maßgeblich vom Zeitpunkt und den eingesetzten Ressourcen beeinflusst."

**→ IT DEPENDS.**

---

### 14. »Proto« vor verschiedenen Artefakten — was bedeutet das?

**Quelle:** Folien 120–131 (Proto-Persona), Folien 100–106 (Scoping Workshop)

Das Präfix **„Proto"** vor einem Artefakt signalisiert:

> **Annahmenbasiert, noch nicht validiert — ein Entwurf, der auf subjektiven Wahrnehmungen des Teams basiert und auf Validierung wartet**

| Artefakt | Was es ist | Was „Proto" bedeutet |
|---|---|---|
| **Proto-Persona** | Archetypischer Nutzer | Basiert auf Team-Annahmen, nicht auf Feldforschung; Validierung ist aufgeschoben |
| **Proto-Problem Statement** | Problembeschreibung | Erste Hypothese über das Problem, noch nicht durch Research bestätigt |
| **Proto-Journey** | User Journey Map | Angenommener Ablauf des Nutzers, noch nicht aus echten Daten gewonnen |

**Kerngedanke:** Proto-Artefakte sind **Werkzeuge zum schnellen Starten** — sie strukturieren Annahmen, die dann durch echte User Research (z. B. Contextual Inquiries) validiert werden. Wichtig: Validierung darf nicht vergessen werden!

---

### 15. Triangulation erklären

**Quelle:** Folien 779–782

**Definition — Triangulation / Mixed Methods:**
> „Deeper understanding by combining different methods!"

**Data Triangulation (Folie 781):**
> Kombination von zwei oder mehr (qualitativen oder quantitativen) Methoden, um Ergebnisse aus verschiedenen Perspektiven zu betrachten und Interpretationen zu validieren.

**Warum Triangulation?**
- Jede einzelne Methode hat **blinde Flecken** → eine andere Methode gleicht diese aus
- Nicht auf eine einzelne Kennzahl verlassen — besonders bei wichtigen Designentscheidungen
- Mehrere KPIs **und** verschiedene Methoden kombinieren

**Erika Hall (Folie 780):**
> „The best way to assess a functional design is through a combination of quantitative and qualitative methods."

**Zwei Achsen der Triangulation (Folie 779):**
1. **Qualitativ vs. Quantitativ** — Tiefe des Verstehens vs. messbare Zahlen
2. **Analytische Inspektion vs. Empirischer Test** — Experte bewertet vs. echte Nutzer testen

**UX Evaluation Methods Matrix (Folie 778, Rohrer 2014):**

|  | **Qualitativ** | **Quantitativ** |
|---|---|---|
| **Behavior** | Usability Testings, Walkthrough | A/B Testing, Analytics |
| **Opinion** | User Interviews | Questionnaire (Fragebogen) |

**Typische Mixed-Methods-Kombination (Folie 782):**

```
Fragebogen  +  Quantitatives Usability Testing  und/oder  Analytics
```

→ Fragebogen liefert Meinung (Opinion), Usability Testing liefert Verhalten (Behavior), Analytics liefert quantitative Daten → drei unabhängige Blickwinkel auf dasselbe Design.

**Anwendungsbeispiel:**
- Nur Fragebogen → weiß was Nutzer **sagen**, aber nicht was sie **tun**
- Nur Analytics → weiß was Nutzer tun, aber nicht **warum**
- Kombination: Fragebogen + Analytics + Usability Test → vollständiges Bild (Triangulation)

---