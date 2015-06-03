Metadata: Penalties

Variable Name (column headers on ACCESS tables and CSV Downloadable files)	|	Label (column headers on CSV Display files)	|	Description	|	Format / Values	|	On CSV Display File	|	On CSV Download File	|	On Access Table
--- | --- | --- | --- | --- | --- | ---
PROVNUM	|	Federal Provider Number	|	Federal Provider Number	|	6 alphanumeric characters	|	Yes	|	Yes	|	Yes
PROVNAME	|	Provider Name	|	Provider Name	|	text  	|	Yes	|	Yes	|	Yes
address	|	Provider Address	|	Provider Address	|	text	|	Yes	|	Yes	|	Yes
city	|	Provider City	|	Provider City	|	text	|	Yes	|	Yes	|	Yes
state	|	Provider State	|	Provider State	|	2-character postal abbreviation	|	Yes	|	Yes	|	Yes
zip	|	Provider Zip Code	|	Provider Zip Code	|	5-digit zip code	|	Yes	|	Yes	|	Yes
pnlty_date	|	Penalty Date	|	Date of inspection that triggered the penalty	|	YYYY-MM-DD	|	Yes	|	Yes	|	Yes
pnlty_type	|	Penalty Type	|	Penalty type: Fine or Payment Denial	|	text	|	Yes	|	Yes	|	Yes
fine_amt	|	Fine Amount	|	Fine amount in whole dollars	|	integer 	|	Yes	|	Yes	|	Yes
payden_strt_dt	|	Payment Denial Start Date	|	Date on which Medicare/Medicaid payment for new admissions was suspended	|	YYYY-MM-DD	|	Yes	|	Yes	|	Yes
payden_days	|	Payment Denial Length in Days	|	Number of days for which Medicare/Medicaid payment was suspended	|	integer 	|	Yes	|	Yes	|	Yes
location	|	Location	|	Latitude and Longitude of Facility Location	|	text	|	Yes	|	No	|	No
filedate	|	Processing Date	|	Date the data were retrieved	|	YYYY-MM-DD	|	Yes	|	Yes	|	Yes