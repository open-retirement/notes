# Metadata: Providers

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
