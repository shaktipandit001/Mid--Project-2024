# Data Analytics - Jan-June 2024
## Bootcamp Mid-project

**Author:** Shakti

### What is this project about?
During inspections of food facilities, health inspectors calculate a score based on observed violations. These violations can be categorized as:

- High-risk: Specific violations directly related to the transmission of foodborne illnesses, adulteration of food products, and contamination of food-contact surfaces.
- Moderate-risk: Specific violations posing a moderate risk to public health and safety.
- Low-risk: Violations with low or no immediate risk to public health and safety.

The scorecard issued by the inspector is maintained at the food establishment and is available to the public in this dataset.

### Overview:
This dataset provides information about the hygiene standards of restaurants, which is important for public awareness.

### Data Science Applications:
This dataset, although compact, is ripe for a variety of data science explorations, including:

- Market Trend Analysis: Identifying evolving trends in inspection scores.
- Predictive Modeling: Forecasting future inspection scores and determining the best places and how hygienic their food is.
- Recommendations: Developing algorithms to suggest the expected inspection scores for different establishments.
- Prediction of Next Visit Score: Predicting the score for the next inspection.
- Train-Test Split.
- Decision Tree Classifier.
- Decision Tree Regressor.

### What is the dataset?
[Historical] Restaurant Inspection Scores (2016-2019)
Updated March 13, 2024, by the Publishing Department of Public Health (Real Data)
License: Open Data Commons Public Domain Dedication and License

### Source Link:
[San Francisco Department of Public Health - Food Safety](http://www.sfdph.org/dph/EH/Food/score/default.asp)
Date Created: October 28, 2015
Details about Data: Rows - 54k, Columns - 17

#### Dataset Details:
The dataset is structured into key columns, detailed as follows:

- **business_id:** Plain Text
- **business_name:** Plain Text
- **business_address:** Plain Text
- **business_city:** Plain Text
- **business_state:** Plain Text
- **business_postal_code:** Plain Text
- **business_latitude:** Number
- **business_longitude:** Number
- **business_location:** Point
- **business_phone_number:** Plain Text
- **inspection_id:** Plain Text
- **inspection_date:** Date & Time
- **inspection_score:** Number
- **inspection_type:** Plain Text 
- **violation_id:** Plain Text
- **violation_description:** Plain Text
- **risk_category:** Plain Text
