## Daten auswerten

Bei Bedarf können Sie über einen Webservice auf Ihre Daten zugreifen. Auf diese Weise sind individuelle Berichte in Excel oder PowerBI möglich. Die Adresse zum Webservice baut sich forgendermaßen zusammen: 

**[ihreDomain.de]/api/v4/csv/[Datenbankname]/[Prozedurname]/[FabrikID]/[ProduktlinienID]?seperator=|**

Die Angabe der Fabrik ID und Produktlinien ID ist optional. Wenn Sie nur die Datenbank und Prozedur angeben, dann wird die Ausgabe der Prozedur nicht entsprechend ihren Angaben gefiltert. Es werden die Werte für die gesamte Datenbank abgefragt.

Für eine detailliertere Beschreibung des Webservices und wie dieser genutzt wird lesen Sie im [Knowledge-Center]( https://github.com/saxess-software/DataFactory-Knowledge-Center/blob/master/4b.%20Integration%20with%20Excel%20Reporting/Create_XLS_Pivottable_from_Webservice_Data.md ) weiter.

Standardmäßig werden mit der DataFactory Prozeduren und Sichten - letztere mit dem Präfix Result oder Datamodel und erstere mit dem Präfix Dataoutput - ausgeliefert:

| Name der Prozedur / Sicht | Beschreibung | [Betriebswirtschaftliches Merkmal](/der-excel-client/templates/template-konfigurieren/effekt-andern.html) |
| :------- | :------: | -------: |
| Balance | Ruft alle Aktiv- und Passivbestandsdaten ab | Aktivbestand, Passivbestand |
| CashValues | Ruft alle Daten zu Geldein- und ausgängen ab | Einzahlung, Auszahlung, Ertrag=Einzahlg, Kosten=Auszahlg |
| dFactories | Erhebt alle Daten die auf Fabrikebene zu entnehmen sind | *alle* |
| dProductLines | Erhebt alle Daten die auf Produktlinienebene zu entnehmen sind | *alle* |
| dProducts | Erhebt alle Daten die auf Produktebene, aber nicht der Datentabelle, zu entnehmen sind | *alle* |
| dValueSeries | Erhebt alle Daten die den ValueSeries zu entnehmen sind | *alle* |
| FactorySummary | Diese Prozedur erfordert die Angabe einer **Factory ID** und gibt die Daten in jener Fabrik aggregiert nach Produkt und Monat wieder | Aktiv-, Passivbestand, Ein-, Auszahlung, Ertrag, Kosten, Ertrag=Einzahlg, Kosten=Auszahlg, Menge, Stück |
| fValues | Ruft die Werte aller Datentabellen ab | *alle* |
| NumericValues | Ruft alle numerischen Tabellenwerte ab | *alle* |
| Profit | Ruft alle gewinn- und verlustwirksamen Daten ab | Ertrag, Kosten, Ertrag=Einzahlg, Kosten=Auszahlg |
| TextValues | Ruft alle nicht-numerischen Tabellenwerte ab | *alle* |

### Zugriff überm Webbrowser

Beim Abruf des Webservices müssen Sie sich mit ihren Daten anmelden. Bestätigen Sie ihre Angaben und der Download wird gestartet. Beachten Sie, dass es sich hierbei um eine csv-Datei handelt. Die hiermit erstellten Auswertungen sind also statisch und können nicht nach Belieben aktualisiert werden ohne händisch die Daten erneut herunterzuladen.

---
![](/Pictures/Web-Client/Daten auswerten/daten_auswerten_1.png)
![](/Pictures/Web-Client/Daten auswerten/daten_auswerten_2.png)

---

>**Hinweis:** Über den Webservice lassen sich nur als Prozeduren und nicht Sichten gespeicherte Datenabfragen aufrufen. Die Sichten können via Excel abgerufen werden.

### Zugriff über Excel & PowerBI

Der Webservice lässt sich auch über Excel abrufen. Der Vorteil gegenüber dem Webbrowser ist, dass die Daten direkt in das Datenmodell der Excel-Mappe importiert werden können und das die Aktualisierung der Daten auf Abruf automatisch durchgeführt wird.
Zum Abrufen einer Prozedur folgen Sie dieser [Anleitung]( https://github.com/saxess-software/DataFactory-Knowledge-Center/blob/master/4b.%20Integration%20with%20Excel%20Reporting/Create_XLS_Pivottable_from_Webservice_Data.md ).
Zum Abrufen einer Sicht gehen Sie wie folgt vor:

Erstellen und öffnen Sie eine neue Excel-Mappe. Auf dem Reiter **Daten** klicken Sie unter **Daten abrufen**, **Aus Datenbank** auf **Aus SQL Server-Datenbank**.

---
![](/Pictures/Web-Client/Daten auswerten/daten_auswerten_3.png)

---

In dem sich öffnenden Dialog geben Sie die Adressen der Datenbanken und ihre Anmeldedaten an.

---
![](/Pictures/Web-Client/Daten auswerten/daten_auswerten_4.png)

---

Abschließend wählen Sie eine Sicht oder Tabelle die Excel in die Tabelle bzw. das Datenmodell laden soll.

---
![](/Pictures/Web-Client/Daten auswerten/daten_auswerten_5.png)

---

>**Hinweis:** Wenn Sie die Datenbank auf der Azure-Cloud betreiben sollten, ist es erforderlich, dass Sie im B2B-Verzeichnis von Azure registriert sind.
