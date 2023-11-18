# SAP Grundlagen

## ERP-System

[https://www.youtube.com/watch?v=ZuDOIUQYePI](https://www.youtube.com/watch?v=ZuDOIUQYePI)

ERP steht für Enterprise Resource Planning --> alle Resourcen eines Unternehmens ganzheitlich zu verwalten
bzw. zu planen.

Resourcen sind
- Finanzen (Ausgaben und Einnahmen, ...)
- Personen (Kunden, Lieferanten, Mitarbeiter, ...)
- Materialien (Produkte, Rohstoffe, ...)
- Maschinen die für die Wertschöpfung notwendig sind

![sap01.JPG](pictures/sap01.JPG)

Meist ist es so, dass wenn sich nur eine dieser Resourcen verändert, dann hat das auch Auswirkungen auf viele andere Resourcen

![sap02.JPG](pictures/sap02.JPG)

Auch wenn dies ziemlich komplex klingt, so sind ERP-Systeme ziemlich einfach aufgebaut.
- große Datenbank die alle Resourcendaten (Mitarbeiter, Kunden, Lieferanten, Material, Bestellungen, Rechnungen, Kostenstellen,
  Stücklisten, ...)  speichert
- Transaktionen (kleine Unterprogramme innerhalb eines ERP-Systems

![sap03.JPG](pictures/sap03.JPG)

## Transaktionen

sind kleine Unterprogramme innerhalb eines ERP-Systems (es gibt viele davon). Jede Einzelne spiegelt
genau einen Prozessschritt in einem Unternehmen wieder und greift auf die jeweiligen Daten zu.<br>
Z.B. gibt es in SAP die Transaktion MM01 die nur für das Anlegen von neuem Material da ist

![sap04.JPG](pictures/sap04.JPG)

Möchte man dieses Material dann auch bestellen müsste man dann auch eine Bestellung anlegen (ME21N Transaktion)

![sap05.JPG](pictures/sap05.JPG)

So gibt es jede Menge weiterer Transaktionen

![sap06.JPG](pictures/sap06.JPG)

Viele stören sich in SAP an diesen komischen scheinbar willkürlichen Transaktionsnamen/kürzel (z.B. MM01, ME21N, ...).
Diese sind auch ziemlich ungeeignet um die Menge der Transaktionen zu überblicken. In SAP bibt es dafür eine Baumstruktur
die alle Transaktionen systematisch gliedert. Versteht man diesen Baum, so versteht man SAP

![sap07.JPG](pictures/sap07.JPG)

z.B. Pflege von Materialdaten

![sap08.JPG](pictures/sap08.JPG)
![sap09.JPG](pictures/sap09.JPG)

z.B. Anzeigen des Materials

![sap10.JPG](pictures/sap10.JPG)
![sap11.JPG](pictures/sap11.JPG)

z.B. einen Kugelschreiber mit der Materialnummer 1172 anzeigen

![sap12.JPG](pictures/sap12.JPG)

Man muss natürlich diese Materialnummer nicht auswendig wissen. SAP hat immer ein ausgeklügeltes Suchsystem eingebaut

![sap13.JPG](pictures/sap13.JPG)

Nach der Auswahl des Materials bekommt die unterschiedlichen Sichten der Stammdaten

![sap14.JPG](pictures/sap14.JPG)

Ein Eintrag in den Stammdaten heißt noch nicht dass dieses Material im Unternehmen vorhanden ist. Dies ist die Aufgabe
der Bewegungsdaten 

## Stamm-/Bewegungsdaten

Stammdaten:

![sap15.JPG](pictures/sap15.JPG)

Bewegungsdaten:<br>
Die auf den Stammdaten basierenden Daten wie Bestellungen, Fertigungsaufträge, Lagerbestände, Auslieferung, ...
nennt man Bewegungsdaten. Diese Daten beleben also das Unternehmen

![sap16.JPG](pictures/sap16.JPG)
