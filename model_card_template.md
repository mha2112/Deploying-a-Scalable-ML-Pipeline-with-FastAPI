# Model Card

For additional information see the Model Card paper: https://arxiv.org/pdf/1810.03993.pdf

## Model Details
Salary prediction from census data using a random forest classifier. Random forest uses multiple decision trees to train the data that improves training efficiency being an ensemble. 
OneHotEncoding is used for the categorical column information and the labelBinarizer for the Salary column.

## Intended Use
Salary prediction from census data shows what common categories make less than or greater than 50K a year. 

## Training Data

## Evaluation Data

## Metrics
precision, recall and F1 score
_Please include the metrics used and your model's performance on those metrics._

## Ethical Considerations
The model will predict salary based on the other categorical information and is using performance slicing to id bias or gender, sex, race. 

## Caveats and Recommendations
