---
title: Transportation Network Providers - Drivers
created: '2020-11-10T16:55:03.109384'
modified: '2020-11-10T16:55:03.109408'
state: active
type: dataset
tags:
  - Drivers
  - Rideshare
  - Tnp
  - Transportation
  - Transportation Network Provider
groups:
  - Local Government
csv_url: >-
  https://data.cityofchicago.org/api/views/j6wf-834c/rows.csv?accessType=DOWNLOAD
json_url: >-
  https://data.cityofchicago.org/api/views/j6wf-834c/rows.json?accessType=DOWNLOAD
layout: post

---
All drivers reported by Transportation Network Providers (sometimes called rideshare companies) to the City of Chicago as part of the licensing process and routine reporting required by ordinance. Inclusion of a driver in a monthly report indicates that the driver was eligible for trips in Chicago in that month for at least one day, regardless of whether he or she actually provided any rides. If a driver is eligible in multiple months, which is common, he or she will have records in each of these reporting months. 

As of the creation of this dataset, there have been four TNPs licensed to operate in Chicago, although never more than three at any given time and currently three. Drivers reported by more than one company in the same month are combined and the MULTIPLE_TNPS column is marked as TRUE. However, the matching process is imperfect so not all such drivers are necessarily identified. Similarly, matching between the licensing and routine reporting databases is imperfect, creating potential for occasional errors.

The reporting is done on a monthly basis, as indicated in the MONTH_REPORTED column. However, starting in 2018, the reports are batched and files for all three months in a quarter are delivered to the City of Chicago at the end of each quarter. Due to an issue in this transition, some vehicle records for Q2 2018 (April-June) were reported for the quarter as a whole, rather than for individual months. For purposes of this dataset, those records have been assigned to 2018-06 (June). Therefore, some caution in interpreting this month and the quarter as a whole is advised.
