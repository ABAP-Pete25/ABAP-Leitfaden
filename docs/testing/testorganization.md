---
layout: page
title: Rahmenbedingungen und die Rolle der Organisation beim Thema ABAP-UNIT-Tests
permalink: /testing/testorganization
parent: Testen und Testbarkeit bei der ABAP-Entwicklung
prev_page_link: /testing/index
prev_page_title: Testen und Testbarkeit bei der ABAP-Entwicklung
next_page_link: /testing/abap_unit/
next_page_title: Das ABAP Unit Framework
nav_order: 1
---

# Automatisierte Tests - Ein Thema der Organisation und der Rahmenbedingungen

## Mangelndes Wissen und Qualifikation als Hindernis für den Einsatz von Unit Tests
Auch im Jahr 2025 bleibt die Herausforderung für Unternehmen bestehen, dass der Großteil der SAP Entwickler nur über eine lückenhafte bis nicht vorhandene Ausbildung und Erfahrung im Bereich der automatisierten Softwaretests hat. 
Dies hat eine Vielzahl von Gründen. Ein Grund ergibt sich aus der Nachfragesituation von SAP Projektkunden.
Eine große Anzahl an Fachkräften werden in Beratungsfirmen im Rahmen von Kundenprojekten ausgebildet, bei denen diese Fähigkeiten nicht vorrangig nachgefragt werden, sondern die Erfüllung der Kundenanfordungen und Einhaltung der Projekttermine im Vordergrund stehen. 
In vielen extern besetzten Projekten wird durch den hohen Erfolgs- und Zeitdruck auf die Möglichkeit,  Software testbar zu entwickeln und mittels ABAP-UNIT Tests abzusichern verzichtet.  Dieses wird oftmals als Option gesehen und fällt dann leider sehr oft unter den Tisch.

Kunden wünschen diese Testbarkeit oft nicht, da sie davon ausgehen, dass diese Methodik nicht zu einer Verkürung der Gesamtentwicklungsdauer beitragen wird. Beratungen fördern aufgrund der mangelnden Nachfrage diese Fähigkeiten der Entwickler viel zu wenig. 
Wenn ein Entwickler aus eigenem Antrieb und Qualitätbewußtsein, aufgrund eigener positiver Erfahrungen mit Unit-Tests oder auch wegen seinem Wissen Mittelfristig weniger Arbeit mit der Entwicklung zu haben sich dafür entscheidet, die Entwicklung mit Unit-Tests umzusetzen, kann es sein, dass gegen Projektregeln verstoßen werden oder Probleme entstehen, da die initiale Erstellung der Anwendung etwas aufwändiger ist und die Lieferung der ersten Version etwas später erfolgt. 

## Umdenken in der Organisation als Voraussetzung um Unit-Tests in den Einsatz zu bringen.
Damit sich der Einsatz von Unit Tests in ABAP weiter durchsetzt ist hier in Umdenken aus dem Projektmanagement und bei den Verantworlichen für den Betrieb von SAP-Software und Systemen nötig. 
Robert C. Martin sagte "The only way to go fast is, to go well". 
Erst wenn dies in den Organisationen angekommen ist, dass der vermeintliche zusätzliche Aufwand für die Erstellung von Unit Tests kein zusätzlicher Aufwand ist, sondern nur eine Verlagerung der Tätigkeiten von der Fehlersuche, der manuellen Erstellung von Testdaten und der manuellen Testdurchführung hin zur Programmierung, wird es nachhaltig dazu kommen, dass Unit Tests flächendeckend eingesetzt werden, da sich die Vorteile in der Praxis zeigen. 
Daher ist es wichtig anzufangen, einfache Beispiele zu suchen, Wissen aufbauen und Erfahrungen sammeln. Dieser Leitfaden soll hierbei den Einstieg erleichtern.
Ein Austausch mit Experten im SAP-Umfeld, die bereits Unit-Tests erfolgreich einsetzen hilft Bedenken zu streuen und Beispiele aus der Praxis motivieren es selbst zu probieren.

?????? HIER NUR KONZEPT NOTIZEN:
** TEMPLATE:  
Agilität wird nicht zuende eingesetzt.  Nur Änderungen am laufenden Band alles andere wird nicht umgesetzt **

Unit Tests und das Wissen dazu muss sich zu einem nötigen und geprüften Skill etablieren. Für einen ABAP Entwickler muss analog zu anderen unabdingbaren Bauteilen gehören unittests zu erstellen, zu pflegen und weiter zu entwickeln. 

** TEMPLATE: Ein fundiertes Wissen zu ABAP OO und objektorientierter Prinzipien sind für die Entwicklung von Unit Tests unabdingbar +++ 
???????   Ende



