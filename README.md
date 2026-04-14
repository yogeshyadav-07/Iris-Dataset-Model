# 🌸 Iris Flower Classification Model

## 📌 Project Overview

This project is a Machine Learning model that classifies iris flowers into three species using their physical features. The model is built using Logistic Regression and trained on the Iris dataset.

### 🎯 Target Classes

* Setosa
* Versicolor
* Virginica

### 📊 Features Used

* Sepal Length
* Sepal Width
* Petal Length
* Petal Width

---

## 🚀 Features

* Data preprocessing using Pandas
* Label Encoding for categorical target
* Feature Scaling using StandardScaler
* Train-test split
* Model training using Logistic Regression
* Prediction on test data

---

## 📂 Dataset

* Dataset file: `Iris.csv`
* Total samples: 150
* Features: 4
* Target column: Species

---

## 🛠️ Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/iris-model.git
cd iris-model
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ Usage

Run the notebook or script:

```bash
jupyter notebook model.ipynb
```

---

## 🔄 Model Workflow

1. Load dataset from CSV
2. Copy dataset for safety
3. Perform basic EDA (`info()`, `head()`)
4. Encode target variable using LabelEncoder
5. Separate features (X) and target (y)
6. Apply StandardScaler to features
7. Split data into training and testing sets
8. Train Logistic Regression model
9. Predict on test data

---

## 📈 Example Prediction

```
Input: [5.1, 3.5, 1.4, 0.2]
Output: 0 (Setosa)
```

---

## 📊 Model Performance

* Model: Logistic Regression
* Good accuracy on test data (depends on split, typically ~95%+)

---


---

## 💡 Future Improvements

* Add model evaluation metrics (accuracy, confusion matrix)
* Save model using Pickle or Joblib
* Convert notebook to Python script
* Add Streamlit UI
* Deploy model online

---

## 👨‍💻 Author

Yogesh Yadav

---

## 📜 License

This project is open-source and available under the MIT License.
