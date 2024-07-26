# Breast Cancer Classification Using Machine Learning

## Project Summary
Breast cancer is one of the most common cancers affecting women worldwide. Early diagnosis and treatment are crucial for improving survival rates and patient outcomes. This project aims to classify breast masses as benign or malignant using machine learning algorithms. The dataset used for this project is from Fine Needle Aspiration (FNA) of breast masses, containing digitized images with characteristics of cell nuclei.

## Objective
The primary objective of this project is to develop a machine learning model to accurately classify whether a breast mass is benign or malignant based on various features. The goal is to enhance diagnostic accuracy and support healthcare professionals in making informed decisions.

## Methodology
- **Analyze Dataset**: Examine the dataset to understand feature distribution.
- **Data Cleaning**: Handle anomalies and ensure the dataset is ready for modeling.
- **EDA**: Exploratory Data Analysis to find the insights.
- **Normalization**: Scale features to ensure consistency and improve model performance.
- **Machine Learning models**: Used Algorithm like Random forest and Logistic Regression for prediction.

## Dataset Overview
The dataset consists of 569 instances with 32 attributes, including:

- Diagnosis: Label indicating whether the tumor is malignant (M) or benign (B).

#### Mean Values:

- radius_mean: Average distance from the center to points on the perimeter of the cell nucleus.
- texture_mean: Standard deviation of gray-scale values.
- perimeter_mean: Mean perimeter of the cell nucleus.
- area_mean: Mean area of the cell nucleus.
- smoothness_mean: Mean local variation in radius lengths.
- compactness_mean: Mean compactness, calculated as (perimeter^2 / area) - 1.0.
- concavity_mean: Mean severity of concave portions of the contour.
- concave_points_mean: Mean number of concave portions of the contour.
- symmetry_mean: Mean symmetry of the cell nucleus.
- fractal_dimension_mean: Mean "coastline approximation" (fractal dimension) - 1.

#### Standard Error Values:

- radius_se: Standard error of the radius.
- texture_se: Standard error of the texture.
- perimeter_se: Standard error of the perimeter.
- area_se: Standard error of the area.
- smoothness_se: Standard error of the smoothness.
- compactness_se: Standard error of the compactness.
- concavity_se: Standard error of the concavity.
- concave_points_se: Standard error of the number of concave points.
- symmetry_se: Standard error of the symmetry.
- fractal_dimension_se: Standard error of the fractal dimension.

#### Worst (Largest) Values:

- radius_worst: Largest (mean of the three largest) radius values.
- texture_worst: Largest texture values.
- perimeter_worst: Largest perimeter values.
- area_worst: Largest area values.
- smoothness_worst: Largest smoothness values.
- compactness_worst: Largest compactness values.
- concavity_worst: Largest concavity values.
- concave_points_worst: Largest number of concave points.
- symmetry_worst: Largest symmetry values.
-fractal_dimension_worst: Largest fractal dimension values.

#### Class Distribution
- Benign: 357 instances
- Malignant: 212 instances

### Insights and Data Manipulation
#### KDE Plot Analysis
- Benign Tumors: The KDE plots for all features show a left-skewed distribution, indicating that most feature values for benign tumors cluster at the lower end of their range.
- Malignant Tumors: The KDE plots for malignant tumors are centered, suggesting a more uniform distribution of feature values around the mean.
#### Positive Correlation:
- Radius Worst: Higher values are strongly associated with malignant tumors.
- Perimeter Worst: Higher values are strongly associated with malignant tumors.
- Concave Points Worst: Higher values are strongly associated with malignant tumors.

## Model Performance
#### Random Forest Classifier
- Accuracy: 96.49%
- F1 Score: 95.24%
- Precision: 97.56%
- Recall: 93.02%

#### Logistic Regression (Basic)
- Accuracy: 96.49%
- F1 Score: 95.24%
- Precision: 97.56%
- Recall: 93.02%

#### Logistic Regression (Optimized)
- Accuracy: 99.12%
- F1 Score: 98.82%
- Precision: 100.00%
- Recall: 97.67%

## Conclusion
By applying machine learning techniques to the Breast Cancer Wisconsin (Diagnostic) dataset, this project has successfully developed a highly accurate classification model for breast cancer diagnosis. The models demonstrated high performance metrics, with the optimized Logistic Regression model achieving an exceptional accuracy of 99.12% and an F1 score of 98.82%. This high level of accuracy and precision indicates that the model is well-suited for aiding in early detection and diagnosis of breast cancer, which can significantly improve patient outcomes and survival rates. The successful implementation of this model highlights its potential for practical use in clinical settings, assisting healthcare professionals in making informed decisions.

Feel free to explore the code and documentation provided in this repository to gain a deeper understanding of the project and replicate the results and if you have any questions or suggestions, please don't hesitate to reach out on this [email](jabcd.1997@gmail.com)

Happy forecasting!

