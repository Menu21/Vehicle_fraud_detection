# Vehicle Insurance Fraud Detection Using Machine Learning & Power BI
### Objective
Vehicle insurance fraud is a widespread issue, leading to financial losses for insurance companies due to fraudulent claims. Fraudsters often file false or exaggerated claims, which range from staged accidents to inflated injury reports. The objective of this project is to use machine learning to efficiently detect fraudulent claims by analyzing historical data. Power BI is used to visualize the results, enabling stakeholders to interpret predictions and take preventive measures, reducing fraudulent activities and improving claim processing efficiency.

### Dataset Description
The dataset contains a wide variety of information related to vehicle insurance claims, which helps in detecting potential fraud. Below is a summary of the key columns used in the analysis:

- Month: Month when the claim was made.
- WeekOfMonth: Week when the claim was made.
- DayOfWeek: Day when the claim was made.
- Make: Car manufacturer.
- AccidentArea: Location of the accident.
- DayOfWeekClaimed: Day of the week the claim was made.
- MonthClaimed: Month when the claim was made.
- WeekOfMonthClaimed: Week in which the claim was made.
- Sex: Gender of the claimant.
- MaritalStatus: Marital status of the claimant.
- Age: Age of the claimant.
- Fault: Party at fault for the accident.
- PolicyType: Type of insurance policy.
- VehicleCategory: Vehicle category (e.g., sports, luxury, etc.).
- VehiclePrice: Value of the vehicle.
- FraudFound_P: Indicator of whether fraud was detected.
- PolicyNumber: Policy number.
- RepNumber: Representative number.
- Deductible: Amount the claimant must pay before the insurance coverage starts.
- DriverRating: Rating of the driver.
- Days_Policy_Accident: Number of days since the accident.
- Days_Policy_Claim: Number of days since the claim.
- PastNumberOfClaims: Number of previous claims made.
- AgeOfVehicle: Age of the vehicle.
- AgeOfPolicyHolder: Age of the policyholder.
- PoliceReportFiled: Whether a police report was filed.
- WitnessPresent: Whether a witness was present.
- AgentType: Type of agent handling the claim.
- NumberOfSuppliments: Number of additional supplements provided for the claim.
- AddressChange_Claim: Whether the claimant changed their address before filing the claim.
- NumberOfCars: Number of cars the claimant owns.
- Year: Year of the policy.
- BasePolicy: Base policy type.
# Project Workflow
- Step 1: Import Libraries
Import the necessary libraries for data preprocessing, analysis, and model building.

- Step 2: Read Datasets
Load the dataset into your environment for further analysis.

- Step 3: Dataset Overview
3.1: View basic information about the dataset.
3.2: Drop irrelevant columns that do not contribute to fraud detection.
3.3: Describe numerical features in the dataset.
3.4: Describe categorical features in the dataset.
- Step 4: Univariate Analysis
4.1: Perform univariate analysis on numerical variables to understand the distribution of data.
4.2: Analyze categorical variables to study their frequency and impact.
- Step 5: Bivariate Analysis
5.1: Explore the relationship between numerical features and the target variable (FraudFound_P).
5.2: Explore the relationship between categorical features and the target variable.
- Step 6: Data Preprocessing
6.1: Handle missing values.
6.2: Remove duplicate records.
6.3: Treat outliers in the dataset.
6.4: Group features to simplify analysis.
6.5: Encode categorical variables.
6.6: Handle imbalanced data using techniques like oversampling or undersampling.
6.7: Apply transformations to skewed features.
6.8: Select the most relevant features for fraud detection.
- Step 7: Logistic Regression Model Building
7.1: Build the base logistic regression model.
7.2: Tune hyperparameters for better performance.
7.3: Evaluate model performance using metrics like accuracy, precision, recall, and F1-score.
7.4: Analyze feature importance.
- Step 8: Decision Tree Model Building
8.1: Build the base decision tree model.
8.2: Tune hyperparameters for better performance.
8.3: Evaluate the decision tree model.
8.4: Analyze feature importance.
- Step 9: Random Forest Model Building
9.1: Define the random forest model.
9.2: Perform hyperparameter tuning to optimize the model.
9.3: Evaluate the model performance.
9.4: Analyze feature importance.
- Step 10: XGBoost Model Building
10.1: Build the XGBoost model.
10.2: Tune hyperparameters for optimal performance.
10.3: Evaluate the XGBoost model.
10.4: Analyze feature importance.
- Step 11: Load New Test Data
11.1: Preprocess the test data.
11.2: Load the trained model.
11.3: Make predictions on the test data.
11.4: Save the predictions for further analysis.
- Step 12: Conclusion
Summarize the findings, highlight the best-performing model, and discuss how the Power BI dashboard aids in interpreting the results.

# Power BI Visualization
Power BI is used for interactive visualization, helping stakeholders interpret predictive models and take actionable steps to mitigate fraud risks. Key features include:

- Fraud Detection Trends: A visualization of historical fraud detection, highlighting patterns in claims.
- Model Performance: Comparison of different models’ performance (e.g., Logistic Regression, Decision Tree, Random Forest, XGBoost).
- Feature Importance: Visual representation of which features are most important in predicting fraud.
- Interactive Filters: Drill down into specific variables like claim date, vehicle make, and claimant demographics to explore fraud patterns.
#Installation
### Prerequisites
Python 3.8+ with required libraries: pandas, scikit-learn, XGBoost, etc.
Power BI Desktop
