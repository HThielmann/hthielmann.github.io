---
layout: method
published: true
title: Behaviour-Driven Prototyping 1.0.0.
image: /assets/methods/bdp.jpg
rating: 5
summary: |
    Ein co-kreativer Prozess, um technische Lösungsideen niedrigschwellig zu prototypisieren.
goal_intia: |
    Den Prototypisierungsprozess partizipativer gestalten, um den Partizipationsgrad der Teilnehmenden in einem sehr Technik-affinen Umfeld zu erhöhen und somit von der Problemdefinition zur Entwicklung von relevanten, kontextbezogenen Lösungen durch Ideen der Teilnehmenden mit Einbezug von Fachkräften überzugehen. Dieser Prozess wird auf den wesentlichsten Inhalten abstrahiert und spielerisch gestaltet, damit technische Lösungsideen co-kreativ gefunden werden können.
goal_audience: |
    Mitentwickelnden: Technische Lösungsideen co-kreativ finden, Selbstwirksamkeit und Spaß erleben
    Fachkräfte: Mitentwickelnden dabei unterstützen technische Lösungsideen co-kreativ zu finden
source: |
    INTIA; Synthese und Abwandlung von User Stories, User Journeys und Behaviour-Driven Development
requirements: |
    - Austattung: Whiteboard oder Miroboard (optional), zwei größere Tische (a 60cmx140cm) zum Ausbreiten einer Papier-Rolle und das Verschieben von Karten, Smartphone zum Abfotografieren der Ergebnisse, Tablet (optional)
    - Inputs: Identifizierte Probleme/Bedarfe, Grobe Lösungsidee (optional)
expected_results: |
    Outputs: Technische Lösungsideen, "Medium-Fidelity-Prototypes"
    Inhaltlich 
        Hinweise auf der Richtigkeit des Bedarfs (Validierung)
        Pro Gruppe 3 konkrete technische Lösungsideen zu einem Bedarf
    Form 
        Fotos von einem technischen Lösungsidee ("Das nervt mich..." → "Ich wünsche mir..." → "WENN... DANN... DAMIT")
    Pro Gruppe von Teilnehmenden mindestens drei selbst konzipierte Funktionen oder Verhalten eines Prototypen, belegt aus den bereitgestellten Karten und im Anschluss abfotografiert
materials: 
    - Statische Whiteboard-Folie oder Whiteboard
    - Whiteboard-Stifte
    - Prototyping-Karten (mehrfarbige)
    - BDP-Felder (mehrfarbige)
    - Flip-Chart-Papier (a 45cmx160cm)
    - Edding-Stifte (2x)
duration:
    - name: Vorbereitung
      duration: ca 8-12 Std.
      description:
        - Erstellen der Prototyping-Karten (ca 8 Std)
        - Erstellen der BDP-Felder (ca 4 Std)
        - Sortieren der Karten und Felder (ca. 20 Minuten)
        - Ggf. Verschicken der Karten an die Einrichtung (4 Std.)
    - name: Durchführung
      duration: ca 2 Std. → kann in mehreren Terminen (bspw 2 oder 3) stattfinden
      description:
        - Verteilung des "Spielbretts" und den Prototyping-Karten (15 Minuten)
        - Gemeinsames Durchführen der Methode anhand eines bekannten Beispiels (1 Std.)
        - MEs führen eigenständig Methode durch (1 Std.)
        - Einsammeln der Materialien und Feedbackrunde (15 Minuten)
    - name: Nachbearbeitung
      duration: ca 2 Std.
      description:
        - Festhalten und Auswerten der Aussagen (1 Std)
        - Feedback für zukünftigen Iteration festhalten (1 Std)
---
# Beschreibung
Die INTIA-Methode "Behaviour-Driven Prototyping" ermöglicht es anhand eines Prototyping-Kartensets 
(eine Art Spiel- oder Methodenkarten) und BDP-Felder technische Funktionen von bestimmten Technologien zu visualisieren. 
Die Struktur folgt die sogenannte **User Story** (North, 2019; Adzic & Evans 2015) nach dem Prinzip 
"Als ... möchte ich ..., damit ..." oder in Form von **User Journey** nach der Struktur "Ich wünsche mir" dass, ... 
"X passiert" wenn ich "Y tue" damit "Z". Dies wird anhand von Felder "Das nervt...", "Ich wünsche mir...", 
"WENN... DANN... DAMIT" nachgebaut, wobei zur Vereinfachung auf die Rolle von User Stories verzichtet wurde. 
Diese Struktur verfolgt den Ziel vom Problemraum der **Bedarfe** zu dem Lösungraum der **Prototypen** oder 
"Alltagshilfen" visuell zu überführen (Tharayil, 2018), sodass auf ein Blick das Problem so wie die daraus 
entstandenen Lösungs-Ideen mit den Karten zu sehen sind. Dies soll helfen immer wieder aufzufrischen welche 
"Nervsituation" als Anfangspunkt und das "DAMIT" um das Wozu deutlich zu haben, damit die Relevanz klar ist. 
So sieht das für die MEs als "Ideen-Schmiede" getaufte 
BDP-Feld aus:

