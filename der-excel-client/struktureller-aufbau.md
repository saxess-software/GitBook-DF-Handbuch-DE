## Struktureller Aufbau

Der strukturelle Aufbau von DataFactory orientiert sich am Konzept der *Abstrakten Fabrik*; einer Art "Schablone" zur Entwicklung von Lösungen im Bereich Softwarearchitektur und -entwicklung. 

Die Struktur von DataFactory untergliedert sich in vier Ebenen mit den abstrakten Bezeichnungen Werk, Fabrik, Produktlinie und Produkt. Durch die unspezifische Bezeichnung der einzelnen Strukturelemente ist es möglich, die Struktur von verschiedensten Anwendungsfällen bzw. Problemstellungen abzubilden und darauf aufbauend die gewünschte Systemlösung zu designen. Aus diesem Grund kann DataFactory in einem sehr breiten Anwendungsspektrum eingesetzt und flexibel nach individuellen Anforderungen angepasst werden.

Die unterste Ebene der Struktur bildet das Produkt. Auf der Ebene des Produkt findet die Datenerfassung statt. Jedes Produkt basiert auf einem sogenannten [Template](templates.md), d.h. einer Vorlage,  auf deren Basis weitere Produkte generiert werden sollen. Ein Template kann als abstraktes Produkt verstanden werden, in welchem nur die Strukturen und Berechnungslogiken eines bestimmten Produkttyps definiert sind. Aus einem Template können beliebig viele konkrete Produkte generiert werden, d.h. Produkte, die konkrete Daten tragen. 

Produkte werden auf Produktlinienebene aggregiert und Produktlinien wiederum auf Fabrikebene. Die oberste Aggregationsebene bildet das Werk.

Auf Fabrik- und Produktlinienebene können die Zugriffsrechte vergeben werden, d.h. dass Benutzer nur für bestimmte Fabriken oder Produktlinien Lese- und/oder Schreibrechte haben. Mehr zu diesem Thema finden Sie im Kapitel [Benutzer verwalten](werk/benutzer-verwalten.md).

Listen und Formate werden auf Werksebene verwaltet und können in allen Hierarchieebenen eingesetzt werden. Mehr dazu lesen Sie im Kapitel [Listen und Formate](listen-und-formate.md).

---
![](/Pictures/Excel-Client/Struktureller Aufbau/struktureller_aufbau_1.png)

---