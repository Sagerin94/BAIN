---
title: "Einheit 07A: Suchmaschinen und Discovery Systeme - Teil 1 "
date: 2024-05-21
---

In diesem Beitrag geht es um die Inhalte des siebten Unterrichtsblocks vom Nachmittag des 21.Mai (15:00 - 18:30). 

## Discovery-Systeme vs. OPAC
Ein OPAC (Online Public Access Catalog) und ein Discovery-System sind grundsätzlich beides Werkzeuge, die Bibliotheken verwenden, um Benutzern den Zugang zu ihren Sammlungen zu ermöglichen. Jedoch unterscheiden sie sich stark in ihren Funktionalitäten.

### OPAC
Ein OPAC ist ein Online-Katalog, der Bibliotheksbenutzenden Zugang zu den physischen und digitalen Beständen einer Bibliothek bietet. Sie wurden in den 1970er Jahren eingeführt und waren zuerst eigentlich nichts weiter als die digitale Abbildung des analogen Katalogs mit seinen Katalogkarten. Mitte der 1990er Jahre wurden erste Schnittstellen hinzugefügt, dass der OPAC über das Internet zugänglich wurde. Trotz aller technischer Fortschritte bieten OPACs nur wenig Suchmöglichkeiten, die selten über die Suche mit Booleschen Operatoren, Indizes, Trunkierung und die Suche nach dem "Exact Match" hinausgehen (Quelle: [Discovery Systeme vs. OPAC, Merle Hofeldt](https://opus4.kobv.de/opus4-fhpotsdam/frontdoor/index/index/docId/2429)).  

### Discovery-Systeme
Durch die Verbreitung moderner Suchmaschinen und ihrer fortschrittlicherern Technologie sind klassische OPACs schnell obsolet geworden. Damit Bibliotheken weiterhin relevant bleiben können in der Bereitstellung von (digitalen) Informationsressourcen wurden die Discovery-Systeme entwickelt. Sie sollen den Nutzenden ermöglichen, nicht nur im Katalog einer Bibliothek zu suchen, sondern gleichzeitig auch lizenzierte Inhalte aus Datenbanken und Repositorien angezeigt zu bekommen (Quelle: [Discovery Systeme vs. OPAC](https://opus4.kobv.de/opus4-fhpotsdam/frontdoor/index/index/docId/2429)).  

Weiterhin sollen bei der Suche in Discovery-Systemen die Suchergebnisse nach ihrer Relevanz beurteilt werden. Die Devise lautet hierbei nicht mehr "Exact Match", sondern "Best Match". So können Nutzende das Discovery-System auch ohne besondere Kenntnisse des Wissensbestands durchsuchen und erhalten eine wesentlich Grössere Trefferliste, da auch die Fehlertoleranz höher ist (Quelle: [OPAC vs. Discovery-System, Felix Lohmeier](https://felixlohmeier.gitbooks.io/kurs-bibliotheks-und-archivinformatik/content/kapitel-1/11-einfuhrung-ins-thema.html) )

### Unterschiede
Aus "Gwunder" habe ich dazu noch ChatGPT befragt und er gibt mir die folgenden Unterschiede zwischen einem OPAC und einem Discovery-System (Abb.1). Allerdings konnte er mir dazu keine wirklich brauchbare Quelle liefern. 

![OPAC vs Discovery System nach ChatGPT](\Lerntagebuch_BAIN\images\Screenshot_chatgpt_opac.jpg)  
*Abb. 1: Unterschied zwischen OPAC und Discovery-System nach ChatGPT*  

## VuFind
VuFind ist eine Open-Source-Discovery-Software, die von Bibliotheken verwendet wird, um Nutzenden eine einheitliche und benutzerfreundliche Schnittstelle zum Durchsuchen und Auffinden von Ressourcen zu bieten. Dazu gehört unter anderem: das Durchsuchen von Bibliothekskatalogen, institutionellen Repositorien, Open-Access-Journalartikeln, digitalisierten Bibliotheksmaterialien. Dabei nutzt VuFind Apache Solr als Suchmaschine, um Daten zu indexieren und durchsuchbar zu machen (Quelle: [VuFind](https://vufind.org/vufind/about.html)).

## Solr

Apache Solr ist eine hoch skalierbare, leistungsstarke Open-Source-Suchserver, der auf Apache Lucene basiert. Solr wird häufig für Volltextsuche, facettierte Navigation und Echtzeit-Indexierung eingesetzt. "The fundamental premise of Solr is simple. You give it a lot of information, then later you can ask it questions and find the piece of information you want" (Quelle: [Introduction to Solr](https://solr.apache.org/guide/solr/latest/getting-started/introduction.html)).