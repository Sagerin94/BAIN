---
title: "Einheit 06B: Metadaten modellieren und Schnittstellen nutzen - Schnittstellen"
date: 2024-05-07
---

In diesem Beitrag geht es um die restlichen Inhalte des sechsten Unterrichtsblocks vom Nachmittag des 07.Mai (15:00 - 16:30). 

## Ausgangsdaten
![Schaubild aus dem Unterricht](\Lerntagebuch_BAIN\images\unterricht_schaubild.png)  
*Abb. 1: Schaubild aus dem Unterricht*  

## Schnittstellen

### Austauschprotokolle für Metadaten
Es gibt zahlreiche  Protokolle für die Übertragung von Metadaten. Im Rahmen des Unterrichts befassen wir uns jedoch vorwiegend mit [OAI-PMH](https://www.openarchives.org/pmh/). OAI-PMH eignet sich insbesondere für grössere Anfragen, da damit keine Suche nach Parametern möglich ist (zu diesem Zweck würde man eher SRU - Search/Retrieve cia URL verwenden). Ein Vorteil von OAI-PMH ist die Angabe eines Timestamps, so dass nur die geänderten Daten ab Zeitpunkt X geharvestet werden und man so einfache Aktualisierungen der Daten vornehmen kann, ohne jeweils die gesamte Datenmenge erneut harvesten zu müssen. 

### VuFindHarvest
Für die Übungen mit VuFindHarvest arbeiten wir wieder mit einem Codespace auf GitHub auf dem alles vorbereitet ist (Hier bin ich wirklich kurz reingefallen, weshalb ich keinen starten kann, weil ich zuerst selbst nicht in meinen GitHub Account eingeloggt war). Bei der Übung laden wir Datensätze aus der entsprechenden Demo-installation herunter, dazu müssen wir die Prefixes finden, um die Daten in den richtigen Formaten herunterzuladen.  

Der Prefix für den Import aus KOHA: --metadataPrefix=marc21  
Der Prefix für den Import aus ArchivesSpace: --metadataPrefix=oai_ead  
Der Prefix für den Import aus DSpace: --metadataPrefix=oai_dc  

![Import Daten aus ArchivesSpace](\Lerntagebuch_BAIN\images\Screenshot_vufindharvest_archivesspace.jpg)  
*Abb. 2: Erfolgreicher Datenimport aus ArchivesSpace*  

## Konvertierung
Mit den vom Dozenten zur Verfügung gestellten Beispieldaten arbeiten wir nun weiter. Das Ziel der Übung soll es sein, die Daten aus den unterschiedlichen Datenformaten einheitlich in das Datenformat MARC21-XML zu konvertieren. Dieser Prozess wird in der Branche auch gerne als *Crosswalk* bezeichnet. Dazu gibt es Regeln welche definieren, wie die Elemente zugeordnet werden sollen (sog. Mapping). 

Ein Beispiel für ein solches Mapping von der Library of Congress: 

![Mapping MARC to DC](\Lerntagebuch_BAIN\images\Screenshot_marc_dc_mapping.jpg)  
*Abb. 3: Mapping für die Konventierung von MARC nach Dublin Core*  
(Quelle: [Library of Congress](https://www.loc.gov/marc/marc2dc.html))


### MarcEdit





Da ich diese Unterrichteinheit nicht live mitverfolgt habe, sondern die Inhalte selbstständig, mit Hilfe der Aufnahme erarbeite, bin ich froh, dass die Übungen gut funktioniert haben. 