![alt text](/assets/methods/ideenschmiede.jpg)

Die Karten sind hierzuu in **Technologie-, Verhalten-** und **Kommando-Karten** unterteilt:

<img src="/assets/methods/technology-cards.jpg" alt="Technologie" width="600"/>
<img src="/assets/methods/behaviour-cards.jpg" alt="Verhalten" width="600"/>
<img src="/assets/methods/command-cards.jpg" alt="Kommando" width="600"/>

Diee Technologie-Karten zeigen die Sensoren (Trigger) wie Dreh- oder Kippschalter, die etwas erkennen sowie 
die Aktuatoren wie Buzzer, Timer, die etwas ausführen. Dazu sind auch ermöglichende Technologien wie Kamera, 
Chat-Bot, zusammengefasst, die nicht direkt einen Sensor oder Aktuator zugeordnet werden können.

Bei den Verhaltens-Karten wird die Frage beantwortet "was passiert?" auf einer etwas abstrakten Ebene 
"abschließen", "anschalten", "bewegen", "öffnen", "lesen". Diese werden aktiv formuliert, da es um eine aktive 
Handlung der entsprechenden Technologie geht.

Bis den Kommando-Karten handelt es sich um konkrete Handlungen, die ausgeführt werden, wie zum Beispiel 
"Um 5 cm nach links bewegen" oder um konkrete Zustände wie zB "hell" oder "dunkel". 
Das können die Mitentwickler*innen selber bestimmen wie konkret sie das darstellen unter dem etwas 
abstrakteren Verhalten "bewegen" und sonstiges. Prinzipiell entstehen durch diese "Befehle" der MEs 
**Ereignisse**, die von anderen Technologien verstanden und dementsprechende Aktionen ausgeführt werden können.

Um Lösungsmöglichkeiten mit den MEs auszuarbeiten sei auf eine abgewandelte Form eines **BDD-Szenarios**  
hingewiesen. Diese werden hier als **Behaviour-Driven-Prototyping-Szenarios** oder kurzform **BDP-Szenarios** 
(siehe Schritte 7 und 8 des Step-by-Step Guides) bezeichnet. Darin wird eine "WENN... DANN... DAMIT" Struktur 
aufgestellt, bei der die MEs im ersten Schritt mithilfe eines Moderators ein Beispiel auf der Tafel durchspielen, 
damit die Vorgehensweise verstanden wird, und im Anschluss sollen die MEs selber auf den Tischen tätig werden und 
anfangen mit den Prototypisierungs-Karten zu „prototypisieren". Somit sollen Ideen für funktionalen Anforderungen 
eines Prototyps aufgestellt werden, und gemeinsam ausdiskutiert werden, ob diese sinnig oder "tauglich" sind. 
Dies erfordert kein tiefes technisches Know-How und ermöglicht anhand von Papier-Sensoren, -Aktuatoren usw. eine niedrigschwellige 
Ideenfindung für sogenannte 
*Low-Fidelity-Prototypes* (Dam & Theo, 2019) oder "Medium-Fidelity-Prototypes". 
Das Haptische wird dadurch unterstützt, dass Karten hin und her geschoben werden können. 
Am Ende hat man einen zwei-teiligen Prototypisierungs-Prozess:

*Teil 1 - Problem und Erste Lösungsideen als Verhalten oder Technologie*

![alt text](/assets/methods/ideenschmiede-1.jpg)

*Teil 2 - WENN... DANN... DAMIT...*

![alt text](/assets/methods/ideenschmiede-2.jpg)

Diese "begreifbare" Interaktion funktoniert mit unterschiedlichen Papierkarten, 
auf welche entsprechende Icons und Bezeichnungen gedruckt sind, damit diese mit Bild und einfache Texte verstanden werden.

# Step-by-Step Guide

Im Folgenden werden konkrete Schritte beschrieben, wie der Prozess dieser Methode durchgeführt werden kann. 
Diese setzt voraus, dass konkrete **Bedarfe** bei der Bedarfserhebung erkannt und optional schon eine 
**grobe Lösungsidee** zusammen mit den Fachkräften und Teilnehmenden ausgefertigt worden sind.

