# Der Excel-Client

Der Excel-Client ist eine Excel-Mappe, die Sie wie jede andere Excel-Datei mit Excel ab Version 2010 öffnen können. Er ist ein vollumfänglicher Client, der alle Funktionen beinhaltet, die Sie benötigen, um Ihre DataFactory zu designen und auf Ihre individuellen Bedürfnisse anzupassen. Sie lernen in den folgenden Abschnitten die gesamte Palette an Funktionen und Möglichkeiten des Excel-Clients kennen.  
Nach dem Öffnen der Arbeitsmappe gelangt man zur Werksübersicht.  
**Hinweis**: Beim ersten Start müssen Sie Makros aktivieren. Diese Einstellung bleibt anschließend bestehen.

## Werk

Ein Werk ist aus physischer Sicht in DataFactory eine Datenbank und ein in sich geschlossenes, unabhängiges System. Es wird auch als Cluster oder Kachel bezeichnet.

![Eine Werkskachel](images/Werk/eine_kachel_fürs_werk.png)

Bevor Sie DataFactory nutzen können, benötigen Sie eine Datenbank auf einem MS-SQL-Server. Sofern Sie DataFactory in der Cloudversion nutzen, bekommen Sie die Datenbank von uns direkt mitgeliefert. Nutzen Sie DataFactory in Ihrem lokalen Intranet, muss die Datenbank durch den Datenbankadministrator angelegt werden.  
In diesem Abschnitt erfahren Sie, wie Sie ein Werk betreten, verbinden oder löschen können. 

### Werksübersicht

Die Werksübersicht unterteilt sich in einen **Kopfbereich** und einen **Arbeitsbereich**.

![Cluster page](images/Werk/die_werksübersichtsseite.png)

Der Kopfbereich bleibt in jeder Ansicht erhalten und enthält Informationen zur verwendeten Version, zum angemeldeten User sowie Informationen zur Navigation. Darüber hinaus enthält der Kopfbereich immer den Button **Werksübersicht**. Über diesen Button gelangt man immer direkt zur Werksübersicht.  

![Der Kopfbereich der Werksübersicht](images/Werk/der_kopfbereich_der_werksübersicht.png) 

Im Arbeitsbereich der Werksübersicht befinden sich die zur Verfügung stehenden Cluster sowie die Optionen zur Verbindungs- und Sprachenverwaltung.  

![Der Arbitsbereich der Werksübersicht](images/Werk/der_arbeitsbereich_der_werksübersicht.png)

**Hinweis**: Sofern Ihnen noch keine Cluster zur Verfügung stehen, erscheint der Text: „kein Keyfiles in Verzeichnis…“ 

### Sprache ändern 

Um die Sprache zu ändern, gehen Sie wie folgt vor: 

1. Klicken Sie auf den ActionLink **Verbindungen und Sprache**.  

![Cluster page](images/Werk/ein_link_verbindungen_und_sprache.png)

2.	Klicken Sie auf die Option **Sprache ändern**. 

![Optionen des Links Verbindungen und Sprache](images/Werk/eine_option_verbindungen_und_sprache.png)

3.	Wählen Sie die gewünschte Sprache und bestätigen Sie mit dem Button **Activate**.  

![Sprachauswahl](images/Werk/sprachauswahl.png)

Es stehen Ihnen 4 Sprachen für die Benutzeroberfläche zur Verfügung:  

* Deutsch
* Englisch
* Niederländisch
* Russisch

Die Standardsprache der Benutzeroberfläche ist deutsch. Die Umstellung der Standardsprache erfolgt im Verzeichnis +\i18n durch das Setzen eines Unterstrichs vor die gewünschte Sprache.  

![Der Inhalt vom Ordner "i18n" der Systemdateien von Data Factory](images/Werk/änderung_der_standardsprache.png) 

### Keys

Keys sind in DataFactory Verbindungen zu Clustern. Physisch gesehen sind Keys spezielle Dateien (.pfk-Dateien), in denen die Verbindungsoptionen gespeichert sind.  

![Der Inhalt vom Ordner "Keys" der Systemdateien von Data Factory](images/Werk/keys.png) 

Standardmäßig befinden sich die Keys im Unterordner Keys des „+“-Ordners Ihrer DataFactory.  
Für jede Verbindung zu einem Cluster wird ein Key angelegt.

### Werk betreten

Um ein Werk zu betreten, gehen Sie wie folgt vor:  

1. In der Werksübersicht sehen Sie die Werke, die Sie betreten können.  

![Eine Werkkachel](images/Werk/eine_kachel_fürs_werk_betreten.png) 

2. Klicken Sie auf die blaue Kachel (Cluster) um die Verbindung herzustellen.
3. Nachdem Sie das Werk betreten haben, sehen Sie die Übersicht Fabriken und Produktlinien.  

![Die Factory Seite](images/Werk/die_übersicht_fabriken_und_produktlinien.png) 

**Hinweis**: Im Bereich oben rechts sehen Sie Informationen zum dem Werk, in dem Sie sich gerade befinden.

### Werk verbinden

Um sich zu einem Werk zu verbinden, müssen Sie einen neuen Key anlegen. Gehen Sie wie folgt vor:

1. Klicken Sie auf den ActionLink **Verbindungen und Sprache**.  

(Bild - ein besseres Bild machen!!)

2. Klicken Sie auf die Option **Verbindungen verwalten**.  

![Optionen des Links Verbindungen und Sprache](images/Werk/eine_option_verbindungen_und_sprache.png)

3. Es öffnet sich der Connection Manager.
4. Klicken Sie auf den Button **Neue Verbindung**.  

![Verbindugsverwaltung](images/Werk/eine_neue_verbindung.png)

5. Geben Sie in den Connection Manager die erforderlichen Informationen ein:  

[Bild - eine Tabelle]  

6. Klicken Sie den Button **Test Connection**, um die Verbindung zu testen. Sofern alle Einstellungen korrekt sind, erfolgt die Meldung: **Die Verbindung konnte erfolgreich hergestellt werden.**  

![Verbindugsverwaltung](images/Werk/herstellung_einer_neuen_verbindung.png)

7. Optional können Sie über den Button **Add Image** der Kachel ein Bild hinzufügen.  
**Hinweis**: Das Bild wird direkt in der Verbindung gespeichert, d.h. das Bild muss nicht bei Ihnen gespeichert bleiben. Das Bild muss 150x100px groß sein und im .png-Format vorliegen.  
8. Klicken Sie auf den Button **Speichern**, um die Verbindung zu speichern.  
9. Nach dem Speichern können Sie den Connection Manager schließen und gelangen zurück zur Werksübersicht und sehen dort die gerade angelegte Verbindung zu Ihrem Cluster.  

![Cluster page](images/Werk/eine_kachel_als_eine_neue_verbindung.png) 

### Werk entfernen

Um ein Werk zu entfernen, gehen Sie wie folgt vor:  

1. Klicken Sie auf den ActionLink **Verbindungen und Sprache**.  

[Bild: ein Bild aus Word überstimmt nicht. Ein neues Bild machen!!]  

2. Klicken Sie auf den Button **Verbindungen verwalten**.  

![Optionen des Links Verbindungen und Sprache](images/Werk/eine_option_verbindungen_und_sprache.png) 

3. Es öffnet sich der Connection Manager.
4. Wählen Sie die Verbindung aus, die Sie löschen möchten.  

![Verbindugsverwaltung](images/Werk/eine_verbindung_zum_auswählen.png)

5. Klicken Sie auf den Button **Verbindung löschen**.  

![Verbindugsverwaltung](images/Werk/ein_button_verbindung_löschen_in_der_verbindungsverwaltung.png)

6. Klicken Sie auf den Button **Ja**, um die Verbindung zu löschen.  

![Message box](images/Werk/message_box_verbindung_löschen.png)

### Werk umbenennen

Um ein Werk umzubenennen, gehen Sie wie folgt vor:

1. Gehen Sie zur Werksübersicht, klicken Sie auf den ActionLink **Verbindungen und Sprache** und wählen Sie die Option **Verbindungen** verwalten.  

![Optionen des Links Verbindungen und Sprache](images/Werk/eine_option_verbindungen_und_sprache.png)  

2. Wählen Sie die Verbindung aus, die Sie umbenennen wollen.  

![Verbindugsverwaltung](images/Werk/eine_verbindung_zum_auswählen.png)

3. Geben Sie im Feld **Kachelbezeichnung** den neuen Namen Ihrer Verbindung ein.  

![Verbindugsverwaltung](images/Werk/eine_reihe_kachelbezeichnung_in_der_verbindungsverwaltung.png)

4. Klicken Sie auf den Button **Speichern**, um Ihr Werk umzubenennen.  

![Verbindugsverwaltung](images/Werk/ein_button_speichern_in_der_verbindungsverwaltung.png)

**Hinweis**: Wenn Sie ein Werk umbenennen, ändert sich nur die Beschriftung der Kachel, die Sie in der Werksübersicht sehen.

### Mehrere Werke organisieren

Wenn Ihnen eine Reihe von verschiedenen Werken zur Verfügung stehen, empfiehlt sich die Werke in verschiedenen Ordnern zu organisieren.  

[Screenshot]

Dazu gehen Sie wie folgt vor:

1. Legen Sie sich Ihre gewünschte Ordnerstruktur in Ihrem Explorer an.  

![Die Ordnerstruktur im Dateisystem von Data Factory](images/Werk/anlegen_der_ordnerstruktur.png)

2. Verschieben Sie Keyfiles in Ihre Ordnerstruktur.

![Die Ordnerstruktur im Dateisystem von Data Factory](images/Werk/keys_in_der_Ordnerstruktur.png)

3. Gehen Sie zur Werksübersicht und klicken Sie auf die Schaltfläche **Neu**.

![Cluster page](images/Werk/ein_link_neu_auf_der_werksübersichtsseite.png)  

4. Wählen Sie Ihr gewünschtes Verzeichnis und klicken Sie auf den Button **OK**.  

![Die Ordnerstruktur im Dateisystem von Data Factory](images/Werk/wahl_eines_verzeichnisses_für_werkorganisation.png)

5. Ihr Verzeichnis wurde nun hinterlegt.  

