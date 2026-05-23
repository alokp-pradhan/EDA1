## Dataset Information

The Cardiotocographic dataset contains fetal health monitoring parameters collected through Cardiotocography (CTG). The dataset is used to classify fetal state conditions based on several medical attributes.

### Features in Dataset

* **LB** → Fetal Heart Rate Baseline
* **AC** → Accelerations
* **FM** → Fetal Movements
* **UC** → Uterine Contractions
* **DL** → Light Decelerations
* **DS** → Severe Decelerations
* **DP** → Prolonged Decelerations
* **ASTV** → Percentage of Abnormal Short-Term Variability
* **MSTV** → Mean Value of Short-Term Variability
* **ALTV** → Percentage of Abnormal Long-Term Variability
* **MLTV** → Mean Value of Long-Term Variability
* **Width** → Histogram Width
* **Tendency** → Histogram Tendency
* **NSP** → Fetal State Class (Target Variable)

---

## Exploratory Data Analysis (EDA)

Performed detailed Exploratory Data Analysis (EDA) to understand fetal health patterns and identify important relationships among medical parameters.

### EDA Steps Performed

* Checked dataset structure using `df.head()` and `df.info()`
* Handled missing and abnormal values
* Performed statistical analysis using `describe()`
* Visualized feature distributions using histograms and boxplots
* Analyzed correlations using heatmaps
* Detected outliers using IQR method
* Studied class distribution of fetal state categories
* Identified relationships between variability, contractions, and fetal condition

### Key Insights

* Higher abnormal variability values were associated with abnormal fetal states
* Certain deceleration features strongly influenced fetal health classification
* Some features contained outliers that required preprocessing
* Correlation analysis helped identify the most important predictive features

### Technologies Used

Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
