### Manuelle Eingabe

Sie können Daten mittels der Eingabe über Ihre Tastatur erfassen, indem Sie die Werte direkt in die gewünschten Zellen eingeben.  

---
![](/Pictures/Excel-Client/Datenerfassung/Manuelle Eingabe/manuelle_eingabe_1.png)

---
  
Sie können für die Eingabe Ihrer Daten auch Excel-Formeln verwenden.  

---
![](/Pictures/Excel-Client/Datenerfassung/Manuelle Eingabe/manuelle_eingabe_2.png)

---
  
> **Hinweis:** Nur, wenn die Wertreihe bei der Einstellung [Herkunft](/der-excel-client/templates/template-konfigurieren/herkunft-andern.md) vom Typ XLS oder XLS-Strict definiert ist, bleibt die Formel im Wertebereich bestehen. Andernfalls wird die Formel beim Speichern durch den Wert ersetzt.   

Wenn Sie mit der rechten Maustaste in eine Zelle klicken, haben Sie die Möglichkeit Inhalte auszuschneiden, zu kopieren, einzufügen oder zu löschen. Werte, die Sie in der Zwischenablage gespeichert haben, können Sie über die Auswahl **Einfügen** in die markierte Zelle einfügen.

---
![](/Pictures/Excel-Client/Datenerfassung/Manuelle Eingabe/manuelle_eingabe_3.png)

---

> **Hinweis:** Mit der Tastenkombination **Alt + Enter** können Sie innerhalb einer Zelle einen **Zeilenumbruch** einfügen.

> **Hinweis:** Achten Sie bei der Dateneingabe darauf, dass keine Kommata am Anfang oder am Ende des Zelleninhalts stehen! Andernfalls wird eine Fehlermeldung (Fehlercode 404 oder 500) ausgelöst und die Eingaben werden nicht gespeichert oder das Komma, gemeinsam mit dem anhängenden Zeichen, wird beim Speichervorgang gelöscht.

>**Hinweis:** Der Web-Client unterstützt im Speichervorgang keine boole'schen Werte (`WAHR` und `FALSCH`). Wenn Sie die Tabelle, samt Formel, also auch überm Web-Client nutzen möchten, müssen Sie beim Erstellen der Formel auf Folgendes achten: Bei Ausgabe eines boole'schen Wertes müssen Sie das Ergebnis im Nachhinein mit Hilfe bspw. einer `wenn()` Funktion umformen.
