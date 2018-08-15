### Allgemeiner Aufbau

Ein Template besteht strukturell immer aus drei wesentlichen Bestandteilen: Zeitachse, Wertreihe und Wertebereich.

---
![](/Pictures/Excel-Client/Templates/Allgemeiner Aufbau/allgemeiner_aufbau_1.png)

---

#### Zeitachse

Die Zeitachse eines Template bestimmt den Detailgrad der zeitlichen Dimension bei der Erfassung der Werte \(z.B. Erfassung von Daten auf Tages-, Monats oder Jahresbasis\).

---
![](/Pictures/Excel-Client/Templates/Allgemeiner Aufbau/allgemeiner_aufbau_2.png)

---

> **Hinweis:** Die Zeitachse ist nicht an einen Kalender gebunden, sondern sie ist vollkommen individuell konfigurierbar.

Bei der Erfassung von zeitunabhängigen Daten ist die Zeitachse eine sog. Pseudozeitachse und ermöglicht die Erfassung von Listen.

---
![](/Pictures/Excel-Client/Templates/Allgemeiner Aufbau/allgemeiner_aufbau_3.png)

---

#### Wertreihe

Wertreihen definieren die Charaktereigenschaften der Werte, die Sie später in den Wertebereich eingeben. In der Standardansicht eines Template sehen Sie den Namen und die ID einer Wertreihe.

---
![](/Pictures/Excel-Client/Templates/Allgemeiner Aufbau/allgemeiner_aufbau_4.png)

---

Jede Wertreihe besitzt eine Reihe von Eigenschaften und Optionen.

* **Nummer** \| Laufende Nummer der Wertreihe \(kann durch den Nutzer nicht verändert werden\) 
* **Aktion** \| ActionLink, hinter dem sich weitere Optionen verbergen

| Einstellung | Beschreibung |
| --- | --- |
| Neu davor | Fügt eine neue Wertreihe vor der aktuellen Wertreihe ein |
| Neu danach | Fügt eine neue Wertreihe nach der aktuellen Wertreihe ein |
| Merhfachkopie | Erstellt mehrere Kopien der aktuellen Wertreihe und fügt sie an der gewünschten Stelle ein |
| Wertreihe löschen | Löscht die aktuelle Wertreihe |
| IDs bearbeiten | Öffnet den Dialog zum Bearbeiten der IDs |
| Kommentar bearbeiten | Öffnet das Kommentarfeld in der Zelle "Name" der Wertreihe |
| Ausschneiden | Schneidet die aktuelle Wertreihe aus |

* **Ist-numerisch** \| Gibt an, ob es sich bei der Eingabe um einen numerischen Wert handelt

| Einstellung | Beschreibung |
| --- | --- |
| 0 | Nein, bei der Eingabe handelt es sich nicht um eine numerische Zahl |
| 1 | Ja, bei der Eingabe handelt es sich um eine numerische Zahl |

* **Sichtbarkeitsstufe** \|  Bietet die Möglichkeit, Spalten für den Nutzer bei der Dateneingabe auszublenden

* **Herkunft** \| Gibt an, woher die Werte stammen

| Einstellung | Beschreibung |
| --- | --- |
| Input | Dateneingabe direkt in Excel, keine Einschränkung |
| Link | Bietet die Möglichkeit einen Link zu hinterlegen \(bspw. zu einem Dokument oder einer Website\) |
| XLS | Werte durch eine Formal berechnen lassen. Die Excel-Formel kann immer überschrieben und bearbeitet werden |
| XLS Strict | Werte durch eine Formel berechnen lassen. Die Excel-Formel kann nur bei aufgeklappten Details überschrieben und bearbeitet werden |

* **Werteliste** \| Bietet die Möglichkeit eine Liste mit Werten zu hinterlegen, die im Wertebereich per Dropdown ausgewählt werden können.

* **Werteformat** \| Einstellung eines vordefinierten Werteformats. Sie können individuelle Formate vordefinieren und hier auswählen.

* **Einheit** \| Gibt an, in welcher Einheit die Werte in der Datenbank gespeichert werden. \(z.B. EUR, Kilogramm, Kilometer, Prozent, Stück, Text, USD\). Sie können jederzeit neue Einheiten in der Liste [**sxUnits**](../listen-und-formate.md) frei definieren.

* **Skalierung** \| Gibt die Skalierung an, in der die Werte in der Datenbank gespeichert werden. Diese Einstellung hat nur Auswirkungen auf numerische Werte.

| Einstellung | Beschreibung |
| --- | --- |
| 1 | Keine Nachkommastelle |
| 10 | Eine Nachkommastelle |
| 100 | Zwei Nachkommastelle |
| 1000 | Drei Nachkommastelle |
| 10000 | Vier Nachkommastelle |

* **Effekt** \| Beschreibt das betriebswirtschaftlichen Merkmal, das ein Wert innehat.

