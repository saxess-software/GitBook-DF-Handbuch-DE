### Pivot Auswertung  

Pivot Auswertungen lassen sich in DataFactory Werksebene, Fabrikebene und auf der Ebene der Produktlinien erstellen und beinhalten alle Informationen der gewählten sowie der darunterliegenden Ebenen.  

Bei einer http-Verbindung wird bei der Erstellung einer Pivot Auswertung eine .csv-Datei mit allen numerischen Werten generiert, die in den Produkten der gewählten Hierarchieebene erfasst sind. Die .csv-Datei wird im Ordner csv im Quellverzeichnis Ihrer DataFactory abgespeichert. Falls Sie eine DataFactory-Datenbank auf Ihrem eigenen SQL-Server nutzen, wird eine Verbindung in Excel hinterlegt, die sich direkt über den Server aktualisiert.

#### Pivot Auswertung auf Werksebene  

Um eine Pivot-Auswertung auf Werksebene zu erstellen, gehen Sie wie folgt vor:  

1) Klicken Sie in der Übersicht Fabriken und Produktlinien auf den ActionLink. wählen Sie die Option **Pivot Ansicht**.  

---
![](/assets/lf1.png) 

---

2) Wählen Sie die Option **Pivot Ansicht**.  

---
![](/assets/piv1.png)

---

3) Falls Sie eine DataFactory-Datenbank auf Ihrem eigenen SQL-Server nutzen, öffnet sich automatisch die Pivot-Ansicht. Nutzen Sie allerdings eine http-Verbindung, öffnet sich ein Dialogfeld, wo sie aus folgenden Optionen auswählen können.

---
![](/assets/piv2.png)

---

|Auswahl|Beschreibung|
|-|-|
|CSV für numerische Werte herunterladen und Pivot-Tabelle herunterladen|Eine .csv-Datei wird heruntergeladen und im DataFactory-Ordner **"csv"** abgelegt. In Ihrer Excel-Mappe wird ein neues Tabellenblatt angelegt, welches die Pivot-Tabelle enthält.|
|CSV für numerische Werte herunterladen|Eine .csv-Datei wird heruntergeladen und im DataFactory-Ordner **"csv"** abgelegt.|
|Pivot-Tabelle aus lokaler CSV erstellen|Der DataFactory-Ordner **"csv"** öffnet sich und Sie können eine .csv-Datei auswählen, die Sie in Ihrer Excelmappe anzeigen lassen wollen.|

---
![](/assets/piv4.png)

---

4) In der Pivot-Tabelle werden Ihnen alle Werte über alle Fabriken und Produktlinien hinweg angezeigt.

---
![](/assets/piv3.png)

---

> **Hinweis**: Sie können sich Ihre Pivot Tabelle frei nach Ihren Wünschen gestalten und anpassen.  
