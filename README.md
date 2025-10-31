# ResidentialEnergyCarbonEmissions-Thornton
This readme file was generated on 2025-10-30 by Adara Thornton

# GENERAL INFORMATION

Residential energy consumption in Calgary from 2019 by city ward and dwelling type. These data look at carbon emissions for 2019 related to energy consumption in Calgary from residential buildings to assess how sustainable housing practices are. Four dwelling types are assessed; single family homes, duplexes, townhouses and apartments. These dwelling types were assessed for overall contribution per captia and overall for the ward totals. 

## Author/Principal Investigator Information
Name: Adara Thornton 
Institution: University of Calgary 
Email: adara.thornton@ucalgary.ca

Data retrieved from Calgary Open Data and Natural Resources Canada 2025-09-22


# DATA & FILE OVERVIEW

## File List: 
Data folder is split into the original data files I retrieved 2025-09-22 in the Data Retrieved folder and thesee data I worked with from those files in the Processed Data folder. 
Data Retrieved contains three files. First is CensusDwellingStructure-OpenDataCalgary. These data cover the number of dwellings per type and amount of residents per type as identified by City of Calgary. These data are given for each of Calgary's 14 city wards. Second is Community-District-Boundaries which is a zip file from Calgary Open Data that contains the shapefile for the city wards. Third is Natural_Resources_Canada-Dwelling_Energy which contains many sheets of data relating to residential energy usage averages by province.
Processed Data folder contains Calgary-Energy-Consumption2019 which contains multiple sheets of data. The sheet titled Organizing was used to copy data from into the sheet titled For ArcGIS in an organized matter. The sheet named For ArcGIS contains the analysis of these data and formated to create a join to the shapefile in GIS. All three sheets that refer to a table are from the Natural Resources Canada data but only contains the Alberta data for each of the tables. Table 7.1a was not used in the analysis. The sheet named dwelling-type-ward is from the CensusDwellingStructure-OpenDataCalgary file. 
Map-Output contains the two map layouts created from these data. CarbonEmissionsByDwellingType has a map with a pie chart for each ward to show how much each dwelling type contributes to emissions from that ward. WardSingleFamilyCarbonEmissions contains two maps using proportional symbols that shows overall ward emissions per captia and single family home emissions per captia by ward. 


# METHODOLOGICAL INFORMATION

## Description of methods used for collection/generation of data: 
Data was retrieved from census information from City of Calgary and Natural Resources Canada.

## Methods for processing the data: 
From the retrieved data, four dwelling types were assigned to all the dwellings from the Calgary Open Data dwelling type by ward data. Average energy consumption in Alberta by dwelling and proportion of energy generated from oil and gas was used from the Natural Resources Canada data to calculate energy consumption and emissions from each Calgary ward by dwelling type. Each step of the calculations has its own column in the Calgary-Energy-Consumption2019 file. 

## Instrument- or software-specific information needed to interpret the data: 
Using microsoft excel for the spreadsheets is ideal as most of the files have multiple sheets in them. GIS software will be needed to use the Community-District-Boundaries shapefile.


# DATA-SPECIFIC INFORMATION FOR: Calgary-Energy-Consumption2019
Has 19 variables on the 'For ArcGIS' sheet which is the data specfic to this file.
A. City of Calgary ward number to identify area these data belong to. All the following variables are broken up by ward. 
B. Amount of occupied single family homes
C. Amount of occupied duplexes
D. Amount of occupied townhouses
E. Amount of occupied apartments
F. Total amount of occupied dwellings
G. Amount of people living in single family homes
H. Amount of people living in duplexes
I. Amount of people living in townhouses
J. Amount of people living in apartments
K. Energy consumed by single family homes based on Alberta average for this dwelling type
L. Energy consumed by duplexes based on Alberta average for this dwelling type
M. Energy consumed by townhouses based on Alberta average for this dwelling type
N. Energy consumed by apartments based on Alberta average for this dwelling type
O. Carbon dioxide emissions from single family homes based on energy consumed and proportion that comes from oil and gas combustion.
P. Carbon dioxide emissions from duplexes based on energy consumed and proportion that comes from oil and gas combustion.
Q. Carbon dioxide emissions from townhouses based on energy consumed and proportion that comes from oil and gas combustion.
R. Carbon dioxide emissions from apartments based on energy consumed and proportion that comes from oil and gas combustion.
S. Carbon dioxide emissions total by ward based on energy consumed and proportion that comes from oil and gas combustion.

# DATA-SPECIFIC INFORMATION FOR: CensusDwellingStructure-Open-Calgary
Has 13 variables, only 5 variables were used from these data which are listed below. 
1. CENSUS_YEAR: Year data was collected. Only 2019 data was used.
2. WARD: City of Calgary ward number to identify area these data belong to. All the following variables are broken up by ward.
3. DWELLING_TYPE: Structure type identified for the dwelling i.e. single family home, duplex, townhouse, etc.
4. RESIDENT_CNT: Amount of residents in each dwelling type in each ward.
5. OCPD_DWELLING_CNT: Amount of occupied dwellings of each type and in each ward.

# DATA-SPECIFIC INFORMATION FOR: Community-District-Boundaries_Open-Calgary
Zip file that contains the shapefile of Calgary city wards from 2019.

# DATA-SPECIFIC INFORMATION FOR: Natural_Resources_Canada-Dwellings_Energy
Tables 2.1a and 3.1a were used from this data
Table 2.1a:
Has 2 main variables broken down into multiple variables.
1. Main heating source: Main sources of energy for heating residential dwellings by province.
2. Type of energy source used by household: Overall energy source for residential dwellings by province.
Table 3.1a:
10 variables but only one was used stated below. 
Type of dwelling: states the type of dwelling and amount of energy used by dwelling type in each province.

# DATA-SPECIFIC INFORMATION FOR: CalgaryEnergyEmissions2019ByWard
Shapefile that has the data from the 'For ArcGIS' sheet in the Calgary-Energy-Consumption2019 file joined to the shapefile of the Calgary wards.
