# Links/Resources

 + http://pension360.org/
 + http://openretirement.org/about-us/
 + http://cms.gov/
 + http://medicare.gov/nursinghomecompare/search.html
 + https://data.medicare.gov/data/nursing-home-compare
 + https://data.medicare.gov/data/archives/nursing-home-compare (download the dataset)

# Problems/ Opportunities

 + Improve the process of finding and choosing a nursing home.
 + Open up the data in a programmatic way (API).
 + Provide and access additional feedback on nursing homes (*yelp*).

# Dataset Notes and Queries

Nursing homes are represented as `providers`. 
The dataset is not normalized, as provider information is duplicated across different tables.
Several tables lack unique identifiers, which will need to be added.

## `deficiences`

Violations of various types. A provider can have one (zero?) or more `deficiencies`.

surveyType  | defstat | provider_count
--- | --- | ---
Health  | Deficient, Provider has date of correction  | 15397
Fire Safety | Deficient, Provider has date of correction  | 14225
Health  | Deficient, Provider has plan of correction  | 2162
Fire Safety | Deficient, Provider has plan of correction  | 1482
Health  | Deficient, Provider has no plan of correction | 1320
Fire Safety | Deficient, Provider has no plan of correction | 950
Health  | Past Non-Compliance | 535
Health  | Waiver has been granted | 398
Fire Safety | Fire Safety Evaluation Survey | 101
Fire Safety | Past Non-Compliance | 31
Fire Safety | Waiver has been granted | 13

## `ownerships`

Providers are owned/operated by one or more `owners`.

## `penalties`

Fines and payments. A provider can have one (zero?) or more `penalties`.

## `providers`

The central table of this dataset. Primary key is `PROVNUM`.

## `quality_ratings` / `quality_measures`

Quality scores for each provider.

msr_cd  | msr_descr | stay_type | count(DISTINCT provnum)
--- | --- | --- | ---
401 | Percent of Long Stay Residents Whose Need for Help with ADLs has Increased  | Long Stay | 15654
430 | Percent of Short Stay Residents Assessed and Appropriately Given the Pneumococcal Vaccine | Short Stay  | 15654
402 | Percent of Long Stay Residents Who Self Report Moderate to Severe Pain  | Long Stay | 15654
434 | Percent of Short Stay Residents Who Newly Received an Antipsychotic Medication  | Short Stay  | 15654
403 | Percent of High Risk Long Stay Residents With Pressure Ulcers | Long Stay | 15654
404 | Percent of Long Stay Residents Who Lose Too Much Weight | Long Stay | 15654
405 | Percent of Low Risk Long Stay Residents Who Lose Control of Their Bowel or Bladder  | Long Stay | 15654
406 | Percent of Long Stay Residents with a Catheter Inserted and Left in Their Bladder | Long Stay | 15654
407 | Percent of Long Stay Residents With a Urinary Tract Infection | Long Stay | 15654
408 | Percent of Long Stay Residents Who Have Depressive Symptoms | Long Stay | 15654
409 | Percent of Long Stay Residents Who Were Physically Restrained | Long Stay | 15654
410 | Percent of Long Stay Residents Experiencing One or More Falls with Major Injury | Long Stay | 15654
411 | Percent of Long Stay Residents Assessed and Appropriately Given the Seasonal Influenza Vaccine  | Long Stay | 15654
415 | Percent of Long Stay Residents Assessed and Appropriately Given the Pneumococcal Vaccine  | Long Stay | 15654
419 | Percent of Long Stay Residents Who Received an Antipsychotic Medication | Long Stay | 15654
424 | Percent of Short Stay Residents Who Self Report Moderate to Severe Pain | Short Stay  | 15654
425 | Percent of Short Stay Residents With Pressure Ulcers That Are New or Worsened | Short Stay  | 15654
426 | Percent of Short Stay Residents Who Were Assessed and Appropriately Given the Seasonal Influenza Vaccine  | Short Stay  | 15654

## `state_averages`

Aggregates.

## `survey_summaries`

Aggregates.
