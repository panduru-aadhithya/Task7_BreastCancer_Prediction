# Task 7 – Breast Cancer Prediction Using Machine Learning

## Project Overview
This project predicts whether a tumor is **malignant** or **benign** using the **Wisconsin Breast Cancer Dataset**. It applies machine learning algorithms to analyze the data, build predictive models, and evaluate their performance.

---

## Dataset
- **Source:** Wisconsin Breast Cancer Dataset (`breast_cancer_data.csv`)  
- **Features include:**  
  - `radius_mean`, `texture_mean`, `perimeter_mean`, `area_mean`, `smoothness_mean`, `compactness_mean`, `concavity_mean`, `concave points_mean`, `symmetry_mean`, `fractal_dimension_mean`  
- **Target variable:** `diagnosis` (M = Malignant, B = Benign)

---

## Project Steps
1. **Data Loading:** Load the dataset using `pandas`.
2. **Exploratory Data Analysis (EDA):**  
   - Check for missing values  
   - Analyze basic statistics  
   - Visualize feature distributions
3. **Data Preprocessing:**  
   - Encode categorical variables  
   - Split data into training and test sets  
   - Standardize/normalize features if required
4. **Model Building:**  
   - Train machine learning models (Logistic Regression, KNN, Decision Tree, Random Forest)  
   - Evaluate models using accuracy, confusion matrix, and classification report
5. **Prediction:** Use the trained model to predict new samples.
6. **Conclusion:** Compare models and determine the best-performing one.

---

## How to Run
1. Clone the repository:
```bash
git clone <your-github-repo-link>
cd <repo-folder>
pip install -r requirements.txt
jupyter notebook
Task7_BreastCancer_Prediction/
│
├── breast_cancer_data.csv       # Dataset
├── Task7_BreastCancer.ipynb     # Jupyter Notebook with code
├── README.md                    # Project description
└── requirements.txt             # Python libraries (optional)
Key Libraries Used

pandas – data manipulation

numpy – numerical operations

matplotlib / seaborn – data visualization

scikit-learn – machine learning models
