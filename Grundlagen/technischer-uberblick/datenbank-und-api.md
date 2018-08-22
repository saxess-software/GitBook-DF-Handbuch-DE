### Datenbank

Das Herzstück von DataFactory ist eine Datenbank, die auf einem MS-SQL Server liegt. Hierfür existieren 2 Möglichkeiten:

1. Die Datenbank liegt im lokalen Intranet
2. Die Datenbank liegt in einer Cloud

### API

Auf der Datenbank ist eine API installiert, die als Zugriffsschicht die Logiken der Zugriffsteuerung definiert. Im Grunde genommen ist die API eine Sammlung von Prozeduren \(stored procedures\), die in der Datenbank angelegt werden und welche die Rechen- und Zugriffslogiken von DataFactory beinhalten und alle Prozesse steuern , die auf der Datenbank stattfinden. Die API stellt das Herz von DataFactory dar. Jede Eingabe bzw. jeder Befehl, der im Excel- oder Web-Client durchgeführt wird, löst im Hintergrund eine Aktion der API aus.

