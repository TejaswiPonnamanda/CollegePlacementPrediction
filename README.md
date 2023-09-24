

https://github.com/TejaswiPonnamanda/CollegePlacementPrediction/assets/121274581/e1d25e60-93ba-44eb-9bc5-450b92dd07bc

# CollegePlacementPrediction
This is a ML Web app to predict college placements for each individual based on some educational features

# Tech Stack:
HTML, CSS, Python.
Flask framework.
Jupyter Notebook.

# Dataset 
The dataset downloaded from the www.Kaggle.com for testing.

# Features
By leveraging the Random Forest Classification technique, the model has been train to analyze the input parameteers and makes predictions ragarding the outcome.
The Machine Learing Model (Random Forest Classification) achieved 94% precision and 88% accuracy.



# Workflow
# Input Parameters:

The web app takes input parameters from the user. These parameters typically include:
Stream (e.g., CSE, Civil, Electronics, etc.)
CGPA (Cumulative Grade Point Average)
Number of Previous Internships
Number of Backlogs
Gender

# Data Validation:

The input data is validated to ensure it meets the required criteria. For example, CGPA should be within a certain range, the number of internships and backlogs should be non-negative integers, and the stream and gender should be selected from predefined options.
# Feature Engineering:

The input parameters are processed and transformed as needed to match the format used during model training. This may involve encoding categorical variables, scaling numerical features, or other preprocessing steps.
# Model Prediction:

The preprocessed input data is passed to a Random Forest Classification model. This machine learning model has been trained on historical placement data and is capable of making predictions about whether a student is likely to be placed.
# Prediction Output:

The model produces a prediction output, typically binary:
Positive prediction (e.g., 1) indicates that the model predicts the student is likely to get placed.
Negative prediction (e.g., 0) indicates that the model predicts the student is less likely to get placed.
#  Display Prediction:

The web app displays the prediction result to the user, indicating whether the student is likely to be placed or not.
Model Evaluation Metrics (Optional):

Optionally, the web app can display additional information such as model accuracy, precision, recall, or F1-score to provide users with insights into the model's performance.
Feedback and Additional Features (Optional):

Users may have the option to provide feedback on the prediction or explore additional features or scenarios, such as adjusting their input parameters to see how it affects the prediction.
# Conclusion:

The web app concludes by providing the user with placement prediction results based on the input parameters. Users can use this information to make informed decisions related to their career.
