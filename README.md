# Zotero Add-on für AOI-Bibliothek

`Zotero Swissbib UZH-AOI Locations` ist ein modifiziertes Add-on `Zotero Swissbib Basel Bern Locations` ([Link](https://github.com/UB-Bern/zotero-swissbib-bb-locations)). Mit diesem Add-on kann man Standortinformation der Bibliothek UZH-AOI (Asien-Orient-Bibliothek an der Universität Zürich) in Swissbib durchsuchen.

`Zotero Swissbib Basel Bern Locations` ist ein Add-on für das Literaturverwaltungsprogramm [Zotero](https://www.zotero.org/) sowie das darauf basierende [Jurism](https://juris-m.github.io/) zur Unterstützung des Bestandesaufbaus an der UB Bern. Das Add-on kann über die SRU-Schnittstelle von [Swissbib](https://www.swissbib.ch/) Standortinformationen im Swissbib Basel Bern zu den ausgewählten Einträgen abrufen und -- je nach Ergebnis der Abfrage -- entsprechende Tags setzen.

Weil das Bibliothekssystem ALMA ab 2021 für die Schweizer Hochschulbibliotheken eingeführt wird und die SRU-Schnittstelle von Swissbib daher nicht mehr verwendet werden, sollte das Add-on bald umgeschrieben werden.

## Anwendung
Wenn man einfach das Add-on benutzen will, kann man die Datei 'zotero-swissbib-aoi-locations-0.1.5.xpi' von dieser Repository herunterladen und ins Zotero installieren.
Wenn man dies jedoch selber modifizieren will, kann man die anderen Datei, vor allem den Ordner "chrome/\*", herunterladen, JS-Code ändern und mit folgenden Befehle xpi-Datei herstellen, was als Add-on ins Zotero installiert werden kann.

`zip -r zotero-swissbib-aoi-locations-[version].xpi chrome/* chrome.manifest install.rdf`  



## License

Copyright (C) 2019 Denis Maier / Modified by Nobutake Kamiya

Distributed under the GPLv3 License.
