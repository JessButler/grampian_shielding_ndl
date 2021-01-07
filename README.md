# People shielding from Coronavirus in NHS Grampian
This is analysis for NHS Grampian to understand people shielding (supported by the Health Foundation's Networked Data Lab and Scotland's Chief Scientist's Office).  
Questions please contact JessicaButler@abdn.ac.uk

## Demographics of patients shielding from COVID in Grampian

**Download "shielding_demographics.xlsx" here for a description of the age, sex, reasons for shielding, and characteristics of home (urban/rural and Scottish Index of Multiple Deprivation) of people shielding from Coronavirus in NHS Grampian.** 

### Methods
#### Population
The population of shielding people used for this analysis was supplied by Health Intelligence in NHS Grampian to the Grampian Data Safe Haven on 12th October 2020. 

This shielding list includes all people instructed to shield who live in the NHS Grampian Region. NHS Grampian covers three local authorities: Aberdeen City, Aberdeenshire and Moray. The total population is 585,700.

People could be included in the shielding list either by being added at the national level or locally.

#### Identification of those who should shield (used for national searches)
Described here https://www.hps.scot.nhs.uk/web-resources-container/covid-19-search-criteria-for-highest-risk-patients-for-shielding 

#### Methods used for local searches
Searches could be carried out by GPs and hospital consultants using any of the databases VISION, EMIS, TrakCare, and datasets held in departments. An overview of how local additions and removals were implemented is provided in the supporting document “Shielding_Information_Flow_04052020.pdf”.

#### Population Exclusions
For this analysis, people on the original shielding list were excluded from the study population for the following reasons:
Incorrectly put on the shielding list (primarily due to a batch that included false positive lung cancer results), moved from Scotland, died before shielding began on 26th March 2020, added to the shielding list after 31st July 2020.

#### Reasons to shield
The list of reasons for shielding and how they were determined in the national searches are given in the methods document linked above. People could have multiple reasons to shield. For patients added locally, the reasons to shield was stated by the GP or consultant rather than derived from the patients’ electronic health care record.

#### Source of shielding directive
For every reason to shield, the source was given as either from the national search or the local search. If a patient had any reason to shield with a national source they have been categorised as shielding from the national directive. Only if all sources were local are they categorised as shielding from a local directive.

#### Age
For data protection reasons date-of-birth is given by month and year only. Age was calculated as of 1st March 2020, assuming date-of-birth on the first of the month given.

#### Deprivation
Measures of patients’ home area deprivation were taken from the Scottish Government’s Scottish Index of Multiple Deprivation measure for 2020 (version 2). Nota bene: SIMD quintile 1 is the most deprived, and SIMD quintile 5 is the least deprived. https://www.gov.scot/collections/scottish-index-of-multiple-deprivation-2020/

#### Urban-Rural
The measure of urbanity of the patients’ home area was taken from the Scottish Government’s Urban Rural Classification 2016. https://www.gov.scot/publications/scottish-government-urban-rural-classification-2016/pages/2/

#### Disclosure Control
These summary data have been released to the public by the Grampian Data Safe Haven. No data for individuals are provided. Due small numbers, for the descriptions of shielding reason + age and shielding reason + deprivation, people in the category of “pregnant with a heart condition” have been combined with the “other” category.

#### Analytic Code
The R code used to generate the tables is given in the RMarkdown document “code_demographics.Rmd”.


