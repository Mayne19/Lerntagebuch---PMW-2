# Lerntagebuch

## Woche 2026-04-13

### Lernziel

- Softwareentwickler arbeiten als Handwerker, nicht als Künstler
- Ein Profi hat: Fachwissen, Werkzeuge, Prinzipien
- Eine Laie macht versehentlich etwas richtig, ein Profi mit Absicht
- Craftsmanship: absichtliches und professionelles Handeln
- Clean Code Developer hat vier Werte: Wandelbarkeit, Korrektheit, Produktionseffizienz, kontinuierliche Verbesserung
- Teure Softwarefehler: Ariane 5 (370 Millionen Dollar), Mariner 1 (18,5 Millionen Dollar)
- GitLab-Account mit DFN-AAI Single Sign-On erstellen
- Repository in Gruppe "Lerntagebuecher" mit Name "fdnummer"
- README.md im Markdown-Format und Datei [MATRIKELNUMMER].mnr anlegen
 

### Erkenntnis

Das Wichtigste, das mich angesprochen hat, ist dass ein Profi mit Absicht arbeitet, nicht zufällig. Ich habe auch gesehen dass die GitLab-Struktur exakt sein muss, sonst funktioniert nichts. Das zeigt mir: Im Gruppenprojekt muss ich auch so arbeiten. Jeder Commit, jeder Dateiname muss einen Grund haben.

### Wiederholung

**Craftsmanship** ist das zentrale Konzept. Ein Handwerker verfügt über drei Elemente: 
- Fachwissen
- Werkzeuge 
- Prinzipien 

In der Softwareentwicklung heißt das: Ich kenne Git und Programmiersprachen, habe eine IDE und GitLab, und arbeite nach Prinzipien wie Clean Code. Das ist nicht zufällig sondern absichtlich.


## Woche 2026-04-20

### Lernziel

- Programmierparadigmen verstehen und unterscheiden
- Imperative und deklarative Programmierung vergleichen
- Prozedurale und objektorientierte Programmierung verstehen
- Grundlagen der funktionalen Programmierung kennenlernen
- Unterschied zwischen typisierten und typenlosen Sprachen verstehen
- Prinzipien wie SOLID, STUPID, KISS und YAGNI kennenlernen
- Conway's Game of Life mit KI umsetzen (C, Python, Java)
- Unterschied zwischen prozeduraler und objektorientierter Logik praktisch anwenden
- Polymorphie verstehen und einsetzen

### Erkenntnis

Ich habe verstanden, dass Programmieren eine Denkweise ist. Besonders wichtig war für mich der Unterschied zwischen imperativer und deklarativer Programmierung. Außerdem habe ich gesehen, dass gute Software nicht zufällig entsteht, sondern auf klaren Prinzipien wie SOLID und KISS basiert.

### Wiederholung

1. Ein Programmierparadigma ist eine grundlegende Denkweise beim Programmieren. Die imperative Programmierung arbeitet Schritt für Schritt mit Befehlen, während die deklarative nur beschreibt, was erreicht werden soll.

2. Die prozedurale Programmierung nutzt Funktionen, die nacheinander ausgeführt werden. Die objektorientierte Programmierung arbeitet mit Klassen und Objekten und nutzt Konzepte wie Kapselung, Vererbung und Polymorphie.

3. Typisierte Sprachen prüfen Datentypen vor der Ausführung, während typenlose Sprachen dies erst zur Laufzeit tun. Prinzipien der Programmierung helfen, den Code einfach und wartbar zu halten.



## Woche 2026-04-27

### Lernziel

- Verständnis von Debugging und Arbeiten mit Breakpoints in Eclipse  
- Beobachtung von Variablen während der Programmausführung  
- Unterschied zwischen funktionierendem und fehlerhaftem Code erkennen  
- Grundlagen von Containern verstehen (Docker)  
- Unterschied zwischen virtuellen Maschinen und Containern kennen  
- Rolle von Kubernetes zur Verwaltung von Containern verstehen  
- Verständnis von Design Patterns als Lösungen für wiederkehrende Probleme  
- Überblick über verschiedene Arten von Design Patterns  
- Anwendung der Inhalte in den Übungen (Analyse von Programmen und Fehlersuche)


### Erkenntnis

Ich fand besonders interessant, wie Debugging funktioniert. Vorher habe ich Programme einfach gestartet und nur das Ergebnis gesehen. Mit Breakpoints konnte ich Schritt für Schritt verfolgen, was passiert.

Besonders bei Übung2 war das wichtig. Das Programm hatte keinen Fehler in der Syntax, aber das Ergebnis war falsch. Durch Debugging konnte ich sehen, dass sich die Variable verändert und dadurch ein falsches Ergebnis entsteht.

Das hat mir gezeigt, dass man Programme nicht nur schreiben, sondern auch richtig analysieren muss.


