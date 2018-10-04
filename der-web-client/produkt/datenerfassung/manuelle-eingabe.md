### Manuelle Eingabe

Sie können Daten direkt über Ihre Tastatur erfassen, indem Sie die Werte in die gewünschten Zellen eingeben.  

---
![](/Pictures/Web-Client/Produkt/Datenerfassung/Manuelle Eingabe/manuelle_eingabe_1.png)

---
>**Hinweis:** Zellen, deren Inhalt verändert wurde, werden orange markiert.

Sie können für die Berechnung Ihrer Daten auch Excel-Formeln verwenden.  

---
![](/Pictures/Web-Client/Produkt/Datenerfassung/Manuelle Eingabe/manuelle_eingabe_2.png)

---
  
> **Hinweis:** Nur, wenn die Wertereihe bei der Einstellung [Herkunft](/der-excel-client/templates/template-konfigurieren/herkunft-andern.md) vom Typ XLS oder XLS-Strict definiert ist, bleibt die Formel im Wertebereich bestehen. Andernfalls wird die Formel beim Speichern durch den Wert ersetzt.   

Wenn Sie zuvor im Excel-Client einer Spalte eine [Werteliste](/der-excel-client/templates/template-konfigurieren/werteliste-hinzufugen.md) zugeordnet haben, dann können Sie in diesen Spalten vorgegebene Werte aus einem Dropdown-Menü auswählen.

---
![](/Pictures/Web-Client/Produkt/Datenerfassung/Manuelle Eingabe/manuelle_eingabe_3.png)

---

Das Dropdown-Menü öffnet sich mit einem Klick auf das Stift-Symbol rechts neben der markierten Zelle. Sie können an dieser Stelle einen der Werte auswählen.

---
![](/Pictures/Web-Client/Produkt/Datenerfassung/Manuelle Eingabe/manuelle_eingabe_4.png)

---
>**Hinweis:** Sollten Sie bei der Einstellung [Herkunft](/der-excel-client/templates/template-konfigurieren/herkunft-andern.md) nicht `List-Strict` angegeben haben, dann lassen sich neben den vorgegebenen auch individuelle Werte eintragen.

Wenn Sie mit der rechten Maustaste in eine Zelle klicken, haben Sie die Möglichkeit Inhalte zu kopieren, einzufügen und Zellenkommentare zu bearbeiten. Werte, die Sie in der Zwischenablage gespeichert haben, können Sie über die Auswahl **Einfügen** in die markierte Zelle einfügen.

---
![](/Pictures/Web-Client/Produkt/Datenerfassung/Manuelle Eingabe/manuelle_eingabe_6.png)

---

> **Hinweis:** Mit der Tastenkombination **Alt + Enter** können Sie innerhalb einer Zelle einen **Zeilenumbruch** einfügen.

> **Hinweis:** Achten Sie bei der Dateneingabe darauf, dass keine Kommata am Anfang oder am Ende des Zelleninhalts stehen! Andernfalls werden die Eingaben nicht gespeichert oder das Komma, gemeinsam mit dem anhängenden Zeichen, wird beim Speichervorgang gelöscht.

>**Hinweis:** Der Web-Client unterstützt im Speichervorgang keine boole'schen Werte (`WAHR` und `FALSCH`). Achten Sie also darauf, wenn Sie eine Formel erstellen. Bei Ausgabe eines boole'schen Wertes müssen Sie das Ergebnis im Nachhinein mit Hilfe bspw. einer `wenn()` Funktion umformen. Sonst schlägt der Speichervorgang fehl.