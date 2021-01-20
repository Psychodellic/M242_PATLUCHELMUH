Modul 242 
# Dokumentation vom Team PATLUCHELMUH über das Modul 242 Mikroprozessoranwendungen realisieren LB3

# Einleitung
In diesem Dokument beschreiben wir unsere Arbeitsschritte von dem Einrichten der Umgebung, Erstellung der eigenen Lernumgebung, arbeiten mit unseren Mikroprozessoranwendungen.  

# Inhaltsverzeichnis
* Team
* MQTT 
* Testing
  * Testfälle
  * Testergebnisse
* Fazit
* Reflexion
* Wissensgewinn


# Team Übersicht
  * Luca Miani
  * Patrick Schwab
  * Helmina Jusufi
  * Muhammed Ercan




# Testing
Tests dienen ganz einfach dazu verschiedene Dinge zu testen, bevor man das getestete verwendet. So kann man Fehler und Grenzen schon im Vorhinein finden und bei Bedarf verbessern. Jeglicher Test muss genau festgehalten werden und er muss von einer anderen Person replizierbar sein, ansonsten ist das Ergebnis des Tests wertlos.

Um unsere Vagrant files auch veröffentlichen wollen müssen wir sie zu erst testen. Dafür haben wir Testfälle erstellt und diese auch durchgeführt.


## Testfälle

### Testfall für VM 

| Die zu testende Aktion                                     | Erwartete Ausgabe/Aktion                                      | Tatsächliche Ausgabe/Aktion                     | 
| -----------------------                                    | -------------------------                                     |----------------------------                     |
| Im Browser auf 10.1.31.8 verbinden                         | Die Seite "m300-08-bist20 Web UI" erscheint                   | Die Seite "m300-08-bist20 Web UI" erscheint     |
| Im Browser auf 10.1.31.8:8080 verbinden                    | Apache2 Ubuntu Default Page öffnet sich                       |Apache2 Ubuntu Default Page öffnet sich          |
| Im Browser auf 10.1.31.8:8080/master verbinden             | /master: Apache2 Ubuntu Default Page öffnet sich              |/master: Apache2 Ubuntu Default Page öffnet sich |
| Die Vagrant files wurden ausgeführt                        | VM wird installiert                                           | VM wird installiert                             |
| Die VM's werden gestartet                                  | Die VMs können gestartet werden und die richtigen Dienste laufen |Die VMs können gestartet werden und die richtigen Dienste laufen|

### Testfall für Minecraft 

| Die zu testende Aktion                                     | Erwartete Ausgabe/Aktion                                      | Tatsächliche Ausgabe/Aktion                     | 
| -----------------------                                    | -------------------------                                     |----------------------------                     |
| VM soll mit Befehl "vagrant up" richtig erstellt werden    | Die VM wird richtig erstellt, alle Konfigurationen werden richtig erstellt und Software wird installiert| Die VM wurde richtig erstellt und die Konfiguration, plus Software wurde installiert | 
| Man kann im Game "Minecraft" mit der IP und dem Port 25565 auf den Minecraft Server beitreten | Ohne Fehlermeldung auf den Server beitereten und spielen könnn | Man kann den Server ohne Probleme betreten und mit seinen Freunde Spielen| 


## Testergebnisse

Der Test wurde erfolgreich abgenommen.
# Fazit

Mit Vagrant files können VM's schnell Aufgebaut werden so wie auch ganze Netzwerk Umgebungen. Duch Vagrant files können vor konfigurierte VM's und ganze Umgebungen einfach weitergegeben werden.

# Reflexion

## Reflexion Muhammed Ercan
Schon am ersten Tag, war es für mich interessant in diesem Modul. Das Projekt hatte mir Spass gemacht, auch wenn es eher kürzer ausgefallen ist, als wie gewohnt. Innerhalb dieses Projektes war es möglich vieles zu lernen. Diese Chance habe ich genützt, um mich mit meinem Team stetig auszutauschen. Auch zum ersten Mal habe ich mit der TBZ Cloud gearbeitet. Das hat mir gefallen, weil ich das Gefühl hatte, dass es viel schneller ist. Das Arbeiten an der Fach Hochschule gefiel mir sehr. Die Lehrperson war immer wieder bei Fragen erreichbar. Somit war es für mich eine gute Mischung aus Inputs vom Lehrer und dem Selbst Orientierten Lernen. Ich freue mich auf die weiteren Module.

## Reflexion Helmina Jusufi
### Arbeit
In diesem Modul habe ich sehr viel neues kennengelernt. Beim Einrichten der Umgebung habe ich gesehen, was es für verschiedene Möglichkeiten gibt. Ich habe gelernt was VirtualBox ist, ich habe GitHub kennengelernt, zudem habe ich mich bei der Umsetzung mit Vagrant auseinandergesetzt, welches ich vorher auch noch nicht kannte. Der Lehrer war für Fragen immer offen und konnte mir auch sehr gut helfen. 
### Zusammenarbeit
Die Zusammenarbeit im Team war ausgezeichnet. Wir haben uns alle zuerst eingelesen und alle Fragen im Team geklärt. Danach haben wir uns die Aufgaben aufgeteilt und haben uns alle an die Aufteilung der Aufgaben gehalten. Dies hat uns die Arbeit am Projekt sehr erleichtert. Wir konnten alle sehr gut miteinander umgehen. Da Muhammed Ercan, Luca Miani und ich bereits oft miteinander Projekte geführt haben und bei Schulaufträgen gemeinsam in einer Gruppe waren, fiel uns die Zusammenarbeit noch leichter. Somit sind wir sehr schnell zum Ziel gekommen und hatten keine Probleme bei der Umsetzung.

