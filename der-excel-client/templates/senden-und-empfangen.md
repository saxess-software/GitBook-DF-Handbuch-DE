### Templates senden und empfangen

Templates dienen als Vorlage für Produkte. Sie verhalten sich zueinander wie eine Vorlage und eine Kopie. Nach der Erstellung ist die Kopie unabhängig, d.h. sie kann verändert werden und ändert sich nicht automatisch, wenn sich das Template ändert. 

Mit der Funktion **Templates senden** und **Templates empfangen** haben Sie die Möglichkeit, Änderungen an Ihren Templates/Vorlagen vorzunehmen und diese Änderungen an die entsprechenden Produkte zu vererben.

**Vererbt werden**:

* Formatänderungen
* Änderungen der Berechnungslogik
* Änderungen der Sichtbarkeitsstufe, des Datentyps, der Herkunft, der Skalierung und des Effekts
* Änderungen in der Spaltenbreite
* Änderungen an Spaltenname und -ID
* Änderungen der Zeitachse
* gelöschte und hinzugefügte Spalten

---
**Hinweis:** Im Produkt manuell eingegebene Daten werden nicht gelöscht oder überschrieben.

**Ausnahmen:**
* Ist eine Wertereihe nicht im Template enthalten, dann wird diese mit ihren Werten gelöscht.
* Die Zeitachse wurde verkürzt bzw. verschoben - Werte, die gelöschten Zeitwerten zugeordnet sind, werden ebenfalls gelöscht.
* Wird der Werttyp von numerisch auf nicht-numerisch (und umgekehrt) geändert, gehen die Werte dieser Spalte verloren.
* Bei Änderung der Skalierung auf eine geringere Zahl gehen Nachkommastellen verloren.

**Empfehlung: Erstellen Sie eine Sicherungskopie der empfangenden Produkte bevor Sie ein Template ausrollen!**

---

#### Template empfangen

Sie können für ein Produkt definieren, von welchem Template es alle Eigenschaften und Logiken übernehmen soll.

1) Klicken Sie auf den ActionLink Ihres ausgewählten Produkts und wählen Sie **Template empfangen**.

---
![](/Pictures/Excel-Client/Templates/Senden und Empfangen/senden_und_empfangen_1.png)

---

2) In dem sich öffnenden Fenster wird Ihnen das Zielprodukt angezeigt, welches das Template empfangen soll.

---
![](/Pictures/Excel-Client/Templates/Senden und Empfangen/senden_und_empfangen_2.png)

---

3) Wählen Sie über die Dropdown-Felder das Template aus, welches auf das ausgewählte Produkt ausgerollt werden soll.

---
![](/Pictures/Excel-Client/Templates/Senden und Empfangen/senden_und_empfangen_3.png)

---

4) Standardmäßig werden bei dieser Funktion die Spalten im Template anhand ihrer Spalten-Id mit denjenigen im Produkt bezüglich aufgetretener Änderungen verglichen. Wenn Sie die Identifizierung allerdings anhand des Spaltennamens durchführen wollen, setzen Sie bei **Anhand des Namens statt der ID vergleichen** ein Häkchen.

---
![](/Pictures/Excel-Client/Templates/Senden und Empfangen/senden_und_empfangen_4.png)

---

5) Klicken Sie auf **Anwenden**. Das Produkt hat nun die Eigenschaften des Templates übernommen.

---
![](/Pictures/Excel-Client/Templates/Senden und Empfangen/senden_und_empfangen_5.png)

---

#### Template senden

Sie können ein Template auswählen und dessen Eigenschaften und Logiken an ein oder mehrere Produkte übergeben.

1) Klicken Sie auf den ActionLink Ihres ausgewählten Templates und wählen Sie **Template senden**.

---
![](/Pictures/Excel-Client/Templates/Senden und Empfangen/senden_und_empfangen_6.png)

---

2) In dem sich öffnenden Fenster wird Ihnen das Template angezeigt, welches als Quelle verwendet werden soll.

---
![](/Pictures/Excel-Client/Templates/Senden und Empfangen/senden_und_empfangen_7.png)

---

3) Wählen Sie über die Reiter aus, ob Sie das Template an ein einzelnes Produkt (**Single**) oder an mehrere Produkte (**Multi**) vererben wollen.

---
![](/Pictures/Excel-Client/Templates/Senden und Empfangen/senden_und_empfangen_8.png)

---

3.1) Wenn Sie das Template nur an ein einzelnes Produkt senden wollen, wählen Sie über das Dropdown-Menü im Reiter **Single** das entsprechende Produkt aus.

---
![](/Pictures/Excel-Client/Templates/Senden und Empfangen/senden_und_empfangen_9.png)

---

3.2) Wenn Sie das Template an mehrere Produkte senden wollen, müssen Sie über das Dropdown-Menü im Reiter **Multi** auswählen, an welche Fabrik, an welche Produktlinie und an welche Template-Arten Sie das Template vererben wollen.

> **Hinweis:** Wenn Sie ein Feld frei lassen, bedeutet das, dass Sie alle auswählen. D.h. wenn Sie bspw. als Fabrik "BK-Vertragsverwaltung" wählen, die Produktlinie und das Template aber frei lassen, vererben Sie das Template an alle Produkte in allen Produktlinien der Fabrik "BK-Vertragsverwaltung".

---
![](/Pictures/Excel-Client/Templates/Senden und Empfangen/senden_und_empfangen_10.png)

---

4) Standardmäßig werden bei dieser Funktion die Spalten im Template anhand ihrer Spalten-Id mit denjenigen im Produkt bezüglich aufgetretener Änderungen verglichen. Wenn Sie die Identifizierung allerdings anhand des Spaltennamens durchführen wollen, setzen Sie bei **Anhand des Namens statt der ID vergleichen** ein Häkchen.

---
![](/Pictures/Excel-Client/Templates/Senden und Empfangen/senden_und_empfangen_11.png)

---

5) Klicken Sie auf **Anwenden**. Das Produkt hat nun die Eigenschaften des Templates übernommen.

---
![](/Pictures/Excel-Client/Templates/Senden und Empfangen/senden_und_empfangen_12.png)

---
