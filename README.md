# Encounter-Workshop – gemeinsame Arbeitsfläche

## Ziel und Kontext

In diesem Workshop betrachten wir Versorgungssituationen als Patient Journeys und untersuchen, wie die darin vorkommenden Kontakte und Encounter-Instanzen fachlich beschrieben und im Informationsmodell abgebildet werden können.

Der Workshop baut auf dem [Zielbild für das Encounter-/Fallmodell 2027](https://github.com/gematik/spec-ISiK-Basismodul/blob/main-stufe-6/Material/Basis/Zielbild-Encounter-Fallmodell-2027.md) sowie auf relevanten Ergebnissen vorausgegangener Arbeitsgruppen auf. Der Fokus liegt auf den Inhalten, die für die gemeinsame Arbeit an den Journeys und die anschließende Betrachtung des Informationsmodells benötigt werden.

Die konkreten Workshop-Termine und -Rahmenbedingungen sind den jeweils bereitgestellten Unterlagen zu entnehmen.

## Arbeitsweise

Der Workshop beginnt mit einer kurzen Einführung in Ziel, Ablauf und Arbeitsregeln. Die Zusammensetzung der Gruppe wird durch Handmeldungen erfasst, statt eine Vorstellungsrunde durchzuführen.

Anschließend werden vorbereitete Versorgungsszenarien als Beispiele betrachtet. Die Teilnehmenden sammeln in Kleingruppen weitere konkrete Versorgungssituationen, insbesondere solche mit prozessualen oder strukturellen Abweichungen. Szenarien werden zunächst einzeln festgehalten und nicht vorzeitig in Kategorien eingeordnet.

Ausgewählte Journeys werden als Abfolge von Versorgungsschritten, Ereignissen, Kontakten und Übergängen beschrieben. Die Journey dient der fachlichen Betrachtung des Versorgungsgeschehens; sie steht nicht primär für eine subjektive Patientenerfahrung.

## Journeys und Encounter-Instanzen

Die Teilnehmenden stellen die ausgewählten Journey-Skizzen vor und ergänzen sie in Kleingruppen. Für definierte, diskrete Schritte wird betrachtet, wann eine Encounter-Instanz angelegt wird.

Im Informationsmodell werden insbesondere `.class` und `type`-Kontaktebene berücksichtigt. `type`-Kontaktart und weitere Elemente können bei Bedarf einbezogen werden.

Bei der weiteren Betrachtung werden Zuordnungen zu Einrichtungskontakt, Abteilungskontakt oder Versorgungsstellenkontakt geprüft. Standort und Organisation werden mitbetrachtet; Diagnose und Prozedur werden einbezogen, wenn sie für den jeweiligen Schritt relevant sind.

Eine mögliche Vermengung von Organisationsstruktur und Standort im Hierarchiemodell wird als zu prüfende Hypothese behandelt, nicht als feststehendes Ergebnis.

## Dokumentation

Im Repository werden die erarbeiteten Versorgungsszenarien und Journey-Skizzen sowie Zuordnungsversuche, Beobachtungen und offene Fragen festgehalten. Dazu gehören insbesondere:

- Journey-Schritte, Ereignisse, Kontakte und Übergänge
- Zuordnungen zu Kontaktebenen und gegebenenfalls Kontaktarten
- unklare oder nicht eindeutige Zuordnungen
- Begriffs- und Abgrenzungsfragen
- fehlende Informationen und Unsicherheiten
- mögliche Modellierungsimplikationen

Die zentrale Gesamtdokumentation erfolgt in [output.md](output.md). Ergänzende Unterlagen und Arbeitsmaterialien werden im Ordner [content/](content/) abgelegt. Jede Teilnehmergruppe dokumentiert ihre Beiträge im jeweils eigenen Ordner ([Teilnehmergruppe-01](Teilnehmergruppe-01/README.md), [Teilnehmergruppe-02](Teilnehmergruppe-02/README.md), [Teilnehmergruppe-03](Teilnehmergruppe-03/README.md), [Teilnehmergruppe-04](Teilnehmergruppe-04/README.md), [Teilnehmergruppe-05](Teilnehmergruppe-05/README.md), [Teilnehmergruppe-06](Teilnehmergruppe-06/README.md), [Teilnehmergruppe-07](Teilnehmergruppe-07/README.md), [Teilnehmergruppe-08](Teilnehmergruppe-08/README.md), [Teilnehmergruppe-09](Teilnehmergruppe-09/README.md), [Teilnehmergruppe-10](Teilnehmergruppe-10/README.md)).

## Clustering der Szenarien

Ähnliche Situationen werden durch eine moderierende Person parallel zur Kleingruppenarbeit gruppiert; die Gemeinsamkeiten der Cluster werden beschrieben. Das Clustern ist keine Aufgabe der Teilnehmenden und kein eigener Arbeitsauftrag.

## Ergebnisse und nächste Schritte

Die Workshop-Ergebnisse bilden einen gemeinsamen Arbeitsstand und eine strukturierte Sammlung fachlicher Bedarfe, offener Fragen und möglicher Modellierungsimplikationen. Sie dienen der weiteren fachlichen und spezifikatorischen Diskussion.

Im Workshop wird keine Spezifikationsentscheidung und keine unmittelbare Änderung am Informationsmodell erzwungen. Offene Fragen dürfen ausdrücklich offenbleiben und werden für die weitere Bearbeitung dokumentiert.

## Offene Angaben

Folgende Angaben sind in den verfügbaren Informationen nicht abschließend festgelegt und werden bei Bedarf ergänzt:

- konkreter Termin und Ort
- Namen oder Zuordnung der Teilnehmenden
- Zuständigkeiten für die weitere Bearbeitung