### Wiederholung

Ein **Container** ist eine isolierte Umgebung, in der ein Programm läuft. Er enthält das Programm und alle notwendigen Abhängigkeiten. Dadurch funktioniert das Programm auf verschiedenen Systemen gleich. Container sind leicht und starten schnell. Sie werden oft mit Docker erstellt und genutzt.


## Woche 2026-05-04

### Lernziel

- Grundlagen von Git als Source-Code-Management-System
- Vorteile von Git gegenüber einfachen Kopien oder ZIP-Archiven
- Unterschied zwischen zentralisiertem und verteiltem Arbeiten
- Grundkonzept von Git: Working Directory, Staging Area, Repository, Commits, Commit-ID und Branches
- Praktische Arbeit mit einem lokalen Git-Repository
- Erstellen und Bearbeiten einer Textdatei
- Vorbereiten und Speichern von Änderungen mit Staging Area und Commit
- Anzeigen und Vergleichen von Änderungen
- Zurücksetzen von Änderungen im Working Directory, in der Staging Area und auf den letzten Commit-Stand

### Erkenntnis

Besonders interessant fand ich die Staging Area, weil sie zeigt, dass ein Commit nicht automatisch alle Änderungen speichert. Man kann vorher genau auswählen, welche Änderungen in den nächsten Commit übernommen werden sollen. Dadurch arbeitet man kontrollierter und kann saubere, kleinere Commits erstellen.

### Wiederholung

Die **Staging Area** ist ein Zwischenbereich zwischen dem Working Directory und dem Repository. Im Working Directory werden Dateien normal bearbeitet. Mit `git add` werden ausgewählte Änderungen in die Staging Area übernommen. Erst mit `git commit` werden diese vorbereiteten Änderungen dauerhaft im Repository gespeichert.


## Woche 2026-05-11

### Lernziel

- Kooperation im Softwareentwicklungsprozess
- Zusammenarbeit mehrerer Entwickler in größeren Softwareprojekten
- Zusammenführen einzelner Arbeitsergebnisse
- Technische und persönliche Konflikte bei der Integration
- Vorteile von Continuous Integration
- Bestandteile eines Softwareentwicklungsprozesses
- Abhängigkeitenverwaltung und semantische Versionierung
- Rolle eines Source-Code-Management-Systems
- Build-Prozess mit Kompilierung, Tests und Bereitstellung
- Bedeutung und Grenzen automatisierter Tests
- Arbeit mit Remote Repositories
- Verbindung zwischen lokalem Repository und Remote Repository
- Push, Pull, Fetch, Clone und Tracking Branches
- Unterschied zwischen gemeinsamem Remote Repository und privatem Fork

### Erkenntnis

Besonders interessant fand ich, dass Zusammenarbeit in der Softwareentwicklung nicht nur bedeutet, Code zu schreiben. Wenn mehrere Entwickler an einem Projekt arbeiten, müssen Änderungen regelmäßig zusammengeführt, getestet und bereitgestellt werden. Dadurch wird klar, warum SCM, Remote Repositories und Continuous Integration wichtig sind.

### Wiederholung

Ein **Remote Repository** ist ein Git-Repository, das nicht nur lokal auf dem eigenen Rechner liegt, sondern als gemeinsamer Speicherort für ein Projekt verwendet wird. Entwickler können ihre Änderungen dorthin hochladen und Änderungen von anderen Entwicklern herunterladen. Dadurch wird die Zusammenarbeit im Team einfacher und der aktuelle Stand des Projekts kann zentral verfügbar gemacht werden.


## Woche 2026-05-18

### Lernziel

- Grundlagen des Projektmanagements
- Unterschied zwischen Regelprozess, Linienmaßnahme, Vorhaben und Projekt
- Merkmale eines Projekts: Ziel, Zeitraum, Ressourcen, Komplexität und Risiko
- Projektmanagement als Planung, Organisation, Durchführung und Kontrolle
- Zusammenarbeit von Menschen als wichtiger Teil des Projektmanagements
- Rollen im Projektmanagement: Auftraggeber, Projektleiter, Projektmitarbeiter und Stakeholder
- Projektmanagement-Modelle: Wasserfallmodell, V-Modell und agile Modelle
- Projektmanagement-Techniken: Kanban, Burn-Down-Chart und Scrum
- Aufwandsschätzung mit Story Points
- Schätzverfahren wie Drei-Werte-Weg, historischer Vergleich und Planning Poker
- Klassische und agile Projektdokumentation

### Erkenntnis

Besonders interessant fand ich, dass Projektmanagement nicht nur aus Planung und Kontrolle besteht. Es geht auch stark um die Zusammenarbeit von Menschen. Aufgaben müssen verteilt werden, Informationen müssen klar sein und mögliche Konflikte sollten früh erkannt werden. Dadurch wird deutlich, dass gute Kommunikation für ein Projekt genauso wichtig ist wie die technische Arbeit.