![Cluster page](images/Werk/die_werksübersicht_mit_mehreren_kacheln.png)    

### Werk verwalten

Um ein Werk zu verwalten, müssen Sie zunächst das Werk betreten. In der Übersicht Fabriken und Produktlinien finden Sie den ActionLink **Dieses Werk verwalten**.  

![Factory Seite](images/Werk/ein_link_dieses_werk_verwalten.png) 

Es stehen Ihnen folgende Optionen zur Verfügung.  

[Bild - eine Tabelle!]

### Benutzer verwalten

DataFactory ermöglicht Ihnen eine komfortable Verwaltung von Benutzern und deren Zugriffsrechten innerhalb der DataFactory. Benutzer werden zentral für ein Werk verwaltet. Es besteht jedoch die Möglichkeit jedem Nutzer individuelle Zugriffsrechte hinunter bis zur Ebene der Produktlinie zu geben. Die Regelung der Zugriffsrechte erfolgt in 3 Stufen:  

[Bild - eine Tabelle!]

Darüber hinaus haben Sie die Möglichkeit zum Zwecke der Sicherheit und Dokumentation von jedem Nutzer beim Lesen und/oder Ändern von Inhalten in Ihrer DataFactory einen Kommentar zu erzwingen.  

[Bild - eine Tabelle!]

### Neuen Benutzer anlegen

Um einen neuen Benutzer anzulegen, gehen Sie wie folgt vor:

1. Klicken Sie der Übersicht Fabrik und Produktlinien auf den ActionLink **Dieses Werk verwalten**.  

![Factory Seite](images/Werk/ein_link_dieses_werk_verwalten.png)   

2. Klicken Sie auf die Option **Benutzer verwalten**.  

![Die Optionsliste des Links Dieses Werk verwalten](images/Werk/eine_option_benutzer_verwalten.png) 

3. Klicken Sie auf die Schaltfläche **Neuer Benutzer**.  

![Die Seite von einer Option Benutzer verwalten](images/Werk/ein_link_neuer_benutzer.png)  

4. Geben Sie den Namen des neuen Benutzers ein.  

![Die Seite von einer Option "Benutzer verwalten"](images/Werk/schaffung_eines_neuen_benutzers.png)  

5. Klicken Sie auf die Schaltfläche **Speichern**, um den Benutzer zu speichern.  

![Die Seite von einer Option Benutzer verwalten](images/Werk/schaffung_eines_neuen_benutzers_speichern.png) 

**Hinweis**: Sie haben nun einen neuen Nutzer angelegt. Sie müssen nun dem Nutzer noch die gewünschten Rechte in Ihrer DataFactory einräumen.

### Benutzerrechte ändern

Sie können jeden Nutzer individuell für bestimmte Fabriken oder Produktlinien berechtigen und entsprechenden Kommentarpflichten definieren.
Um die Rechte eines Benutzers zu ändern, gehen Sie wie folgt vor:

1. Klicken Sie auf den Namen des Benutzers.  

![Die Seite von einer Option Benutzer verwalten](images/Werk/auswahl_eines_benutzers.png) 

2. Wählen Sie in der Spalte **Right** die entsprechenden Rechte für die jeweiligen Fabriken und Produktlinien aus.

![Die Seite von einer Option Benutzer verwalten mit der Seite von Benutzerrechten](images/Werk/rechtevergebung.png) 

3. Nehmen Sie die gewünschten Einstellungen in den Spalten **ReadCommentMandatory** und **WriteCommentMandatory** vor.  

![Die Seite von einer Option Benutzer verwalten mit der Seite von Benutzerrechten](images/Werk/einstellungen_der_benutzerrechte.png) 

4. Klicken Sie auf die Schaltfläche **Speichern**, um Ihre Eingaben zu sichern.  

![Die Seite von einer Option Benutzer verwalten mit der Seite von Benutzerrechten](images/Werk/ein_link_speichern_von_benutzerrechteeinstellungen.png)  

**Hinweis**: Berechtigungen werden in DataFactory vererbt. Wenn Sie einem Nutzer die gleichen Rechte und Kommentarpflichten für das gesamte Werk einräumen wollen, müssen Sie die Einstellung lediglich in der ersten Zeile vornehmen. Nach dem Speichern übertragen sich die Einstellungen auf alle Zeilen. Ebenso definieren Sie nur die Zugriffsrechte für eine Factory, wenn der Benutzer auf alle Produktlinien einer Factory Zugriff haben soll. Wenn Sie Benutzern Rechte entziehen wollen, führen Sie zuerst auf oberster Ebene ein Deny aus. 

### Benutzer löschen

Um einen Benutzer zu löschen, gehen Sie wie folgt vor:  

1. Gehen Sie zu dem Benutzer, den Sie löschen wollen und klicken Sie in der Spalte **Action** auf den ActionLink.  

![Die Seite von einer Option Benutzer verwalten](images/Werk/auswahl_eines_benutzers_zum_löschen.png)   

2. Klicken Sie auf die Option **Löschen**.  

![Die Seite von einer Option Benutzer verwalten](images/Werk/eine_option_löschen_auf_der_seite_benutzer_verwalten.png)   

3. Klicken Sie auf **Ja**, um den Benutzer endgültig zu löschen.  

![Message box](images/Werk/message_box_benutzer_löschen.png)  

## Fabrik 

Eine Fabrik ist die oberste Hierarchieebene innerhalb eines Werkes. Sie ist gekennzeichnet durch eine **FabrikID** und einen **Fabriknamen**. Darüber hinaus können Ihr verschiedene Eigenschaften sowie Globalattribute zugewiesen werden.  
Im den folgenden Abschnitten erfahren Sie alle Funktionen und Möglichkeiten im Umgang mit Fabriken.

### Übersicht Fabriken und Produktlinien

Wenn Sie sich mit einem Werk verbunden haben, gelangen Sie zur Übersicht der Fabriken und Produktlinien. Fabriken sind in der Übersicht durch dunkelblaue Balken gekennzeichnet. Die Fabrik **Templates** ist in jeder DataFactory enthalten und ist standardmäßig zugeklappt.  

![Factory Seite](images/Fabrik/die_factory_seite.png)   

### Fabrik anlegen

Um eine neue Fabrik anzulegen, gehen Sie wie folgt vor:

1. Klicken Sie in der Übersicht Fabriken und Produktlinien auf die Schaltfläche **Neue Fabrik**.  

![Factory Seite](images/Fabrik/ein_link_neue_fabrik.png)  

2. Geben Sie eine **FabrikID** und einen **Fabriknamen** ein.  

![Message box fürs Schaffen einer neuen Fabrik](images/Fabrik/anlegen_einer_neuen_fabrik.png)

**Hinweis**: Die FabrikID muss eindeutig sein und darf in jedem Werk nur einmal vorkommen.  

3. Klicken Sie auf den Button **Speichern**, um Ihre neue Fabrik zu speichern.  

![Message box fürs Schaffen einer neuen Fabrik](images/Fabrik/ein_button_speichern_beim_anlegen_einer_fabrik.png)

4. Die neue Fabrik sortiert sich alphabetisch in die Liste der Fabriken ein.  

![Factory Seite](images/Fabrik/die_factory_seite_mit_einer_frischgebackenen_fabrik.png)  

### Fabrik kopieren

Um eine bestehende Fabrik zu kopieren, gehen Sie wie folgt vor:

1. Gehen Sie zu der Fabrik, die Sie kopieren wollen und klicken Sie auf den **ActionLink**.  

![Factory Seite](images/Fabrik/ein_actionlink_einer_fabrik.png)  

2. Klicken Sie auf die Option **Kopieren**.  

![Die Optionsliste einer Fabrik](images/Fabrik/eine_option_kopieren_bei_einer_fabrik.png)   

3. Geben Sie für die Zielfabrik eine **FabrikID** und einen **Fabriknamen** ein und klicken Sie anschließend auf **Speichern**.  

![Message box fürs Kopieren einer Fabrik](images/Fabrik/speichern_einer_fabik.png) 

4. Die neue Fabrik sortiert sich in die Liste der Fabriken ein.  

![Factory Seite](images/Fabrik/sortierung_einer_kopierten_fabik.png)  

**Hinweis**: Beim Kopieren einer Fabrik werden alle zugehörigen Produktlinien und Produkte inklusive der darin enthaltenen Inhalte ebenfalls kopiert.

### Fabrik verschieben

Über die Funktion Fabrik verschieben, verschieben Sie eine Fabrik an eine andere Position innerhalb Ihres Werks. Dies geschieht durch die Änderung der **FabrikID**.  
Um eine Fabrik zu verschieben, gehen Sie wie folgt vor:

1. Gehen Sie zu der Fabrik, die Sie verschieben wollen und klicken Sie auf den ActionLink.  

![Factory Seite](images/Fabrik/ein_actionlink_einer_fabrik.png)  

2. Klicken Sie auf die Option **Verschieben**.  

![Die Optionsliste einer Fabrik](images/Fabrik/eine_option_verschieben_bei_einer_fabrik.png)   

3. Geben Sie für die Zielfabrik eine **FabrikID** ein und klicken Sie anschließend auf **Speichern**.  

![Message box für die Verschiebung einer Fabrik](images/Fabrik/verschiebung_einer_fabrik.png) 

4. Die Fabrik sortiert sich in die Liste der Fabriken ein.  

![Factory Seite](images/Fabrik/sortierung_einer_verschobenen_fabrik.png) 

### Fabrik löschen

Um eine bestehende Fabrik zu löschen, gehen Sie wie folgt vor:  

1. Gehen Sie zu der Fabrik, die Sie löschen wollen und klicken Sie auf den ActionLink.  

![Factory Seite](images/Fabrik/ein_actionlink_einer_fabrik.png)   

2. Klicken Sie auf die Option **Löschen**.  

![Die Optionsliste einer Fabrik](images/Fabrik/eine_option_löschen_bei_einer_fabrik.png)

3. Klicken Sie auf **Ja**, um die Fabrik endgültig zu löschen.  

![Message box fürs Löschen einer Fabrik](images/Fabrik/löschen_einer_fabrik.png) 

### Fabrik umbenennen

