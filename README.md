# Flight Delay Classification Project ✈️

## Project Description

This project focuses on building and evaluating multiple machine learning classification models to predict **flight delays** based on historical flight data. It involves data cleaning, feature engineering, exploratory analysis, model training, and performance evaluation using metrics such as accuracy, precision, recall, and F1-score.

##  Installation Instructions

To run this project locally:

1. Clone the repository:
   `git clone https://github.com/your-username/flight-delay-classification.git`  
   `cd flight-delay-classification`

2. Open the following Jupyter notebooks in your IDE or Jupyter environment:
   - `Task1.ipynb` – Data cleaning and exploration
   - `Task2.ipynb` – Feature engineering
   - `Task3.ipynb` – Model training
   - `Task4.ipynb` – Results analysis

##  Task Breakdown

###  Task 1: Data Cleaning & Exploration
- Loaded raw flight data.
- Cleaned null values and irrelevant columns.
- Explored key features using visualizations and descriptive stats.
- Saved cleaned data as `Cleaned_Flight_data.csv`.

###  Task 2: Feature Engineering
- Encoded categorical variables (e.g., Airline, Source).
- Extracted date/time-based features.
- Scaled/standardized numerical columns.
- Output saved as `feature_engineered_data.csv`.

###  Task 3: Model Building & Training
- Trained and evaluated:
  - Logistic Regression
  - Decision Tree
  - Random Forest
  - Support Vector Machine
- Evaluated using Accuracy, Precision, Recall, F1-Score.
- Results saved to `classification_model_results.csv`.

###  Task 4: Results Analysis
- Loaded and compared model results.
- Random Forest identified as best with 98.5% accuracy.
- Visualized performance metrics (optional in notebook).
- Summarized findings and potential improvements.


##  Data Sources

- `Flight_Data.csv` – Original flight dataset  
- `Cleaned_Flight_data.csv` – Preprocessed dataset  
- `feature_engineered_data.csv` – Dataset after feature engineering  
- `classification_model_results.csv` – Summary of model performances

##  Code Structure

├── Task1.ipynb                  <br>
├── Task2.ipynb             <br>
├── Task3.ipynb          <br>
├── Task4.ipynb                <br>
├── feature_engineered_data.csv   <br>
├── classification_model_results.csv  <br>
├── README.md           <br>




## 📊 Results and Evaluation
 ______________________________________________________________________
| Model                    | Accuracy | Precision | Recall | F1 Score |
|--------------------------|----------|-----------|--------|----------|
| Logistic Regression      | 80.3%    | 83.6%     | 88.9%  | 86.2%    |
| Decision Tree            | 96.7%    | 97.1%     | 98.1%  | 97.6%    |
| **Random Forest**        | **98.5%**| **99.8%** | 98.1%  | **98.9%**|
| Support Vector Machine   | 80.2%    | 83.9%     | 88.1%  | 86.0%    |
_______________________________________________________________________

✅ **Random Forest** achieved the highest performance and is the most accurate model for this task.

##  Future Work

- Tune hyperparameters using GridSearchCV for better model optimization.
- Incorporate real-time weather and air traffic data to enhance predictive accuracy.
- Deploy the best-performing model via a web dashboard (e.g., using Flask or Streamlit).
- Explore deep learning alternatives for further improvement.

