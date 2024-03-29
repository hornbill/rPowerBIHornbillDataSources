# CHANGELOG

## 1.8.3 (Dec 8th, 2023)

Changes:

- Updated XMLMC API Endpoint
- Inclided Dav Endpoint

## 1.8.2 (Just 2nd, 2021)

Changes:

- Updated method to pull CSV report data

## 1.8.1 (June 30th, 2021)

Changes:

- URL encoded the report filename 

## 1.8.0 (November 12th, 2020)

Features:

- Added support for data in XLSX files to be added to the output dataframe in the codepage as defined in the csvEncoding variable 

## 1.7.0 (November 12th, 2020)

Features:

- Added support for XLSX report output for Report and HistoricReport scripts

## 1.6.0 (November 9th, 2020)

Features:

- Added support for updated JSON API response
- Removed jsonlite and readr dependency
- Introduced new dependency in TrendingData script - [data.table](https://cran.r-project.org/web/packages/data.table/)

## 1.5.0 (June 29th, 2020)

Features:

- Added support for proxies

## 1.4.0 (January 20th, 2020)

Features:

- Better handling and reporting of API call errors

## 1.3.0 (December 30th, 2019)

Features:

- Replaced textConnection & CSV reader code, replaced with httr content parser
- Added support to define which character set to use when parsing CSV code

## 1.2.0 (November 26th, 2019)

Features:

- Added support for TLS 1.2/1.3
- Removed need to provide instance zone
- General tidy-up of code
- Updated package dependencies - now requires httr and jsonlite, and no longer requires RCurl and XML

## 1.1.0 (June 28th, 2018)

Features:
- Added functionality to delete the historic report run instance from Hornbill once the data has been imported to Power BI;
- Added suspend code to work around a Power BI / RCurl incompatibility, where if you make more than 4 HTTP calls using getURL in the same script, the script hangs until you hit cancel in Power BI.

## 1.0.0 (May 9th, 2017)

Features:
- Initial Release