Um einer Fabrik einen neuen Namen zu geben, gehen Sie wie folgt vor:  

1. Gehen Sie zu der Fabrik, die Sie umbenennen wollen und klicken Sie auf den ActionLink.  

![Factory Seite](images/Fabrik/ein_actionlink_einer_fabrik.png)   

2. Klicken Sie auf die Option **Globalattribut editieren**.  

![Die Optionsliste einer Fabrik](images/Fabrik/eine_option_globalattribute_editieren_bei_einer_fabrik.png)  

3. Geben Sie in der Spalte **Fabrikname** einen neuen Namen für Ihre Fabrik ein und bestätigen Sie Ihre Eingabe mit dem Button **Speichern**.  

![Factory Seite mit geöffnetem Message box](images/Fabrik/umbenennen_einer_fabrik.png)  

### Globalattribute

Globalattribute sind allgemeine Merkmale, die eine Fabrik beschreiben. Jede Fabrik besitzt die Globalattribute **Verantwortlicher**, **Bildname** und **Benutzerkommentar**.  
Um die Globalttribute zu verwalten, gehen Sie wie folgt vor:  

1. Gehen Sie zu der Fabrik, dessen Globalattribute Sie verwalten wollen und klicken Sie auf den ActionLink.  

![Factory Seite](images/Fabrik/ein_actionlink_einer_fabrik.png)    

2. Klicken Sie auf die Option **Globalattribut editieren**.  

![Die Optionsliste einer Fabrik](images/Fabrik/eine_option_globalattribute_editieren_bei_einer_fabrik.png)  

3. Sie können hier nun Informationen hinzufügen oder entfernen.  

![Factory Seite mit geöffnetem Message box](images/Fabrik/globalattribute_einer_fabrik.png)    

4. Klicken Sie auf den Button **Speichern**, um Ihre Eingabe zu sichern.  

![Message box fürs Speichern Globalattribute](images/Fabrik/speichern_globalattribute.png)  

### Eigenschaften

Eigenschaften sind in DataFactory technische Steuerelemente. Sie finden vor allem dann Anwendung, wenn DataFactory mit anderen Datenquellen verbunden ist und beim Speichern bzw. Laden von Daten spezielle Aktionen ausgelöst werden sollen.

## Produktlinie

Die Produktlinien sind die zweite Hierarchieebene innerhalb eines Werkes. Unter einer Fabrik können beliebig viele Produktlinien angelegt werden.  

![Factory Seite](images/Produktlinie/übersicht_der_factory_seite_mit_prodoktlinien.png)   

Eine Produktlinie besitzt eine **ProduktlinienID** und einen **Produktliniennamen**. In Verbindung mit ihr übergeordneten Fabrik ist eine Produktlinie immer eindeutig innerhalb des Werks zu identifizieren. Darüber hinaus besitzt eine Produktlinie Globalattribute und Eigenschaften.  
In den folgenden Abschnitten wird der Umgang mit Produktlinien beschrieben.  

### Produktlinie anlegen

Um eine neue Produktlinie anzulegen, gehen Sie wie folgt vor:  

1. Gehen Sie zu der Fabrik, in der Sie eine neue Produktlinie anlegen wollen und klicken Sie auf die Schaltfläche **Neue Produktlinie**.  

![Factory Seite](images/Produktlinie/ein_link_neue_produktlinie.png)  

2. Geben Sie für die neue Produktlinie eine **ProduktlinienID** und einen **Produkliniennamen** ein und klicken Sie anschließend auf **Speichern**.  

![Message box fürs Schaffen einer Produktlinie](images/Produktlinie/schaffen_einer_neuen_produktlinie.png)   

3. Die neue Produktlinie sortiert sich alphabetisch in die Liste der bestehenden Produktlinien ein.  

![Factory Seite](images/Produktlinie/sortierung_einer_frischgebackenen_produktlinie.png)  

### Produktlinie kopieren

Um eine bestehende Produktlinie zu kopieren, gehen Sie wie folgt vor:  

1. Gehen Sie zu der Produktlinie, die Sie kopieren wollen und klicken Sie auf den ActionLink.  

![Factory Seite](images/Produktlinie/ein_actionlink_einer_produktlinie.png)   

2. Klicken Sie auf die Option **Kopieren**.  

![Die Optionliste einer Produktlinie](images/Produktlinie/eine_option_kopieren_einer_produktlinie.png)   

3. Geben Sie für die Ziel Produktlinie eine **Zielfabrik**, eine **ProduktlinienID** und einen **Produktliniennamen** ein und klicken Sie anschließend auf **Speichern**.  

![Message box fürs Kopieren einer Produktlinie](images/Produktlinie/kopieren_einer_produktlinie.png)    

4. Die neue Produktlinie sortiert sich in die Liste der Produktlinien ein.  

![Factory Seite](images/Produktlinie/sortierung_einer_kopierten_produktlinie.png)  

**Hinweis**: Beim Kopieren einer Produktlinie werden alle zugehörigen Produkte inklusive der darin enthaltenen Inhalte ebenfalls kopiert.

### Produktlinie verschieben

Über die Funktion Produktlinie verschieben, verschieben Sie eine Produktlinie an eine andere Position innerhalb Ihres Werks, d.h. Sie können Produktlinien auch zwischen verschiedenen Fabriken bewegen. Dies geschieht durch die Änderung der **ProduktlinienID**.  
Um eine Produktlinie zu verschieben, gehen Sie wie folgt vor:  

1. Gehen Sie zu der Produktlinie, die Sie verschieben wollen und klicken Sie auf den ActionLink.  

![Factory Seite](images/Produktlinie/ein_actionlink_einer_produktlinie.png)   

2. Klicken Sie auf die Option **Verschieben**.  

![Die Optionliste einer Produktlinie](images/Produktlinie/eine_option_verschieben_einer_produktlinie.png)   

3. Wählen Sie für die Produktlinie eine Zielfabrik, geben Sie eine **ProduktlinienID** ein und bestätigen Sie Ihre Eingabe mit dem Button **Speichern**.  

![Message box für die Verschiebung einer Produktlinie](images/Produktlinie/verschiebung_einer_produktlinie.png)  

4. Die verschobene Produktlinie sortiert an der entsprechend von Ihnen gewählten Stelle innerhalb Ihres Werkes ein.  

![Factory Seite](images/Produktlinie/sortierung_einer_verschobenen_produktlinie.png)   

### Produktlinie löschen

Um eine bestehende Produktlinie zu löschen, gehen Sie wie folgt vor:  

1. Gehen Sie zu der Produktlinie, die Sie löschen wollen und klicken Sie auf den ActionLink.  

![Factory Seite](images/Produktlinie/ein_actionlink_einer_produktlinie-2.png)   

2. Klicken Sie auf die Option **Löschen**.  

![Die Optionliste einer Produktlinie](images/Produktlinie/eine_option_löschen_einer_produktlinie.png)    

3. Klicken Sie auf **Ja**, um die Produktlinie endgültig zu löschen.  

![Message box fürs Löschen einer Produktlinie](images/Produktlinie/löschen_einer_produktlinie.png)   

### Produktlinie umbenennen

Um einer Produktlinie einen neuen Namen zu geben, gehen Sie wie folgt vor: 

1. Gehen Sie zu der Produktlinie, die Sie umbenennen wollen und klicken Sie auf den ActionLink.  

![Factory Seite](images/Produktlinie/ein_actionlink_einer_produktlinie-2.png)   

2. Klicken Sie auf die Option **Globalattribut editieren**.  

![Die Optionliste einer Produktlinie](images/Produktlinie/eine_option_globalattribut_editieren_einer_produktlinie.png)  

3. Geben Sie im Feld **Produktlinienname** einen neuen Namen für Ihre Produktlinie ein und bestätigen Sie Ihre Eingabe mit dem Button **Speichern**.  

![Factory Seite mit Message box Globalattribut editieren für eine Produktlinie](images/Produktlinie/umbenennen_einer_produktlinie.png)   

### Globalattribute  

Jede Produktlinie besitzt die Globalattribute **Verantwortlicher**, **Bildname** und **Benutzerkommentar**. Darüber hinaus können für jede Produktlinie 25 weitere Globalattribute konfiguriert werden. Diese dienen in späteren Auswertungen als Hierarchie- oder Gliederungsebenen.  
Um Globalattribute zu verwalten, gehen Sie wie folgt vor:  

1. Gehen Sie zu der Produktlinie, dessen Globalattribute Sie verwalten wollen und klicken Sie auf den ActionLink.  

![Factory Seite](images/Produktlinie/ein_actionlink_einer_produktlinie-2.png)   

2. Klicken Sie auf die Option **Globalattribut editieren**.  

![Die Optionliste einer Produktlinie](images/Produktlinie/eine_option_globalattribut_editieren_einer_produktlinie.png)  

3.	Sie können im oberen Bereich Informationen zu den 3 vordefinierten Globalattributen hinzufügen oder entfernen.  

![Factory Seite mit Message box Globalattribut editieren für eine Produktlinie](images/Produktlinie/verwaltung_globalattribute_einer_produktlinie.png)   

**Hinweis**: Vergeben Sie in allen Produktlinien, die Sie gemeinsam auswerten wollen ein Globalattribut an gleicher Position (z.B. Kostenstelle als Globalattribut 1 in allen Produktlinien).  

4. Im unteren Bereich können Sie bis zu 25 eigene Globalattribute definieren, indem Sie einen Namen geben und ggf. eine Liste zuordnen.  

![Factory Seite mit Message box Globalattribut editieren für eine Produktlinie](images/Produktlinie/25_globalattribute_einer_produktlinie.png)   

5. Klicken Sie auf den Button **Speichern**, um Ihre Eingabe zu sichern.  

![Factory Seite mit Message box Globalattribut editieren für eine Produktlinie](images/Produktlinie/ein_button_speichern_in_globalattributen_einer_produktlinie.png)  

### Eigenschaften

Eigenschaften sind in DataFactory technische Steuerelemente. Sie finden vor allem dann Anwendung, wenn DataFactory mit anderen Datenquellen verbunden ist und beim Speichern bzw. Laden von Daten spezielle Aktionen ausgelöst werden sollen.

## Produkt

