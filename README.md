CAR PRICE PROJECTS:

OVERVIEW:
This project aims to predict the price of a used car based on various parameters, including the company name, model name, year of purchase, fuel type, and the number of kilometers it has been driven.

HOW TO USE:
Clone the repository to your local machine.
Install the required packages listed in the "requirements.txt" file, including:
numpy
pandas
scikit-learn

WHAT THE PROJECT DOES:
Data Collection: The data for this project was scraped from Quikr.com. The dataset can be found here.

Data Preprocessing: The collected data was cleaned and analyzed to handle any inconsistencies.

Model Development: A Linear Regression model was built with an impressive R2_score of 0.92. The notebook detailing the analysis and model development can be found here.

Web Application: The predictive model was integrated into a Flask web application. Users can input the details of a car, and the system will predict its price based on the trained Linear Regression model.

EXAMPLE:
For instance, the image below illustrates the predicted price of a Hyundai Grand i10.
