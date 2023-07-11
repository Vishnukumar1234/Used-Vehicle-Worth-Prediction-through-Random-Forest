
# Used Vehicle Worth Prediction through Random Forest

Predictive analysis using Random Forest Classifier on used car auction data to help dealerships make informed decisions. Achieves 90.4% accuracy, reducing risks and optimizing inventory selection. A valuable resource for the automotive industry.

## Table of Contents

* [Introduction](https://github.com/Vishnukumar1234/Used-Vehicle-Worth-Prediction-through-Random-Forest#Introduction)
* Dataset
* Installation
* Usage
* Data Preprocessing
* Model Training
* Evaluation
* Results
* Conclusion
* Contributing

## Introduction

This project focuses on leveraging machine learning techniques to analyze a comprehensive dataset of used cars from auto auctions. With the aim of assisting auto dealerships in making informed decisions, a Random Forest Classifier is employed to predict the suitability of a car as a potential purchase or a "kick" (a vehicle with significant issues). Achieving an impressive accuracy of 90.4%, this project significantly reduces the risks associated with purchasing undesirable vehicles, enabling dealerships to optimize their inventory selection and drive improved profitability. The open-source nature of this project makes it a valuable resource for the automotive industry, providing advanced insights and tools for dealership decision-making.
## Dataset
The dataset used for this project contains over 67,000 records with 31 attributes. Each attribute provides information about the cars and their characteristics. Here is an overview of the key attributes:

* class: The target variable indicates whether the car is a kick (bad buy) or not.
* PurchDate: The date of the purchase.
* VehYear: The manufacturing year of the vehicle.
* VehicleAge: The age of the vehicle.
* VehOdo: The odometer reading of the vehicle.
* MMRAcquisitionAuctionAveragePrice: Average price of the vehicle at acquisition from auctions.
* MMRCurrentRetailCleanPrice: Clean retail price of the vehicle at the current market.
* VehBCost: Acquisition cost of the vehicle.
* WarrantyCost: Warranty cost for the vehicle.
* Several other attributes describing the vehicle's make, model, trim, color, transmission, wheel type, etc.

You can access the dataset on OpenML.

## Installation

To run this project locally, you need to follow these steps:

* Clone this repository:
    
    git clone https://github.com/Vishnukumar1234/Used-Vehicle-Worth-Prediction-through-Random-Forest

* Download the dataset and place it in the project directory.

* Run the Jupyter Notebook or Python script to see the results.

## Usage

After completing the installation steps, you can either run the Jupyter Notebook Vehicle_Kick_prediction.ipynb.

In the Jupyter Notebook or script, you will find the following sections:

* Data preprocessing: Handling missing values, feature scaling, and encoding categorical variables.
* Model training: Building and training the Random Forest Classifier using GridSearch CV for hyperparameter tuning.
* Evaluation: Assessing the model's performance through various metrics.
* Results: Summarize the key findings and accuracy achieved.

Feel free to modify the notebook or script to suit your needs or experiment with different machine-learning algorithms.

## Data Preprocessing

Data preprocessing is a crucial step in any machine learning project. In this project, I have performed the following preprocessing tasks:

* Handled missing values: Checked for missing values in the dataset and applied appropriate strategies such as imputation or removal.
* Feature scaling: Ensured that all features were on a similar scale by applying Min-Max scaling to numerical attributes.
* Encoding categorical variables: Converted categorical variables into numerical representations using one-hot encoding.

These preprocessing steps help in preparing the data for model training and improve the accuracy of predictions.

## Model Training

For this project, I have implemented the Random Forest Classifier algorithm. Random forests are a popular ensemble learning method that combines multiple decision trees to make predictions. The algorithm is known for its robustness, ability to handle large datasets and resistance to overfitting.

To find the best hyperparameters for our model, I used GridSearch CV, a technique that systematically searches for the optimal combination of hyperparameters. This process maximizes the model's performance and helps achieve the best accuracy.

## Evaluation

I have evaluated the trained model's performance using various metrics, including accuracy, precision, recall, and F1-score. These metrics provide insights into the model's ability to correctly classify kicked and non-kicked cars.

To ensure reliable evaluation, we employed cross-validation techniques such as stratified k-fold to assess the model's generalization capability.

## Results

After training and evaluating the model, It has achieved an accuracy of 90.4%. This high accuracy demonstrates the model's capability to predict whether a car is a good buy or a kick.

The model provides valuable insights to auto dealerships, enabling them to make informed decisions during auto auctions. By avoiding kicked cars, dealerships can reduce costs associated with transportation, repair work, and market losses, resulting in improved profitability.


## Conclusion

The Used Car Auction Analysis project showcases the application of machine learning techniques to predict whether a car purchased at an auto auction is a good buy or a kick. By leveraging a Random Forest Classifier, I have created a model that achieves 90.4% accuracy in identifying kicked cars.

This project aims to provide value to auto dealerships by reducing the risk associated with purchasing vehicles with serious issues. By using the model, dealerships can optimize their inventory selection, avoid costly kicked cars, and improve overall profitability.

I encourage you to explore the project further, experiment with different models, and enhance prediction accuracy by leveraging more advanced machine-learning techniques.

## Contributing

Contributions are always welcome!

