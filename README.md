🚢 Titanic Survival Analysis

An end-to-end **Exploratory Data Analysis (EDA)** project on the Titanic dataset, uncovering the demographic and socio-economic factors that influenced passenger survival.

---

 📌 Project Overview

The sinking of the RMS Titanic in 1912 is one of history's most well-known maritime disasters. This project analyzes the Titanic passenger dataset to identify patterns and factors that determined survival — including gender, passenger class, age, family size, and fare.

---

 Libraries Used

| Library | Purpose |
|---|---|
| `Pandas` | Data loading, cleaning, and preprocessing |
| `NumPy` | Numerical operations and median imputation |
| `Matplotlib` | Base plotting and chart customization |
| `Seaborn` | Statistical visualizations (heatmaps, boxplots, bar charts) |

---

📂 Project Structure

```
titanic_survival_analysis/
│
├── titanic_survival_analysis.ipynb   # Main analysis notebook
├── README.md                         # Project documentation
└── data/
    └── titanic.csv                   # Dataset (from Kaggle / Seaborn)
```

---

📊 Analysis Breakdown

### 1. Data Overview & Descriptive Statistics
- Dataset spans passengers aged ~5 months to 80 years, with an average age of 30
- Overall survival rate: **38.4%**
- Fare is heavily right-skewed — average fare ~$32 vs. median ~$14.45, with outliers reaching $512

### 2. Univariate Analysis
- Majority of passengers did **not** survive (500+)
- **3rd class** was the most populated passenger class
- Male passengers significantly outnumbered females
- Most passengers boarded from **Southampton, England**
- Most passengers travelled **solo**

### 3. Bivariate & Multivariate Analysis

#### 🎯 Key Survival Insights

| Factor | Finding |
|---|---|
| **Gender** | Females had 70%+ survival rate; males under 20% |
| **Passenger Class** | 1st class: 60%+ survival; 3rd class: below 30% |
| **Embarkation Port** | Southampton passengers had the highest survival rate (50%+) |
| **Family Size** | Small families (2–4) survived more than solo travelers or large families (5+) |
| **Age** | Infants and young children had higher survival; young adults (20–30) had the most casualties |
| **Cabin Availability** | Passengers with a cabin had higher survival rates |

---

## 💡 Key Takeaways

- **Gender** was the strongest predictor of survival, driven by the *"women and children first"* evacuation protocol
- **Socio-economic status** (passenger class) played a decisive role — higher class meant better access to lifeboats
- **Family dynamics** mattered — small families coordinated evacuation better than large ones or solo travelers
- **Fare and cabin data** were strong proxies for wealth and class, correlating with survival outcomes

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/titanic-survival-analysis.git
   ```
2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
3. Open the notebook:
   ```bash
   jupyter notebook titanic_survival_analysis.ipynb
   ```
   Or open directly in [Google Colab](https://colab.research.google.com/)

---

## 📁 Dataset

The Titanic dataset is publicly available via:
- [Kaggle Titanic Competition](https://www.kaggle.com/c/titanic/data)
- Built-in Seaborn dataset: `sns.load_dataset('titanic')`

---

## 👩‍💻 Author

**Rohitha Mettu** 
 Python | EDA | Data Visualization  
[LinkedIn](https://www.linkedin.com/in/your-profile) • [GitHub](https://github.com/your-username)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
