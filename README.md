# Student Dropout Rates Prediction

## Project Overview

This project aims to predict student dropout rates using three different machine learning models: Logistic Regression, K-Nearest Neighbors (KNN), and K-Means Clustering. The dataset used in this project includes various features related to students' academic performance and other relevant factors.

## Dataset

The dataset contains features such as:

- `Feature1`: Description of feature 1
- `Feature2`: Description of feature 2
- `...`

The target variable (`Target`) indicates whether a student has "Dropped out" (0) or "Graduated" (1).

## Project Structure

- `student_dropout_prediction.ipynb`: The main notebook containing the code for EDA, data preprocessing, model training, evaluation, and predictions.
- `README.md`: Documentation of the project.
- `requirements.txt`: List of Python packages required to run the project.

## Steps Involved

1. **Exploratory Data Analysis (EDA):**
   - Analyzed the dataset for missing values and distribution of the target variable.
   - Visualized the distribution of the target variable.

2. **Data Preprocessing:**
   - Handled missing values and encoded the target variable.
   - Scaled the features using `StandardScaler`.

3. **Model Training and Evaluation:**
   - **Logistic Regression:**
     - Trained and evaluated using accuracy and classification report.
   - **K-Nearest Neighbors (KNN):**
     - Trained and evaluated using accuracy and classification report.
   - **K-Means Clustering:**
     - Applied clustering and evaluated using silhouette score.

## Results

- **Logistic Regression:**
  - Achieved an accuracy of `X.XX%` on the test set.
  
- **K-Nearest Neighbors (KNN):**
  - Achieved an accuracy of `X.XX%` on the test set.
  
- **K-Means Clustering:**
  - Achieved a silhouette score of `X.XX`.

## Requirements

- Python 3.7 or later
- Packages: 
  - `pandas`
  - `numpy`
  - `scikit-learn`
  - `matplotlib`
  - `seaborn`

To install the required packages, run:
```
pip install -r requirements.txt

```
## How to Run

1. Clone the repository.
2. Install the required packages.
3. Run the notebook **student_dropout_prediction.ipynb** to see the results.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

Thanks to the open-source community for providing the tools and datasets used in this project.
