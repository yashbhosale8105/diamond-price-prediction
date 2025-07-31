# 💎 Diamond Price Prediction

This project uses supervised regression algorithms to predict the **price of diamonds** based on features like carat, cut, clarity, color, and more.

---

## 📌 Problem Statement

Accurately predict diamond prices (in USD) based on physical and visual characteristics of diamonds using machine learning models.

---

## 🛠 Technologies Used

- Python 🐍
- Pandas, NumPy, Matplotlib, Seaborn
- scikit-learn
- Decision Tree Regressor
- Random Forest Regressor

---

## 📈 Results

| Model                   | Accuracy |
|------------------------|----------|
| Decision Tree Regressor| 91.5%    |
| Random Forest Regressor| **96.0%** ✅ |

---

## 📊 Dataset Features

- `carat`: weight of the diamond
- `cut`: quality of the cut (Ideal, Premium, Good, Fair, Very Good)
- `color`: diamond color (graded from D to J)
- `clarity`: clarity grading (IF, VVS1, VVS2, etc.)
- `depth`, `table`, `x`, `y`, `z`: physical measurements
- `price`: target variable (USD)

---

## 🧪 How to Run the Project

```bash
# 1. Clone the repository
git clone https://github.com/YOUR_USERNAME/diamond-price-prediction.git
cd diamond-price-prediction

# 2. Create virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Launch the notebook
jupyter notebook

