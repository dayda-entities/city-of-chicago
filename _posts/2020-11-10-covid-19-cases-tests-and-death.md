---
title: 'COVID-19 Cases, Tests, and Deaths by ZIP Code'
created: '2020-11-10T16:55:38.082991'
modified: '2020-12-04T19:31:13.452084'
state: active
type: dataset
tags:
  - Covid 19
  - Death
  - Health
  - Link To Article Present
  - Public Health
  - Zip Code
groups:
  - Local Government
csv_url: >-
  https://data.cityofchicago.org/api/views/yhhz-zm2v/rows.csv?accessType=DOWNLOAD
json_url: >-
  https://data.cityofchicago.org/api/views/yhhz-zm2v/rows.json?accessType=DOWNLOAD
layout: post

---
NOTE: Starting 10/29/2020, the testing-related columns in this dataset will be based on individual tests, even if performed on the same person, rather than unique people. Please see https://www.chicago.gov/content/dam/city/depts/cdph/statistics_and_reports/COVID%20POSITIVITY%20RATE%20CHANGES%20102720.pdf  for more information. -- This is the place to look for important information about how to use this dataset, so please expand this box and read on!

This is the place to look for important information about how to use this dataset, so please expand this box and read on! 

This is the source data for some of the metrics available at https://www.chicago.gov/city/en/sites/covid-19/home/latest-data.html. 

For all datasets related to COVID-19, see https://data.cityofchicago.org/browse?limitTo=datasets&sortBy=alpha&tags=covid-19.
 
Only Chicago residents are included based on the home ZIP Code as provided by the medical provider. If a ZIP was missing or was not valid, it is displayed as "Unknown". 
 
Confirmed cases are counted based on the week the test specimen was collected. For privacy reasons, until a ZIP Code reaches five cumulative cases, both the weekly and cumulative case counts will be blank. Therefore, summing the “Cases - Weekly” column is not a reliable way  to determine case totals. Deaths are those that have occurred among confirmed cases based on the week of death. 
 
For tests, each test is counted once, based on the week the test specimen was collected. Tests performed prior to 3/1/2020 are not included. Test counts include multiple tests for the same person (a change made on 10/29/2020). Only molecular (PCR) tests reported to CDPH through electronic lab reporting are included. Early in the pandemic, electronic lab reporting took time to onboard and testing availability was severely restricted. As a result, numbers prior to May 1, 2020 will be an undercount of community infection.

The “Percent Tested Positive” columns are calculated by dividing the number of positive tests by the number of total tests . Because of the data limitations for the Tests columns, such as persons being tested multiple times as a requirement for employment, these percentages may vary in either direction from the actual disease prevalence in the ZIP Code. 
 
All data are provisional and subject to change. Information is updated as additional details are received. 

To compare ZIP Codes to Chicago Community Areas, please see http://data.cmap.illinois.gov/opendata/uploads/CKAN/NONCENSUS/ADMINISTRATIVE_POLITICAL_BOUNDARIES/CCAzip.pdf. Both ZIP Codes and Community Areas are also geographic datasets on this data portal.
 
Data Source: Illinois National Electronic Disease Surveillance System, Cook County Medical Examiner’s Office, Illinois Vital Records, American Community Survey (2018)
