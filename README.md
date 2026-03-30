# Phishing Website Detector (BYOP)

## What this project does
This is an End-to-End Machine Learning Pipeline designed to detect malicious phishing websites using their URL characteristics. It creates a synthetic dataset to mimic the extracted URL features (such as length, IP, etc.) and uses a **Random Forest Classifier** to learn from the data to detect patterns of phishing attempts.

## How to set it up
1. Clone this repository to your local machine.
2. Ensure you have Python 3.x installed.
3. Install the necessary packages by executing the following in your terminal/command prompt:
   `pip install pandas numpy scikit-learn`

## How to use it
To use the code, execute the main script in your terminal/command prompt:
`python Code.py`
The script is self-contained, meaning you don't have to worry about anything else. It will automatically create `phishing_data.csv`, train the machine learning model, and print the accuracy metrics and classification report directly to your console on the first execution.
