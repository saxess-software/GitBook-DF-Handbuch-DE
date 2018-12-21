### Fabriktabs

Auf Fabrikebene lassen sich im Web Client Fabriktabs anzeigen. Es können beliebig viele innerhalb einer Fabrik hinterlegt werden. Sie zeigen entweder eine Pivottabelle (inkl. Pivotdiagramm), eine externe Webseite oder eine individuell erstellte HTML-Seite, die mit dem [HTML-Editor](/der-web-client/werk/clusterseite-bearbeiten.md) bearbeitet werden kann. Wenn Sie erfahren wollen wie man Fabriktabs erstellt lesen Sie im [Knowledge-Center]( https://github.com/saxess-software/DataFactory-Knowledge-Center/blob/master/3d.%20DataFactory%20-%20Webclient%20Configuration/Configuration%20of%20FactoryTabs/How%20to%20create%20FactoryTabs.md ) weiter.

Wenn Sie einen Fabriktab erstellen haben Sie die Wahl zwischen folgenden Anzeigeformaten:

* **Pivot:** Lädt die Daten einer Prozedur in ein Datenmodell das als Pivottabelle und Pivotdiagramm dargestellt werden kann.
* **DataGrid:** Lädt die Daten einer Prozedur in ein Datenmodell das in Tabellenform präsentiert wird.
* **HTML_Editor:** Erstellt eine leere HTML-Seite und schaltet den [HTML-Editor](/der-web-client/werk/clusterseite-bearbeiten.md) frei.
* **HTML_URL:** Öffnet eine beliebige externe Webseite.
* **HTML_Static:** Erstellt eine HTML-Seite aus einer gespeicherten Prozedur.

Standardmäßig verfügt die Fabrik **Templates (ZT)** über Fabriktabs mit Fehlerreports. Zu diesen gehören:

* **Rechteübersicht:** Zeigt alle für das Cluster berechtigte Nutzer und ihre Privilegien.
* **Systemfehler:** Zeigt das Ergebnis der Prozedur `control.spSystemFailureReport` die auf Datenkonsistenz prüft.
* **Anwenderfehler:** Ein für jeden Anwenderfall individuell entwickelter Test der auf potentielle Fehlerquellen prüft (z.B. Überprüfung des Stagings, Imports, Kalkulationen o.ä.).
* **Clusterstatistik:** Gibt eine kurze Zusammenfassung zu der Anzahl der Fabriken, Produktlinien und Produkten.

---
![](/Pictures/Web-Client/Fabrik/Pivot-Ansicht/fabriktabs_1.png)

---
