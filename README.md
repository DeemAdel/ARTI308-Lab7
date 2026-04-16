# ARTI308-Lab7

# Logistic Regression for Heart Disease Prediction

## Dataset

- File: `heart.csv`
- Rows: 1025 (original)
- Features: 14

## Data Preprocessing Steps

### 1. Data Exploration

- Checked structure using `.info()` and `.describe()`
- Verified all columns are numeric
- Identified `target` as the label (0 = no disease, 1 = disease)

### 2. Missing Values

- No missing values found in the dataset

### 3. Duplicate Removal

- Found duplicate rows
- Removed duplicates
- Dataset reduced to 302 rows

### 4. Data Consistency

- No negative or invalid values found
- All features are within logical ranges


## Exploratory Data Analysis (EDA)

- Visualized target distribution using count plots
- Used heatmap to analyze feature correlations
- Observed relationships between variables using pairplot


## Model Building

### 1. Feature Selection

- Input features: All columns except `target`
- Target variable: `target`

### 2. Train-Test Split

- Split dataset into training (70%) and testing (30%)

### 3. Model Used

- Logistic Regression

### 4. Training

- Trained model using training dataset


## Model Evaluation

- Evaluated model using:

  - Accuracy Score
  - Confusion Matrix
  - Classification Report

- Model performance indicates good ability to classify heart disease cases


## Tools & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
