# Logistic Regression Binary Classifier

## 📌 Objective
Build a **binary classification model** using **Logistic Regression** to predict whether a tumor is **benign (0)** or **malignant (1)** using the **Breast Cancer Wisconsin dataset**.

---

## 🛠 Tools & Libraries
- **Python**
- **Pandas** – Data handling
- **Matplotlib** – Visualization
- **Scikit-learn** – Logistic Regression, metrics, ROC curve

---

## 📂 Dataset
You can either:
1. **Use Scikit-learn's built-in dataset:**
   ```python
   from sklearn.datasets import load_breast_cancer
   data = load_breast_cancer()
2. Load from CSV ([Kaggle Breast Cancer Wisconsin Dataset](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)):
    ```python
    DATA_PATH = os.path.join("/kaggle", "input", "breast-cancer-wisconsin-data", "data.csv")
    if not os.path.exists(DATA_PATH):
        raise FileNotFoundError(f"Dataset not found at '{DATA_PATH}'. Please download breast cancer wisconsin data CSV and place it there.")
    df = pd.read_csv(DATA_PATH)

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone git@github.com:Elevate-Labs-Intern/AIML-Task-4.git
2. Import the .ipynb in Kaggle