### Wiederholung

**Planning Poker** ist eine Methode zur Aufwandsschätzung in agilen Projekten. Jedes Teammitglied schätzt den Aufwand einer Aufgabe zuerst allein mit speziellen Karten. Danach werden die Karten gleichzeitig gezeigt. Sehr niedrige oder sehr hohe Schätzungen müssen begründet werden. So kann das Team gemeinsam eine nachvollziehbare Einschätzung finden.


## Woche 2026-06-01

### Lernziel

- Grundlagen des Softwaretestens
- Motivation für Tests: Fehler erkennen und unerwünschtes Verhalten vermeiden
- Begriffe aus dem Testbereich: Qualitätssicherung, Testmanagement, Testumgebung und Test
- Unterschied zwischen Error, Defect und Failure
- Arten von Fehlern: latente, maskierte und kaskadierte Fehler
- Arten von Tests: manuelle Tests, automatisierte Tests, statische Codeanalyse und dynamische Tests
- Bestandteile eines Tests: Testfall, Testdaten, Testobjekt, Testumgebung, Testziel und Soll-Ist-Vergleich
- Ziele von Tests: Fehler aufzeigen, Qualität erfassen, Vertrauen erhöhen und Grenzen ermitteln
- Testebenen und Bedeutung der Testpyramide
- Ablauf des Testprozesses: Planung, Analyse, Design, Testausführung und Testnachbereitung
- Definition konkreter Testfälle für einfache Softwarefunktionen
- Einordnung veröffentlichter Softwarefehler nach Fehlerarten
- Psychologische Aspekte beim Testen, zum Beispiel Betriebsblindheit und gegenseitiges Testen

### Erkenntnis

Besonders interessant fand ich, dass ein Test nicht nur bedeutet, ein Programm kurz auszuprobieren. Ein guter Testfall braucht ein klares Testziel, passende Testdaten, ein Testobjekt, eine Testumgebung und einen Soll-Ist-Vergleich. Dadurch kann man gezielt prüfen, ob eine Software das erwartete Verhalten zeigt. Außerdem wurde deutlich, dass Tests Fehler nicht vollständig ausschließen, aber helfen, Risiken zu reduzieren und Vertrauen in die Software zu erhöhen.

### Wiederholung
  
Ein **Testfall:** beschreibt eine konkrete Situation, mit der geprüft wird, ob eine Software wie erwartet funktioniert. Dazu gehören bestimmte Eingaben, ein erwartetes Ergebnis und der Vergleich zwischen Soll-Wert und Ist-Wert. Ein Testfall hilft also dabei, das Verhalten eines Programms gezielt und nachvollziehbar zu überprüfen.

## Woche 2026-06-08

### Lernziel

- Grundlagen der Testautomatisierung
- Probleme manueller Tests, zum Beispiel hoher Aufwand, fehlende Wiederholbarkeit und nachlassende Aufmerksamkeit
- Gründe für automatisierte Tests
- Zusammenhang zwischen automatisierten Tests und Qualitätskosten
- Kriterien für Tests, die sich gut automatisieren lassen
- Unterschied zwischen UnitTests, Modultests und ApplicationTests
- Bedeutung von UnitTests als ausführbare Dokumentation
- Eigenschaften guter UnitTests: schnell, unabhängig, wiederholbar, selbstauswertend, zeitnah, lesbar, vertrauenswürdig und wartbar
- Testbarkeit von produktivem Code
- Einfluss von Clean Code und SOLID-Prinzipien auf gute Tests
- Ersetzen von Abhängigkeiten durch Test-Doubles
- Arten von Test-Doubles: Stub, Fake und Mock
- Praktische Umsetzung automatisierter Tests in Java mit Maven und JUnit

### Erkenntnis

Besonders interessant fand ich, dass UnitTests nicht einfach nur Code testen, sondern das von außen beobachtbare gewünschte Verhalten einer Unit überprüfen. Ein guter UnitTest sollte schnell, unabhängig und wiederholbar sein. Dadurch kann er regelmäßig ausgeführt werden und hilft dabei, Fehler früh zu erkennen. In der Übung wurde außerdem deutlich, dass automatisierte Tests nicht nur Theorie sind, sondern direkt in einem Projekt geschrieben, ausgeführt und versioniert werden können.

### Wiederholung
  
Ein **UnitTest** überprüft eine einzelne Unit, zum Beispiel eine Methode oder eine kleine Funktionseinheit. Dabei wird geprüft, ob die Unit bei bestimmten Eingaben das erwartete Verhalten zeigt. Ein guter UnitTest ist unabhängig von anderen Tests, liefert ein eindeutiges Ergebnis und kann häufig automatisch ausgeführt werden.