Ein Produkt ist in DataFactory ein datentragendes Objekt. In einem Produkt werden die konkreten Daten durch Sie erfasst. Ein Produkt besitzt eine **ProduktID** und einen **Produktnamen**. In Verbindung mit der ihm übergeordneten Produktlinie und Fabrik ist ein Produkt eindeutig innerhalb eines Werks zu identifizieren. Darüber hinaus besitzt ein Produkt einen Status, welcher über eine zentral im Werk hinterlegte Liste gesteuert werden kann sowie das Attribut **ResponsbilePerson**.  
Jedes Produkt basiert auf einem Template, d.h. auf einer Vorlage aus der es entstanden ist.  
Wenn Sie in eine Produktlinie hineingehen, gelangen Sie zur Übersicht der Produkte. In der Übersicht sehen Sie die in der Produktlinie definierten Globalattribute.  

![Die Seite einer Produktlinie mit Produkten](images/Produkt/die_liste_von_produkten_einer_produktlinie.png)   

In dieser Ansicht haben Sie die Möglichkeit, die Globalattribute mit Informationen zu füllen.  

### Neues Produkt anlegen  

Ein neues Produkt basiert immer auf einem bestehenden Produkt, in der Regel auf einem Template.  
Um ein neues Produkt anzulegen, gehen Sie wie folgt vor:  

1. Gehen Sie in die Produktlinie, in der Sie ein neues Produkt erstellen wollen.  

![Factory Seite](images/Produkt/auswahl_einer_produktlinie.png)    

2. Klicken Sie auf die Schaltfläche **Neues Produkt**.  

![Die Seite einer Produktlinie mit Produkten](images/Produkt/die_liste_von_produkten_einer_produktlinie.png)   

3.	Wählen Sie ein Quelltemplate aus, in dem Sie die entsprechende Fabrik, die entsprechende Produktlinie und das entsprechende Produkt auswählen.  

![Message box für die Erzeugung eines neuen Produktes](images/Produkt/erzeugen_eines_neuen_produktes.png)     

4. Geben Sie für Ihr Zielprodukt eine **ProduktID** und einen **Produktnamen** ein.  

![Message box für die Erzeugung eines neuen Produktes](images/Produkt/erzeugen_eines_neuen_produktes-2.png)     

5. Klicken Sie auf **Anwenden**, um das neue Produkt anzulegen.  

![Message box für die Erzeugung eines neuen Produktes](images/Produkt/erzeugen_eines_neuen_produktes-3.png)   

6. Das neue Produkt sortiert sich automatisch in die Liste der Produkte ein.  

![Die Seite einer Produktlinie mit Produkten](images/Produkt/sortierung_eines_neuen_produktes.png)  

### Produkt kopieren

Um ein bestehendes Produkt zu kopieren, gehen Sie wie folgt vor:  

1. Gehen Sie zu dem Produkt, das Sie kopieren wollen und klicken Sie auf den ActionLink in der Spalte Action.  

![Die Seite einer Produktlinie mit Produkten](images/Produkt/ein_actionlink_eines_produktes.png)  

2. Klicken Sie auf die Option **Kopieren**.  

![Die Optionsliste eines Produktes](images/Produkt/eine_option_kopieren_von_einem_produkt.png)   

3. Wählen Sie für Ihr Zielprodukt eine **Zielfabrik** und **Zielproduktlinie** aus.  

![Message box fürs Kopieren eines Produktes](images/Produkt/kopieren_eines_produktes.png)   

4. Geben Sie für Ihre Zielprodukt eine **ProduktID** und einen **Produktnamen** ein.  

![Message box fürs Kopieren eines Produktes](images/Produkt/kopieren_eines_produktes-2.png)

5. Klicken Sie auf **Anwenden**, um das Produkt zu kopieren.  

![Message box fürs Kopieren eines Produktes](images/Produkt/kopieren_eines_produktes-3.png) 

6. Das neue Produkt sortiert sich automatisch in die Liste der Produkte ein.  

![Die Seite einer Produktlinie mit Produkten](images/Produkt/sortierung_eines_kopierten_produktes.png)  

### *Mehrfachkopie*  

DataFactory bietet die Möglichkeit, gleichzeitig mehrere Kopien eines Produkts anzulegen.  
Um mehrere Kopien gleichzeitig anzulegen, gehen Sie wie folgt vor:  

1. Gehen Sie zu dem Produkt, das Sie kopieren wollen und klicken Sie auf den ActionLink in der Spalte Action.  

![Die Seite einer Produktlinie mit Produkten](images/Produkt/ein_actionlink_eines_produktes.png)  

2. Klicken Sie auf die Option **Kopieren**.  

![Die Optionsliste eines Produktes](images/Produkt/eine_option_kopieren_von_einem_produkt.png) 

3. Wählen Sie für Ihr Zielprodukt eine **Zielfabrik** und **Zielproduktlinie** aus.  

![Message box fürs Kopieren eines Produktes](images/Produkt/kopieren_eines_produktes.png)   

4. Klicken Sie auf den Reiter **Serienkopie**.  

![Message box fürs Kopieren eines Produktes](images/Produkt/eine_option_serienkopie_beim_kopieren_eines_produktes.png)   

