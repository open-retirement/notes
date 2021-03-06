# Metadata: MSR (Quality Ratings)

Variable Name (column headers on ACCESS tables and CSV Downloadable files)	|	Label (column headers on CSV Display files)	|	Description	|	Format / Values	|	On CSV Display File	|	On CSV Download File	|	On Access Table
--- | --- | --- | --- | --- | --- | ---
PROVNUM	|	Federal Provider Number	|	Federal Provider Number	|	6 alphanumeric characters	|	Yes	|	Yes	|	Yes
PROVNAME	|	Provider Name	|	Provider Name	|	text	|	Yes	|	Yes	|	Yes
address	|	Provider Address	|	Provider Address	|	text	|	Yes	|	Yes	|	Yes
city	|	Provider City	|	Provider City	|	text	|	Yes	|	Yes	|	Yes
state	|	Provider State	|	Provider State	|	2-character postal abbreviation	|	Yes	|	Yes	|	Yes
zip	|	Provider Zip Code	|	Provider Zip Code	|	5-digit zip code	|	Yes	|	Yes	|	Yes
msr_cd	|	Measure Code	|	Numeric code assigned to each quality measure	|	integer	|	Yes	|	Yes	|	Yes
msr_descr	|	Measure Description	|	Measure Description	|	text	|	Yes	|	Yes	|	Yes
stay_type	|	Resident type	|	Identifies the measure as pertaining to either short-stay or long-stay stay residents	|	text	|	Yes	|	Yes	|	Yes
q1_measure_score	|	Q1 Measure Score	|	The value for the quality measure for quarter one	|	real number, six decimal places	|	Yes	|	Yes	|	Yes
q1_measure_fn	|	Footnote for Q1 Measure Score	|	Footnote for the quality measure for quarter one	|	text	|	Yes	|	Yes	|	Yes
q2_measure_score	|	Q2 Measure Score	|	The value for the quality measure for quarter two	|	real number, six decimal places	|	Yes	|	Yes	|	Yes
q2_measure_fn	|	Footnote for Q2 Measure Score	|	Footnote for the quality measure for quarter two	|	text	|	Yes	|	Yes	|	Yes
q3_measure_score	|	Q3 Measure Score	|	The value for the quality measure for quarter three	|	real number, six decimal places	|	Yes	|	Yes	|	Yes
q3_measure_fn	|	Footnote for Q3 Measure Score	|	Footnote for the quality measure for quarter three	|	text	|	Yes	|	Yes	|	Yes
measure_score_3qtr_avg	|	Three Quarter Average	|	The value for the three quarter average	|	real number, six decimal places	|	Yes	|	Yes	|	Yes
score3qtr_fn	|	Footnote for Three Quarter Average	|	Footnote for Three Quarter Average	|	text	|	Yes	|	Yes	|	Yes
five_star_msr	|	Used in Quality Measure Five Star Rating	|	Identifies whether the quality measure is used in the calculation of the quality measure rating in the Five-Star Quality Rating System	|	Y/N	|	Yes	|	Yes	|	Yes
q1_quarter	|	Q1 quarter	|	Identifies the calendar quarter associated with quarter 1	|	text	|	Yes	|	Yes	|	Yes
q2_quarter	|	Q2 quarter	|	Identifies the calendar quarter associated with quarter 2	|	text	|	Yes	|	Yes	|	Yes
q3_quarter	|	Q3 quarter	|	Identifies the calendar quarter associated with quarter 3	|	text	|	Yes	|	Yes	|	Yes
location	|	Location	|	Latitude and Longitude of Facility Location	|	text	|	Yes	|	No	|	No
filedate	|	Processing Date	|	Date the data were retrieved	|	YYYY-MM-DD	|	Yes	|	Yes	|	Yes