## Installation und Updates

Der Umfang der Installation richtet sich danach, ob Sie Ihre DataFactory-Datenbank auf einem eigenen SQL Server verwalten oder wir Ihre Datenbank auf unseren Cloud-Server für Sie hosten. 

In beiden Fällen wird zunächst der Excel-Client auf Ihrem System installiert. Wenn Sie Ihren eigenen SQL Server nutzen, sind zusätzliche Installationsschritte im SQL Management Studio durchzuführen, welche ggf. durch den Systemadministrator vorgenommen werden müssen.

### Installation des Excel-Clients

Die Installationsdatei wird Ihnen von uns zur Verfügung gestellt.

> **Hinweis:** Bei der Installationsdatei handelt es sich um eine .zip-Datei, d.h. eine Datei, deren Inhalt komprimiert wurde. Diese muss zunächst entpackt werden.

#### Datei entpacken und öffnen

1) Öffnen Sie den Ordner, in welchen Sie die Download-Datei gespeichert haben und klicken Sie mit der rechten Maustaste auf die .zip-Datei. Es öffnet sich ein Fenster, in welchem Sie die Option **Alle extrahieren...** auswählen.

---
![](/Pictures/Excel-Client/Installation/installation_6.png)

---

2) Es öffnet sich ein Fenster, in welchem Sie definieren, in welchen Zielordner die .zip-Datei extrahiert werden soll. Indem Sie auf den Button **Durchsuchen** klicken, können Sie den Zielordner ändern. Im Anschluss klicken Sie auf **Extrahieren**.

---
![](/Pictures/Excel-Client/Installation/installation_7.png)

---

3) In Ihrem Zielordner finden Sie nun den Ordner **DataFactoryBrowser_X.X.X**, welcher wiederum zwei Items beinhaltet. Zum einen den Ordner **+** und zum anderen den **DataFactory Excel-Client**. 

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

Den aktuellen Release des Excel-Clients stellen wir Ihnen stets zur Verfügung. Nachdem Sie die neue Version des Excel-Clients heruntergeladen, haben installieren Sie Ihn wie oben beschrieben. Bei Nutzung eines neuen Releases gehen die Verbindungen, die Sie im alten Client genutzt haben, verloren. Im Folgenden wird Ihnen erklärt, wie Sie die Verbindungen wiederherstellen können.

Die Verbindungen zu Ihren DataFactory-Datenbanken haben Sie bereits über Ihre bisherigen Excel-Client-Versionen definiert. Für jede Datenbankverbindung, die Sie in Ihrem Excel-Client anlegen, wird eine sogenannte Key-File erstellt und in Ihrem DataFactory-Ordner **+** abgelegt. Lesen Sie dazu mehr in Kapitel [Keys](werk/keys.md).

Über diese Key-Files können Sie in Ihrer neuen Excel-Client-Version einfach und schnell Ihre Datenbankverbindungen  wiederherstellen. Ihre Key-Files haben Sie wie in Kapitel [Keys](werk/keys.md) erläutert in einem von Ihnen gewählten Ordner gespeichert. In Ihrem neuen Excel-Client muss nun die Information hinterlegt werden, in welchem Ordner  sich die Key-Files befinden. Gehen Sie dazu wie folgt vor.

1) Wählen Sie in der **Werksübersicht** die Option **Neu**.

---
![](/Pictures/Excel-Client/Updates/updates_1.png)

---

2) In dem sich öffnenden Fenster wählen Sie den Ordner aus, in dem sich Ihre Key-Files befinden und klicken Sie auf **OK**.

---
![](/Pictures/Excel-Client/Updates/updates_2.png)

---

3) In Ihrem Excel-Client werden Ihnen nun Ihre Cluster angezeigt.

---
![](/Pictures/Excel-Client/Updates/updates_3.png)

---

### Update der API

Es kann notwendig sein, ein Update der API durchzuführen. Sollte die Versionsnummer der Datei nicht der Versionsnummer des Servers entsprechen, bitten Sie den Administrator diesen zu updaten. Sollten Sie selbst der Administrator sein, lesen Sie in Kapitel [Installation der DataFactory-Datenbank](../installation-der-datafactory-datenbank.md) weiter.