1.  Moderationskoffer mit Erfinder-Rolle, Prototyping-Karten und beistehendes Material packen. (5 Minuten)
2.  Raum und Gruppensetting vorbereiten. (5 Minuten)

    * zwei Tische werden vorbereitet.
    * auf Tisch A wird die Erfinder-Rolle ausgeweitet, auf Tisch B die noch verpackten BDPrototyping-Karten 1.0.0. gelegt.
    * auf Tisch B werden die gelben Verhalten-Karten ausgepackt und auf dem Tisch verteilt.
    * (falls Remote, iPad samt Stativ auflegen, damit der Tisch gefilmt wird)
    
3.  Das "Das nervt..."- und "Ich wünsche mir..."-Feld werden auf der Erfinder-Rolle nebeneinander gelegt (5 Minuten)
4.  Die Nervsituation wird mit den MEs abgestimmt und validiert, ob das so stimmt (Bedarfe wurden schon vorher erhoben). (5 Minuten)
5.  Danach werden erste Lösungsvorschläge anhand vom "Verhalten" des Systems 
    (siehe Verhalten-Karten) 
    auf dem "Ich wünsche mir..."-Feld gelegt (5 bis 10 Minuten):
    
    * Es wird gefragt: "Was wünscht Ihr euch, damit die nervige Situation nicht mehr nervt? Wie würdet ihr das lösen?"
    * Auf Tisch B werden die gelben Verhalten-Karten ausgebreitet und gefragt: "Welche von diesen Karten fühlt sich richtig an für euch? Was soll passieren, damit diese nervige Situation (Nervsituation wiederholen) nicht weiter nervt? Ihr könnt eine oder mehrere auswählen. Bespricht das bitte untereinander. Jede Idee ist willkommen! Die Karten, die sich richtig für euch anfühlen bitte in dem "Ich wünsche mir..."-Feld legen. Wenn mehrere von euch diesselbe Karte auswählen wollen, dann bitte einfach eine leere gelbe Karte daneben legen.
    * Nachdem alle Lösungsvorschläge auf dem "Ich wünsche mir..."-Feld gelegt wurden, wird pro Verhalten-Karte abgefragt "Wieso habt ihr diese Karte gewählt?" Alle Erklärungen werden auf eckige Sprechblasen mit Edding geschrieben und neben der entsprechenden Verhalten-Karte gelegt.
    * Bitte Foto eures Ergebnisses machen und uploaden.
    
6.  Die MEs werden aufgefordert die auf Tisch B restlichen gelben Verhalten-Karten zu bündeln, zur Seite zu schieben, und die grünen Technologie-Karten auf Tisch B zu verteilen. (20 Minuten)

    * "Diese Karten sagen aus 'womit' etwas passiert. Im Prinzip heißt es 'durch welche Technologie etwas passiert'. Dieses 'etwas' sieht ihr in den gelben Verhalten-Karten links." (5 Minuten)
    * "Welche dieser grünen Technologie-Karten passen zu den gelben Verhalten-Karten auf dem anderen Tisch? Bespricht das untereinander für 5 Minuten und legt die Karten, die sich richtig für euch anfühlen auf Tisch A, wo die gelben Karten sind, die ihr ausgewählt habt." (5 Minuten)
    * "Welche Technologie verhält sich wie? Welche der gelben Verhalten-Karten passen zu welche der grünen Technologie-Karten?" (5 Minuten)
    * Nachdem alle Lösungsvorschläge auf dem "Ich wünsche mir..."-Feld gelegt wurden, wird pro Technologie-Karte abgefragt "Wieso habt ihr diese Karte gewählt?" Alle Erklärungen werden auf eckige Sprechblasen mit Edding geschrieben und neben der entsprechenden Technologie-Karte gelegt. (5 Minuten)
    * Bitte Foto eures Ergebnisses machen und uploaden. (2 Minuten)

7.  MEs werden aufgefordert die Büroklammer wo "DAMIT" oben in der Rolle steht zu entfernen und die Rolle vorsichtig aufzumachen, sodass die ganze Rolle ausgestreckt ist. Die "WENN... DANN..."-Felder sind dann zu sehen. MEs werden aufgefordert das "DAMIT" auf das "Ich wünsche mir..." Post-It-Zettel zu klebben. (1 Minuten)
8.  Es wird formuliert: "WENN etwas passiert DANN passiert etwas anderes DAMIT ich einen Nutzen davon habe." (5 Minuten)

    * "Platziert bitte die Technologie- und Verhalten-Karten auf dem 'WENN... DANN...'-Feld sowie es sich richtig für euch anfühlt. Wichtig hierbei ist, dass die grünen und gelbe Karten zueinander passen." (3 Minuten)
    * "Was wollt ihr DAMIT erreichen? Welcher Nutzen soll diese Idee haben? Nimmt einer der Sprechblasen, die ihr aufgeschrieben habt. Wo würdet ihr das legen?" (2 Minuten)

