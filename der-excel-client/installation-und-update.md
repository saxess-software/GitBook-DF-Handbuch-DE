## Installation

Der Umfang der Installation richtet sich danach, ob Sie Ihre DataFactory-Datenbank auf einem eigenen SQL Server verwalten oder wir Ihre Datenbank auf unseren Cloud-Server für Sie hosten. 

In beiden Fällen wird zunächst der Excel-Client auf Ihrem System installiert. Wenn Sie Ihren eigenen SQL Server nutzen, sind zusätzliche Installationsschritte im SQL Management Studio durchzuführen, welche ggf. durch den Systemadministrator vorgenommen werden müssen.

### Installation des Excel-Clients

Die Installationsdatei wurde Ihnen ggf. bereits zur Verfügung gestellt. Wenn nicht, können Sie sich diesen unter <https://planning-factory.com> herunterladen.

#### Registrierung und Download

Um den Excel-Client herunterzuladen, müssen Sie sich zunächst zunächst auf **planning-factory.com** registrieren.

1) Öffnen Sie die Seite <https://planning-factory.com> und klicken Sie auf den Button **Register**.

---
![](/Pictures/Excel-Client/Installation/installation_1.png) 

---
2) Tragen Sie Ihre **Email-Adresse** ein, vergeben Sie ein **Passwort** und geben Sie dieses ein zweites Mal zur Bestätigung ein. Bestätigen Sie Ihre Eingaben mit einem Klick auf den Button **Register**.

---
![](/Pictures/Excel-Client/Installation/installation_2.png)

---

3) In dem sich öffnenden Browser-Fenster können Sie durch Klicken des Buttons **Download Excel Client** den Download des Excel Clients starten. 

---
![](/Pictures/Excel-Client/Installation/installation_3.png)

---

4) Es öffnet sich ein Fenster, in dem Sie **Datei speichern** auswählen und mit **OK** bestätigen. 

---
![](/Pictures/Excel-Client/Installation/installation_4.png)

---

5) Wählen Sie nun den gewünschten Speicherort und klicken Sie auf **OK**.

---
![](/Pictures/Excel-Client/Installation/installation_5.png)

---

> **Hinweis**: Bei der heruntergeladenen Datei handelt es sich um eine .zip-Datei, d.h. eine Datei, deren Inhalt komprimiert wurde. Diese muss zunächst entpackt werden.

#### Datei entpacken und öffnen

1) Öffnen Sie den Ordner, in welchen Sie die Download-Datei gespeichert haben und klicken Sie auf mit der rechten Maustaste auf die .zip-Datei. Es öffnet sich ein Fenster, in welchem Sie die Option **Alle extrahieren...** auswählen.

---
![](/Pictures/Excel-Client/Installation/installation_6.png)

---

2) Es öffnet sich ein Fenster, in welchem Sie definieren, in welchen Zielordner die .zip-Datei extrahiert werden soll. Indem Sie auf den Button **Durchsuchen** klicken, können Sie den Zielordner ändern. Im Anschluss klicken Sie auf **Extrahieren**.

---
![](/Pictures/Excel-Client/Installation/installation_7.png)

---

3) In Ihrem Zielordner finden Sie nun den Ordner **DataFactory X.0 Build XXXX**, welcher wiederum zwei Items beinhaltet. Zum einen den Ordner **+** und zum anderen den **DataFactory Excel-Client**. 

---
![](/Pictures/Excel-Client/Installation/installation_8.png)

---

Wenn Sie in Ihrem Ordner auf den DataFactory Excel-Client klicken, öffnet sich Excel mit der Excel-Mappe, die den XLS-Client enthält. Beim ersten Start müssen Sie die Makros aktivieren, indem Sie in der gelben eingeblendeten Zeile unterhalb des Navigationsbereichs den Button **Inhalt aktivieren** anklicken. Diese Einstellung bleibt anschließend bestehen und muss nicht wieder ausgeführt werden.

---
![](/Pictures/Excel-Client/Installation/installation_9.png)

---

Sie gelangen im Anschluss in die Werksübersicht, wo Sie wie in Kapitel [Werk verbinden](werk/werk-verbinden.md) beschrieben, eine Verbindung zu einer Datenbank herstellen können. Wenn Sie einen eigenen SQL Server nutzen, sind allerdings zuvor noch weitere Installationsschritte notwendig. Mit einer Datenbank in der Saxess-Cloud können Sie sich aber jetzt bereits verbinden.

Wenn Sie eine DataFactory-Datenbank auf Ihrem eigenen Server nutzen wollen, bitten Sie Ihren Administrator, diese für Sie einzurichten. Wenn Sie selbst der Administrator sind, dann lesen Sie in Kapitel [Installation der DataFactory-Datenbank](../installation-der-datafactory-datenbank.md) weiter.

### Update des Excel-Clients

Den aktuellen Release des Excel-Clients finden Sie auf <https://planning-factory.com>. Laden Sie ihn dort herunter und installieren Sie Ihn wie Kapitel [Updates](updates.md) beschrieben.

