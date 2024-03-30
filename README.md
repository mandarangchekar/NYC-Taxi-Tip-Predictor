# NYC-Taxi-Tip-Predictor\

Introduction: The overarching goal of this project was to create an algorithm that can be used to examine the patterns of cab operations in a city and attempt to forecast the tip that can be expected per fare.The premise behind this study was that the trip histories of cab drivers when paired with demographic information, might be used to predict people's propensities to tip differently depending on where they are, when they are traveling, and what kind of journey they are on. We sought to create a system that would divide a given trip into several groups with varied tipping guidelines using various machine-learning approaches.

Data on taxi travel in New York City from the last 5-10 years was the foundation for this research. The NYC Taxi and Limousine Commission made this information public, and it included data on all the fares and rides taken during this time. We were able to anticipate tips with a high degree of accuracy using this information along with local demographic data from the US Census. Although this issue has been addressed earlier, we think that by merging the demographic data, our method is somewhat more city-independent.

Installation: Clone the repository to your local machine using "https://github.com/mishrapiyush30/CIS-675.git" link. Install the required packages by running pip install -r commands. Open the terminal and navigate to the project directory. Run the command python main.py

Files:

Feature&Modeling.ipynb: Jupyter notebook containing the code for data cleaning, feature engineering, and model training. Visualization.ipynb: Jupyter notebook containing the code for data visualization. merge.py: Python script for merging the trip and fare datasets into a single dataset. merge.sh: Bash script for executing the merge.py script.

Usage: To run the model, first make sure you have the necessary data in the correct format. The data should be in a CSV file, with each row representing a single user and each column representing a user behavior feature. The last column should be the target variable, indicating whether the user has churned or not.

Once you have your data in the correct format, you can run the model using the following command: python predict.py --data /path/to/your/data.csv --model /path/to/your/trained/model.pkl This will generate predictions for each user in your dataset, and output the results to a CSV file.

Model Training: To train your own model using your own data, you can use the train.py script provided. This script takes a CSV file as input, and trains a machine learning model using the specified algorithm and hyperparameters. python train.py --data /path/to/your/data.csv --algorithm [random_forest | logistic_regression] --params /path/to/your/hyperparameters.yaml --output /path/to/your/trained/model.pkl

Visualization: To generate visualization for your data and model predictions, you can use the visualization.ipynb Jupyter notebook provided. This notebook contains various visualizations to explore your data and model performance.
