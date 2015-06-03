# Metadata: Ownerships

Variable Name (column headers on ACCESS tables and CSV Downloadable files)	|	Label (column headers on CSV Display files)	|	Description	|	Format / Values	|	On CSV Display File	|	On CSV Download File	|	On Access Table
--- | --- | --- | --- | --- | --- | ---
PROVNUM	|	Federal Provider Number	|	Federal Provider Number	|	6 alphanumeric characters	|	Yes	|	Yes	|	Yes
PROVNAME	|	Provider Name	|	Provider Name	|	text	|	Yes	|	Yes	|	Yes
address	|	Provider Address	|	Provider Address	|	text	|	Yes	|	Yes	|	Yes
CITY	|	Provider City	|	Provider City	|	text	|	Yes	|	Yes	|	Yes
STATE	|	Provider State	|	Provider State	|	2-character postal abbreviation	|	Yes	|	Yes	|	Yes
ZIP	|	Provider Zip Code	|	Provider Zip Code	|	5-digit zip code	|	Yes	|	Yes	|	Yes
ROLE_DESC	|	Role played by Owner or Manager in Facility	|	Role Description	|	"text; values are: 5% OR GREATER DIRECT OWNERSHIP INTEREST; 5% OR GREATER INDIRECT OWNERSHIP INTEREST; 5% OR GREATER MORTGAGE INTEREST; 5% OR GREATER SECURITY INTEREST; DIRECTOR; MANAGING EMPLOYEE; OFFICER; OPERATIONAL/MANAGERIAL CONTROL; PARTNERSHIP INTEREST; if there is no ownership data available for this PROVNUM, Role Description = ""Ownership Data Not Available"" and other ownership fields will be blank (null)"	|	Yes	|	Yes	|	Yes
OWNER_TYPE	|	Owner Type	|	Indicates if owner is an individual or organization	|	"Individual" or "Organization"	|	Yes	|	Yes	|	Yes
OWNER_NAME	|	Owner Name	|	Name of Owner	|	text: name of organization, or, if an individual, formatted as "LastName, FirstName"	|	Yes	|	Yes	|	Yes
OWNER_PERCENTAGE	|	Ownership Percentage	|	Last Name	|	text: NN% or "No Percentage Provided"; value provided only for owners with ROLE_DESC of "5% OR GREATER DIRECT OWNERSHIP INTEREST" or "5% OR GREATER INDIRECT OWNERSHIP INTEREST"; for other ROLE_DESC values, "Not Applicable"	|	Yes	|	Yes	|	Yes
ASSOCIATION_DATE	|	Association Date	|	Date when given owner/manager became associated with provider in this role	|	text: "since MM/DD/YYYY" or "No Date Provided"	|	Yes	|	Yes	|	Yes
location	|	Location	|	Latitude and Longitude of Facility Location	|	text	|	Yes	|	No	|	No
filedate	|	Processing Date	|	Date the data were retrieved	|	YYYY-MM-DD	|	Yes	|	Yes	|	Yes