| Einstellung | Beschreibung |
| --- | --- |
| Aktivbestand | Wert geht in die Bilanzaktiva ein |
| Auszahlung | Reine Auszahlung |
| Einzahlung | Reine Einzahlung |
| Ertrag | Einzahlungsunwirksamer Ertrag |
| Ertrag=Einzahlung | Einzahlungswirksamer Ertrag |
| Hilfswert | Reiner Hilfswert, dient der Zwischenberechnung |
| Kosten | Auszahlungsunwirksame Kosten |
| Kosten=Auszahlung | Auszahlungswirksame Kosten |
| Menge | Gibt die mengenmäßige Veränderung an |
| Passivbestand | Wert geht in die Bilanzpassiva ein |
| Stück | Anzahl |
| Text | Textwert |
| Überschrift | Reine Überschrift |

* **Parameter** \| Gibt die Breite der Wertreihe an.

* **Name** \| Bezeichnung der Wertreihe. Es empfiehlt sich, an den Namen einen aussagekräftigen, beschreibenden Kommentar anzufügen, um dem Nutzer die Eingabe zu erleichtern.

* **ID** \| ID der Wertreihe. Kann durch den Nutzer verändert werden. Innerhalb einen Produkts muss die ID der Wertreihe eindeutig sein.

Die Eigenschaften und Optionen werden durch das Klicken auf die Schaltfläche **Details zeigen** sichtbar.

---
![](/Pictures/Excel-Client/Templates/Allgemeiner Aufbau/allgemeiner_aufbau_5.png)

---

#### Wertebereich

Der Wertebereich ist der Bereich, in dem die konkreten Daten erfasst werden.

---
![](/Pictures/Excel-Client/Templates/Allgemeiner Aufbau/allgemeiner_aufbau_6.png)

---

Je nachdem wie die Wertreihen definiert sind, können Sie hier Daten frei eingeben und erfassen. Es können sämtliche Excel Formeln genutzt werden.

> **Hinweis:** Formeln werden in den Wertreihen nur gespeichert, wenn die Wertreihe vom Typ XLS oder XLS-Strict definiert ist. Andernfalls werden nur die Werte gespeichert.

#### Orientierung und Namenskonvention

Ein Template ist entweder horizontal oder vertikal orientiert. Die Orientierung basiert auf einer Namenskonvention und wird durch das angehängte Suffix bestimmt.

---
![](/Pictures/Excel-Client/Templates/Allgemeiner Aufbau/allgemeiner_aufbau_7.png)

---

Das Suffix hat sowohl Auswirkung auf die Orientierung als auch auf die Zeitachse und wird an den Namen des Template mit einem „\_“ angehangen. Der erste Buchstabe definiert die Orientierung, der zweite Buchstabe den Detailgrad bei der Anzeige der Zeitachse.

* ** Erster Buchstabe = V**

| Zweiter Buchstabe | Suffix | Beschreibung |
| :--- | :--- | :--- |
| T | \_VT | Vertikale Ausrichtung mit Tagesdarstellung |
| M | \_VM | Vertikale Ausrichtung mit Monatsdarstellung |
| J | \_VJ | Vertikale Ausrichtung mit Jahresdarstellung |
| N | \_VN | Vertikale Ausrichtung ohne Zeitachse |

* ** Erste Buchstabe = H**

| Zweiter Buchstabe | Suffix | Beschreibung |
| :--- | :--- | :--- |
| T | \_HT | Horizontale Ausrichtung mit Tagesdarstellung |
| M | \_HM | Horizontale Ausrichtung mit Monatsdarstellung |
| J | \_HJ | Horizontale Ausrichtung mit Jahresdarstellung |
| J | \_HN | Horizontale Ausrichtung ohne Zeitachse |

> **Hinweis**: Die Wahl der Zeitachsendarstellung hat einen Einfluss auf die Darstellungsweise der einzelnen Zeilen. Bei der Tagesdarstellung wird der letzte Tag des Monats vom ersten Tag des darauffolgenden Monats durch eine dicke Rahmenlinie abgegrenzt. Bei der Monatsdarstellung wrid der letzte Monat des Jahres vom ersten Monat des darauffolgenden Jahres auf diese Art abgegrenzt.

---
![](/Pictures/Excel-Client/Templates/Allgemeiner Aufbau/allgemeiner_aufbau_8.png)

---

#### _Drehen des Templates_

Es besteht jederzeit die Möglichkeit, das Template zu drehen. Dies ist zum einen im Template selbst möglich sowie durch die Änderung der Namenskonvention.

Im Template selbst können Sie durch Klick auf den Button **Drehen** zwischen vertikaler und horizontaler Ansicht wechseln. Allerdings ist das Speichern nur in der Ansicht möglich, die durch die Namenskonvention vorgeben wird.

---
![](/Pictures/Excel-Client/Templates/Allgemeiner Aufbau/allgemeiner_aufbau_9.png)

---

In der Produktübersicht können Sie die Orientierung des Templates durch Änderung der Namenskonvention ändern. Ersetzen Sie in der Spalte **Template** den ersten Buchstaben des Suffixes durch den gewünschten Buchstaben und klicken Sie auf **Speichern**. Diese Änderung ist permanent.

---
![](/Pictures/Excel-Client/Templates/Allgemeiner Aufbau/allgemeiner_aufbau_10.png)

---