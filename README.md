# Data Science Course Project
## Project Details

### Dataset
The dataset is provided in an Excel file named `CollectedData.xlsx` (see sheet 2). The dataset contains information about individuals, their clothing, and atmospheric elements. The goal is to apply machine learning models for both regression (PMV) and classification (AMV) based on user feedback on feeling cold.

### Feature Description
The table below describes the columns of interest in the dataset:

| Column Number | Feature Name        | Feature Description                  |
|---------------|---------------------|--------------------------------------|
| 3             | Age                 | Age                                  |
| 22            | Clo                 | Clothing insulation                 |
| 19            | Met                 | Met Rate                             |
| 26            | Dewpt               | Dewpt                                |
| 27            | PlaneRadTemp        | Plane radiant temperature            |
| ...           | ...                 | ...                                  |

### Part A. Preprocessing
#### 1. Data Summary Table
For each input dimension, create a data summary table with statistics like mean, median, mode, variance, and standard deviation.

#### 2. Data Visualization
For each input dimension, plot a histogram and create a Box Plot. Provide comments on the distribution type and the presence of outliers.

#### 3. Handling Missing Values
Identify missing values in each dimension and fill them using an appropriate methodology. Mention your approach and justification.

#### 4. Handling Outliers
Identify and handle outliers for each dimension. Explain your approach and reasoning.

#### 5. Feature Selection
Based on variance, decide whether to include each dimension as an input feature.

#### 6. Correlation Matrix
Create a correlation matrix (Heat Map) for all dimensions. Comment on the most and least informative dimensions.

#### 7. Entropy and Information Gain
Apply entropy and information gain on selected columns. Specify your selection criteria.

### Part B. Applying Algorithms
#### 1. Data Splitting and Normalization
Split the data into 80/20 for training and testing. Normalize the dataset as needed.

#### 2A. Forward Selection (PMV)
Apply forward selection with Multilinear Regression as the model. Create a table of dimensions and performance achieved.

#### 2B. Backward Selection (PMV)
Apply backward selection with Multilinear Regression. Create a table of dimensions and performance achieved.

#### 3A. Forward Selection (AMV)
Apply forward selection with Logistic Regression as the model. Create a table of dimensions and performance achieved.

#### 3B. Backward Selection (AMV)
Apply backward selection with Logistic Regression. Create a table of dimensions and performance achieved.

#### 4. Cross Validation and Confusion Matrix
Using the optimal feature vector, apply 3-fold cross-validation for both regression (PMV) and classification (AMV). Record optimal parameter values and plot a confusion matrix for classification.
