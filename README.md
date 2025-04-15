
# 🎮 Analysis and Prediction of Video Game Sales using Machine Learning Algorithms

## 📚 Project Overview

This project focuses on analyzing and predicting the sales of video games using various machine learning algorithms. The dataset includes game features such as platform, genre, regional sales, and global sales. We used regression and classification models to gain insights and predict success based on sales performance.

---

## 🛠 Technologies & Libraries Used

- Python 🐍
- Jupyter Notebook 📒
- Pandas, NumPy, Matplotlib, Seaborn, Plotly 📊
- Scikit-learn (Linear Regression, Random Forest, Logistic Regression, KNN) 🤖

---

## 📂 Dataset

- **File:** `video games data.csv`
- **Source:** Included in the same directory as the notebook.

---

## 🧠 Models Implemented

### Regression Models (Global Sales Prediction)
1. **Linear Regression**
2. **Random Forest Regressor**

### Classification Models (Success Prediction)
1. **Logistic Regression**
2. **K-Nearest Neighbors (KNN)**

---

## 🧹 Data Preprocessing

- Missing values handled using `dropna()`.
- `LabelEncoder` used for categorical features like `Platform` and `Genre`.
- Features were scaled using `StandardScaler` for classification models.

---

## 📊 Exploratory Data Analysis

- Correlation heatmap
- Distribution of sales by year
- Frequency of games by platform and genre

---

## ✅ Classification Target

A binary target variable `Successful` was created based on whether the `Global_Sales > 1 million`. This target is used in classification models.

---

## ▶️ How to Run the Project

### Step 1: Clone this Repository

```bash
git clone (https://github.com/Abhishekkarnam/Video-Games-Sales-Prediction-.git)
cd video-game-sales-ml
```

### Step 2: Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn plotly scikit-learn
```

### Step 3: Open and Run Jupyter Notebook

```bash
jupyter notebook
```

Open the notebook file and run cells sequentially to perform:
- Data analysis
- Regression prediction (Linear & Random Forest)
- Classification prediction (Logistic Regression & KNN)

---

## 📈 Results & Observations

- Among the regression models, **Linear Regression** showed better performance based on MAE and RMSE.
- For classification, both **Logistic Regression** and **KNN** gave good results after hyperparameter tuning.
- Visualizations clearly showed trends in platforms, genres, and sales distribution.

---

## 📄 File Structure

```
├── video_game_sales_analysis.ipynb     # Jupyter Notebook with full project code
├── video games data.csv                # Dataset
└── README.md                           # Project description and usage instructions
```

---

## 🙋‍♂️ Author

- Name: *Abhishek karnam*
- Email: *abhishekk.btech23@rvu.edu.in*
- GitHub: [Abhishekkarnam](https://github.com/Abhishekkarnam)

---

## 📌 Note

All code is written in a single `.ipynb` notebook file for simplicity and easier understanding. For production or collaborative work, separating code into `.py` modules is recommended.
