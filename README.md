# Breast Cancer Classification using Logistic Regression

This project demonstrates the use of **Logistic Regression** to classify breast cancer patient status (`Alive` or `Dead`) based on clinical data.

---

## 📊 Dataset Description

The dataset contains the following features:
- Demographic details (Age, Race, Marital Status)
- Tumor characteristics (T Stage, N Stage, Grade, Tumor Size, etc.)
- Hormone Receptor Status (Estrogen, Progesterone)
- Regional Node details

### Target Variable:
- **Status** (`Alive` or `Dead`)

---

## ⚙ Model Details

- Algorithm: **Logistic Regression**
- Special Handling:  
  - **Class Imbalance managed using `class_weight='balanced'`.**
  - **Categorical features encoded using one-hot encoding.**

---

## 🔍 Key Results

| Class  | Precision | Recall | F1-Score |
|--------|-----------|--------|----------|
| Alive  | 0.94      | 0.79   | 0.86     |
| Dead   | 0.39      | 0.73   | 0.51     |

- Overall Accuracy: **78%**
- Imbalance is present.
- Model shows **high recall but low precision for the 'Dead' class**, meaning it's catching most cases but also giving false alarms.

---

## 💻 Technologies Used

- Python
- Pandas, NumPy
- Scikit-Learn

---

## 📜 References

- [Scikit-learn Documentation](https://scikit-learn.org/stable/)
- [Imbalanced-Learn Documentation](https://imbalanced-learn.org/stable/)

