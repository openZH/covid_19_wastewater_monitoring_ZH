![](https://opendata.swiss/content/uploads/2016/02/kt_zh.png)

# Projekt Name

*Read this in other languages: [English](README_EN.md)*

## Projektbeschreibung

Beschreibe hier das Projekt: Einführung, Methodik, Ergebnisse, empfohlene Zitierform etc. <br>
Bedenke, dass github der Ort ist, an dem wir Code austauschen. Dies ist also der Ort, an dem interessierte Personen nach Anweisungen suchen. Interessierte möchen hier z.B: informationen zu folgenden Themen finden: Wie die Analyse durchgeführt wurde? Was muss beim Ausführen des Codes beachtet werden? Was bedeuten die Variablennamen? Ein schönes Beispiel ist hier zu finden: https://github.com/tamedia-ddj/SUV_Analyse_Schweiz

## Voraussetzungen

z.B.: 

R version 3.5.0 (2018-04-23) <br>
RStudio version 1.1.453 <br>
Deppendencies: <br>
|package name | version number |
| ------------- | ------------- | 
|dplyr     |    0.8.3 |
|sf     |    0.8-1 |


R Code um die obigen Informationen zu erhalten: 

```R 
# R version
print(version[['version.string']])
# R Studio Version
require(rstudioapi)
RStudioversionInfo <- versionInfo()
print(paste("RStudio version", RStudioversionInfo$version))
# list names of loaded libraries with version number
print(subset(data.frame(sessioninfo::package_info()), attached==TRUE, c(package, loadedversion)),  row.names = FALSE)
```

## Mitwirkende

Vielen Dank an folgende Personen die mitgewirkt haben: 

[@kalakaru](https://github.com/kalakaru)
[@mmznrSTAT](https://github.com/mmznrSTAT)

## Kontakt

Vorname Nachname  <br>
vorname.nachname@statistik.ji.zh.ch <br>
Telefonnummer <br>

![Twitter Follow](https://img.shields.io/twitter/follow/statistik_zh?style=social)

## Lizenzen

Dieses Projekt untersteht folgenden Lizenzen: <br>
- Datenlizenz: [Attribution 4.0 International](https://github.com/statistikZH/STAT_Schablone/blob/master/LICENSE_data)
- Codelizenz: [Copyright (c) <2019> <Statistisches Amt Kanton Zürich>](https://github.com/statistikZH/STAT_Schablone/blob/master/LICENSE_code)

## Richtlinien für Beiträge
Wir begrüßen Beiträge. Bitte lesen Sie unsere [CONTRIBUTING.md](https://github.com/statistikZH/STAT_Schablone/blob/master/CONTRIBUTING.md) Datei, wenn sie daran interessiert sind. Hier finden Sie Informationen die zeigen wie Sie beitragen können. 

Bitte beachten Sie, dass dieses Projekt mit einem [Verhaltenskodex](https://github.com/statistikZH/STAT_Schablone/blob/master/CodeOfConduct.md) veröffentlicht wird. Mit Ihrer Teilnahme an diesem Projekt erklären Sie sich mit dessen Bedingungen einverstanden.


