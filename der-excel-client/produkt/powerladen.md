### PowerLaden  

Die Funktion **PowerLaden** kommt insbesondere dann zur Anwendung, nachdem Sie Daten aus anderen Anwendungen in DataFactory importiert haben und diese als Grundlage für weitere Berechnungen dienen. Die Funktion **PowerLaden** betritt automatisch jedes Produkt, berechnet es und speichert es ab. Es stehen Ihnen folgende Möglichkeiten des PowerLadens zur Verfügung.  

| Einstellung | Beschreibung |
| : | : |
| Alle PowerLaden | Für alle Produkte wird das PowerLaden durchgeführt |
| Auswahl PowerLaden | Für ausgewählte Produkte wird das PowerLaden durchgeführt |
| Unvollendete PowerLaden | Für Produkte, bei denen PowerLaden-Vorgang nicht vollständig ausgeführt wurde, wird das PowerLaden durchgeführt |
| Fehler Powerladen | Für fehlerhaft geladene Produkte wird das PowerLaden durchgeführt |

#### Ebenen

Sie können die Funktion **PowerLaden** auf unterschiedlichen Ebenen Ihres Clusters durchführen. Entsprechend der Ebene, die Sie für den PowerLaden-Vorgang ausgewählt haben, reduziert sich die Anzahl an Produkten, die Ihnen zum PowerLaden zur Auswahl angeboten werden.

|Ebene|ActionLink|Menü|
|-|-|-|
|Werk|![](/Pictures/Excel-Client/Produkt/PowerLaden/powerladen_1.png)|![](/Pictures/Excel-Client/Produkt/PowerLaden/powerladen_2.png)|
|Fabrik|![](/Pictures/Excel-Client/Produkt/PowerLaden/powerladen_3.png)|![](/Pictures/Excel-Client/Produkt/PowerLaden/powerladen_4.png)|
|Produktlinie|![](/Pictures/Excel-Client/Produkt/PowerLaden/powerladen_5.png)|![](/Pictures/Excel-Client/Produkt/PowerLaden/powerladen_6.png)|
|Produkt|![](/Pictures/Excel-Client/Produkt/PowerLaden/powerladen_7.png)| ![](/Pictures/Excel-Client/Produkt/PowerLaden/powerladen_8.png)| 

#### Durchführen des PowerLaden-Vorgangs

1) Mit Klick auf den ActionLink wird die Sicht **PowerLaden** aufgerufen. Je nachdem von welcher Ebene der PowerLoader aufgerufen wird, werden auch nur die Produkte jener Ebene angezeigt. Wählen Sie hier die Produkte aus, die Sie aktualisieren wollen.

---
![](/Pictures/Excel-Client/Produkt/PowerLaden/powerladen_9.png) 

---

> **Hinweis:** Standardmäßig werden die Templates im PowerLoader nicht angezeigt. Sollten Sie dennoch einmal die Templates erneut kalkulieren wollen rufen Sie den PowerLoader von der Sicht **Fabriken und Produktlinien** aus auf und klicken Sie auf **Templates anzeigen**.

2) Die Auswahl kann noch weiter verfeinert werden.
- Klicken Sie auf eine Spaltenüberschrift um nach Werten zu filtern und bestätige mit **OK**.
 
- Wählen Sie mit den zwei Kontrollkästchen ob nur Produkte geladen werden sollen die entweder noch nicht neu geladen oder auf ein Fehler hinausgelaufen sind.

---
![](/Pictures/Excel-Client/Produkt/PowerLaden/powerladen_10.png) 

---

3) Um alle angezeigten Produkte zu powerladen wählen Sie **Powerladen starten**.

---
![](/Pictures/Excel-Client/Produkt/PowerLaden/powerladen_11.png) 

---

5) Nach dem Ausführen sehen Sie den Status der geladenen Produkte.
- Grün: Es gab nichts neues zu speichern.
- Orange: Änderungen wurden gespeichert.
- Rot: Es ist ein Fehler aufgetreten.

> **Hinweis:** Mit einem Rechtsklick auf ein Produkt lässt sich dieses einzelne neu laden oder öffnen.

---
![](/Pictures/Excel-Client/Produkt/PowerLaden/powerladen_12.png) 

---
