
<img src="https://github.com/openZH/covid_19/blob/master/gd.png" alt="GD-logo" width="200"/>

[![GitHub commit](https://img.shields.io/github/last-commit/openZH/covid_19)](https://github.com/openZH/covid_19_wastewater_monitoring_ZH/commits/master)

# Sars-Cov-2 wastewater monitoring data reported by the Canton of Zurich

### Scope
As part of the cantonal SARS-CoV-2 wastewater monitoring, the __Health Department of the Canton of Zurich__ publishes measurements of samples from twelve wastewater treatment plants (WTPs) distributed __throughout the Canton of Zurich__. The measurements are based on the EAWAG (Swiss Federal Institute of Aquatic Science and Technology) project "SARS-CoV-2 in wastewater". Further information: https://www.eawag.ch/en/department/sww/projects/sars-cov2-in-wastewater/

__Please note:__ <br>
- The measurements of SARS-CoV-2 RNA in wastewater are partly subject to considerable measurement errors. Therefore, an interpretation of the wastewater measurements of SARS-CoV-2 in comparison to the case numbers is only meaningful over longer periods of time and depends on the scale chosen. Consequently, the data should be interpreted with caution, as there is a large scope for misinterpretation.
- Information about the twelve WTPs is available in [this resource](jump to respective resource below), including their abbreviation, full name, location (cantonal district) and indicating their respective catchment area (number of connected inhabitants).

### Update
Wastewater samples are taken three times a week at the twelve WWTPs. The analysis of the data is usually published a few days later.

### Contact
If you have questions regarding the __content of the data__, please contact the __Division for Data Analysis of the Office of Health Care of the Canton of Zurich__, <br>
- by [creating a GitHub issue](https://github.com/openZH/covid_19_wastewater_monitoring_ZH/issues) or <br>
- by writing an e-mail to [gdstab@gd.zh.ch](mailto:gdstab@gd.zh.ch). <br>

If you have questions regarding the __provision of the data__, please contact the __Specialist Unit for Open Government Data of the Canton of Zurich__, <br>
- by [writing a Twitter direct message](https://twitter.com/OpenDataZH) or <br>
- by writing an e-mail to [info@open.zh.ch](mailto:info@open.zh.ch). <br>

Many thanks for your feedback!

<br>

## 1. List of wastewater treatment plants with catchment area / Liste der Abwasserreinigungsanlagen mit Einzugsgebiet 

**Data** <br>

>**https://raw.githubusercontent.com/openZH/covid_19_wastewater_monitoring_ZH/master/ara_einzugsgebiet.csv** <br>
>*Description:* Wastewater treatment plants, which are included in the monitoring, with respective catchment areas (i.e. number of inhabitants connected) <br>
>*Update frequency:* weekly <br>
>*Spatial unit:* Canton of Zurich <br>
>*Format:* csv <br>

**Metadata**

| Fieldname / Spaltenname | Description (EN)             | Beschreibung (DE)             | Format     |
|-------------------------|------------------------------|-------------------------------|------------|
| ARA_code                | Abbreviation of the wastewater treatment plant (WTP)        | Abkürzung der Abwasserreinigungsanlage ARA                      | Text   |
| catchment_area          | Catchment ara (Number of inhabitants connected to the WTP)  | Einzugsgebiet (Anzahl an die ARA angeschlossene Einwohner:innen | Number |
| ARA_name                | Full name of the WTP                                        | Ausgeschriebener Name der ARA                                   | Text   |
| district                | Cantonal district, where the WTP is located                 | Kantonaler Bezirk, in dem die ARA liegt                         | Text   |

<br>
