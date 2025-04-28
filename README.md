Car Data Regression with KNN Imputation and Gradient Descent
This project focuses on predicting the combination MPG (miles per gallon) for cars based on various features like transmission type, fuel type, and engine specifications.
It involves data preprocessing, KNN imputation for handling missing values, feature normalization, data visualization, and implementing linear regression from scratch using gradient descent.

📂 Project Structure
Data Loading and Cleaning:

Dropped unnecessary columns (make, model, year).

Rearranged columns for better processing.

Converted categorical features (transmission, class, drive, fuel_type) into numerical codes.

Handling Missing Values:

Applied KNNImputer (n_neighbors=4) to fill missing values.

Feature Normalization:

Standardized the features (zero mean, unit variance).

Visualization:

Plotted scatter plots for each feature vs. the target (combination_mpg) to understand relationships.

Model Training:

Implemented linear regression from scratch using:

Cost function (Mean Squared Error)

Gradient computation

Gradient descent optimization

Trained the model for 10,000 iterations with a learning rate of 0.001.

📈 Model Performance
Initial Cost: ~317

Final Cost: ~0.10 after 10,000 iterations

Observations:

The model achieved good convergence with steady cost reduction.

Feature normalization helped in speeding up convergence.

No missing values remained after imputation.

🛠️ Technologies Used
Python

NumPy

Pandas

Matplotlib

Scikit-learn (for KNNImputer)
