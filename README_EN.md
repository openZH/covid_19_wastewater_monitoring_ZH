![](https://opendata.swiss/content/uploads/2016/02/kt_zh.png)

# Project Name

## Project Description

Describe the project here: introduction, methodology, results, recommended form of citation etc. <br>
Remember that github is the place where we exchange code. So this is the place where interested people look for instructions: How was the analysis carried out? What has to be considered when running the code? What do the variable names mean? 

## Prerequisites

E.g.: 

R version 3.5.0 (2018-04-23) <br>
RStudio version 1.1.453 <br>
Deppendencies: <br>
|package name | version number |
| ------------- | ------------- | 
|dplyr     |    0.8.3 |
|sf     |    0.8-1 |


R Code to obtain above listed information :

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

## Contributors

Thanks to the following people who have contributed to this project

[@kalakaru](https://github.com/kalakaru)
[@mmznrSTAT](https://github.com/mmznrSTAT)

## Contact

first name last name  <br>
firstname.lastname@ji.statistik.zh.ch <br>
phone number <br>

![Twitter Follow](https://img.shields.io/twitter/follow/statistik_zh?style=social)

## License

This project uses the following license: <br>
- Data license: [Attribution 4.0 International](https://github.com/statistikZH/STAT_Schablone/blob/master/LICENSE_data)
- Code license: [Copyright (c) <2019> <Statistisches Amt Kanton Zürich>](https://github.com/statistikZH/STAT_Schablone/blob/master/LICENSE_code)

## Guidelines for contributing
We welcome contributions. Please see our [CONTRIBUTING.md](https://github.com/statistikZH/STAT_Schablone/blob/master/CONTRIBUTING.md) file for detailed guidelines of how to contribute.

Please note that this project is released with a [Contributor Code of Conduct](https://github.com/statistikZH/STAT_Schablone/blob/master/CodeOfConduct.md). By participating in this project you agree to abide by its terms.

