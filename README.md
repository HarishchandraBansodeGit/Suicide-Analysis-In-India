---

# 📊 Suicide Data Analysis in India (2001–2012)

![suicide-image](https://static.theprint.in/wp-content/uploads/2020/01/suicide.jpg)

**Analysis of suicide data in India to uncover demographic, state-wise, and cause-based trends.**

This project examines suicide data over a decade (2001–2012) to provide insights into **gender, age, profession, education, causes, and geographic distribution**. The analysis can inform policymakers, researchers, and social organizations for preventive measures.

---

## 📝 Project Overview

This project is a **data analysis and visualization study** using Python, focused on suicide trends in India. It was developed as a mini-project for the **M.Sc. (Computer Science) curriculum at Sir Parashurambhau College, Pune**.

The main objectives are:

* Identify states with **highest and lowest suicide rates**
* Analyze **demographics**: gender, age groups, marital status
* Explore **professional and educational factors**
* Examine **most common causes and methods of suicide**
* Visualize trends over the decade

---

## 📂 Dataset Details

* **Source:** [data.world](https://data.world/rajanand/suicides-in-india) / [Kaggle](https://www.kaggle.com/rajanand/suicides-in-india)
* **Time Period:** 2001–2012
* **Entries:** 237,519
* **Columns:** 7
* **Key Fields:**

  * `State`: 35 States/UTs
  * `Year`: Year of record
  * `Type_code`: Causes, Education, Means, Professional Profile, Social Status
  * `Gender`: Male / Female
  * `Age_Group`: 0-14, 15-29, 30-44, 45-59, 60+

---

## 🛠️ Tech Stack

| Layer             | Technology                      |
| ----------------- | ------------------------------- |
| Language          | Python                          |
| Data Manipulation | Pandas, NumPy                   |
| Visualization     | Matplotlib, Seaborn             |
| IDE               | Jupyter Notebook / Google Colab |

---

## 🔍 Methodology

1. **Data Preprocessing**

   * Imported CSV data using Pandas
   * Checked for null values (none found)
   * Standardized state names and cleaned inconsistent entries

2. **Exploratory Data Analysis (EDA)**

   * Temporal trends (year-wise)
   * Demographic distributions (gender, age, marital status)
   * Socio-economic factors (profession, education)

3. **Visualization**

   * Bar charts, line charts, and pie charts to highlight trends
   * State-wise heatmaps and reason-based breakdowns

---

## 💡 Key Insights & Observations

### 1. Geographic Trends

* **High Suicide Rates:** Maharashtra, West Bengal, Tamil Nadu, Andhra Pradesh
* **Low Suicide Rates:** Nagaland, Lakshadweep, Daman & Diu

### 2. Demographics

* **Gender:** Males significantly outnumber females
* **Age:** Most vulnerable groups are **15–29** and **30–44**
* **Marital Status:** Married individuals constitute the majority

### 3. Professional & Educational Profile

* **Profession:** Farmers and housewives have the highest suicide rates, highlighting agrarian distress and domestic issues
* **Education:** Lower education correlates with higher suicide incidence

### 4. Causes and Means

* **Top Causes:** Family problems, prolonged illness, mental illness, bankruptcy
* **Common Methods:** Hanging, poisoning (insecticides), self-immolation

---

## 📉 Conclusion

* Suicide in India primarily affects the **productive age group (15–44 years)**
* Slight dip observed in 2012 after a general increase from 2006–2011
* High prevalence among farmers and housewives suggests **targeted social and economic interventions** are needed

---

## 📊 Sample Visualizations

* State-wise suicide counts
* Gender vs. age distribution
* Top causes of suicide
* Year-wise trend of suicides

---

## ⚡ How to Run

1. Clone the repository:

```bash
git clone https://github.com/HarishchandraBansodeGit/Suicide-Analysis-In-India.git
```

2. Extract the CSV if zipped
3. Open `Suicide_Analysis_in_India.ipynb` in Jupyter Notebook or Google Colab
4. Install dependencies (optional if using Colab):

```bash
pip install pandas numpy matplotlib seaborn
```

5. Run all cells to reproduce the analysis and visualizations

---

## 📚 References

* [Wikipedia – Suicide in India](https://en.wikipedia.org/wiki/Suicide_in_India)
* [Our World in Data](https://ourworldindata.org/suicide)
* [National Crime Records Bureau](https://ncrb.gov.in/)

---

## 👤 Author

**Harishchandra Devadatta Bansode**
*Department of Computer Science*
*Sir Parashurambhau College (Autonomous), Pune*

---

## 🏷 Topics / Tags

`visualization` `dataanalysis` `suicide-prevention` `python` `EDA` `pandas` `Jupyter`

---

