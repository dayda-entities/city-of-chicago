---
title: CDPH Environmental Permits
created: '2020-11-10T16:55:02.103770'
modified: '2020-12-04T19:30:16.174435'
state: active
type: dataset
tags:
  - Environmental Permits
groups:
  - Local Government
csv_url: >-
  https://data.cityofchicago.org/api/views/ir7v-8mc8/rows.csv?accessType=DOWNLOAD
json_url: >-
  https://data.cityofchicago.org/api/views/ir7v-8mc8/rows.json?accessType=DOWNLOAD
layout: post

---
Permits issued by the Department of Environment (DOE) from January 1993 to December 31, 2011 and by the Department of Public Health (CDPH) since January 1, 2012. This dataset also includes tank permits issued by CDPH on behalf of the Office of the Illinois State Fire Marshall (OSFM). On January 1, 2012, the DOE was disbanded and all its inspection, permitting, and enforcement authorities were transferred to the CDPH.   
Data fields requiring description are detailed below. 
APPLICATION ID:  This is the unique id of the issued permit. Permits from the historic DOE are prefixed with “DOE.” Permits issued by CDPH are prefixed with “ENV_”
APPLICATION NAME: This is the name of the site that is being permitted. This is usually the company/owner name, address, or building name.  
MAPPED LOCATION: Contains latitude/longitude coordinates of the site as determined through the Chicago Open Data Portal’s geocoding engine. In instances where the facility address is a range, the lower number (the value in the “Street Number From” column) is used for geocoding. For example, for the range address 1000-1005 S Wabash Ave, the Mapped Location would be the coordinates for 1000 S Wabash Ave. 
 APPLICATION TYPE:       
"ABOVEGROUND STORAGE TANK" Permits to install or remove an Above Ground Storage Tank (AST) for dispensing and non-dispensing with a volume greater than 110 gallons. For more information go to http://tinyurl.com/bg7yrvx. 
"UNDERGROUND STORAGE TANK"  Permits to install, upgrade, repair, remove, abandon a UST or install an interior lining or Stage II vapor recovery systems in a UST. For more information go to http://tinyurl.com/bkqa8a8.
“AIR POLLUTION CONTROL PERMIT” Permits to install, operate, erect, construct, reconstruct, alter or add a piece of process equipment, process area, or air pollution control equipment and for sandblasting, grinding or chemical washing of any building, facility, statue or other architectural surface. This also includes annual certificate of operation (COO) for regulated process equipment, process area, or air pollution control equipment as defined in 11-4-610 of the Municipal Code. For more information go to http://tinyurl.com/az7ph79 .  
“RECYCLING FACILITY” Permits for recycling facilities including but not limited to junkyards, scrap metal, vehicle, vehicle parts, clean construction and demolition debris, and composting facilities. For more information go to http://tinyurl.com/azzpa93 .
“WASTE HANDLING FACILITY” Permits for solid waste transfer stations, liquid waste facilities, and permanent rock crushing facilities. For more information, refer to Chapter 11-4 Article IX and Article XIV of the Municipal Code at   http://tinyurl.com/crvyb29.  
“TEMPORARY ROCK CRUSHING” Permits to temporarily process concrete debris at the construction or demolition site. For more information go to http://tinyurl.com/a6atybq.    
APPLICATION SUBTYPE: The specific work type being permitted as applicable. 
STATUS: The current status of the permit (e.g. Open, Closed, Stop Work, etc.).
ISSUE/ENTRY DATE: For historic DOE records, this date is the issue date of the permit. For CDPH records, this is either the date the permit was issued, or the date the permit application was entered into the database. 
EXPIRATION DATE: This is the permit expiration date. Not all permits may have an expiration date. Some permits are renewed annually or every three years. If the applicant does not renew, the permit Status will be set to “Closed.”
COMMENT: Contains general comments and permit-specific information. 
DATA SOURCE: The department that collected or owns the data.
