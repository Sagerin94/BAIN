---
title: "Einheit 06A: Metadaten modellieren und Schnittstellen nutzen - Open Refine"
date: 2024-04-23
---

In diesem Beitrag geht es um die Inhalte des sechsten Unterrichtsblocks von den Nachmittagen des 23. April (15:00 - 16:30) und 30. April 2024 (15:00 - 16:30).

## Open Refine  
![Logo OpenRefine](\Lerntagebuch_BAIN\images\logo_openrefine.jpg)  
*Abb. 1: Logo OpenRefine*

OpenRefine hat als Logo einen grossen Diamanten, diese Metapher wird verwendet, weil es darum geht Rohdaten aufzubereiten und zu bereinigen, also zu schleifen wie einen Rohdiamanten.

Hauptfunktionen von OpenRefine:
- Facetierung zur Filterung und Navigation durch die Daten, zur Analyse und die Bereinigung
- Clustering zur Erkennung von Namensgleichheiten
- Reconciliation um Daten aus Wikidata abzurufen oder Daten an Wikidata zu spenden
- Infinite undo / redo um die Datenänderungen zu protokollieren
- speichert Daten nur lokal und werden nur Veröffentlicht wenn vom User gewünscht (Privacy)

OpenRefine hat eine grosse, aktive Community, da die Software mal zu Google gehörte und damit eine grosse Prominenz erlangen konnte. Dadurch wird die Software auch nicht nur in der Bibliotheks- und Archivbranche benutzt, sondern auch in anderen Branchen, wobei Bibliotheken schon den grössten Anteil ausmachen.  
![Wer benutzt OpenRefine](\Lerntagebuch_BAIN\images\Screenshot_openrefine_branchen.jpg)  
*Abb. 2: Nutzung von OpenRefine (Quelle: [Nutzungsstatistik](https://openrefine.org/blog/2022/06/28/2022-survey-results.html))*  

### Bearbeiten eines Übungsdatensatzes
Über gitHub haben wir einen Codespace gestartet, über den wir OpenRefine benutzen (spart uns die lokale Installation der Software, wäre aber durchaus auch möglich). 

Tipps: Vor einer Datenänderung (insbesondere in der Undo / Redo Ansicht) prüfen ob nicht noch eine Facette ausgewählt ist (zweifelsfrei in der Titelzeile erkennbar)
![OpenRefine Titelzeile](\Lerntagebuch_BAIN\images\Screenshot_openrefine_aktiveFacette.jpg)  
*Abb. 3: Titelzeile bei aktiver Facettierung OpenRefine*  

Fingerübungen:  
Was ist die am häufigsten vergebene Lizenz? --> CC BY (954 Zeilen)  
Wieviele Artikel haben keine Lizenz? --> 6 Zeilen  
Warum erscheint MDPI AG zweimal und wie lässt sich das korrigieren? --> Der eine Treffer hat 2 Leerschläge dazwischen; editieren und 1 Leerschlag aus der Facette löschen.

### Export von OpenRefine nach MARCXML  
OpenRefine besitzt keine direkte Möglichkeit, die Datensätze in MARCXML zu exportieren. Jedoch gibt es über die Funktion "Templating" die Möglichkeit, das Schema des Ausgabeformats selbst zu definieren. Wenn man hier also das MARCXML Schema einfügt, werden die Daten dementsprechend angepasst.  

![OpenRefine Tempating Export](\Lerntagebuch_BAIN\images\Screenshot_openrefine_export.jpg)  
*Abb. 4: Templating Export in OpenRefine mit Teilen des MARCXML Schemas*  

Daraus lässt sich zum Beispiel lesen, dass nur der erste Wert der Zelle "Authors" in das Tag 100 (also der Lead Author) und die rechtlichen Autoren ins Tag 700, oder der Wert der Zelle "Title" in das Tag 245 übertragen wird. Die Angabe von ".escape('xml')" sorgt dafür, dass Zeichen welche in XML nicht erlaubt sind, abgefangen werden. Die Prüfung des augegebenen Files ergibt ein valides XML.   
![XML Validation](\Lerntagebuch_BAIN\images\Screenshot_xml_validation.jpg)  
*Abb. 5: XML Validation*  

## Fazit
Die Übung mit OpenRefine hat mir sehr Spass gemacht. Ich habe die LibraryCarpentry Lessons noch nicht durchgearbeitet, doch könnte ich mir vorstellen dies zu einem späteren Zeitpunkt noch zu tun, denn wir haben bis jetzt wohl nur an der Oberfläche dessen gekratzt, wozu OpenRefine in der Lage wäre. Den Export mit MARCXML habe ich grundsätzlich verstanden, aber auch hier merke ich, dass mir wohl noch das tiefere Verständnis für das Datenformat fehlt. Also welche Felder / Tags wofür stehen und auch die zugehörige Dokumentation finde ich immer noch schwer verständlich. Das liegt wohl einfach daran, dass ich bis jetzt immer noch nie vertieft damit gearbeitet habe, sondern ich nur die Basics durch den Unterricht vermittelt bekommen habe. In der nächsten Lektion geht es dann um das modellieren von Metadaten und das Nutzen von Schnittstellen, vielleicht arbeiten wir da nochmals mit MARC so dass ich mein Wissen noch etwas vertiefen kann. 