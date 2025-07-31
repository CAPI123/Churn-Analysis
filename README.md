Collecting workspace information# README

## Customer Churn Classification Project

This project analyzes customer churn in a telecommunication company using machine learning classification models. The goal is to predict whether a customer will churn and to identify key factors influencing churn, providing actionable insights for improving customer retention.

---

## Project Structure

- **notebook .ipynb**: Main Jupyter notebook containing all code, analysis, and results.
- **LP2_Telco-churn-second-2000.csv**: CSV dataset for model training/testing.
- **Telco-churn-last-2000.xlsx**: Excel dataset for additional analysis.
- **.env**: Environment variables for database credentials.
- **.gitignore**: Specifies files to ignore in version control.

---

## Workflow Overview

1. **Business Understanding**
   - Defines objectives, hypotheses, and research questions regarding customer churn.

2. **Data Understanding**
   - Loads data from SQL Server and local files.
   - Explores feature definitions and data structure.

3. **Data Preparation**
   - Handles missing values and feature selection.
   - Converts categorical variables to numeric using one-hot encoding.
   - Splits data into training, validation, and test sets (with stratification for balanced classes).

4. **Modeling**
   - Trains multiple classification models: K-Nearest Neighbors (KNN), Random Forest, and Support Vector Machine (SVM).
   - Evaluates models using accuracy, precision, recall, and F1 score.

5. **Model Comparison**
   - Compares model performance and displays results in a sorted table.

---

## How to Run

1. **Install Dependencies**
   - Ensure you have Python 3.11+ and the following packages:
     - pandas, numpy, matplotlib, seaborn, scikit-learn, imbalanced-learn, openpyxl, pyodbc, dotenv

   ```sh
   pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn openpyxl pyodbc python-dotenv
   ```

2. **Set Up Environment Variables**
   - Create a .env file with your database credentials:
     ```
    

3. **Run the Notebook**
   - Open `notebook .ipynb` in VS Code or Jupyter Notebook.
   - Execute cells sequentially to load data, preprocess, train, and evaluate models.

---

## Key Files

- [notebook .ipynb](notebook%20.ipynb): Main analysis and modeling code.
- [LP2_Telco-churn-second-2000.csv](LP2_Telco-churn-second-2000.csv): Training/testing dataset.
- [Telco-churn-last-2000.xlsx](Telco-churn-last-2000.xlsx): Additional dataset for analysis.

---

## Results

- Model performance metrics are displayed at the end of the notebook.
- The best model is selected based on the highest F1 Score.

---

## Notes

- The code uses both SQL and local files for data loading.
- Ensure your database connection is active if using SQL data.
- All preprocessing and modeling steps are reproducible within the notebook.

---

## License

This project is for educational and research purposes. Please check data source licenses before commercial use.3. **Run the Notebook**
   - Open `notebook .ipynb` in VS Code or Jupyter Notebook.
   - Execute cells sequentially to load data, preprocess, train, and evaluate models.

---

## Key Files

- [notebook .ipynb](notebook%20.ipynb): Main analysis and modeling code.
- [LP2_Telco-churn-second-2000.csv](LP2_Telco-churn-second-2000.csv): Training/testing dataset.
- [Telco-churn-last-2000.xlsx](Telco-churn-last-2000.xlsx): Additional dataset for analysis.

---

## Results

- Model performance metrics are displayed at the end of the notebook.
- The best model is selected based on the highest F1 Score.

---

## Notes

- The code uses both SQL and local files for data loading.
- Ensure your database connection is active if using SQL data.
- All preprocessing and modeling steps are reproducible within the notebook.

---

## License

This project is for educational and research purposes. Please check data source licenses before commercial use.