## Reflexion Luca Miani
Obwohl ich schon ein wenig Vorwissen hatte, konnte ich in diesem Modul sehr viel neues lernen. Ich habe Vagrant sehr gut kennengelernt und kann nun gut damit umgehen. Da ich schon oft mit Linux gearbeitet habe und es sehr gerne mache, hat mir diese LB sehr Spass gemacht. Bei Problemen habe ich mich beim Lehrer oder bei meinen Teamkollegen gewendet. Die Zusammenarbeit mit Muhammed Ercan, Helmina Jusufi und Patrick Schwab war sehr gut. Wir sind gut miteinander ausgekommen, haben uns gegenseitig unterstützt und unsere Arbeiten zeitgerecht fertiggestellt. Was ich auch sehr gut fand war, dass wir mit Github gearbeitet haben und so alle jederzeit ganz einfach Zugriff darauf hatten.

## Reflexion Patrick Schwab
Ich habe für die Zukunft gelernt, dass die Vagrant Files einen grossen Wert haben. Ausserdem weiss ich nun, dass ich im Team mehr Spass am Lernen habe als allein und es nicht darauf ankommt, ob ich mit meinen Freunden in einer Gruppe bin oder mit anderen Mitschülern, die ich weniger gut kenne. Dazu kommt, dass ich viele neue Funktionen kennenlernen durfte im Bezug auf Virtuelle Maschinen, Systemsicherheit und Vagrant Files. Das Arbeiten mit Github hat mir ausserdem auch Spass gemacht, weil man alles für jeden verfügbar hat.

# Wissensstand und Gewinn der Teammitglieder

## Luca Miani

Ich arbeite ab und zu im Geschäft mit Linux. Ausserdem habe ich Zuhause mehrere Linux Server. Daher behaupte ich, dass ich sicherlich Kenntnisse habe mit Linux. Einen eigenen Github Acount hatte ich schon vor diesem Modul. Jedoch hatte ich am Anfang dieses Moduls auch keine Erfahrungen mit Vagrant. Dies lernte ich jedoch im Laufe dieses Projektes kennen. Dazu lies ich verschiedene Beiträge und machte mich schlau auf Github. Ausserdem konnte ich bei Fragen immer wieder mein Team fragen, welches mir auch weiterhilf. Das Arbeiten auf der TBZ Cloud fand ich sehr angenehm.  Ich konnte ausserdem einiges lernen im Bereich Systemsicherheit. In das Thema SSH habe ich mich ein wenig vertieft und konnte somit auch dies so im Projekt einsetzen.

## Muhammed Ercan

Im Geschäft arbeite ich mehrheitlich mit Macs. Weil Mac OS und Linux sehr ähnlich sind, hatte ich schon einige Erfahrungen mit Linux. Ausserdem habe ich mehrere Server mit Linux aufgesetzt und diese betrieben. Des weiteren habe ich noch einige Services drauf lauffen lassen. Jedoch hatte ich noch vor dem Modul keinen Github Account. Daher schaute ich am Anfang einige Blogs zu Github. Daher kamen mit der Zeit Kentnisse auch über Mark Down und Github. Ich habe zusammen mit Helmina Jusufi im Modul Systemsicherheit gearbeitet. Daher hatten wir von diesem Modul auch Erfahrungen mit der Sicherheit eines Systems. Zu den verschiedenen Vagrant Files habe ich nicht viel gewusst, daher konnte ich auch einiges zu den Vagrant-Files dazulernen. Ausserdem hat mir das Arbeiten auf TBZ Cloud gefallen.

## Patrick Schwab


Mit den Themen Linux hatte ich schon zuvor zutuhn, doch mit Github oder ähnliche Systeme hatte ich zuvor noch nie gearbeitet. Ich habe privat schon mit Linux gearbeitet. Jedoch muss ich sagen, dass ich über eine längere Zeit hinweg nicht mehr damit gearbeitet habe. Daher habe ich einige coole Funnktionen schon vergessen. Mit Github hatte ich am anfang Problem edoch danach gieng es sehr einfach, da ich mir mehrere Tutorials und Dokus angeschaut und durchgelesen habe. Ich habe viel über Container gelernt und selbst gesehen welche Vorteile dies gegen den normalen VM hat. Ich finde Git macht in vielen Anwendungsbereichen viel Sinn und werde versuchen, dies in Zukunft mehr zu gebrauchen. Was mir auch gefallen hat, ist das Arbeiten mit diesem Team. Jeder hatte jeden respektiert und wir haben alle gut arbeiten können.


## Helmina Jusufi

Auch Ich habe einige Male in der Schule mit Linux gearbeitet. Zudem haben wir Testserver im Geschäft die ich selber aufsetzen durfte und auf denen ich einiges ausprobieren konnte, somit bin ich vertraut mit einigen Befehlen. Für die Systemsicherheit interssiere ich mich sehr, daher habe ich in diesem Modul viel dazulernen können. Ich kannte Github vorher noch nicht. Ich habe nur davon gehört und in diesem Modul habe ich mich zum ersten Mal richtig damit auseinandergesetzt. Auch von Vagrant habe ich zum ersten Mal gehört und konnte auch dazu neues lernen. Die Unterlagen, welche uns zur Verfügung stehen, haben mir geholfen mich schnell in dieses Modul einzulesen und gleich loszulegen. Das Arbeiten auf der TBZ Cloud empfand ich ebenfalls wie meine Teammitglieder als angenehm.

