# MachineLearningProject

### Link to the answer code for "Pump it Up: Data Mining the Water Table" challenge in GitHub :
https://github.com/HashiniDisanayaka/MachineLearningProject/blob/main/PumpItUpDataMiningTheWaterTableMLchallenge.ipynb

## Introduction to the problem:

"Pump it Up: Data Mining the Water Table" (competition link: https://www.drivendata.org/competitions/7/pump-it-up-data-mining-the-water-table/). Here the goal is to predict the operating condition of a waterpoint for each record in the dataset. A set of information about the waterpoints are provided there. 

### Distribution of Labels
#### The labels in this dataset are simple. There are three possible values:

* functional - the waterpoint is operational and there are no repairs needed
* functional needs repair - the waterpoint is operational, but needs repairs
* non functional - the waterpoint is not operational

## Preprocessing Techniques :
### Label Encoding
* By using a for loop, the label encoding is done by manually and each label is assigned a unique integer based on alphabetical ordering.
* Removed some features from the colunm labels.

## Feature Engineering Techniques : 
### Target Encoding
* Target variable: status_group = [functional, non functional, functional needs repair]
* Classification using RandomForestClassifier
* Fit encoder: Classifier.fit(X,Y)
### Feature Selection : 
* Features for trainning: 'installer', 'latitude', 'wpt_name', 'num_private', 'basin', 'subvillage', 'district_code', 'lga', 'population', 'scheme_name', 'extraction_type_class', 'management_group', 'source_type'
### Classifier
* RandomForestClassifier

## Steps in brief 
1. Preprocessing the given csv data files using label encoding 
2. Then combine the train value and train label processed files to get the train data
3. Then select the features for the trainning
4. Set the target variables
5. Classification and Feature engineering
6. Prediction for test data
7. Create the Submission file and store data

## Proof of Submission
![MachineLearningChallenge_submission](https://user-images.githubusercontent.com/47105941/133821927-c4e1681e-e1e7-4a05-8ef9-91297ea155df.png)

## Final Rank
![MachineLearningChallenge_rank](https://user-images.githubusercontent.com/47105941/133821781-18bcdf65-4bce-4504-8f04-aeb83221722c.png)
