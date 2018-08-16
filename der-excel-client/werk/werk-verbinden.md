### Werk verbinden

Um sich zu einem Werk bzw. mit einer Datenbank zu verbinden, müssen Sie einen neuen Key anlegen. Gehen Sie wie folgt vor:

1) Klicken Sie auf den **ActionLink** innerhalb der Werksübersicht.  

---
![](/Pictures/Excel-Client/Werk/Werk verbinden/werk_verbinden_1.png)

---

2) Klicken Sie auf die Option **Verbindungen verwalten**.

---
![](/Pictures/Excel-Client/Werk/Werk verbinden/werk_verbinden_2.png)

---

3) Es öffnet sich der Connection Manager.

4) Klicken Sie auf den Button **Hinzufügen**.

---
![](/Pictures/Excel-Client/Werk/Werk verbinden/werk_verbinden_3.png)

---

5) Geben Sie in den Connection Manager die erforderlichen Informationen ein:

|Einstellung|Beschreibung|
| - | - |
|**Dateiname**|Name der Key-Datei, kann beliebig gewählt werden|
|**Kachelbezeichnung**|Name der Kachel in der Werksübersicht, kann beliebig gewählt werden|
|**Protokoll**|SQL: Nutzung von DataFactory im Intranet http: Nutzung von DataFactory in der Cloud|
|**Server**|Adresse des Servers (z.B. https://servername.com/|
|**Datenbank**|Name der Datenbank|
|**Authentifizierung**|windows: Nutzt die Windowsauthentifizierung - Benutzername und Passwort bleiben in diesem Falle leer  
basic: Authentifizierung über Benutzername und Passwort  
oidc: Authentifizierung über eine oidc-Schnittstelle|
|**Benutzer**|Name des Benutzers (bei Nutzung der Cloudversion ist Ihr Benutzername Ihre E-Mail-Adresse)|
|**Kommentar**|Kommentarzeile die bei Eingabe der Login-Daten angezeigt wird|

>**Hinweis:** Das Passwort wird erst beim Verbindungsversuch abgefragt und wird nicht vom Connection Manager erfasst.

<!---

---
![](/Pictures/Excel-Client/Werk/Werk verbinden/werk_verbinden_4.PNG)

---

-->

6) Klicken Sie den Button **Verbindung testen**, um die Verbindung zu testen. Sofern alle Einstellungen korrekt sind, erfolgt die Meldung: **Die Verbindung konnte erfolgreich hergestellt werden.**  

---
![](/Pictures/Excel-Client/Werk/Werk verbinden/werk_verbinden_5.PNG)

---

7) Optional können Sie über den Button **Bild hinzufügen** der Kachel ein Bild hinzufügen.  

> **Hinweis:** Das Bild wird direkt in der Verbindung gespeichert, d.h. das Bild muss nicht bei Ihnen gespeichert bleiben. Das Bild muss 150x100px groß sein und im .png-Format vorliegen.  

8) Klicken Sie auf den Button **Speichern**, um die Verbindung zu speichern.

>**Hinweis:** Optional können Sie auf **Speicher als** klicken, um sowohl den Dateinamen als auch den Speicherort der Key-Datei anzupassen.

9) Nach dem Speichern können Sie den Connection Manager schließen und gelangen zurück zur Werksübersicht und sehen dort die gerade angelegte Verbindung zu Ihrem Cluster.  

---
![](/Pictures/Excel-Client/Werk/Werk verbinden/werk_verbinden_6.png)

---

10) Der zu diesem Cluster dazugehörige Key wurde im entsprechenden Key-Ordner abgelegt.

---
![](/Pictures/Excel-Client/Werk/Werk verbinden/werk_verbinden_7.png)

---
