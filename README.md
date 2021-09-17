# MachineLearningProject

### Link to the "Pump it Up: Data Mining the Water Table" challenge
https://github.com/HashiniDisanayaka/MachineLearningProject/blob/main/PumpItUpDataMiningTheWaterTableMLchallenge.ipynb

## Preprocessing Techniques :
### Label Encoding
* By using a for loop, the label encoding is done by manually and each label is assigned a unique integer based on alphabetical ordering.

## Feature Engineering Techniques : 
### Target Encoding
* Target variable: status_group = [functional, non functional, functional needs repair]
* Classification using RandomForestClassifier
* Fit encoder: Classifier.fit(X,Y)
### Feature Selection : 
* Features for trainning: 'installer', 'latitude', 'wpt_name', 'num_private', 'basin', 'subvillage', 'district_code', 'lga', 'population', 'scheme_name', 'extraction_type_class', 'management_group', 'source_type'

## Proof of Submission
![MachineLearningChallenge_submission](https://user-images.githubusercontent.com/47105941/133821927-c4e1681e-e1e7-4a05-8ef9-91297ea155df.png)

## Final Rank
![MachineLearningChallenge_rank](https://user-images.githubusercontent.com/47105941/133821781-18bcdf65-4bce-4504-8f04-aeb83221722c.png)
