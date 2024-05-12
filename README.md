# TestDatasetModelSelector


# A.P. Moller - Maersk Product Forecasting

## Overview

This project aims to forecast the demand for a product provided by A.P. Moller - Maersk using machine learning and deep learning models. The dataset spans from July 2020 to May 2021 and includes various features related to the product.

Certainly! Here's the updated workflow section with the addition you requested:

---

## Workflow

### TrainData_Preprocessing

- This file handles preprocessing tasks such as outlier detection and removal, encoding categorical features, and performing Exploratory Data Analysis (EDA) on the training data.
- After preprocessing, the cleaned data is saved to a new Excel file named "Updated_TrainingData.xlsx".

### TestData_Preprocessing

- This file preprocesses the test data to ensure consistency with the training data.
- The cleaned test data is saved to a new Excel file named "Updated_TestData.xlsx".

### ML_Models

- In this notebook, various machine learning models are applied to the updated and cleaned training data.
- The notebook includes a comparative analysis of the performance of different machine learning models.

### DL_Model

- This notebook focuses on applying the Long Short-Term Memory (LSTM) model as a deep learning approach for forecasting.
- The LSTM model is trained for 300 epochs using the updated training data.

### SakshamJain_AIML_Assessment

- Alternatively, you can directly run the **SakshamJain_AIML_Assessment.ipynb** file where all the notebooks are merged, providing a comprehensive view of the entire project workflow.

## Repository Structure

- **/data**: Contains the original raw data files provided by A.P. Moller - Maersk and the updated data files after preprocessing.
  - **Test_Data.xlsx**: Raw test data file.
  - **Train_Data.xlsx**: Raw training data file.
  - **Updated_TrainingData.xlsx**: Cleaned and preprocessed training data.
  - **Updated_TestData.xlsx**: Cleaned and preprocessed test data.
- **/notebooks**:
  - **TrainData_Preprocessing.ipynb**
  - **TestData_Preprocessing.ipynb**
  - **ML_Models.ipynb**
  - **DL_Model.ipynb**
- **/results**: Stores the results and outputs generated during the analysis and model training process.

## Getting Started

To replicate the project's results and analyses, follow these steps:

1. Clone the repository to your local machine.
2. Navigate to the respective notebook in the /notebooks directory.
3. Execute the code cells in each notebook sequentially.
4. Refer to the outputs and results saved in the /results directory for insights and model performance.

## Contact

Got it! Here's the updated contact section:

---

## Contact

For any questions or inquiries, please contact [Saksham Jain](https://www.linkedin.com/in/saksham-jain-59b2241a4/).

