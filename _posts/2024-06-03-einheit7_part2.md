---
title: "Einheit 07B: Suchmaschinen und Discovery Systeme - Teil 2"
date: 2024-06-03
---

In diesem Beitrag geht es um die restlichen Inhalte des siebten Unterrichtsblocks vom Morgen des 3.Juni (08:30 - 12:00). 

## VuFind Datenintegration
Diese Gruppenarbeit habe ich während der Vorlesung zwar live mitbekommen, doch um mein eigenes Verständnis dafür zu sichern, führe ich sie selbst noch einmal durch mit Hilfe der Aufzeichnung. Glückicherweise scheint der Server über den Cloudhoster noch zu laufen, damit mir dies auch möglich ist. Abbildung 1 zeigt, wie ich die Institution in der properties-Datei benannt habe, und den erfolgreichen Datenimport in VuFind.  

![Datenimport VuFind](\Lerntagebuch_BAIN\images\Screenshot_vufind_test240630.jpg)  
*Abb. 1: Test Datenimport in VuFind*  

Was mir hier auch gleich auffällt, ist das jemand an dieser VuFind Konfiguration Änderungen vorgenommen hat. Das ist wahrscheinlich im zweiten Teil der Vorlesung passiert, den ich nicht mehr live mitangesehen habe. Auf dem dem Programm für den Unterricht steht zumindest auch "Gruppenarbeit VuFind Konfiguration". Aber dazu komme ich sicher später auch noch. Abbildung 2 zeigt hier schon einmal eine Side-by-Side Comparison. Auf der linken Seite eine, meiner Meinung nach unveränderte, Konfiguration. Auf der rechten Seite die abgeänderte Konfiguration mit meinen zuvor importierten Testdaten. Ganz auffällig ist auf der rechten Seite, dass der Tab-Header im Browser umbenannt wurde und mir freundlich hallo sagt.  

![VuFind Side-by-Side Comparison](\Lerntagebuch_BAIN\images\Screenshot_vufind_comparison.jpg)  
*Abb. 2: VuFind Side-by-Side Comparison*  

Gemeinsam mit der Aufzeichnung hab ich auch noch den Error beim Import der Archivesspace Datei behoben, also die ID vergeben, und so diesen Datensatz auch noch importiert:  

![VuFind ArchivesSpace Controlfield](\Lerntagebuch_BAIN\images\Screenshot_vufind_importarchivesspace.jpg)  
*Abb. 3: Controlfield Tag der ArchivesSpace XML Datei*  

### VuFind Konfiguration
Hier probiere ich auch kurz kleine Änderungen vorzunehmen. Ich ändere wieder den Titel im Header des Browsertabs, sowie den Separator, ändere das Theme zu sandal und positioniere die sidebar wieder auf der rechten Seite. Ich habe die Änderungen in Abbildung 4 farbig markiert.  

![VuFind Konfiguration](\Lerntagebuch_BAIN\images\Screenshot_vufind_config.jpg)  
*Abb. 4: Änderungen der Konfiguration von VuFind*  

## Suchportal der HAAB
Im nächsten Teil der Vorlesung betrachten wir die Beta-Version des Suchportals der Herzogin Anna Amalia Bibliothek (kurz HAAB), welches auch auf VuFind basiert. Für ihr Discovery-System benutzen sie keinen eigenen Suchindex, sondern benutzen den externen Solr von K10plus-Zentral, aus diesem sie lediglich die eigenen Daten herausfiltern und für die eigene Suche anbieten. Abbildung 5 zeigt einen Überblick über die Systemarchitektur des Suchportals der HAAB, aus dem ersichtlich wird, dass verschiedene Schnittstellen zur Betreibung des Systems notwendig sind.  

![HAAB Systemarchitektur](\Lerntagebuch_BAINimages\Screenshot_HAAB_systemarchitektur.jpg)  
*Abb. 5: Systemarchitektur des Suchportals der HAAB*  
(Quelle: [Gemeinsames Dokument zu dieser Lehreinheit](https://pad.gwdg.de/5jn060c8RDC6WukTIuP5RQ#Beispiel-Suchportal-der-HAAB))  

