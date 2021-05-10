---
title: Contracts
created: '2020-11-10T16:55:20.311091'
modified: '2020-12-04T19:30:41.901158'
state: active
type: dataset
tags:
  - Contracts
  - Procurement
groups:
  - Local Government
csv_url: >-
  https://data.cityofchicago.org/api/views/rsxa-ify5/rows.csv?accessType=DOWNLOAD
json_url: >-
  https://data.cityofchicago.org/api/views/rsxa-ify5/rows.json?accessType=DOWNLOAD
layout: post

---
Contracts and modifications awarded by the City of Chicago since 1993. This data is currently maintained in the City’s Financial Management and Purchasing System (FMPS), which is used throughout the City for contract management and payment. 
Legacy System Records: Purchase Order/Contract Numbers that begin with alpha characters identify records imported from legacy systems. Records with a null value in the Contract Type field were imported from legacy systems. 
"Comptroller-Other" Contract Type: Some records where the Contract Type is "COMPTROLLER-OTHER" are ordinance-based agreements and may have start dates earlier than 1993. 
Depends Upon Requirements Contracts: If the contract Award Amount is $0, the contract is not cancelled, and the contract is a blanket contract, then the contract award total Depends Upon Requirements. A Depends Upon Requirements contract is an indefinite quantities contract in which the City places orders as needed and the vendor is not guaranteed any particular contract award amount. 

Blanket vs. Standard Contracts: Only blanket contracts (contracts for repeated purchases) have FMPS end dates. Standard contracts (for example, construction contracts) terminate upon completion and acceptance of all deliverables. These dates are tracked outside of FMPS. 

Negative Modifications: Some contracts are modified to delete scope and money from a contract. These reductions are indicated by negative numbers in the Award Amount field of this dataset. 

Data Owner: Procurement Services. 
Time Period: 1993 to present. 
Frequency: Data is updated daily.
