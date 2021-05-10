---
title: CDPH Environmental Records Lookup Table
created: '2020-11-10T16:54:36.556040'
modified: '2020-12-04T19:29:43.190711'
state: active
type: dataset
tags: []
groups:
  - Local Government
csv_url: >-
  https://data.cityofchicago.org/api/views/a9u4-3dwb/rows.csv?accessType=DOWNLOAD
json_url: >-
  https://data.cityofchicago.org/api/views/a9u4-3dwb/rows.json?accessType=DOWNLOAD
layout: post

---
This dataset serves as a lookup table to determine if environmental records exist in a Chicago Department of Public Health (CDPH) environmental dataset for a given address.   
Data fields requiring description are detailed below. 
MAPPED LOCATION: Contains the address, city, state and latitude/longitude coordinates of the facility. In instances where the facility address is a range, the lower number (the value in the “Street Number From” column) is used. For example, for the range address 1000-1005 S Wabash Ave, the Mapped Location would be 1000 S Wabash Ave. The latitude/longitude coordinate is determined through the Chicago Open Data Portal’s geocoding process.  Addresses that fail to geocode are assigned the coordinates 41.88415000022252°, -87.63241000012124°.This coordinate is located approximately just south of the intersection of W Randolph and N LaSalle.
COMPLAINTS:  A ‘Y’ indicates that one or more records exist in the CDPH Environmental Complaints dataset. 
NESHAPS & DEMOLITON NOTICES:  A ‘Y’ indicates that one or more records exist in the CDPH Asbestos and Demolition Notification dataset. 
ENFORCEMENT:  A ‘Y’ indicates that one or more records exist in the CDPH Environmental Enforcement dataset. 
INSPECTIONS:  A ‘Y’ indicates that one or more records exist in the CDPH Environmental Inspections dataset. 
PERMITS:  A ‘Y’ indicates that one or more records exist in the CDPH Environmental Permits dataset. 
TANKS:  A ‘Y’ indicates that one or more records exist in the CDPH Storage Tanks dataset.  Each 'Y' is a clickable link that will download the corresponding records in CSV format.
