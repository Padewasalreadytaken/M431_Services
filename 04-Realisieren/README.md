# Realisierung 
* [Einführung](#einführung) 
* [Basis Struktur](#basis-struktur)
* [Website](#webseite)
* []

## Einführung 

Im Ersten Schritt «I» Informieren musste man sich inspirieren lassen oder herausfinden was für ein Projekt man machen wolle.<br>
Bei mir war das sehr leicht da mein Chef sich eine Sharepoint Cloud wünschte und ich früher oder später hin oder her <br>eine mal errichten müsste. <br>

Sharepoint ist eine Applikation, welche auf dem von Microsoft entwickeltem Office aufgebaut ist.<br>
Nutzen kann man es nur solange man einen Microsoft Account mit einer gültigen Office 365 Lizenz hat. <br>
Man nutzt es, um eine Webseite zu errichten wo sich Gruppen zum einen Unterhalten und Arbeiten Können.<br>

Wir werden das volle Potenzial von Sharepoint in diesem Projekt nicht ausschöpfen. <br>

Wir werden in Sharepoint eine Ortner Struktur errichten, dort bestimmte Berechtigungen vergeben und dies dann auf <br>Onedrive freigeben.<br>

So durch kann man in einem Geschäft daten in einer Cloud teilen aber auch seinen eigenen Privaten Cloudspeicher nutzen.<br>

Als Abschluss wird die Sharepoint Webseite und alle Daten noch auf das NAS der Firma Comworld gesichert im falle von <br>menschlichem Versagen.

## Basis Struktur

Nach einem Gespräch mit meinem Chef über die Struktur und die Berechtigungen entschieden wir uns auf etwas Simples.
<br>
<br>

![Konzept](Konzeptt.jpg)<br>

Verlangt war lediglich ein Root Ortner «Comworld» darunter 2 Ortner für angestellte «Patrick», «Kevin», einen für «Anleitungen», und einen «Projekte», wo wir einzelne Informationen für Kunden zwischenspeichern.<br>

«Projekte» und «Anleitungen» sollten alle Zugriffe darauf haben.<br>
Die Mitarbeiter Ordner sollten nur die Mitarbeiter zugriff haben 


## Webseite 

Zum Erstellen einer Sharepoint Webseite sollte man manche Einzelheiten vorbereitet haben.
•	Einen Microsoft Account
•	Office 365 Administration und Sharepoint Admin Rechte
•	Knowhow

Der erste schritt ist im Office 365 Admin Center eine Gruppe zu erstellen mit den verlangten Teilnehmern der Daten-Struktur.
Danach folgt die Erstellung der Webseite selbst.
Welche man im Sharepoint selbst macht.

Der erste schritt ist somit auch der wichtigste.
Ich habe mich dort für Teamwebseite entschieden.
![Website](Website.png)

### Dies sind meine einstellungen.
![Website](Websitezusammenfassung.png) 

## Datenstrucktur

Dass erstellen der Daten Struktur ist von hier aus keine grosse Sache mehr da von hier aus die Ortner Per GUI erstellbar sind.<br>
Auf dem Root Ortner Comworld entferne ich alle Berechtigungen und füge die Gruppe hinzu die ich Office 365 Admin Center erstellt habe.<br>

![Gruppen](Gruppen.png)<br>

Darunter folgt der Rest der Ortner.<br>
Bei den beiden Ortner der Mitarbeiter entferne ich die Gruppe und füge die übereinstimmenden Nutzer per Mail hinzu.<br>

## Onedrive
Nun kann man noch die Daten Struktur mit Onedrive verbinden.
