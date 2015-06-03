# Metadata: Survey Summaries

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
