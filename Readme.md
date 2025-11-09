# 🚀 SpaceX Landing Prediction Project

## 🎯 What This Project Is

This is the capstone project for the **IBM Data Science Professional Certificate**. The main goal was to use data science and machine learning to **accurately predict if the Falcon 9 rocket's first stage would land successfully**.

We used historical launch data to build and test models that help understand what makes a landing successful.

---

## ⚙️ How It Was Done

The project followed key data science steps:

1.  **Data Preparation:** Collected real launch data (like payload mass and launch site) and prepared it for analysis.
2.  **Analysis (EDA):** Visualized the data to find important patterns, such as the relationship between orbit type and success rate.
3.  **Model Building:** Trained four different classification models: **Logistic Regression**, **SVM**, **Decision Tree**, and **KNN**.
4.  **Best Model Selection:** Evaluated the models to choose the best predictor based on accuracy and reliability.

### Key Tools Used
* **Python**
* **Pandas & NumPy** (for data handling)
* **Scikit-learn** (for machine learning models)
* **Matplotlib & Seaborn** (for visualizations)

---

## 📊 Main Results

* **High Accuracy:** The final model achieved a high accuracy score of approximately **83.33%** on the test data.
* **Reliability:** The model is extremely reliable for mission success: it **never failed to predict an actual successful landing** (zero false negatives), which is essential for aerospace operations.
* **Predictors:** Launch site location and the type of orbit were identified as the strongest factors in predicting landing success.

---

## 🚀 Getting Started

To explore this project:

1.  **Clone the Repository:** Download the project files to your local machine.
2.  **Install Libraries:** Install the necessary Python packages listed above (e.g., `pip install pandas scikit-learn`).
3.  **Run Notebooks:** Open the notebooks in the `notebooks/` folder to view the complete analysis step-by-step.

---

##  Author : Ait Bouhnmad Omar

* **Project Status:** Successfully completed for the IBM Data Science Professional Certificate.
