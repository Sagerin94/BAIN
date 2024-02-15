---
title: "Einheit 1.2: Technische Grundlagen 2/2"
date: 2024-02-14
---

In diesem Beitrag geht es um die Inhalte des zweiten Unterrichtsblocks vom Nachmittag des 14. Februars 2024 (13:00 - 16:30). Er führt die Inhalte aus dem vorhergehenden Post [Technische Grundlagen 1/2](https://sagerin94.github.io/Lerntagebuch_BAIN/2024/02/14/einheit1_part1.html) weiter und vervollständigt die Zusammenfassung der ersten Lehreinheit.

## Codespace und Unix-Shell

Wie wir im Unterricht vom Vormittag bereits ausporbiert haben, verwenden wir an diesem Nachmittag eine, der die nötigen Dateien für die korrekte Bearbeitung der Nachfolgenden Übungen enthält. Abbildung 1 zeigt den aktiven Codespace.  

![Screenshot des zur Verfügung gestellten Codespaces auf GitHub](\Lerntagebuch_BAIN\images\Screenshot_codespace.jpg)
*Abb. 1: Screenshot des zur Verfügung gestellten Codespaces auf GitHub*

### Library Carpentry Lesson

Um den Umgang mit den Unix Commands zu üben bearbeiten wir selbstständig die [Library Carpentry Lesson](https://librarycarpentry.org/lc-shell/02-navigating-the-filesystem.html) zur Unix Shell. In Kapitel 2 werden die Basics der Navigation im Filesystem mit Hilfe der Shell erklärt. Im Kapitel 3 geht es um einfache Befehle zum Erstellen, Betrachten und Bearbeiten von Files und Directories. Diese Commands sind uns aus dem Modul ARIS bereits bekannt, doch bin ich selbst froh um die Repetition, da ich stets mit Windows arbeite und mich kaum mit Linux beschäftige.  

### Komplexere Shell Commands

Im nächsten Teil der Vorlesung arbeiten wir immer noch mit der Library Carpentry Lesson, diesmal bearbeiten wir Kapitel 5: Counting and Mining with the shell. Diese Commands werden schnell komplexer. Was ebenfalls grob erklärt wird, und was ich noch vage aus ARIS in Erinnerung hatte, ist das Prinzip der Pipes und Filters. Dies besagt, dass diverse Befehle aneinander gereiht werden können, die dann nacheinander ausgeführt und verkettet werden (Pipes) und 


![Darstellung Prinzip Pipes und Filter in Linux](\Lerntagebuch_BAIN\images\Screenshot_pipes_filters.jpg)
*Abb. 2: Input und Output von Befehlen in der Shell (Bildquelle: [https://librarycarpentry.org/lc-shell/05-counting-mining.html](https://librarycarpentry.org/lc-shell/05-counting-mining.html))*


## Git und GitHub


### Erstellen der Blogbeiträge

Ich habe mich dazu entschieden für die Erstellung der Blogbeiträge lokal mit Visual Studio Code zu arbeiten, so wie ich es mir aus anderen Projekten bereits gewöhnt bin. Durch eine lokale Kopie meines Repository auf GitHub kann ich die Versionsverwaltung mittels Git vornehmen und meine Änderungen im Anschluss direkt im Terminal des Editors auf den master zu pushen. Best Practice wäre es wohl, zuerst auf einem anderen Branch zu arbeiten und anschliessend in den master zu mergen. Da ich jedoch alleine auf diesem Repository arbeite und die vorgenommenen Änderungen auch direkt deployen möchte, spare ich mir diesen zusätzlichen Schritt. 

![Screenshot Visual Studio Code](\Lerntagebuch_BAIN\images\Screenshot_VSCode.jpg)
*Abb. 2 : Meine Arbeit an den Blogbeiträgen im Visual Studio Code mit Versionsverwaltung durch Git.*


