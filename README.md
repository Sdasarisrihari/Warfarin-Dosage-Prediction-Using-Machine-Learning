# Warfarin Dosage Prediction Using Machine Learning

# Problem

Determining the optimal dosage of Warfarin is a critical and challenging task in clinical settings. Warfarin, an anticoagulant, is widely prescribed to prevent and treat thromboembolic events. However, finding the right dose is difficult due to its narrow therapeutic index and the high variability in dose requirements across patients. Incorrect dosages can lead to adverse effects such as bleeding or thromboembolism. The objective of this project is to use machine learning models to predict the correct dosage of Warfarin for individual patients, based on their medical and genetic information, thereby reducing the risk of complications.<br />

# Approach

In this project, we apply machine learning techniques to predict the optimal Warfarin dosage for patients. The dataset undergoes preprocessing to handle missing values and convert categorical features into numerical formats. We then train models like Linear Regression, Random Forest, and Neural Networks to predict the dosage based on patient data. Each model's performance is evaluated using metrics such as Mean Squared Error, Precision, and F1-score. This approach aims to assist clinicians in making accurate dosage decisions, improving patient outcomes.<br />

# Data

The project utilizes the International Warfarin Pharmacogenetics Consortium (IWPC) dataset, comprising 6161 patient records with features such as Gender, Age, Race, Height, and Weight, along with genetic markers like CYP2C9 and VKORC1 genotypes. The target variable is the Therapeutic Dose of Warfarin measured in milligrams per week. This dataset enables the development of machine learning models to predict the optimal Warfarin dosage for individual patients.<br />


# Visualizations

In this section, we present the performance metrics of the machine learning models along with relevant visualizations.

### Correlation Heatmap

![Correlation Heatmap](images/correlation_heatmap.png)
*Figure 1: Heatmap showing the correlations between different features in the dataset.*

### Confusion Matrix
![Confusion Matrix](images/confusion_matrix.png)
*Figure 2: Confusion matrix for the Random Forest model, showing true vs. predicted values.*


# Conclusion:
This project aims to build an accurate and reliable Warfarin dosage prediction system using machine learning techniques. The models will help clinicians make better-informed decisions regarding Warfarin therapy, ultimately improving patient outcomes and reducing the risk of adverse effects. We will evaluate the models' performance based on their accuracy in predicting dosage levels and their robustness across various patient profiles.

