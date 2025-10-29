# ResidentialEnergyCarbonEmissions-Thornton
This readme file was generated on 2025-10-29 by Adara Thornton

*Note:
[text within square brackets should be changed to specific information about your dataset.]
*help text within asterisks should be deleted before finalizing your document**

# GENERAL INFORMATION

Residential energy consumption in Calgary from 2019 by city ward and dwelling type. These data look at carbon emissions for 2019 related to energy consumption in Calgary from residential buildings to assess how sustainable housing practices are. Four dwelling types are assessed; single family homes, duplexes, townhouses and apartments. These dwelling types were assessed for overall contribution per captia and overall for the ward totals. 

## Author/Principal Investigator Information
Name: Adara Thornton
Institution: University of Calgary
Email: adara.thornton@ucalgary.ca

## Author/Associate or Co-investigator Information
Name: 
ORCID:
Institution: 
Address: 
Email: 

Data retrieved from Calgary Open Data and Natural Resources Canada 2025-09-22


# SHARING/ACCESS INFORMATION

* Licenses/restrictions placed on the data: 
* Links/relationships to ancillary data sets: 
* Was data derived from another source?
Data was derived from data retreived from Calgary Open Data and Natural Resources Canada data, both are publically available.
* Recommended citation for this dataset: 


# DATA & FILE OVERVIEW

## File List: 
Data folder is split into the original data files I retrieved 2025-09-22 in the Data Retrieved folder and thesee data I worked with from those files in the Processed Data folder. 
Data Retrieved contains three files. First is CensusDwellingStructure-OpenDataCalgary. These data cover the number of dwellings per type and amount of residents per type as identified by City of Calgary. These data are given for each of Calgary's 14 city wards. Second is Community-District-Boundaries which is a zip file from Calgary Open Data that contains the shapefile for the city wards. Third is Natural_Resources_Canada-Dwelling_Energy which contains many sheets of data relating to residential energy usage averages by province.
Processed Data folder contains Calgary-Energy-Consumption2019 which contains multiple sheets of data. The sheet titled Organizing was used to copy data from into the sheet titled For ArcGIS in an organized matter. The sheet named For ArcGIS contains the analysis of these data and formated to create a join to the shapefile in GIS. All three sheets that refer to a table are from the Natural Resources Canada data but only contains the Alberta data for each of the tables. Table 7.1a was not used in the analysis. The sheet named dwelling-type-ward is from the CensusDwellingStructure-OpenDataCalgary file. 
Map-Output contains the two map layouts created from these data. CarbonEmissionsByDwellingType has a map with a pie chart for each ward to show how much each dwelling type contributes to emissions from that ward. WardSingleFamilyCarbonEmissions contains two maps using proportional symbols that shows overall ward emissions per captia and single family home emissions per captia by ward. 

* Relationship between files, if important: 
* Additional related data collected that was not included in the current data package: 
* Are there multiple versions of the dataset?
	* If yes, name of file(s) that was updated: 
	* Why was the file updated? 
	* When was the file updated? 


# METHODOLOGICAL INFORMATION

## Description of methods used for collection/generation of data: 
*include links or references to publications or other documentation containing experimental design or protocols used in data collection*

## Methods for processing the data: 
*describe how the submitted data were generated from the raw or collected data*

## Instrument- or software-specific information needed to interpret the data: 
*include full name and version of software, and any necessary packages or libraries needed to run scripts*

*include any additional methodological information needed to interpret and/or use the data, as appropriate*
* Standards and calibration information, if appropriate: 
* Environmental/experimental conditions: 
* Describe any quality-assurance procedures performed on the data: 
* People involved with sample collection, processing, analysis and/or submission: 


# DATA-SPECIFIC INFORMATION FOR: [FILENAME]
*repeat this section for each dataset, folder or file, as appropriate*

* Number of variables: 
* Number of cases/rows: 
* Variable List: *list variable name(s), description(s), unit(s) and value labels as appropriate for each*
* Missing data codes: *list code/symbol and definition*
* Specialized formats or other abbreviations used: 