9.  Die MEs werden aufgefordert die auf Tisch B restlichen grünen Technologie-Karten zu bündeln, zur Seite zu schieben, und die roten Kommando-Karten auf Tisch B zu verteilen. (10 bis 15 Minuten)

    * "Was genau soll passieren? Wie genau soll es sich verhalten? Welche dieser roten Kommando-Karten passen zu den gelben Verhalten-Karten auf Tisch A? Ihr könnt ein oder mehrere rote Karten **einer** gelben Karte zuordnen. Jede und Jeder von euch kann eigene Vorschläge einbringen, auch wenn sie doppelt vorkommen." (5 Minuten)
    * Bsp: "WENN der Timer erinnern in 2 Stunden DANN klingelt der Buzzer DAMIT wir wissen wann die Wäsche fertig ist."
    * "Habt ihr denn sonst Ideen welche roten Karten zu den gelben Karten passen können?" (2 Minuten)
    * Nachdem alle Lösungsvorschläge auf dem "WENN... DANN..."-Feld gelegt wurden, wird pro Kommando-Karte abgefragt 
      "Wieso habt ihr diese Karte gewählt?" Alle Erklärungen werden auf eckige Sprechblasen mit Edding geschrieben und neben der 
      entsprechenden Technologie-Karte gelegt. (3 Minuten)
    * Bitte Foto eures Ergebnisses machen und uploaden. (2 Minuten)

10. Aufforderung das Material, samt Prototyping-Karten, Erfinder-Rolle und iPad zu sammeln. (5 Minuten)
11. Großes Dankeschön für's aktive Mitmachen!

# Gestaltungskriterien

- siehe BDPrototyping-Karten 1.0.0.
- siehe BDP-Felder 1.0.0.

# Erfolgskriterien

- MEs konzipieren mindestens drei Ideen zu Prototyp-Verhalten (innovative oder schon existierende)
- Klar erkennbarer Diskurs zwischen den unterschiedlichen Stakeholdern auf gleicher Augenhöhe, die zu relevanten Prototyp-Ideen führen

# Auswertung

Leichte Abwandlung zu Behaviour-Driven Prototyping 0.9.0.

# Referenzen

-   Tharayil, R. (2018, April 4). Behavior-Driven Development: Simplifying the Complex Problem Space. Retrieved March 17, 2020, from <https://www.solutionsiq.com/resource/blog-post/behavior-driven-development-simplifying-the-complex-problem-space/>
-   North, D. (n.d.). BDDWiki: BehaviourDrivenDevelopment. Retrieved from <https://behaviourdriven.org/>
-   North, D. (2019, June 5). What's in a Story? Retrieved March 17, 2020, from <https://dannorth.net/whats-in-a-story/#1>
-   Adzic, G., Evans, D. (2015). *Fifty Quick Ideas to Improve Your Stories*. Neuri Consulting LLP.
-   Wright, M., Block, M., & von Unger, H. (2007). Stufen der Partizipation in der Gesundheitsförderung. *Info_Dienst für Gesundheitsförderung*, *7*(3), 4-5.
-   Wright, M. T., Block, M., & von Unger, H. (2008). Partizipation in der Zusammenarbeit zwischen Zielgruppe, Projekt und Geldgeber. *Das Gesundheitswesen*, *70*(12), 748-754.
-   gesundheitliche-chancengleichheit: Partizipation der Zielgruppe. (n.d.). Retrieved March 17, 2020, from <https://www.gesundheitliche-chancengleichheit.de/gesundheitsfoerderung-im-quartier/aktiv-werden-fuer-gesundheit-arbeitshilfen/teil-2-probleme-erkennen/partizipation-der-zielgruppe/>
-   What is Prototyping? (n.d.). Retrieved March 16, 2020, from <https://www.interaction-design.org/literature/topics/prototyping>
-   World Leaders in Research-Based User Experience. (n.d.). Paper Prototyping: Getting User Data Before You Code. Retrieved March 16, 2020, from <https://www.nngroup.com/articles/paper-prototyping/>
-   Interaction Design Foundation. (n.d.). What is Paper Prototyping? Retrieved March 18, 2020, from <https://www.interaction-design.org/literature/topics/paper-prototyping>
-   Dam, R. F. & Teo, Y. S. (2019). Stage 4 in the Design Thinking Process: Prototype. Retrieved March 18, 2020, from <https://www.interaction-design.org/literature/article/stage-4-in-the-design-thinking-process-prototype>
-   Buxton, B. (n.d.). What Sketches (and Prototypes) Are and Are Not. Retrieved March 18, 2020, from <https://www.cs.cmu.edu/~bam/uicourse/Buxton-SketchesPrototypes.pdf>