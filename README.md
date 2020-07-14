# covid19monitoring_economy_Kreditkarten

## Grundlage
Die ausgewiesenen Zahlen beziehen sich auf Transaktionen mit inländischen Kreditkarten (ohne Bargeldbezüge). Die Daten stammen von den Mitgliedern der Swiss Payment Association/SPA (BonusCard.ch AG, Cembra Money Bank AG, Cornèr Bank AG, PostFinance AG, Swisscard AECS GmbH, UBS Switzerland AG, Viseca Card Services SA). 

Seit dem 14. Juli 2020 werden die Daten vom [Projekt Monitoring Consumption](https://public.tableau.com/profile/monitoringconsumptionswitzerland#!/) aufbereitet und öffentlich zur Verfügung gestellt. Die Dokumentation sowie die Daten können auch direkt dort bezogen werden: [Link](https://drive.switch.ch/index.php/s/PSg7Y8Za5LmQ5dn).

## Methodisches

* Für die ausgewiesenen Datenkategorien (=Variablen) gelten die Definitionen der Finanzmarktstatistik der SNB ([Daten und Definitionen SNB](https://data.snb.ch/de/topics/finma#!/cube/zavezaluba)) 

*  Weil die Erhebung der hier verfügbaren Daten in kürzeren Intervallen stattfindet als für die SNB, werden vereinzelte Kreditkartenprodukte nicht berücksichtigt, welche in die monatlichen Daten SNB-Finanzmarktstatistik einfliessen. Die Zahlen sind hinsichtlich der stattgefundenen bzw. stattfindenden Entwicklungen aber dennoch aussagekräftig. 

* Die ausgewiesenen Werte sind über einen Zeitraum von sieben Tagen kumuliert (Donnerstag bis Mittwoch). So werden verarbeitungsbedingte Tages-Peaks zu vermieden. Das Datum (variable = date) entsprich jeweils dem Donnerstag, sprich dem ersten Tag des berücksichtigen Zeitraumes.

## Variablen
Für jede Transaktionskategorie gibt es Angaben zum Betrag (in Mio. Fr.) sowie zur Anzahl (in Tausend). Die ensprechenden Varialbennamen beginnen mit 'betrag' bzw. mit 'anz'. <br>

**..._kktrans_ch** = Betrag/Anzahl Kreditkarten-Transaktionen im Inland <br>
**..._kktrans_ausl** = Betrag/Anzahl Kreditkarten-Transaktionen im Ausland <br>
**..._kktrans_ch_praes** = 	Betrag/Anzahl Kreditkarten-Transaktionen Präsenzgeschäft im Inland insgesamt <br>
**..._kktrans_ch_praes_contactless** = Betrag/Anzahl  kontaktlose Kreditkarten-Transaktionen Präsenzgeschäft im Inland <br>
**..._kktrans_ch_distanz** =	Betrag/Anzahl  Kreditkarten-Transaktionen Distanzgeschäft im Inland <br>
**..._kktrans_ausl_distanz** =	Betrag/Anzahl  Kreditkarten-Transaktionen Distanzgeschäft im Ausland <br>


## Weitere Informationen 
[Projektseite: "Gesellschafsmonitoring COVID19"](https://github.com/statistikZH/covid19monitoring) <br>
[Datenbezug](https://www.web.statistik.zh.ch/covid19_indikatoren_uebersicht/#/) <br>
[Visualisierung](https://www.web.statistik.zh.ch/cms_vis/covid19_indikatoren/) <br>






