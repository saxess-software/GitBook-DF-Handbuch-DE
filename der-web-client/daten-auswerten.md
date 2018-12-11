## Daten auswerten

Bei Bedarf können Sie über einen Webservice auf Ihre Daten zugreifen. Auf diese Weise sind individuelle Berichte in Excel oder PowerBI möglich. Die Adresse zum Webservice baut sich forgendermaßen zusammen: **[ihreDomain.de]/api/v4/csv/[Datenbankname]/[Prozedurname]/[FabrikID]/[ProduktlinienID]?seperator=|** Die Angabe der Fabrik ID und Produktlinien ID ist optional. Wenn Sie nur die Datenbank und Prozedur angeben, dann wird die Ausgabe der Prozedur nicht gefiltert. dann werden die Werte für die gesamte Datenbank abgefragt.

Für eine detailliertere Beschreibung des Webservices und wie dieser genutzt wird lesen Sie im [Knowledge-Center]( https://github.com/saxess-software/DataFactory-Knowledge-Center/blob/master/4b.%20Integration%20with%20Excel%20Reporting/Create_XLS_Pivottable_from_Webservice_Data.md ) weiter.

Standardmäßig werden mit der DataFactory folgende Prozeduren ausgeliefert:

| Name der Prozedur | Beschreibung | [Betriebswirtschaftliches Merkmal](/der-excel-client/templates/template-konfigurieren/effekt-andern.html) |
| :------- | :------: | -------: |
| DATAOUTPUT_Balance | Ruft alle Aktiv- und Passivbestandsdaten ab | Aktivbestand, Passivbestand |
| DATAOUTPUT_CashValues | Ruft alle Daten zu Geldein- und ausgängen ab | Einzahlung, Auszahlung, Ertrag=Einzahlg, Kosten=Auszahlg |
| DATAOUTPUT_dFactories | Erhebt alle Daten die auf Fabrikebene zu entnehmen sind ||
| DATAOUTPUT_dProductLines | Erhebt alle Daten die auf Produktlinienebene zu entnehmen sind ||
| DATAOUTPUT_dProducts | Erhebt alle Daten die auf Produktebene, aber nicht der Datentabelle, zu entnehmen sind ||
| DATAOUTPUT_dValueSeries | Erhebt alle Daten die den ValueSeries zu entnehmen sind ||
| DATAOUTPUT_FactorySummary | Diese Prozedur erfordert die Angabe einer **Factory ID** und gibt die Daten in jener Fabrik aggregiert nach Produkt und Monat wieder | Aktiv-, Passivbestand, Ein-, Auszahlung, Ertrag, Kosten, Ertrag=Einzahlg, Kosten=Auszahlg, Menge, Stück |
| DATAOUTPUT_fValues | Ruft alle Daten der Datentabellen ab |
| DATAOUTPUT_NumericValues | Ruft alle als numerisch angegebenen Werte ab ||
| DATAOUTPUT_Profit | Ruft alle gewinn- und verlustrelevanten Daten ab | Ertrag, Kosten, Ertrag=Einzahlg, Kosten=Auszahlg |
| DATAOUTPUT_TextValues | Ruft alle nicht-numerischen Daten ab ||

### Zugriff überm Webbrowser

Beim Abruf des Webservices müssen Sie sich mit ihren Daten anmelden. Bestätigen Sie ihre Angaben und der Download wird gestartet. Beachten Sie, dass es sich hierbei um eine csv-Datei handelt. Die hiermit erstellten Auswertungen sind also statisch und können nicht nach Belieben aktualisiert werden ohne händisch die Daten erneut herunterzuladen.

---
![](/Pictures/Web-Client/Daten auswerten/daten_auswerten_1.png)
![](/Pictures/Web-Client/Daten auswerten/daten_auswerten_2.png)

---

<!---
### Zugriff über Excel & PowerBI

Der Webservice lässt sich auch über Excel abrufen. Der Vorteil gegenüber dem Webbrowser ist, dass die Daten direkt in das Datenmodell der Excel-Mappe importiert werden können und das die Aktualisierung der Daten auf Abruf automatisch durchgeführt wird.

Erstellen Sie eine neue Excel-Mappe und wählen Sie im Reiter **Daten**
-->
