# Property Price Assessment Using Predictive Modelling

## Project Description
This project assists a property assessor’s office in a Midwestern state of the USA to adopt a data-driven method for assessing property prices. The dataset consists of 113 variables describing 3970 property sales from 2006 to 2010. Our goal is to build and evaluate predictive models to predict housing prices based on relevant property attributes.

We specifically focus on two types of predictive models:
- Regression Models
- Decision Trees

## Dataset
The dataset used contains 31 variables that are directly related to property sales, which are typically used by assessors to estimate property prices. These variables include:
- **LotArea**: The size of the lot.
- **TotalBSF**: The size of the living room in square feet.
- **YearBuilt**: The year the property was built.
- **FullBath**: Number of bathrooms.
- **GarageCars**: Number of cars the garage can hold.
- **OverallQuality**: The overall quality of the property, as evaluated by assessors.

## Key Tasks Performed
### 1. Exploratory Data Analysis
- Calculated summary statistics (mean, median, max, standard deviation) for continuous variables.
- Generated counts for categorical variables.
- Visualized distributions of continuous variables using histograms.
- Checked for missing values and applied multiple methods for handling them (e.g., imputation with mean, mode).
- Evaluated correlations between variables and performed dimension reduction.

### 2. Predictive Modelling
#### **Regression Models**:
- Built and evaluated three regression models to predict property prices.
- Evaluated models using metrics like Root Mean Square Error (RMSE) and R-squared (R²).
- Identified the optimal regression model based on feature selection techniques.

#### **Decision Tree Models**:
- Built and evaluated three decision tree models, including pruning techniques for optimization.
- Evaluated models using performance metrics and visualized tree plots.
- Compared decision tree results with regression models to find the most suitable model.

### 3. Model Comparison
- Compared the accuracy of the final regression model and the optimal decision tree.
- Discussed the most suitable model for the business case based on evaluation metrics.

## How to Run the Project
1. **Clone this repository**:
   ```bash
   git clone https://github.com/DRAPerera/property-price-assessment-using-predictive-modelling.git
