# 🧠 Breast Cancer Classification with Support Vector Machines (SVM)

This project uses Support Vector Machines (SVM) to classify breast cancer data into malignant or benign classes using linear and RBF kernels. PCA is used for 2D visualization of decision boundaries.

## 🛠 Tools Used
- Python, NumPy, Pandas
- Scikit-learn (SVC, PCA, GridSearchCV)
- Matplotlib, Seaborn

## 🚀 Features
- SVM with linear and RBF kernels
- PCA for visualization
- Confusion matrix and accuracy metrics
- Hyperparameter tuning (C, gamma) via GridSearchCV
- Decision boundary visualization

## 📁 Folder Structure
- `notebook/` – Jupyter notebook with full implementation
- `src/` – Optional Python script version
- `outputs/` – Decision boundary plots
- `README.md` – Project explanation and instructions
- `requirements.txt` – Python dependencies

## 📈 Dataset
We use the built-in `load_breast_cancer` dataset from `sklearn.datasets`.

## 📊 Model Evaluation
- Accuracy
- Confusion matrix
- Classification report
- GridSearchCV for best `C` and `gamma`

## 🧪 How to Run

### Option 1: Google Colab
- Open `notebook/svm_breast_cancer.ipynb` in [Colab](https://colab.research.google.com/)
- Run all cells and view the visualizations

### Option 2: Locally in VS Code
```bash
git clone https://github.com/yourusername/svm-breast-cancer-classification.git
cd svm-breast-cancer-classification
pip install -r requirements.txt
python src/svm_classifier.py
