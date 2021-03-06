# Metadata: Deficiencies

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
