# Flask Diabetes Prediction App
This repository contains a simple Flask project for predicting the probability of diabetes using a pre-trained random forest classification model. The model is loaded from the random_forest_classifier_default_42.sav file.

# Usage Instructions
1. Clone this repository on your local machine.

git clone https://github.com/your-username/repository-name.git
cd repository-name

2. Ensure you have Python installed on your system.
   
4. Install the required dependencies:
pip install -r requirements.txt
1. Run the Flask application:
python app.py
Open your web browser and visit http://127.0.0.1:5000/.

Enter the required values in the form and click the "Predict" button to get the probability of diabetes.

# Project Structure
app.py: Contains the main logic of the Flask application.
templates/index.html: HTML template for the user interface.
models/random_forest_classifier_default_42.sav: File storing the pre-trained classification model.
# Additional Files
requirements.txt: List of project dependencies.
README.md: This file providing information about the project.
# Important Notes
Ensure you have the necessary permissions to access the classification model (random_forest_classifier_default_42.sav). In case of changes to the model, update the corresponding file and adjust the code accordingly.
