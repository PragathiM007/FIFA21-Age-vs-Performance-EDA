# FIFA21: Age vs Player Performance Ratings (EDA Project)

## 📄 Overview
This project investigates whether a player's **age** significantly impacts their **overall performance ratings** in FIFA 21. Conducted as part of Bellevue University's DSC530 - Data Exploration & Analysis course, the analysis uses statistical methods and visualizations to explore patterns, distributions, and relationships between player age and key performance metrics such as passing and shooting.

---

## 🔍 Hypothesis
**Does a player's age impact their overall performance ratings in FIFA 21?**

The project assumes a positive correlation between player age and performance rating, exploring whether peak performance aligns with certain age ranges in professional soccer players.

---

## 📊 Key Insights from EDA
- **Correlation Coefficient**: ~0.47 between age and overall rating, indicating a moderate positive relationship.
- **Skill Metrics**: Shooting and passing scores also showed positive correlation with age.
- **Descriptive Stats**: Majority of players are in their 20s, with ratings forming an approximately normal distribution.
- **CDF & Analytical Distribution**: Revealed skew due to top-rated star players.

---

## 📁 Dataset
- **Source**: [FIFA 21 Player Dataset on Kaggle](https://www.kaggle.com/datasets/stefanoleone992/fifa-21-complete-player-dataset)
- **Size**: ~18,000 players
- **Key Variables**:
  - `age`
  - `overall`
  - `shooting`, `passing`, `pace`, etc.
  - `position`, `club`, `nationality`

---

## 📈 Tools & Methods
- **Python** (Pandas, Matplotlib, Seaborn, NumPy)
- **Statistical Analysis**:
  - Descriptive statistics (mean, median, mode, spread)
  - Correlation analysis
  - CDFs and PMFs
  - Distribution fitting
- **Visualization**:
  - Histograms, scatter plots, heatmaps

---

## 🧠 Missed Elements (Reflections)
- Position-based and league-based performance breakdowns were not included and could add significant value.
- Variables like `experience` and `stamina` could reveal more nuance in age-performance patterns.
- Real-world generalizability of FIFA ratings may be limited due to composite scoring.

---

## 📦 Folder Structure
FIFA21-Age-vs-Performance-EDA/
├── data/
│ └── players_21.csv
├── notebooks/
│ └── age_vs_rating_analysis.ipynb
├── README.md



---

## ⚖️ Ethical Considerations
- No PII present; data is public and game-based.
- All transformations and filtering steps documented.
- Caution applied when generalizing findings beyond FIFA ratings.

---

## 👤 Author
**Pragathi Porawakara Arachchige**  
Bellevue University – DSC530 Data Exploration and Analysis  
[GitHub](https://github.com/PragathiM007)
