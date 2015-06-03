# Links/Resources
 + http://pension360.org/
 + http://openretirement.org/about-us/
 + http://cms.gov/
 + [downloadable data](https://data.medicare.gov/data/nursing-home-compare)

# Problems/ Opportunities
 + Which fields correlate with the overall quality of the nursing homes?

# Dataset Notes

todo

# Data Dictionary

## `deficiencies`

Variable Name (column headers on ACCESS tables and CSV Downloadable files)	|	Label (column headers on CSV Display files)	|	Description	|	Format / Values	|	On CSV Display File	|	On CSV Download File	|	On Access Table
--- | --- | --- | --- | --- | --- | --- 
PROVNUM	|	Federal Provider Number	|	Federal Provider Number	|	6 alphanumeric characters	|	Yes	|	Yes	|	Yes
PROVNAME	|	Provider Name	|	Provider Name	|	text	|	Yes	|	Yes	|	Yes
ADDRESS	|	Provider Address	|	Provider Address	|	text	|	Yes	|	Yes	|	Yes
CITY	|	Provider City	|	Provider City	|	text	|	Yes	|	Yes	|	Yes
STATE	|	Provider State	|	Provider State	|	2-character postal abbreviation	|	Yes	|	Yes	|	Yes
ZIP	|	Provider Zip Code	|	Provider Zip Code	|	5-digit zip code	|	Yes	|	Yes	|	Yes
PHONE	|	Provider Phone Number	|	Provider Phone Number	|	10 numeric characters	|	Yes	|	Yes	|	Yes
COUNTY_SSA	|	Provider SSA County	|	SSA county code	|	3-digit SSA code	|	Yes	|	Yes	|	Yes
COUNTY_NAME	|	Provider County Name	|	Provider County Name	|	text	|	Yes	|	Yes	|	Yes
OWNERSHIP	|	Ownership Type	|	Nature of organization that operates a provider of services 	|	text	|	Yes	|	Yes	|	Yes
BEDCERT	|	Number of Certified Beds	|	Number of Federally Certified Beds	|	integer	|	Yes	|	Yes	|	Yes
RESTOT	|	Number of Residents in Certified Beds	|	Number of Residents in Federally Certified Beds	|	integer	|	Yes	|	Yes	|	Yes
CERTIFICATION	|	Provider Type	|	Category which is most indicative of provider	|	text	|	Yes	|	Yes	|	Yes
INHOSP	|	Provider Resides in Hospital	|	Facility Resides in Hospital Inidcator	|	Y/N	|	Yes	|	Yes	|	Yes
LBN	|	Legal Business Name	|	Legal Business Name	|	text	|	Yes	|	Yes	|	Yes
PARTICIPATION_DATE	|	Date First Approved to Provide Medicare and Medicaid services	|	Date First Approved to Provide Medicare/Medicaid Services	|	YYYY-MM-DD	|	Yes	|	Yes	|	Yes
CCRC_FACIL	|	Continuing Care Retirement Community	|	Continuing Care Retirement Community Indicator	|	Y/N	|	Yes	|	Yes	|	Yes
SFF	|	Special Focus Facility	|	Special Focus Facility Indicator	|	Y/N	|	Yes	|	Yes	|	Yes
CHOW_LAST_12MOS	|	Provider Changed Ownership in Last 12 Months	|	Facility Changed Ownership in Last 12 Months Indicator	|	Y/N	|	Yes	|	Yes	|	Yes
resfamcouncil	|	With a Resident and Family Council	|	With a Resident and Family Council	|	Resident, Family, Both, None	|	Yes	|	Yes	|	Yes
sprinkler_status	|	Automatic Sprinkler Systems in All Required Areas	|	Automatic Sprinkler Systems in All Required Areas	|	Yes, Partial, No, Data Not Available	|	Yes	|	Yes	|	Yes
overall_rating	|	Overall Rating	|	Overall Rating	|	one-digit, values 1-5	|	Yes	|	Yes	|	Yes
overall_rating_fn	|	Overall Rating Footnote	|	Overall Rating Footnote	|	text	|	Yes	|	Yes	|	Yes
survey_rating	|	Health Inspection Rating	|	Health Inspection Rating	|	one-digit, values 1-5	|	Yes	|	Yes	|	Yes
survey_rating_fn	|	Health Inspection Rating Footnote	|	Health Inspection Rating Footnote	|	text	|	Yes	|	Yes	|	Yes
quality_rating	|	QM Rating	|	QM Rating	|	one-digit, values 1-5	|	Yes	|	Yes	|	Yes
quality_rating_fn	|	QM Rating Footnote	|	QM Rating Footnote	|	text	|	Yes	|	Yes	|	Yes
staffing_rating	|	Staffing Rating	|	Staffing Rating	|	one-digit, values 1-5	|	Yes	|	Yes	|	Yes
staffing_rating_fn	|	Staffing Rating Footnote	|	Staffing Rating Footnote	|	text	|	Yes	|	Yes	|	Yes
RN_staffing_rating	|	RN Staffing Rating	|	RN Staffing Rating	|	one-digit, values 1-5	|	Yes	|	Yes	|	Yes
rn_staffing_rating_fn	|	RN Staffing Rating Footnote	|	RN Staffing Rating Footnote	|	text	|	Yes	|	Yes	|	Yes
STAFFING_FLAG	|	Reported Staffing Footnote	|	Reported Staffing Footnote	|	text	|	Yes	|	Yes	|	Yes
PT_STAFFING_FLAG	|	Physical Therapist Staffing Footnote	|	Physical Therapy Staffing Footnote	|	text	|	Yes	|	Yes	|	Yes
AIDHRD	|	Reported CNA Staffing Hours per Resident per Day	|	Reported CNA Staffing - Hours per Resident per Day	|	real number, up to 5 decimal places	|	Yes	|	Yes	|	Yes
VOCHRD	|	Reported LPN Staffing Hours per Resident per Day	|	Reported LPN Staffing - Hours per Resident per Day	|	real number, up to 5 decimal places	|	Yes	|	Yes	|	Yes
RNHRD	|	Reported RN Staffing Hours per Resident per Day	|	Reported RN Staffing - Hours per Resident per Day	|	real number, up to 5 decimal places	|	Yes	|	Yes	|	Yes
TOTLICHRD	|	Reported Licensed Staffing Hours per Resident per Day	|	Reported Licensed Staffing - Hours per Resident per Day (RN + LPN)	|	real number, up to 5 decimal places	|	Yes	|	Yes	|	Yes
TOTHRD	|	Reported Total Nurse Staffing Hours per Resident per Day	|	Reported Total Nurse Staffing - Hours per Resident per Day (CNA+LPN+RN)	|	real number, up to 5 decimal places	|	Yes	|	Yes	|	Yes
PTHRD	|	Reported Physical Therapist Staffing Hours per Resident Per Day	|	Reported Physical Therapy Staffing - Hours per Resident Per Day	|	real number, up to 5 decimal places	|	Yes	|	Yes	|	Yes
exp_aide	|	Expected CNA Staffing Hours per Resident per Day	|	Expected CNA Staffing - Hours per Resident per Day	|	real number, up to 5 decimal places	|	Yes	|	Yes	|	Yes
exp_lpn	|	Expected LPN Staffing Hours per Resident per Day	|	Expected LPN Staffing - Hours per Resident per Day	|	real number, up to 5 decimal places	|	Yes	|	Yes	|	Yes
exp_rn	|	Expected RN Staffing Hours per Resident per Day	|	Expected RN Staffing - Hours per Resident per Day	|	real number, up to 5 decimal places	|	Yes	|	Yes	|	Yes
exp_total	|	Expected Total Nurse Staffing Hours per Resident per Day	|	Expected Total Nurse Staffing - Hours per Resident per Day (CNA+LPN+RN)	|	real number, up to 5 decimal places	|	Yes	|	Yes	|	Yes
adj_aide	|	Adjusted CNA Staffing Hours per Resident per Day	|	Adjusted CNA Staffing - Hours per Resident per Day	|	real number, up to 5 decimal places	|	Yes	|	Yes	|	Yes
adj_lpn	|	Adjusted LPN Staffing Hours per Resident per Day	|	Adjusted LPN Staffing - Hours per Resident per Day	|	real number, up to 5 decimal places	|	Yes	|	Yes	|	Yes
adj_rn	|	Adjusted RN Staffing Hours per Resident per Day	|	Adjusted RN Staffing - Hours per Resident per Day	|	real number, up to 5 decimal places	|	Yes	|	Yes	|	Yes
adj_total	|	Adjusted Total Nurse Staffing Hours per Resident per Day	|	Adjusted Total Nurse Staffing - Hours per Resident per Day (CNA+LPN+RN)	|	real number, up to 5 decimal places	|	Yes	|	Yes	|	Yes
cycle_1_defs	|	Cycle 1 Total Number of Health Deficiencies	|	Total Number of Health Deficiencies in Cycle 1 - See CMS 5-Star Techinical Users' Guide for description of Cycles	|	integer	|	Yes	|	Yes	|	Yes
cycle_1_nfromdefs	|	Cycle 1 Number of Standard Health Deficiencies	|	Number of Health Deficiencies from the Standard Survey During Cycle 1	|	integer	|	Yes	|	Yes	|	Yes
cycle_1_nfromcomp	|	Cycle 1 Number of Complaint Health Deficiencies	|	Number of Health Deficiencies from Complaint Surveys during Cycle 1	|	integer	|	Yes	|	Yes	|	Yes
cycle_1_defs_score	|	Cycle 1 Health Deficiency Score	|	Cycle 1 - Health Deficiency Score	|	integer	|	Yes	|	Yes	|	Yes
CYCLE_1_SURVEY_DATE	|	Cycle 1 Standard Survey Health Date	|	Date of Cycle 1 Standard Health Survey Date	|	YYYY-MM-DD	|	Yes	|	Yes	|	Yes
CYCLE_1_NUMREVIS	|	Cycle 1 Number of Health Revisits	|	Number of Health Survey Repeat-Revisits for Cycle 1	|	integer	|	Yes	|	Yes	|	Yes
CYCLE_1_REVISIT_SCORE	|	Cycle 1 Health Revisit Score	|	Points Associated with Health Survey Repeat Revisits for Cycle 1	|	integer	|	Yes	|	Yes	|	Yes
CYCLE_1_TOTAL_SCORE	|	Cycle 1 Total Health Score	|	Cycle 1 - Total Health Inspection Score	|	integer	|	Yes	|	Yes	|	Yes
cycle_2_defs	|	Cycle 2 Total Number of Health Deficiencies	|	Total Number of Health Deficiencies in Cycle 2 - See CMS 5-Star Techinical Users' Guide for description of Cycles	|	integer	|	Yes	|	Yes	|	Yes
cycle_2_nfromdefs	|	Cycle 2 Number of Standard Health Deficiencies	|	Number of Health Deficiencies from the Standard Survey during Cycle 2	|	integer	|	Yes	|	Yes	|	Yes
cycle_2_nfromcomp	|	Cycle 2 Number of Complaint Health Deficiencies	|	Number of Health Deficiencies from Complaint Surveys during Cycle 2	|	integer	|	Yes	|	Yes	|	Yes
cycle_2_defs_score	|	Cycle 2 Health Deficiency Score	|	Cycle 2 - Health Deficiency Score	|	integer	|	Yes	|	Yes	|	Yes
CYCLE_2_SURVEY_DATE	|	Cycle 2 Standard Health Survey Date	|	Date of Cycle 2 Standard Health Survey Date	|	YYYY-MM-DD	|	Yes	|	Yes	|	Yes
CYCLE_2_NUMREVIS	|	Cycle 2 Number of Health Revisits	|	Number of Health Survey Repeat-Revisits for Cycle 2	|	integer	|	Yes	|	Yes	|	Yes
CYCLE_2_REVISIT_SCORE	|	Cycle 2 Health Revisit Score	|	Points Associated with Health Survey Repeat Revisits for Cycle 2	|	integer	|	Yes	|	Yes	|	Yes
CYCLE_2_TOTAL_SCORE	|	Cycle 2 Total Health Score	|	Cycle 2 - Total Health Inspection Score	|	integer	|	Yes	|	Yes	|	Yes
cycle_3_defs	|	Cycle 3 Total Number of Health Deficiencies	|	Total Number of Health Deficiencies in Cycle 3 - See CMS 5-Star Techinical Users' Guide for description of Cycles	|	integer	|	Yes	|	Yes	|	Yes
cycle_3_nfromdefs	|	Cycle 3 Number of Standard Health Deficiencies	|	Number of Health Deficiencies from the Standard Survey during Cycle 3	|	integer	|	Yes	|	Yes	|	Yes
cycle_3_nfromcomp	|	Cycle 3 Number of Complaint Health Deficiencies	|	Number of Health Deficiencies from Complaint Surveys during Cycle 3	|	integer	|	Yes	|	Yes	|	Yes
cycle_3_defs_score	|	Cycle 3 Health Deficiency Score	|	Cycle 3 - Health Deficiency Score	|	integer	|	Yes	|	Yes	|	Yes
CYCLE_3_SURVEY_DATE	|	Cycle 3 Standard Health Survey Date	|	Date of Cycle 3 Standard Health Survey Date	|	YYYY-MM-DD	|	Yes	|	Yes	|	Yes
CYCLE_3_NUMREVIS	|	Cycle 3 Number of Health Revisits	|	Number of Health Survey Repeat-Revisits for Cycle 3	|	integer	|	Yes	|	Yes	|	Yes
CYCLE_3_REVISIT_SCORE	|	Cycle 3 Health Revisit Score	|	Points Associated with Health Survey Repeat Revisits for Cycle 3	|	integer	|	Yes	|	Yes	|	Yes
CYCLE_3_TOTAL_SCORE	|	Cycle 3 Total Health Score	|	Cycle 3 - Total Health Inspection Score	|	integer	|	Yes	|	Yes	|	Yes
WEIGHTED_ALL_CYCLES_SCORE	|	Total Weighted Health Survey Score	|	Total Weighted Health Survey Score for all 3 cycles - See CMS 5-Star Techical Users' Guide for explanation of Weighting	|	real number, up to 3 decimal places	|	Yes	|	Yes	|	Yes
incident_cnt	|	Number of Facility Reported Incidents	|	Number of Facility-Reported Incidents	|	integer	|	Yes	|	Yes	|	Yes
cmplnt_cnt	|	Number of Substantiated Complaints	|	Number of Substantiated Complaints	|	integer	|	Yes	|	Yes	|	Yes
FINE_CNT	|	Number of Fines	|	Number of Fines	|	integer	|	Yes	|	Yes	|	Yes
FINE_TOT	|	Total Amount of Fines in Dollars	|	Total Amount of Fines in Dollars	|	integer	|	Yes	|	Yes	|	Yes
PAYDEN_CNT	|	Number of Payment Denials	|	Number of Payment Denials	|	integer	|	Yes	|	Yes	|	Yes
TOT_PENLTY_CNT	|	Total Number of Penalties	|	Total Number of Penalties	|	integer	|	Yes	|	Yes	|	Yes
LOCATION	|	Location	|	Latitude and Longitude of Facility Location	|	text	|	Yes	|	No	|	No
FILEDATE	|	Processing Date	|	Date the data were retrieved	|	YYYY-MM-DD	|	Yes	|	Yes	|	Yes

## `ownerships`

Variable Name (column headers on ACCESS tables and CSV Downloadable files)	|	Label (column headers on CSV Display files)	|	Description	|	Format / Values	|	On CSV Display File	|	On CSV Download File	|	On Access Table
--- | --- | --- | --- | --- | --- | --- 
PROVNUM	|	Federal Provider Number	|	Provider Number	|	6 alphanumeric characters	|	Yes	|	Yes	|	Yes
PROVNAME	|	Provider Name	|	Provider Name	|	text	|	Yes	|	Yes	|	Yes
address	|	Provider Address	|	Provider Address	|	text	|	Yes	|	Yes	|	Yes
city	|	Provider City	|	Provider City	|	text	|	Yes	|	Yes	|	Yes
state	|	Provider State	|	Provider State	|	2-character postal abbreviation	|	Yes	|	Yes	|	Yes
zip	|	Provider Zip Code	|	Provider Zip Code	|	5-digit zip code	|	Yes	|	Yes	|	Yes
survey_date_output	|	Survey Date	|	Survey Date	|	YYYY-MM-DD	|	Yes	|	Yes	|	Yes
SurveyType	|	Survey Type	|	Type of survey: Health or Fire Safety	|	text	|	Yes	|	Yes	|	Yes
DEFPREF	|	Deficiency Prefix	|	The alphabetic character that is assigned to a series of data tags that apply to a provider	|	text	|	Yes	|	Yes	|	Yes
TAG	|	Deficiency Tag Number	|	Deficiency Tag Number	|	4-digit tag code	|	Yes	|	Yes	|	Yes
TAG_DESC	|	Deficiency Description	|	Text definition of deficiency	|	text	|	Yes	|	Yes	|	Yes
SCOPE	|	Scope Severity Code	|	Indicates the level of harm to the resident(s) involved and the scope of the problem within the nursing home.	|	text	|	Yes	|	Yes	|	Yes
DEFSTAT	|	Deficiency Corrected	|	Indicates whether the deficiency has been corrected, a plan of correction has been devised, or the deficiency has yet to be corrected	|	text	|	Yes	|	Yes	|	Yes
statdate	|	Correction Date	|	Date the deficiency was corrected	|	YYYY-MM-DD	|	Yes	|	Yes	|	Yes
cycle	|	Inspection Cycle	|	The inspection cycle of deficiency, where 1 is the most recent cycle. Standard inspection cycles are counted sequentially into the past, complaint inspection cycles are counted annually into the past. If a defiency is found on a co-occurring standard and complaint inspection, it is assigned to the standard cycle.  Please refer to the 5-star Technical Users Guide for further information.	|	integer	|	Yes	|	Yes	|	Yes
standard	|	Standard Deficiency	|	Indicates that the deficiency was found on a standard inspection	|	Y/N	|	Yes	|	Yes	|	Yes
complaint	|	Complaint Deficiency	|	Indicates that the deficiency was found on a complaint inspection	|	Y/N	|	Yes	|	Yes	|	Yes
location	|	Location	|	Latitude and Longitude of Facility Location	|	text	|	Yes	|	No	|	No
filedate	|	Processing Date	|	Date the data were retrieved	|	YYYY-MM-DD	|	Yes	|	Yes	|	Yes

## `penalties`

Variable Name (column headers on ACCESS tables and CSV Downloadable files)	|	Label (column headers on CSV Display files)	|	Description	|	Format / Values	|	On CSV Display File	|	On CSV Download File	|	On Access Table
--- | --- | --- | --- | --- | --- | --- 
PROVNUM	|	Federal Provider Number	|	Provider Number	|	6 alphanumeric characters	|	Yes	|	Yes	|	Yes
PROVNAME	|	Provider Name	|	Provider Name	|	text	|	Yes	|	Yes	|	Yes
address	|	Provider Address	|	Provider Address	|	text	|	Yes	|	Yes	|	Yes
city	|	Provider City	|	Provider City	|	text	|	Yes	|	Yes	|	Yes
state	|	Provider State	|	Provider State	|	2-character postal abbreviation	|	Yes	|	Yes	|	Yes
zip	|	Provider Zip Code	|	Provider Zip Code	|	5-digit zip code	|	Yes	|	Yes	|	Yes
cycle	|	Inspection Cycle	|	The inspection cycle of deficiency, where 1 is the most recent cycle. Standard inspection cycles are counted sequentially into the past.	|	integer (1, 2 or 3)	|	Yes	|	Yes	|	Yes
H_SURVEY_DATE	|	Health Survey Date	|	Health Survey Date	|	YYYY-MM-DD	|	Yes	|	Yes	|	Yes
F_SURVEY_DATE	|	Fire Safety Survey Data	|	Fire Safety Survey Date	|		|		|		|	
H_TOT_DFCNCY	|	Total Number of Health Deficiencies 	|	Total Number of Health Deficiencies 	|	integer (0-nn)	|	Yes	|	Yes	|	Yes
F_TOT_DFCNCY	|	Total Number of Fire Safety Deficiencies 	|	Total Number of Fire Safety Deficiencies 	|	integer (0-nn)	|	Yes	|	Yes	|	Yes
H_SS_MAX	|	Scope and Severity of most Severe Health Deficiency	|	Scope and Severity Code of most Severe Health Deficiency	|	Letter (B-L)	|	Yes	|	Yes	|	Yes
F_SS_MAX	|	Scope and Severity of most Severe Fire Safety Deficiency	|	Scope and Severity Code of most Severe Health Deficiency	|	Letter (B-L)	|	Yes	|	Yes	|	Yes
H_IJ_N	|	Count of Immediate Jeopardy Deficiencies on Health Survey	|	Count of Immediate Jeopardy Deficiencies on Health Survey; IJ deficiencies are those with Scope/Severity code of J,K or L	|	integer (0-nn)	|	Yes	|	Yes	|	Yes
F_IJ_N	|	Count of Immediate Jeopardy Deficiencies on Fire Safety Survey	|	Count of Immediate Jeopardy Deficiencies on Fire Safety Survey; IJ deficiencies are those with Scope/Severity code of J,K or L	|	integer (0-nn)	|	Yes	|	Yes	|	Yes
H_SEVERE_N	|	Count of Severe Deficiencies on Health Survey	|	Count of Severe Deficiencies on Health Survey; Severe deficiencies are those with Scope/Severity Code of G or higher	|	integer (0-nn)	|	Yes	|	Yes	|	Yes
F_SEVERE_N	|	Count of Severe Deficiencies on Fire Safety Survey	|	Count of Severe Deficiencies on Fire Safety Survey; Severe deficiencies are those with Scope/Severity Code of G or higher	|	integer (0-nn)	|	Yes	|	Yes	|	Yes
H_SUBSTNDRD_QOC_N	|	Count of Substandard QOC Deficiencies on Health Survey	|	Count of Health Deficiencies indicating Substandard Quality of Care; See technical users guide for more information	|	integer (0-nn)	|	Yes	|	Yes	|	Yes
H_ADMINISTRATION_N	|	Count of Administration Deficiencies (Health)	|	Count of Administration Deficiencies (Health)	|	integer (0-nn)	|	Yes	|	Yes	|	Yes
H_ENVIRONMENTAL_N	|	Count of Environmental Deficiencies (Health)	|	Count of Environmental Deficiencies (Health)	|	integer (0-nn)	|	Yes	|	Yes	|	Yes
H_MISTREAT_N	|	Count of Mistreatment Deficiencies (Health)	|	Count of Mistreatment Deficiencies (Health)	|	integer (0-nn)	|	Yes	|	Yes	|	Yes
H_NUTRITION_N	|	Count of Nutrition and Dietary Deficiencies (Health)	|	Count of Nutrition and Dietary Deficiencies (Health)	|	integer (0-nn)	|	Yes	|	Yes	|	Yes
H_PHARMACY_N	|	Count of Pharmacy Service Deficiencies (Health)	|	Count of Pharmacy Service Deficiencies (Health)	|	integer (0-nn)	|	Yes	|	Yes	|	Yes
H_QUALITY_CARE_N	|	Count of Quality of Care Deficiencies (Health)	|	Count of Quality of Care Deficiencies (Health)	|	integer (0-nn)	|	Yes	|	Yes	|	Yes
H_RES_ASMNT_N	|	Count of Resident Assessment Deficiencies (Health)	|	Count of Resident Assessment Deficiencies (Health)	|	integer (0-nn)	|	Yes	|	Yes	|	Yes
H_RES_RIGHTS_N	|	Count of Resident Rights Deficiencies (Health)	|	Count of Resident Rights Deficiencies (Health)	|	integer (0-nn)	|	Yes	|	Yes	|	Yes
F_CONSTRUCTION_N	|	Count of Building Construction Deficiencies (Fire Safety)	|	Count of Building Construction Deficiencies (Fire Safety)	|	integer (0-nn)	|	Yes	|	Yes	|	Yes
F_CORRIDOR_DOORS_N	|	Count of Corridor Walls and Doors Deficiencies (Fire Safety)	|	Count of Corridor Walls and Doors Deficiencies (Fire Safety)	|	integer (0-nn)	|	Yes	|	Yes	|	Yes
F_ELECTRICAL_N	|	Count of Electrical Deficiencies (Fire Safety)	|	Count of Electrical Deficiencies (Fire Safety)	|	integer (0-nn)	|	Yes	|	Yes	|	Yes
F_EMERGENCY_PLAN_N	|	Count of Emergency Plans and Fire Drills Deficiencies (Fire Safety)	|	Count of Emergency Plans and Fire Drills Deficiencies (Fire Safety)	|	integer (0-nn)	|	Yes	|	Yes	|	Yes
F_EXIT_EGRESS_N	|	Count of Exits and Egress Deficiencies (Fire Safety)	|	Count of Exits and Egress Deficiencies (Fire Safety)	|	integer (0-nn)	|	Yes	|	Yes	|	Yes
F_EXIT_ACCESS_N	|	Count of Exit and Exit Access Deficiencies (Fire Safety)	|	Count of Exit and Exit Access Deficiencies (Fire Safety)	|	integer (0-nn)	|	Yes	|	Yes	|	Yes
F_FIRE_ALARM_N	|	Count of Fire Alarm Systems Deficiencies (Fire Safety)	|	Count of Fire Alarm Systems Deficiencies (Fire Safety)	|	integer (0-nn)	|	Yes	|	Yes	|	Yes
F_FURNISHINGS_N	|	Count of Furnishings and Decorations Deficiencies (Fire Safety)	|	Count of Furnishings and Decorations Deficiencies (Fire Safety)	|	integer (0-nn)	|	Yes	|	Yes	|	Yes
F_HAZARD_AREA_N	|	Count of Hazardous Area Deficiencies (Fire Safety)	|	Count of Hazardous Area Deficiencies (Fire Safety)	|	integer (0-nn)	|	Yes	|	Yes	|	Yes
F_ILLUMINATION_N	|	Count of Illumination and Emergency Power Deficiencies (Fire Safety)	|	Count of Illumination and Emergency Power Deficiencies (Fire Safety)	|	integer (0-nn)	|	Yes	|	Yes	|	Yes
F_INTERIOR_N	|	Count of Interior Finish Deficiencies (Fire Safety)	|	Count of Interior Finish Deficiencies (Fire Safety)	|	integer (0-nn)	|	Yes	|	Yes	|	Yes
F_LABORATORIES_N	|	Count of Laboratories Deficiencies (Fire Safety)	|	Count of Laboratories Deficiencies (Fire Safety)	|	integer (0-nn)	|	Yes	|	Yes	|	Yes
F_MEDICAL_GAS_N	|	Count of Medical Gases and Anesthetizing Areas Deficiencies (Fire Safety)	|	Count of Medical Gases and Anesthetizing Areas Deficiencies (Fire Safety)	|	integer (0-nn)	|	Yes	|	Yes	|	Yes
F_MISCELLANEOUS_N	|	Count of Miscellaneous Deficiencies (Fire Safety)	|	Count of Miscellaneous Deficiencies (Fire Safety)	|	integer (0-nn)	|	Yes	|	Yes	|	Yes
F_SERVICE_EQUIPMENT_N	|	Count of Building Service Equipment Deficiencies (Fire Safety)	|	Count of Building Service Equipment Deficiencies (Fire Safety)	|	integer (0-nn)	|	Yes	|	Yes	|	Yes
F_SMOKE_CONTROL_N	|	Count of Smoke Compartmentation and Control Deficiencies (Fire Safety)	|	Count of Smoke Compartmentation and Control Deficiencies (Fire Safety)	|	integer (0-nn)	|	Yes	|	Yes	|	Yes
F_SMOKING_REG_N	|	Count of Smoking Regulations Deficiencies (Fire Safety)	|	Count of Smoking Regulations Deficiencies (Fire Safety)	|	integer (0-nn)	|	Yes	|	Yes	|	Yes
F_SPRINKLER_N	|	Count of Automatic Sprinkler Systems Deficiencies (Fire Safety)	|	Count of Automatic Sprinkler Systems Deficiencies (Fire Safety)	|	integer (0-nn)	|	Yes	|	Yes	|	Yes
F_VERT_OPENINGS_N	|	Count of Vertical Openings Deficiencies (Fire Safety)	|	Count of Vertical Openings Deficiencies (Fire Safety)	|	integer (0-nn)	|	Yes	|	Yes	|	Yes
location	|	Location	|	Latitude and Longitude of Facility Location	|	text	|	Yes	|	No	|	No
filedate	|	Processing Date	|	Date the data were retrieved	|	YYYY-MM-DD	|	Yes	|	Yes	|	Yes

## `providers`

## `quality_ratings`

## `state_summaries`

## `survey_averages`