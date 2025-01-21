---
layout: page
title: Testen und Testbarkeit bei der ABAP-Entwicklung
permalink: /testing/
next_page_link: /testing/testorganization
next_page_title: Rahmenbedingungen und die Rolle der Organisation beim Thema ABAP-UNIT-Tests
has_children: true
nav_order: 4
---

{: .no_toc}
# Testen und Testbarkeit bei der ABAP-Entwicklung  

1. TOC
{:toc}


## Einführung ins Thema und Inhalte des Kapitels.

Testen von SAP Anwendungenn ist immer ein großes Thema in Projekten und im Betrieb. Testen ist notwendig, es ist sehr Aufwändig und es gibt viele Bestrebungen in den Unternehmen und technisch viele Möglichkeiten, Tests zu automatisieren.
Die Möglichkeit ABAP Unit Tests zu implementieren besteht nun schon einige Jahre, doch der flächendeckende Einsatz in den Unternehmen ist noch nicht so fortgeschritten wie in anderen Programmiersprachen. 
In diesem Kapitel möchten wir ein paar Hintergründe beleuchten, Hilfestellung geben sich in das Thema einzuarbeiten und vor allem Motivieren, das Thema UNIT TESTS in der ABAP Entwicklung in die Praxis zu bringen.

Dieses Kapitel teilt sich in folgende Abschnitte auf:
- [**AAutomatisierte Tests - Ein Thema der Organisation und der Rahmenbedingungen**](testorganization.md)
   Gründe warum es schwierig ist, Unit Test in den Entwicklungsalltag einzubinden und Hinweise zu Rahmenbedingungen die erforderlich sind, dies zu ändern.

- [**Das ABAP UNIT Test Framework - Entwicklung automatisiert Tests**](abap-unit.md) 
   Beschreibung wie Unit Tests erstellt werden und Hilfestellung zum schnellen Einstieg, sowie Tipps und  Praxiserfahrungen von Experten. 

- [**Empfehlungen für Testwerkzeuge**](recommended-tools.md)
  Ein paar Tipps welche Testwerkzeuge es gibt.  

- [**Andere Test Tools**](abap-unit.md) 
  Und hier müssen wir schauen was wir wirklich hier brauchen


## Zielgruppe des Kapitels 
In diesem Kapitel werden einige komplexere Themen erläutert, daher ist eine Zielgruppe die der erfahrenen Entwickler die sich mit dem Thema ABAP-Unit auseinandersetzen möchten und entweder Unterstützung beim Einarbeiten oder generell Hinweise und Anregungen zur Anwendung bekommen möchten.  Wir hoffen, dass dieser Leitfaden in manchen Teams, dem Thema ABAP Unit und Testen etwas Anschub geben kann, denn die hier beschriebenen Vorgehensweisen sind Erfahrungswerte aus der Praxis.  

Wir möchten hier aber auch wie in den anderen Kapiteln Entscheider, Vorgesetzte und Projektleiter ansprechen und motivieren sich mit den hier beschriebenen Inhalten auseinandersetzen um moderne Entwicklungsmethoden wie ABAP-UNIT besser zu verstehen, die Vorteile zu erkennen und darauf basierend, fundiertere Entscheidungen treffen zu können. Lassen Sie sich also bitte nicht von manch komplexen technischen Erläuterungen nicht abschrecken. Für die Unsetzung haben Sie ja Ihre Entwickler.


## Abgrenzungen 
* Was betrachten wir nicht. ! Am Ende schreiben ! - ALSO hier kommt noch was.
Als ABAP-/Entwicklungsleitfaden können wir leider nicht jeden Aspekt des Testens betrachten. Daher liegt der Schwerpunkt auf der Unterstützung des Testens mittels des ABAP UNIT Frameworks und damit programmierter Tests die einem definierten Muster folgen.
Damit schließen wir hier die Programmierung von Testtreibern, Testprogrammen oder Simulationsprogrammen aus, die den Produktcode direkt ausführen. Dies kann sinnvoll sein, wird in diesem Leitfaden aber nicht betrachtet.
