---
title: Traffic Crashes - People
created: '2020-11-10T16:55:28.478891'
modified: '2020-12-04T19:30:54.417829'
state: active
type: dataset
tags:
  - Public Safety
  - Traffic Crashes
  - Transportation
  - Vision Zero
groups:
  - Local Government
csv_url: >-
  https://data.cityofchicago.org/api/views/u6pd-qa9d/rows.csv?accessType=DOWNLOAD
json_url: >-
  https://data.cityofchicago.org/api/views/u6pd-qa9d/rows.json?accessType=DOWNLOAD
layout: post

---
This data contains information about people involved in a crash and if any injuries were sustained. This dataset should be used in combination with the traffic Crash and Vehicle dataset. Each record corresponds to an occupant in a vehicle listed in the Crash dataset. Some people involved in a crash may not have been an occupant in a motor vehicle, but may have been a pedestrian, bicyclist, or using another non-motor vehicle mode of transportation. Injuries reported are reported by the responding police officer. Fatalities that occur after the initial reports are typically updated in these records up to 30 days after the date of the crash. Person data can be linked with the Crash and Vehicle dataset using the “CRASH_RECORD_ID” field. A vehicle can have multiple occupants and hence have a one to many relationship between Vehicle and Person dataset. However, a pedestrian is a “unit” by itself and have a one to one relationship between the Vehicle and Person table.
