# MachineLearningProject

### Link to the "Pump it Up: Data Mining the Water Table" challenge
https://github.com/HashiniDisanayaka/MachineLearningProject/blob/main/PumpItUpDataMiningTheWaterTableMLchallenge.ipynb

## The features in this dataset

### Your goal is to predict the operating condition of a waterpoint for each record in the dataset. You are provided the following set of information about the waterpoints:

* amount_tsh - Total static head (amount water available to waterpoint)
* date_recorded - The date the row was entered
* funder - Who funded the well
* gps_height - Altitude of the well
* installer - Organization that installed the well
* longitude - GPS coordinate
* latitude - GPS coordinate
* wpt_name - Name of the waterpoint if there is one
* num_private -
* basin - Geographic water basin
* subvillage - Geographic location
* region - Geographic location
* region_code - Geographic location (coded)
* district_code - Geographic location (coded)
* lga - Geographic location
* ward - Geographic location
* population - Population around the well
* public_meeting - True/False
* recorded_by - Group entering this row of data
* scheme_management - Who operates the waterpoint
* scheme_name - Who operates the waterpoint
* permit - If the waterpoint is permitted
* construction_year - Year the waterpoint was constructed
* extraction_type - The kind of extraction the waterpoint uses
* extraction_type_group - The kind of extraction the waterpoint uses
* extraction_type_class - The kind of extraction the waterpoint uses
* management - How the waterpoint is managed
* management_group - How the waterpoint is managed
* payment - What the water costs
* payment_type - What the water costs
* water_quality - The quality of the water
* quality_group - The quality of the water
* quantity - The quantity of water
* quantity_group - The quantity of water
* source - The source of the water
* source_type - The source of the water
* source_class - The source of the water
* waterpoint_type - The kind of waterpoint
* waterpoint_type_group - The kind of waterpoint

## Distribution of Labels
### The labels in this dataset are simple. There are three possible values:

* functional - the waterpoint is operational and there are no repairs needed
* functional needs repair - the waterpoint is operational, but needs repairs
* non functional - the waterpoint is not operational

## Preprocessing Techniques :
### Label encoding
* by using a for loop, the label encoding is done by manually and each label is assigned a unique integer based on alphabetical ordering.

## Feature engineering techniques
### Target encoding
* Features for trainning : functional, non functional, functional needs repair
* Classification using RandomForestClassifier

## Proof of Submission
![MachineLearningChallenge](https://user-images.githubusercontent.com/47105941/133801671-a0561fdc-18a1-4dd5-bb37-dc87adab5173.png)
