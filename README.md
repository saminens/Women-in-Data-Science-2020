# Women-in-Data-Science-2020
The WiDS Datathon 2020 focuses on patient health through data from MIT’s GOSSIS (Global Open Source Severity of Illness Score) initiative. Brought to you by the Global WiDS team, the West Big Data Innovation Hub, and the WiDS Datathon Committee, this year’s datathon is open until February 24, 2020. Winners will be announced at the WiDS Conference at Stanford University and via livestream, reaching a community of 100,000+ data enthusiasts across more than 50 countries.

The challenge is to create a model that uses data from the first 24 hours of intensive care to predict patient survival. MIT's GOSSIS community initiative, with privacy certification from the Harvard Privacy Lab, has provided a dataset of more than 130,000 hospital Intensive Care Unit (ICU) visits from patients, spanning a one-year timeframe. This data is part of a growing global effort and consortium spanning Argentina, Australia, New Zealand, Sri Lanka, Brazil, and more than 200 hospitals in the United States.

The solution : 
Performed feature engineering:
  1. Imputed missing values using fancyimpute
  2. Label encoded categorical features
  3. Removed highly correlated features

Trained a Light Gradient Boosting Model :
  1. Performed hyperparameter optimization using hyperopts
  2. Stratified k-fold cross validation
  3. Checked feature importance

Adversarial Validation :
  Test drift in features between test and train dataset. Check distributions!!

Shap values :
  Check the variable importance
  1. Feature importance: Variables are ranked in descending order.
  2. Value: Color shows whether that variable is high (in red) or low (in blue) for that observation.
  3. Correlation:  The “high” comes from the red color, and the “positive” impact is shown on the X-axis.

Predict the labels.....!

