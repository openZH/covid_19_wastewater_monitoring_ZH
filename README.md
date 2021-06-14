
<img src="https://github.com/openZH/covid_19/blob/master/gd.png" alt="GD-logo" width="200"/>

[![GitHub commit](https://img.shields.io/github/last-commit/openZH/covid_19)](https://github.com/openZH/covid_19_wastewater_monitoring_ZH/commits/master)

# Sars-Cov-2 wastewater monitoring data reported by the Canton of Zurich

### Scope
This repository contains official open government data resources of the Sars-Cov-2 wastewater monitoring __in the Canton of Zurich__ reported by the __Department of Health of the Canton of Zurich__.

### Update
Data resources in this repository are updated on weekdays by the __Division for Data Analysis of the Office of Health Care of the Canton of Zurich__.

### Contact

If you have questions or want to report something regarding this repository, please contact the __Division for Data Analysis of the Office of Health Care of the Canton of Zurich__, Mr. Gianluca Macauda, by: <br>
- [creating a GitHub issue](https://github.com/openZH/covid_19_wastewater_monitoring_ZH/issues) <br>
- [writing an e-mail](mailto:gianluca.macauda@gd.zh.ch) <br>

Many thanks for your feedback!

<br>

## 1. Cumulative number of vaccinations by vaccination groups / Kumulierte Anzahl Impfungen nach Impfgruppen

**Data** <br>

>**https://github.com/openZH/covid_19_vaccination_campaign_ZH/tree/master/...** <br>
>*Description:* detailed numbers (1st vaccination, 2nd vaccination) up to and including the reporting date, vaccination group <br>
>*Update frequency:* daily (on weekdays) <br>
>*Spatial unit:* Canton of Zurich <br>
>*Format:* csv <br>

**Metadata**

| Fieldname / Spaltenname | Description (EN)             | Beschreibung (DE)             | Format     |
|-------------------------|------------------------------|-------------------------------|------------|
| __date__                | Reporting date (earlier than 2021-01-04 are accumulated to 'n.a.') | Stichtag (frühere als 2021-01-04 sind unter 'n.a.' kumuliert) | YYYY-MM-DD |
| __vaccgroup_zh__        | Vaccination group ('A' to 'T') according to [categorisation of the Canton of Zurich](https://www.zh.ch/de/gesundheit/coronavirus/coronavirus-impfung/impfgruppen.html#main_table_copy_copy) | Impfgruppe ('A' bis 'T') gemäss [Kategorisierung des Kantons Zürich](https://www.zh.ch/de/gesundheit/coronavirus/coronavirus-impfung/impfgruppen.html#main_table_copy_copy) | Text |
| __ncumul_firstvacc__    | Number of persons who received the first vaccination up to and including the reporting date | Anzahl Personen, die bis und mit Stichtag die erste Impfung erhalten haben | Number     |
| __ncumul_secondvacc__   | Number of persons who received the second vaccination up to and including the reporting date | Anzahl Personen, die bis und mit Stichtag die zweite Impfung erhalten haben | Number     |

<br>
