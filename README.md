# 🧠 EDA PROJECT 3:
# Mapping Parkinson's Journey — An Exploratory Analysis of Telemonitoring Data

---

## 📘 About the Project

This project undertakes an Exploratory Data Analysis (EDA) of a Parkinson's disease telemonitoring dataset. The dataset comprises biomedical voice measurements collected from individuals with early-stage Parkinson's disease during a six-month clinical trial utilizing a telemonitoring device. The primary objective of this EDA is to gain a comprehensive understanding of the dataset's structure, the characteristics of vocal features and clinical scores (UPDRS), and to explore the relationships and trends within the data over time. The insights gained will shed light on the variability of Parkinson's disease progression and the potential of telemonitoring data, particularly voice features, as indicators of disease severity and progression.

---

## 🧰 Tools & Libraries

* **Python (Jupyter Notebook)**
* **pandas** and **numpy** for data wrangling
* **matplotlib** and **seaborn** for visualization
* **scipy** and **statsmodels** for basic statistical analysis

---

## 🔍 Key Exploratory Questions Addressed

1. What are the main variables present in the Parkinson’s telemonitoring dataset?
2. How do **motor_UPDRS** and **total_UPDRS** scores vary across patients and over time?
3. What patterns emerge in **voice frequency features** (MDVP measures) related to disease severity?
4. How does the distribution of **age** and **sex** relate to UPDRS variability?
5. Are there strong correlations between vocal biomarkers and clinical scores?
6. Which features exhibit potential multicollinearity or redundancy?
7. What outliers exist in the dataset, and how do they influence observed trends?
8. How stable are the telemonitored features across repeated sessions for each subject?
9. Can we visually distinguish high vs. low UPDRS cases through pairplots and histograms?
10. What early hypotheses can be drawn about telemonitoring as a predictive tool for Parkinson’s progression?

---

## 📊 Findings and Concluding Remarks

* The dataset contains **5875 observations** and **22 features**, primarily numeric, representing continuous voice-based measurements.
* Significant correlations were found between **frequency and amplitude-based voice features** and both **motor_UPDRS** and **total_UPDRS** scores.
* Outlier analysis revealed a few anomalous **test_time** readings that may stem from data recording inconsistencies.
* Patterns suggest that **voice signal features** could act as non-invasive indicators for disease monitoring.
* The exploratory phase confirms strong potential for building predictive regression models to forecast disease severity based on vocal biomarkers.

---

## 📸 Sample Visuals

| UPDRS Score Distribution                             | Correlation Heatmap                        | Voice Feature Trends                     | Outlier Detection                |
| ---------------------------------------------------- | ------------------------------------------ | ---------------------------------------- | -------------------------------- |
| ![UPDRS Distribution](images/updrs_distribution.png) | ![Correlation Heatmap](images/heatmap.png) | ![Voice Trends](images/voice_trends.png) | ![Outliers](images/outliers.png) |

*(Save these plots from your notebook as `.png` files and upload them into the `images/` folder in this repo.)*

---

## 📁 Repository Structure

```
eda3_parkinsons_disease_telemonitoring/
│── notebooks/
│   └── EDA_Project3_Parkinsons.ipynb
│── images/
│   ├── updrs_distribution.png
│   ├── heatmap.png
│   ├── voice_trends.png
│   └── outliers.png
│── README.md
```

---

## 📂 Dataset Access

Due to data licensing restrictions, the dataset is not uploaded to this repository.
You can access it here:
👉 [Oxford Parkinson’s Disease Telemonitoring Dataset (UCI Repository)](https://archive.ics.uci.edu/ml/datasets/parkinsons+telemonitoring)

---

## 🚀 Next Steps

* Apply **feature selection** and correlation filtering
* Develop **predictive regression models** for UPDRS estimation
* Explore **time-series modeling** of progression per patient
* Visualize longitudinal patterns in **vocal biomarkers**

---

## ✍️ Author

**Adebayo Fashina**
📍 Toronto, Canada | [LinkedIn](https://www.linkedin.com/in/your-link-here)
