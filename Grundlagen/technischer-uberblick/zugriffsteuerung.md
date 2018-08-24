### Zugriffssteuerung
DataFactory unterstützt verschiedene Berechtigungssysteme - das Active Directory im Intranet und das Azure Active Directory im Cloudbetrieb.

#### Im Intranet

Im Intranet werden die Benutzer über das Active Directory identifiziert. In der DataFactory Rechteverwaltung werden die Benutzer mit dem Name **Domäne\Username** hinterlegt.  Beim Zugriff auf DataFactory werden Sie dann vom Webbrowser durch Ihre Anmeldung am PC authentifiziert (single-sign-on).

Nicht alle Browser unterstützen diese Anmeldung per Windows Authorisierung im Default. Bei Firefox muss diese zum Beispiel erst aktiviert werden.

---
![](/Pictures/Grundlagen/Technischer-Überblick/Zugriffssteuerung/zugriffssteuerung_1.png)

---

Da Sie im Intranet an Ihrer Windows Anmeldung erkannt werden, brauchen und können Sie sich dort nie ausloggen.

Auch im Intranet wäre die Anmeldung über eine Benutzernamen / Kennwort Kombination möglich. Das ist aber unüblich da es die Sache für den Benutzer weniger komfortabel macht. Falls Sie dies dennoch wünschen, können auf dem SQL Server Benutzer angelegt werden, welche in der DataFactory Datenbank die Rolle **pf_PlanningFactoryUser** erhalten.

#### In der Cloud

Beim Zugriff auf eine in der Cloud gehosteten Datenbank erfolgt die Anmeldung über ein Benutzerkonto im Azure Active Directory. Dabei haben Sie die Wahl:

* Sie können ein vorhandenes Google Konto nutzen
* Sie können Ihre Emailadresse mit einem Passwort registrieren

Sofern Ihre Firma Google Mail o.ä. nutzt oder Sie eine Privatperson sind und ein Google Konto besitzen ist die erste Variante günstig (nicht noch ein Passwort...), sonst die Zweite.

In DataFactory wird zur Authorisierung bei Cloudhosting immer die Emailadresse als Benutzer hinterlegt. Gehen Sie wie folgt zur Aktivierung Ihres Zugangs vor:

1. Sie erhalten von uns einen Zugangslink. Dieser lautet z.B. [https://factoryprovider.com/[Firma]](https://factoryprovider.com/[Firma])
2. wenn Sie diesen Link aufrufen werden Sie aufgefordert sich einzuloggen

---
![](/Pictures/Grundlagen/Technischer-Überblick/Zugriffssteuerung/zugriffssteuerung_2.png)

---

3a. Sie klicken oben auf Google und loggen sich über den Google Anmeldedialog ein und sind drin

3b. Sie klicken auf **Jetzt registrieren**

* Sie tragen Ihre Mailadresse ein und lassen sich den Verifizierungscode senden
* Sie geben den Verifizierungscode ein und lassen ihn prüfen
* Sie vergeben Ihr Passwort und klicken auf **Erstellen**

---
![](/Pictures/Grundlagen/Technischer-Überblick/Zugriffssteuerung/zugriffssteuerung_3.png)

---

Der Anmeldedialog wird dann periodisch erscheinen, da sich der Browser die Anmeldedaten für einen gewissen Zeitraum merkt. Wenn Sie sich bewußt abmelden möchten klicken Sie auf **Log Off**.

---
![](/Pictures/Grundlagen/Technischer-Überblick/Zugriffssteuerung/zugriffssteuerung_4.png)

---

Die Anmeldung gilt datenbankübergreifend, Sie können also nach der Anmeldung alle Datenbanken betreten für welche Sie berechtigt sind.

Auch der Excel-Client wird diesen Anmeldedialog im Browser öffnen, sofern Sie auf eine Clouddatenbank zugreifen wollen. Sollten Sie sich bereits im Webclient angemeldet haben, wird der Excel-Client diese Anmeldung nutzen und Sie direkt das Cluster betreten lassen.


<!---


**Active Directory**  
Das Active Directory kommt zum Einsatz, wenn DataFactory auf dem lokalen Server liegt. Im Active Directory sind alle Nutzer des Intranets gespeichert. Beim Zutritt in die DataFactory werde Sie über das Active Directory durch Ihre Anmeldung am PC authentifiziert (single-sign-on).

**E-Mail-Adresse und Passwort**  
Beim Zugriff über die Cloud erfolge die Authentifizierung über E-Mail-Adresse und Passwort. Dazu ist es notwendig, dass die E-Mail-Adresse unter www.planning-factory.de registriert wird.


-->