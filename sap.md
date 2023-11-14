# SAP Grundlagen

## ERP-System

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


## Stamm-/Bewegungsdaten