5. Geben Sie im Feld **Produktname mit optionalem Platzhalter (#)** einen Produktnamen für Ihre Kopien ein.  

![Message box fürs Kopieren eines Produktes](images/Produkt/eine_option_serienkopie_beim_kopieren_eines_produktes-2.png)   

**Hinweis**: Das # - Symbol ist in DataFactory ein Platzhalter. Sie können dem Produktnamen optional einen Platzhalter hinzufügen, um bspw. eine fortlaufende Nummerierung zu erstellen.  

6. Geben Sie im Feld **Anzahl** die Anzahl Ihrer gewünschten Kopien ein und im Feld **Erste Nummer** die erste Nummer Ihrer gewünschten Kopien ein.  

![Message box fürs Kopieren eines Produktes](images/Produkt/eine_option_serienkopie_beim_kopieren_eines_produktes-3.png)  

7. Geben Sie im Feld **Produkt ID mit Platzhalter (#)** das gewünschte Format Ihrer Produkt ID ein.  

![Message box fürs Kopieren eines Produktes](images/Produkt/eine_option_serienkopie_beim_kopieren_eines_produktes-4.png) 

**Hinweis**: Im Feld ProduktID Vorschau sehen Sie einer Vorschau Ihrer getätigten Eingaben.  

8. Klicken Sie auf die Schaltfläche **Anwenden**, um die Kopien zu erstellen.  

![Message box fürs Kopieren eines Produktes](images/Produkt/eine_option_serienkopie_beim_kopieren_eines_produktes-5.png) 

9. Die erstellten Kopien sortieren sich in die bestehende Liste der Produkte ein.  

![Die Seite einer Produktlinie mit Produkten](images/Produkt/sortierung_kopierter_produkte.png)  

### Produkt verschieben  

Über die Funktion **Produkt verschieben** verschieben Sie ein Produkt an eine andere Position innerhalb Ihres Werks, d.h. Sie können Produkte auch zwischen verschiedenen Fabriken und Produktlinien bewegen.  

1. Gehen Sie zu dem Produkt, das Sie verschieben wollen und klicken Sie auf den ActionLink in der Spalte **Action**.  

![Die Seite einer Produktlinie mit Produkten](images/Produkt/ein_actionlink_eines_produktes.png)  

2. Klicken Sie auf die Option **Verschieben**.  

![Die Optionsliste eines Produktes](images/Produkt/eine_option_verschieben_eines_produktes.png) 

3. Wählen den Zielort aus, in dem Sie eine **Zielfabrik** und eine **Zielproduktlinie** auswählen.  

![Message box für die Verschiebung eines Produktes](images/Produkt/verschiebung_eines_produktes.png) 

4. Geben Sie eine **ProduktID** ein.  

![Message box für die Verschiebung eines Produktes](images/Produkt/verschiebung_eines_produktes-2.png)  

5. Klicken Sie auf **Anwenden**, um das Produkt zu verschieben.  

![Message box für die Verschiebung eines Produktes](images/Produkt/verschiebung_eines_produktes-3.png)  

6. Das verschobene Produkt sortiert sich automatisch mit der neuen ProduktID in die Liste der Produkte ein.  

![Die Seite einer Produktlinie mit Produkten](images/Produkt/sortierung_verschobener_produkte.png)  

### Produkt löschen  

1. Gehen Sie zu dem Produkt, das Sie löschen möchten und klicken Sie auf den ActionLink in der Spalte **Action**.  

![Die Seite einer Produktlinie mit Produkten](images/Produkt/ein_actionlink_eines_produktes_zum_löschen.png)  

2. Klicken Sie auf die Option **Löschen**.  

![Die Optionsliste eines Produktes](images/Produkt/eine_option_löschen_eines_produktes.png) 

3. Klicken Sie auf **Ja**, um das Produkt endgültig zu löschen.  

![Message box fürs Löschen eines Produktes](images/Produkt/löschen_eines_produktes.png)  

**Hinweis**: Das Löschen kann nicht rückgängig gemacht werden.  

### *Mehrfachlöschen*  

Um mehrere Produkte gleichzeitig zu löschen, gehen Sie wie folgt vor:  

1. Klicken Sie in der Übersicht der Produkte auf den ActionLink über der Spalte **Action**.  

![Die Seite einer Produktlinie mit Produkten](images/Produkt/ein_actionlink_einer_produktlinie.png)    

2. Klicken Sie auf die Option **Mehrfachlöschen**.  

![Die Optionsliste einer Produktlinie](images/Produkt/eine_option_mehrfachlöschen_auf_einer_produktlinienseite.png) 

3. Markieren Sie die Produkte, die Sie löschen wollen.  

![Message box fürs Mehrfachlöschen von Produkten](images/Produkt/mehrfachlöschen_von_produkten.png)    

4. Klicken Sie auf **Löschen all selektierten Produkte**, um die ausgewählten Produkte zu löschen. 

![Message box fürs Mehrfachlöschen von Produkten](images/Produkt/mehrfachlöschen_von_produkten-2.png)     

5. Klicken Sie auf **Ja**, um die Produkte endgültig zu löschen.  

![Message box fürs Mehrfachlöschen von Produkten](images/Produkt/mehrfachlöschen_von_produkten-3.png)   

### *PowerLaden*  

Die Funktion **PowerLaden** kommt insbesondere dann zur Anwendung, nachdem Sie Daten aus anderen Anwendungen in DataFactory importiert haben und diese als Grundlage für weitere Berechnungen dienen. Die Funktion **PowerLaden** betritt jedes Produkt, berechnet es und speichert es ab. Es stehen Ihnen folgende Möglichkeiten des PowerLadens zur Verfügung.  

[Bild - eine Tabelle!] 

Um die Funktion **PowerLaden** auszuführen, gehen Sie wie folgt vor: 

1. Klicken Sie in der Übersicht Ihrer Produkte auf den ActionLink über der Spalte Action und wählen Sie die Option **PowerLaden**.  

![Die Optionsliste einer Produktlinie](images/Produkt/eine_option_powerladen_auf_einer_produktlinienseite.png) 

2. Markieren die Produkte, die Sie aktualisieren wollen.  

![Message box fürs Powerladen von Produkten](images/Produkt/powerladen_von_produkten.png) 

3. Wählen Sie im Dropdown Menü Ihre gewünschte Einstellung.   

![Message box fürs Powerladen von Produkten](images/Produkt/powerladen_von_produkten-2.png)   

4. Klicken Sie auf **Ausführen**, um die Funktion auszuführen.  

![Message box fürs Powerladen von Produkten](images/Produkt/powerladen_von_produkten-3.png)  

5. Nach dem Ausführen sehen Sie den Status der geladenen Produkte.

![Message box fürs Powerladen von Produkten](images/Produkt/der_produktstatus_nach_dem_powerladen.png)

## Templates  

Templates sind Produkte, die mit Ziel geschaffen werden, als Vorlage für weitere Produkte zu dienen. Aus technischer Sicht sind Templates und Produkte völlig identisch. Templates und Produkte verhalten sich zueinander wie eine Vorlage und eine Kopie (oder aus Sicht eines Programmierers: wie Klasse und Instanz). Nach der Erstellung ist die Kopie unabhängig, d.h. sie kann verändert werden und ändert sich nicht automatisch, wenn sich das Template ändert.  
Es empfiehlt sich, thematische zusammengehörige Templates in jeweils separaten Produktlinien zu organisieren.  

### Unikum Templates  

Unikum Templates sind die allgemeinste Form von Templates. Sie sind standardmäßig Bestandteil jeder DataFactory und im Werk **Templates** in der Produktlinie **Unikum** organisiert.  

![Factory Seite](images/Templates/unikum_templates_auf_der_factory_seite.png)

Es stehen Ihnen standardmäßig folgende Templates zur Verfügung:  

* •	Unikum für Monatswerte 2016-2020
* •	Unikum für Tageswerte 2016-2017
* •	Unikum für Werktageswerte 2016-2017
* •	Unikum für 3 Tage pro Monat 2016-2017 
* •	Unikum für Wochenwerte 2016-2017 
* •	Unikum für Jahreswerte 1970-2060 
* •	Einfache Liste
* •	Gruppierte Liste  

Sie betreten ein Template, indem Sie auf den Namen des Template klicken.  

### Allgemeiner Aufbau  

Ein Template besteht strukturell immer aus 3 wesentlichen Bestandteilen: Zeitachse, Wertreihe und Wertebereich.  

![Struktur von eines Template](images/Templates/struktur_von_eines_template.png) 

### *Zeitachse* 

Die Zeitachse eines Template bestimmt den Detailgrad der zeitlichen Dimension bei der Erfassung der Werte (z.B. Erfassung von Daten auf Tages-, Monats oder Jahresbasis).  

![Die Produktseite eines Template](images/Templates/horizontale_zeitachse_eines_template.png)   

**Hinweis**: Die Zeitachse ist nicht an einen Kalender gebunden, sondern sie ist vollkommen individuell konfigurierbar.   

Bei der Erfassung von zeitunabhängigen Daten ist die Zeitachse eine sog. Pseudozeitachse und ermöglicht die Erfassung von Listen.  

![Die Produktseite eines Template](images/Templates/vertikale_zeitachse_eines_template.png)  

### *Wertreihe*

Wertreihen definieren die Charaktereigenschaften der Werte, die Sie später in den Wertebereich eingeben. In der Standardansicht eines Template sehen Sie den Namen und die ID einer Wertreihe.  

![Die Produktseite eines Template](images/Templates/die_wertereihe_eines_template.png)  

Jede Wertreihe besitzt eine Reihe von Eigenschaften und Optionen.  

[Bild - Tabelle!]    

Die Eigenschaften und Optionen werden durch das Klicken auf die Schaltfläche **Details zeigen** sichtbar.  

![Die Produktseite eines Template](images/Templates/eine_option_details_zeigen_auf_der_produktseite_eines_tepmlate.png)    

### *Wertebereich*  

Der Wertebereich ist der Bereich, indem die konkreten Daten erfasst werden. 

![Die Produktseite eines Template](images/Templates/der_wertebereich_eines_template.png) 

Je nachdem wie die Wertreihen definiert sind, können Sie hier frei Daten eingeben und erfassen. Es können sämtliche Excel Formeln genutzt werden.  
**Hinweis**: Formeln werden in den Wertreihen nur gespeichert, wenn die Wertreihe vom Typ XLS oder XLS-Strict definiert ist. Andernfalls werden nur die Werte gespeichert.  

### *Orientierung und Namenskonvention*  

Ein Template ist entweder horizontal oder vertikal orientiert. Die Orientierung basiert auf einer Namenskonvention und wird durch das angehängte Suffix bestimmt.   

![Die Seite der Produktlinie von Templates mit Produkten](images/Templates/suffixe_der_templateorientierung.png) 

Das Suffix hat sowohl Auswirkung auf die Orientierung als auch auf die Zeitachse und wird an den Namen des Template mit einem „_“ angehangen. Der erste Buchstabe definiert die Orientierung, der zweite Buchstabe den Detailgrad bei der Anzeige der Zeitachse.  

[Bild - eine Tabelle!]  

**Hinweis**: Es besteht jederzeit die Möglichkeit, das Template zu drehen. Allerdings erlaubt nur die Default-Ansicht das speichern.  

### Template anlegen 

Um ein neues Template anzulegen, gehen Sie wie folgt vor:

1. Gehen Sie zur Fabrik **Templates** und klicken Sie auf die Produktlinie, in der Sie ein neues Template anlegen wollen.  

![Die Fabrik Templates](images/Templates/auswahl_einer_produktlinie_von_templates.png) 

**Hinweis**: Aus Gründen der Übersichtlichkeit, bietet es sich an, eigene Templates in separaten Produktlinien zu speichern.  

2. Klicken Sie auf die Schaltfläche **Neues Produkt**. 

![Die Seite der Produktlinie von Templates mit Produkten](images/Templates/ein_link_neues_produkt.png)   

3. Wählen Sie ein bestehendes Template aus, aus dem Ihr neues Template entstehen soll.  

![Message box fürs Schaffen eines neuen Template](images/Templates/schaffen_eines_neuen_template.png) 

4. Geben Sie für Ihr neues Template eine **ProduktID** und einen **Produktnamen** ein und klicken Sie auf den Button **Anwenden**, um Ihr Template zu erzeugen. 

![Message box fürs Schaffen eines neuen Template](images/Templates/schaffen_eines_neuen_template-2.png) 

5. Das neue Template wurde erstellt. 

![Die Seite der Produktlinie von Templates mit Produkten](images/Templates/das_geschaffte_template_in_der_liste_von_templates.png)  

**Hinweis**: Es wird empfohlen in der Spalte Template dem neuen Template einen eindeutigen und aussagekräftigen Namen zu geben. Dies ist wichtig, wenn Sie später aus Ihrem Template neue Produkte erzeugen wollen und deren Klasse später wiedererkennen wollen.  

### Template konfigurieren  

Sie können jedes Template individuell gestalten und konfigurieren. Um ein Template zu konfigurieren, müssen Sie das Template betreten und auf die Schaltfläche **Details zeigen** klicken.  

![Die Produktseite eines Template](images/Templates/eine_option_details_zeigen_auf_der_produktseite_eines_tepmlate-2.png)

Im Folgenden sind die Funktionen für die Konfiguration von Templates beschrieben. Die Beschreibung der Funktionen beziehen sich auf ein Template mit vertikaler Zeitachse. Das Vorgehen bei horizontaler Zeitachse ist analog.  

### *Neue Wertreihe anlegen*

Um eine neue Wertreihe anzulegen, gehen Sie wie folgt vor:  

1. Klicken Sie in der Zeile **Aktion** auf den ActionLink.  

![Die Produktseite eines Template](images/Templates/der_actionlink_einer_wertreihe.png)   

2. Klicken Sie auf die Option **Neu davor**, wenn Sie eine neue Spalte vor der aktuellen Spalte oder auf die Option **Neu danach**, wenn Sie eine neue Spalte nach der aktuellen Spalte anlegen wollen.

![Die Optionsliste einer Wertereihe](images/Templates/optionen_neu_davor_neu_danach_einer_wertreihe.png)   

3. Eine neue Wertreihe wurde eingefügt. Klicken Sie auf die Schaltfläche **Speichern**, um die Wertreihe zu sichern.  

![Die Produktseite eines Template](images/Templates/der_link_speichern_eines_template.png)     

### *Wertreihe löschen*  

Um eine Wertreihe zu löschen, gehen Sie wie folgt vor:

1. Klicken Sie in der Spalte, die Sie löschen wollen auf den ActionLink in der Zeile **Aktion**.  

![Die Produktseite eines Template](images/Templates/der_actionlink_einer_wertreihe.png)     

2. Klicken Sie auf die Option **Wertreihe löschen**.  

![Die Optionsliste einer Wertereihe](images/Templates/eine_option_wertreihe_löschen.png)

3. Die Wertreihe ist nun zu löschen markiert (rot straffiert). Um die Wertreihe endgültig zu löschen, klicken Sie auf die Schaltfläche **Speichern**.  

![Die Produktseite eines Template](images/Templates/löschen_einer_wertreihe.png)    

### *Wertreihe kopieren*  

1. Klicken Sie in der Spalte, die Sie kopieren wollen auf den ActionLink in der Zeile **Aktion**.  

![Die Produktseite eines Template](images/Templates/der_actionlink_einer_wertreihe.png)      

2. Klicken Sie auf die Option **Mehrfachkopie**.  

![Die Optionsliste einer Wertereihe](images/Templates/eine_option_mehrfachkopie_einer_wertreihe.png)

3. Geben Sie die Zeile bzw. Spalte ein, vor der Sie die Kopie/n einfügen wollen und geben Sie die Anzahl der Kopien, die Sie erstellen wollen.  

![Message box fürs Kopieren einer Wertreihe](images/Templates/kopieren_einer_wertreihe.png) 

4. Klicken Sie auf den Button **Kopieren**, um die Kopien einzufügen.  

![Message box fürs Kopieren einer Wertreihe](images/Templates/kopieren_einer_wertreihe-2.png) 

5. Klicken Sie auf die Schaltfläche **Speichern**, um Ihre Kopien endgültig zu speichern.  

![Die Produktseite eines Template](images/Templates/kopieren_einer_wertreihe.png)    

### *Wertreihe verschieben*  

Um eine Wertreihe zu verschieben, gehen Sie wie folgt vor:  

1. Klicken Sie in der Spalte, die Sie verschieben wollen auf den ActionLink in der Zeile **Aktion**.  

![Die Produktseite eines Template](images/Templates/der_actionlink_einer_wertreihe.png)  

2. Klicken Sie auf die Option **Ausschneiden**.  

![Die Optionsliste einer Wertereihe](images/Templates/eine_option_ausschneiden_einer_wertreihe.png)

3. Klicken Sie in der Spalte, in die Sie die Wertreihe verschieben auf den ActionLink in der Zeile **Aktion** und klicken Sie auf die Option **Davor einfügen**, wenn Sie die Spalte vor die gewählte Spalte verschieben wollen oder klicken Sie auf die Option **Danach einfügen**, wenn Sie die Spalte nach der gewählten Spalte einfügen wollen.  

![Die Optionsliste einer Wertereihe](images/Templates/optionen_davor_einfügen_danach_einfügen.png)

4. Klicken Sie auf die Schaltfläche **Speichern**, um Ihre Änderung zu sichern.  

![Die Produktseite eines Template](images/Templates/verschiebung_einer_wertreihe.png)   

### *IDs ändern* 

Um die IDs Ihrer Wertreihen zu ändern, gehen Sie wie folgt vor: 

1. Klicken Sie in der Spalte, deren ID Sie ändern wollen auf den ActionLink in der Zeile **Aktion**.  

![Die Produktseite eines Template](images/Templates/der_actionlink_einer_wertreihe.png)   

2. Klicken Sie auf die Option **IDs bearbeiten**.  

![Die Optionsliste einer Wertereihe](images/Templates/eine_option_ids_bearbeiten.png) 

3. Sie sehen im Dialog **SerienID Editor** die aktuelle ID und den Kurznamen. Geben Sie in der Spalte Neue ID ihre neuen IDs ein.  

![Message box SerienID Editor](images/Templates/serienid_editor.png) 

4. Klicken Sie auf die Schaltfläche **Anwenden**, um die neuen IDs zu speichern.  

![Message box SerienID Editor](images/Templates/speichern_neue_ids.png)   

### *Herkunft ändern*  

Um die Herkunft einer Wertreihe zu ändern, gehen Sie wie folgt vor:

1. Gehen Sie zu der Wertreihe, deren Herkunft Sie ändern möchten, öffnen Sie in der Zeile **Herkunft** das Dropdown Menü und wählen Sie Ihre gewünschte Herkunft aus.  

![Die Produktseite eines Template](images/Templates/optionen_der_herkunft_auf_der_template_seite.png)   

2. Klicken Sie auf die Schaltfläche **Speichern**, um Ihre Auswahl zu speichern.  

![Die Produktseite eines Template](images/Templates/speichern_herkunftsänderungen.png)    

### *(betriebswirtschaftlichen) Effekt ändern*  

Um den betriebswirtschaftlichen Effekt einer Wertreihe zu ändern, gehen Sie wie folgt vor:  

1. Gehen Sie zu der Wertreihe, deren Effekt Sie ändern möchten, öffnen Sie in der Zeile **Effekt** das Dropdown Menü und wählen Sie Ihren gewünschten Effekt aus.  

![Die Produktseite eines Template](images/Templates/optionen_des_effekts_auf_der_template_seite.png)   

**Hinweis**: Eine Beschreibung der betriebswirtschaftlichen Effekte finden Sie in Kapitel 3.5.2.  

2. Klicken Sie auf die Schaltfläche **Speichern**, um Ihre Auswahl zu speichern.  

![Die Produktseite eines Template](images/Templates/speichern_effektänderungen.png)  

### *Werteliste hinzufügen*  

1. Gehen Sie zu der Wertreihe, der Sie eine Liste zuordnen möchten, öffnen Sie in der Zeile **Werteliste** das Dropdown Menü und wählen Sie Ihre gewünschte Liste aus.  

![Die Produktseite eines Template](images/Templates/optionen_der_werteliste.png)   

**Hinweis**: Es stehen Ihnen standardmäßig eine Reihe von Listen zur Verfügung. Sie können jedoch auch eigen Listen anlegen (vgl. Kap. 3.6).  

2. Klicken Sie auf die Schaltfläche **Speichern**, um Ihre Auswahl zu speichern.  

![Die Produktseite eines Template](images/Templates/speichern_wertelistenänderungen.png)  

### *Werteformat ändern* 

Um das Werteformat einer Wertereihe zu ändern, gehen Sie wie folgt vor:  

1. Gehen Sie zu der Wertreihe, deren Werteformat Sie ändern möchten, öffnen Sie in der Zeile **Werteformat** das Dropdown Menü und wählen Sie Ihr gewünschtes Werteformat aus.  

![Die Produktseite eines Template](images/Templates/optionen_des_werteformats.png)  
 
**Hinweis**: Es stehen Ihnen standardmäßig eine Reihe von Werteformaten zur Verfügung. Sie können jedoch auch eigene Werteformate anlegen (vgl. Kap. 3.6).  

2. Klicken Sie auf die Schaltfläche **Speichern**, um Ihre Auswahl zu speichern.  

![Die Produktseite eines Template](images/Templates/speichern_werteformatänderungen.png)  

### *Spaltenbreite ändern*  

Um die Breite einer Spalte zu ändern, gehen Sie wie folgt vor:  

1. Gehen Sie zur der Wertreihe, deren Breite Sie ändern wollen, öffnen Sie in der Zeile **Parameter** das Dropdown Menü und wählen Sie Ihre gewünschte Spaltenbreite.  

![Die Produktseite eines Template](images/Templates/optionen_des_parameters.png) 

**Hinweis**: Sie können neben der Auswahl über das Dropdown Menü auch Ihre gewünschte Spaltenbreite frei eingeben. 

2. Klicken Sie auf die Schaltfläche **Speichern**, um Ihre Auswahl zu speichern.  

### *Spalte (Wertreihe) ausblenden*  

Sie können Wertreihen ausblenden, sodass diese bei eingeklappten Details nicht zu sehen ist.  
Um eine Spalte auszublenden, gehen Sie wie folgt vor:  

1. Gehen Sie zu der Wertreihe, die Sie ausblenden wollen und wählen Sie in der Zeile **Sichtbarkeitsstufe** den Wert „0“.   

![Die Produktseite eines Template](images/Templates/optionen_der_sichtbarkeitsstufe.png) 

2. Klicken Sie auf die Schaltfläche **Speichern**, um Ihre Auswahl zu speichern.  

![Die Produktseite eines Template](images/Templates/speichern_sichstbarkeitsänderungen.png)   

### *Excel-Formel im Template verwenden*  

Sie können bereits beim Design Ihres Templates Excel-Formeln nutzen.   
Um Excel-Formeln in Ihr Template zu integrieren, gehen Sie wie folgt vor:  

1. Gehen Sie zu der Wertreihe, in der Sie eine Excel-Formel verwenden wollen und öffnen Sie in der Zeile **Herkunft** das Dropdown Menü.  

![Die Produktseite eines Template](images/Templates/dropdown_menü_mit_excel-formeln.png) 

2. Wählen Sie die Einstellung **XLS** oder **XLS-Strict** und klicken Sie auf **Speichern**, um Ihre Änderung zu speichern.  

![Die Produktseite eines Template](images/Templates/speichern_formeländerungen.png)  

**Hinweis**: Wie Sie später bei der Dateneingabe die Möglichkeit haben wollen, die Formel zu überschreiben, wählen Sie die Einstellung XLS. Soll die Formel schreibgeschützt sein, wählen Sie die Einstellung XLS-Strict.  

3. Gehen Sie nun in die erste Zeile Ihres Wertebereichs und geben Sie Ihre gewünschte Formel ein.  

![Die Produktseite eines Template](images/Templates/eingeben_einer_formel.png)  

4. Kopieren Sie die Excel-Formel bis ans Ende Ihrer Zeitachse.  

![Ein Teil des Wertebereiches eines Template](images/Templates/kopieren_einer_formel.png)  

5. Klicken Sie auf die Schaltfläche **Speichern**, um Ihre Eingabe zu sichern.  

![Ein Link Speichern auf der Produktseite eines Template](images/Templates/speichern_einer_neuen_formel.png)    

**Hinweis**: Sie können all ihre bekannten Excel-Formeln in gewohnter Art und Weise nutzen.  

### Solutions  

Solutions sind branchenspezifische Musterlösung für DataFactory und beinhalten eine Reise von vordefinierten Templates für ausgewählte Anwendungsfälle.  
Derzeit existieren Solutions für folgende Anwendungsbereiche:  

* •	Personalverwaltung
* •	Vertragsverwaltung  
* •	Kreditverwaltung 
* •	Fuhrparkverwaltung
* •	Windparkverwaltung

Weitere Solutions sind in der kontinuierlichen Entwicklung.  

## Listen und Formate  

Listen und Formate werden in DataFactory zentral für ein Werk verwaltet und sind in allen Hierarchieebenen gleichermaßen einsetzbar. Es existieren in DataFactory jeweils 3 Typen von Listen, die jeweils durch ein bestimmtes Präfix gekennzeichnet sind.  
**Hinweis**: Legen Sie eigene Listen und Formate immer mit dem Präfix c an. 

[Bild - eine Tabelle!
] 
Wie Sie ihre Listen und Formate verwalten können, erfahren Sie im folgenden Abschnitt.  

## Neue Liste anlegen  

Um eine neue Liste anzulegen, gehen Sie wie folgt vor:  

1. Gehen Sie zur Übersicht Fabriken und Produktlinien und klicken Sie auf den ActionLink **Dieses Werk verwalten**.  

![Factory Seite](images/Listen und Formate/ein_link_dieses_werk_verwalten.png)  

2. Klicken Sie auf die Option **Listen editieren**.  

![Die Optionsliste des Links Dieses Werk verwalten](images/Listen und Formate/eine_option_listen_editieren.png) 

3. Klicken Sie auf die Schaltfläche **Neue Liste**.  

![Die Seite vom Listeneditor](images/Listen und Formate/ein_link_neue_liste.png)   

4. Geben Sie in der Spalte **ListID** eine ListeID ein.  

![Die Seite vom Listeneditor](images/Listen und Formate/schaffen_einer_neuen_listeid.png)    

**Hinweis**: Achten Sie bei der Eingabe auf die Verwendung des korrekten Präfixes.  

5. Fügen Sie der Liste ggf. weitere Einstellungen hinzu (**NameShort**, **CommentUser**) und ändern Sie ggf. den Datentyp.  

![Die Seite vom Listeneditor](images/Listen und Formate/schaffen_einer_neuen_listeid-2.png)    

6. Klicken Sie auf die Schaltfläche **Speichern**.  

![Die Seite vom Listeneditor](images/Listen und Formate/ein_link_speichern_vom_listeneditor.png)      

7. Die Liste ordnet sich automatisch in die Übersicht der Listen ein.  

![Die Seite vom Listeneditor](images/Listen und Formate/sortierung_einer_frischgebackenen_liste.png)    

**Hinweis**: Sie haben nun eine neue Liste angelegt. Diese enthält allerdings noch keine Werte.  
Wenn Sie diese Liste in einem Template verwenden wollen, müssen Sie die Liste noch sichtbar machen.  

### *Werte zu einer Liste hinzufügen*   

Um Werte zu einer Liste hinzuzufügen, gehen Sie wie folgt vor:  

1. Klicken Sie auf die Liste, zu der Sie Werte hinzufügen wollen.  

![Die Seite vom Listeneditor](images/Listen und Formate/eine_liste_im_listeneditor.png)    

2. Klicken Sie auf die Schaltfläche **Neuer Eintrag** und geben Sie in der Spalte **ValueText** Ihren neuen Wert ein.  

![Die Seite vom Listeneditor mit der Wertetabelle einer Liste](images/Listen und Formate/die_wertetabelle_einer_liste_auf_der_seite_vom_listeneditor.png)    

3. Geben Sie ggf. in die Spalte **ValueComment** einen Kommentar und in die Spalte **FormatID** das gewünschte Format ein.  

![Die Seite vom Listeneditor mit der Wertetabelle einer Liste](images/Listen und Formate/die_wertetabelle_einer_liste_auf_der_seite_vom_listeneditor-2.png)   

4. Klicken Sie auf die Schaltfläche **Speichern**.  

![Die Seite vom Listeneditor mit der Wertetabelle einer Liste](images/Listen und Formate/speichern_wertetabelleänderungen.png)    

### *Werte aus einer Liste löschen*   

Um Werte aus einer Liste zu löschen, gehen Sie wie folgt vor:  

1. Klicken Sie auf die Liste, aus der Sie Werte löschen wollen.  

![Die Seite vom Listeneditor](images/Listen und Formate/auswahl_einer_liste.png)    

2. Klicken Sie auf den ActionLink des Wertes, den Sie löschen möchten und klicken Sie auf die Option **Löschen**.  

![Die Seite vom Listeneditor mit der Wertetabelle einer Liste](images/Listen und Formate/eine_option_löschen_in_der_wertetabelle.png) 

3. Klicken Sie auf **Ja**, um den Wert endgültig zu löschen.  

![Message box fürs Löschen Werte aus der Wertetabelle](images/Listen und Formate/löschen_werte_aus_der_wertetabelle.png) 

**Hinweis**: Wenn Sie einen Wert löschen, der an irgendeiner Stelle Ihrer Factory verwendet wird, so bleibt der Wert bestehen. Das Löschen eines Wertes aus einer Liste hat keinen Einfluss auf seine bisherige Verwendung.  

### *Liste sichtbar machen*  

Damit Sie eine Liste in einem Template in Ihrer DataFactory verwenden können, muss die Liste für Templates sichtbar gemacht werden.  

Um eine Liste sichtbar und somit verwendbar zu machen, gehen Sie wie folgt vor:  

1. Klicken Sie auf die Liste **sxValueLists**.  

![Die Seite vom Listeneditor](images/Listen und Formate/eine_liste_sxvaluelists.png)

2. Klicken Sie auf die Schaltfläche **Neuer Eintrag**.  

![Die Seite vom Listeneditor mit der Wertetabelle einer Liste](images/Listen und Formate/die_wertetabelle_einer_liste_sxvaluelists.png)   

3. Geben Sie in die Spalte **ValueText** die Liste ein, die Sie sichtbar machen wollen.  

[Die Seite vom Listeneditor mit der Wertetabelle einer Liste](images/Listen und Formate/ergänzung_der_wertetabelle_einer_liste_sxvaluelists-2.png)   

4. Geben Sie ggf. in die Spalte **ValueComment** einen Kommentar und in die Spalte **FormatID** das gewünschte Format ein. 

[Die Seite vom Listeneditor mit der Wertetabelle einer Liste](images/Listen und Formate/ergänzung_der_wertetabelle_einer_liste_sxvaluelists.png)   

5. Klicken Sie auf **Speichern**.  

[Die Seite vom Listeneditor mit der Wertetabelle einer Liste](images/Listen und Formate/speichern_wertetabelleänderungen_von_der_sxvaluelists.png)   

### Liste löschen  

Um eine Liste zu löschen, gehen Sie wie folgt vor:  

1. Klicken Sie auf den ActionLink der Liste, die Sie löschen wollen und klicken Sie auf die Option **Löschen**.  

![Die Seite vom Listeneditor](images/Listen und Formate/eine_option_löschen_bei_einer_liste.png) 

2. Klicken Sie auf **Ja**, um die Liste zu löschen.  

![Message box fürs Löschen einer Liste](images/Listen und Formate/löschen_einer_liste.png) 

**Hinweis**: Die Liste ist nun gelöscht. Sie muss nun noch ggf. aus der Liste sxValueLists entfernt werden.  

3. Klicken Sie auf die Liste **sxValueLists**.  

![Die Seite vom Listeneditor](images/Listen und Formate/eine_liste_sxvaluelists-2.png)   

4. Klicken Sie auf den ActionLink der Liste, die Sie gerade gelöscht haben und klicken Sie auf die Option **Löschen**.  

[Die Seite vom Listeneditor mit der Wertetabelle einer Liste](images/Listen und Formate/eine_option_löschen_in_der_wertetabelle_sxvaluelists.png) 

5. Klicken Sie auf **Ja**, um den Eintrag zu löschen.  

![Message box fürs Löschen eines Listenwert](images/Listen und Formate/löschen_eines_listenweres.png) 

6. Klicken Sie auf **Speichern**, um die Änderung endgültig zu übernehmen.  

[Die Seite vom Listeneditor mit der Wertetabelle einer Liste](images/Listen und Formate/speichern_des_löschens_eines_listenwertes.png)   

### Neues Format anlegen  

Um ein neues Format anzulegen, gehen Sie wie folgt vor:  

1. Gehen Sie zur Übersicht Fabriken und Produktlinien und klicken Sie auf den ActionLink **Dieses Werk verwalten**.  

![Factory Seite](images/Listen und Formate/ein_link_dieses_werk_verwalten.png)  

2. Klicken Sie auf die Option **Formate editieren**.  

![Die Optionsliste des Links Dieses Werk verwalten](images/Listen und Formate/eine_option_formate_editieren.png)  

3. Klicken Sie auf die Schaltfläche **Neues Format**.  

![Die Seite vom Formateditor](images/Listen und Formate/ein_link_neues_format.png)   

4. Geben Sie in der Spalte **FormatID** eine FormatID ein.  

![Die Seite vom Formateditor](images/Listen und Formate/schaffen_eines_neuen_formats.png)     

**Hinweis**: Achten Sie bei der Eingabe auf die Verwendung des korrekten Präfixes.  

5. Wählen Sie in der Spalte **BackColor** ggf. eine Hintergrundfarbe, FontColor eine Schriftfarbe und bestimmen Sie in der Spalte **ValueFormat** ggf. ein Anzeigeformat ein.  

![Die Seite vom Formateditor](images/Listen und Formate/formateinstellungen.png)

6. Klicken Sie auf die Schaltfläche **Speichern**, um das neue Format zu speichern.  

![Die Seite vom Formateditor](images/Listen und Formate/ein_link_speichern_im_formateditor.png)  

**Hinweis**: In der Spalte Example sehen Sie eine Vorschau des von Ihnen erstellten Formats.  
Sie haben nun ein neues Format erstellt. Damit Sie dieses in Ihrer DataFactory verwenden können, müssen Sie das Format in die Liste sxValueFormats eintragen.  

7. Klicken Sie auf die Liste **sxValueFormats**.  

[Die Seite vom Listeneditor](images/Listen und Formate/eine_liste_sxvalueformats.png)

8. Klicken Sie auf die Schaltfläche **Neuer Eintrag**.  

[Die Seite vom Listeneditor mit der Wertetabelle einer Liste](images/Listen und Formate/werte_der_liste_sxvalueformats.png)     

9. Geben Sie in der Spalte **ValueText** für Ihr Format einen Namen ein.  

[Die Seite vom Listeneditor mit der Wertetabelle einer Liste](images/Listen und Formate/eine_spalte_valuetext_in_den_werten_der_liste_sxvalueformats.png)   

10. Wählen Sie in der Spalte **FormatID** die FormatID, die Sie neu angelegt haben.  

[Die Seite vom Listeneditor mit der Wertetabelle einer Liste](images/Listen und Formate/auswahl_einer_formatid.png)     

11. Geben Sie in der Spalte **ValueComment** ggf. einen ergänzenden Kommentar ein.  

[Die Seite vom Listeneditor mit der Wertetabelle einer Liste](images/Listen und Formate/kommentarergänzung_der_werte_der_liste_sxvalueformats.png)   

12. Klicken Sie auf die Schaltfläche **Speichern**.  

[Die Seite vom Listeneditor mit der Wertetabelle einer Liste](images/Listen und Formate/speichern_änderungen_bei_der_werte_der_liste_sxvalueformats.png)    

### Format löschen  

Um ein Format zu löschen, gehen Sie wie folgt vor:  

1. Klicken Sie auf den ActionLink in der Spalte **Action** des Wertes, den Sie löschen möchten und klicken Sie auf die Option **Löschen**.  

![Die Seite vom Formateditor](images/Listen und Formate/eine_option_löschen_des_formateditors.png)

2. Klicken Sie auf **Ja**, um das Format endgültig zu löschen.  

![Message box fürs Löschen eines Formats](images/Listen und Formate/löschen_eines_formats.png)   

**Hinweis**: Das Format ist nun gelöscht. Es muss nun noch aus der Liste sxValueFormats entfernt werden.  

3. Klicken Sie auf die Liste **sxValueFormats**.  

[Die Seite vom Listeneditor](images/Listen und Formate/ein_link_sxvalueformats_im_listeneditor.png)   

4. Klicken Sie auf den ActionLink des Formats, das Sie gerade gelöscht haben und nun aus der Liste entfernen wollen und klicken Sie auf die Option **Löschen**.  

[Die Seite vom Listeneditor mit der Wertetabelle einer Liste](images/Listen und Formate/listeneintrag_entfernen.png)     

5. Klicken Sie auf **Ja**, um den Wert endgültig zu löschen.  

![Message box fürs Löschen eines Listenwertes(images/Listen und Formate/löschen_eines_listenwertes-2.png)    

6. Klicken Sie auf die Schaltfläche **Speichern**, um Ihre Änderung zu speichern.  

[Die Seite vom Listeneditor mit der Wertetabelle einer Liste](images/Listen und Formate/speichern_änderungen_bei_der_werte_der_liste_sxvalueformats-2.png)   

*Hinweis**: Das Löschen eines Formats wirkt sich auf alle Stellen in Ihrem Werk aus, in denen das Format Anwendung fand.  

## Datenerfassung  

DataFactory bietet verschiedene Möglichkeiten der Datenerfassung. Die Datenerfassung erfolgt im Wertebereich der DataFactory.  

![Die Produktseite eines Template](images/Datenerfassung/der_wertebereich_eines_template.png)   

**Hinweis**: Alle von Ihnen erfassten Daten sind zunächst orangefarben hinterlegt. Erst wenn Sie auf die Schaltfläche Speichern klicken, werden die Daten in die Datenbank übertragen.  

### Manuelle Eingabe  

Sie können Daten mittels der Eingabe über Ihre Tastatur erfassen, indem Sie die Werte direkt in die gewünschten Zellen eingeben.  

![Die Produktseite eines Template](images/Datenerfassung/dateneingabe_über_tastatur.png)   

Sie können für die Eingabe Ihrer Daten auch Excel-Formeln verwenden.  

![Die Produktseite eines Template](images/Datenerfassung/dateneingabe_mit_excel-formel.png) 
  
**Hinweis**: Nur, wenn die Wertreihe bei der Einstellung Herkunft vom Typ XLS oder XLS-Strict definiert ist, bleibt die Formel im Wertebereich bestehen. Andernfalls wird die Formel beim Speichern durch den Wert ersetzt.   

### Dateneigabe mittels Rechner   

In DataFactory haben Sie die Möglichkeit, Ihre Daten komfortabel über einen Rechner einzugeben. Der Rechner bietet folgende Rechenoperationen.  

[Bild - eine Tabelle!]  

### *Einfügen von Werten (=)* 

Um Werte mit Hilfe des Rechners einzufügen, gehen Sie wie folgt vor:  

1. Geben Sie im Feld Wert den Wert ein, den Sie einfügen wollen.  

2. Markieren Sie die Zellen, in den Sie den Wert einfügen wollen und klicken Sie auf den Button **=**.  

![Die Produktseite eines Template](images/Datenerfassung/dateneingabe_über_rechner.png)  

3. Der eingegebene Wert wird jedem Wert in den markierten Zellen eingefügt.  

![Die Produktseite eines Template](images/Datenerfassung/einfügung_eingegebener_werte.png)  

### *Addition (+)*

Um Werte mit Hilfe des Rechners zu addieren, gehen Sie wie folgt vor:  

1. Geben Sie im Feld Wert den Wert ein, den Sie Addieren wollen.  

2. Markieren Sie die Zellen, zu denen Sie den Wert addieren wollen und klicken Sie auf den Button **+**.  

![Der Wertebereich eines Template](images/Datenerfassung/werteaddition_über_rechner.png)    

3. Der eingegebene Wert wird jedem Wert in den markierten Zellen hinzuaddiert.  

![Der Wertebereich eines Template](images/Datenerfassung/hinzuaddierte_werte.png)    

### *Subtraktion (-)*  

1. Geben Sie im Feld Wert den Wert ein, den Sie subtrahieren wollen.  

2. Markieren Sie die Zellen, von denen Sie den Wert subtrahieren wollen und klicken Sie auf den Button **-**.  

![Der Wertebereich eines Template](images/Datenerfassung/substraktion_über_rechner.png)    

3. Der eingegebene Wert wird von jedem Wert in den markierten Zellen subtrahiert.  

![Der Wertebereich eines Template](images/Datenerfassung/substrahierte_werte.png)     

### *Multiplikation (*)* 

1. Geben Sie im Feld **Wert** den Wert ein, mit dem Sie multiplizieren wollen.   

2. Markieren Sie die Zellen, die mit dem Wert multipliziert werden sollen und klicken Sie auf den Button *.  

![Der Wertebereich eines Template](images/Datenerfassung/multiplikation_über_rechner.png)   

3. Der eingegebene Wert wird mit jedem Wert in den markierten Zellen multipliziert.  

![Der Wertebereich eines Template](images/Datenerfassung/multiplizierte_werte.png) 
 
### *Division (/)* 

1. Geben Sie im Feld **Wert** den Wert ein, durch den Sie dividieren wollen.  

2. Markieren Sie die Zellen, die durch den Wert dividiert werden sollen und klicken Sie auf den Button **/**.  

![Der Wertebereich eines Template](images/Datenerfassung/division_über_rechner.png) 

3. Jeder der markierten Werte wird durch den eingegebenen Wert dividiert. 

![Der Wertebereich eines Template](images/Datenerfassung/dividierte_werte.png) 

### *Gleichverteilung*  

1. Geben Sie im Feld **Wert** den Wert ein, den Sie gleichverteilen wollen.  

2. Markieren Sie die Zellen, in denen Wert gleichverteilt werden soll und klicken Sie auf den Button **Gleichverteilung**.  

![Der Wertebereich eines Template](images/Datenerfassung/gleichverteilung_über_rechner.png) 

3. Der eingegebene Wert wird in jede Zelle gleichverteilt.  

![Der Wertebereich eines Template](images/Datenerfassung/gleichverteilte_werte.png) 

### *Verhältnis*  

1. Geben Sie im Feld **Wert** den Wert ein, den Sie verteilen wollen.  

2. Markieren Sie die Zellen, deren Verhältnis Sie als Grundlage für die Verteilung nutzen wollen und klicken Sie auf den Button **Verhältnis**.  

![Der Wertebereich eines Template](images/Datenerfassung/verteilung_eines_wertes_auf_basis_eines_vorhandenen_verhältnisses.png)  

3. Der eingegebene Wert wird auf Basis des Verhältnisses der markierten Zellen verteilt.  

![Der Wertebereich eines Template](images/Datenerfassung/verteilte_werte_auf_basis_eines_vorhandenen_verhältnisses.png)   

## Daten auswerten  

DataFactory bietet eine Vielzahl von Möglichkeiten, Daten auszuwerten. Standardmäßig in jeder DataFactory implementiert ist die Möglichkeit, Daten direkt über Pivot Tabellen und Pivot Diagramme auszuwerten.  
Darüber hinaus können Daten aus DataFactory individuell über gesonderte ReportingMappen oder durch die Anbindung an dritte System ausgewertet werden.  

### Pivot Auswertung  

Pivot Auswertungen lassen sich in DataFactory Werksebene, Fabrikebene und auf der Ebene der Produktlinien erstellen und beinhalten alle Informationen der gewählten sowie der darunterliegenden Ebenen.  
Bei der Erstellung einer Pivot Auswertung generiert DataFactory eine .csv-Datei mit allen numerischen Werten, die in den Produkten der gewählten Hierarchieebene erfasst sind.  
Die .csv-Datei wird im Ordner csv im Quellverzeichnis Ihrer DataFactory abgespeichert.  

### Pivot Auswertung auf Werksebene  

Um eine Pivot-Auswertung auf Werksebene zu erstellen, gehen Sie wie folgt vor:  

1. Klicken Sie in der Übersicht Fabriken und Produktlinien auf den ActionLink **Dieses Werk verwalten** und wählen Sie die Option **Pivot Ansicht**.  

![Factory Seite](images/Daten auswerten/eine_option_pivot_ansicht.png)   

2. Es öffnet sich automatisch in einem neuen Sheet eine Pivot Tabelle über alle Fabriken und Produktlinien hinweg.  

![Pivot Tabelle](images/Daten auswerten/eine_pivot_tabelle.png)   

**Hinweis**: Sie können sich Ihre Pivot Tabelle frei nach Ihren Wünschen gestalten und anpassen.  
