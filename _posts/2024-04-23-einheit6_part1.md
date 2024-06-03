---
title: "Einheit 06A: Metadaten modellieren und Schnittstellen nutzen - Open Refine"
date: 2024-03-26
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
*Abb. 3: Titelzeile bei aktiver Facettierung Openrefine*

Fingerübungen:
Was ist die am häufigsten vergebene Lizenz? --> CC BY (954 Zeilen)
Wieviele Artikel haben keine Lizenz? --> 6 Zeilen
Warum erscheint MDPI AG zweimal und wie lässt sich das korrigieren? --> Der eine Treffer hat 2 Leerschläge dazwischen; editieren und 1 Leerschlag aus der Facette löschen.





