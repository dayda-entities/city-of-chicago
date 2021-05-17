---
title: Transportation Network Providers - Vehicles
created: '2020-11-10T16:54:40.889995'
modified: '2020-11-10T16:54:40.890005'
state: active
type: dataset
tags:
  - Rideshare
  - Tnp
  - Transportation
  - Transportation Network Provider
  - Vehicles
groups:
  - Local Government
csv_url: >-
  https://data.cityofchicago.org/api/views/bc6b-sq4u/rows.csv?accessType=DOWNLOAD
json_url: >-
  https://data.cityofchicago.org/api/views/bc6b-sq4u/rows.json?accessType=DOWNLOAD
layout: post

---
All vehicles reported by Transportation Network Providers (sometimes called rideshare companies) to the City of Chicago as part of routine reporting required by ordinance.  Inclusion of a vehicle in a monthly report indicates that the vehicle was eligible for trips in Chicago in that month for at least one day, regardless of whether it actually provided any rides. If a vehicle is eligible in multiple months, which is common, it will have records in each of these reporting months. 

As of the creation of this dataset, there have been four TNPs licensed to operate in Chicago, although never more than three at any given time and currently three. Vehicles reported by more than one company in the same month are combined and the MULTIPLE_TNPS column is marked as TRUE. However, the matching process is imperfect so not all such vehicles are necessarily identified.  

Information on last inspection date was not required before September 2017 so will not be found in older records.  

The reporting is done on a monthly basis, as indicated in the MONTH_REPORTED column. However, starting in 2018, the reports are batched and files for all three months in a quarter are delivered to the City of Chicago at the end of each quarter. Due to an issue in this transition, some vehicle records for Q2 2018 (April-June) were reported for the quarter as a whole, rather than for individual months. For purposes of this dataset, those records have been assigned to 2018-06 (June). Therefore, some caution in interpreting this month and the quarter as a whole is advised.
