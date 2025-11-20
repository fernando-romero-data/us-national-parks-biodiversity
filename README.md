# us-national-parks-biodiversity

Absolutely — here is the **clean, copy-and-paste–ready version** with perfect spacing and formatting.
Just drop this directly into your `README.md` on GitHub.

---

# 🌿 **Biodiversity in U.S. National Parks**

### *Data Science Case Study • Conservation Analysis • Exploratory Research*

---

## 👋 **Project Summary**

This project investigates **biodiversity and endangered species patterns** across four U.S. National Parks.
Using real ecological data, I performed **data cleaning, exploratory analysis, visualization, and statistical testing** to uncover patterns in conservation status across species categories and parks.

The project answers:

* Which species are most at risk?
* Are some species categories disproportionately endangered?
* Do parks differ in how many protected species they host?
* Are differences between categories statistically significant?

This is a **portfolio-grade analysis** demonstrating practical data science skills relevant to analytics, research, and applied machine learning roles.

---

## 🧰 **Tech Stack**

**Python • pandas • NumPy • matplotlib • seaborn • SciPy • Jupyter Notebook**

---

## 📊 **Key Findings**

### **1️⃣ Conservation status is highly imbalanced**

Only **3%** of all species are under protection.

* **5,633 species** — No Intervention
* **191 species** — Under Protection

---

### **2️⃣ Mammals & Birds are most likely to be endangered**

These categories show the **highest proportion of protected species**, indicating heightened ecological risk or stronger monitoring.

---

### **3️⃣ Conservation status differences are statistically significant**

(Chi-square testing)

* **Mammals vs Birds** — *No significant difference*
* **Mammals vs Reptiles** — *Significant difference found*

➡️ Some species groups face disproportionately higher conservation pressure.

---

### **4️⃣ Bats are the most protected species across the parks**

* Bats have the **highest conservation counts**
* **Yellowstone National Park** contains the **largest protected bat population**

---

## 📁 **Repository Structure**

```
📦 national-parks-biodiversity-analysis
│
├── data/
│   ├── species.csv
│   └── parks.csv
│
├── notebooks/
│   ├── 01_data_cleaning.ipynb
│   ├── 02_eda.ipynb
│   ├── 03_visualizations.ipynb
│   └── 04_statistical_tests.ipynb
│
├── visuals/
│   ├── conservation_status_distribution.png
│   ├── species_by_category.png
│   └── park_bat_distribution.png
│
└── README.md
```

---

## 🧪 **Methods Used**

* Data wrangling & cleaning
* Exploratory data analysis (EDA)
* Group-by + aggregation
* Crosstabs
* Chi-square hypothesis testing
* Species category comparisons
* Park-level visualizations

---

## 🧠 **What This Project Demonstrates**

This project highlights my ability to:

✔ Clean and preprocess real-world data
✔ Identify meaningful ecological insights
✔ Validate findings with statistical testing
✔ Produce clear, compelling visualizations
✔ Communicate technical results in a business-friendly way
✔ Build a clean, reproducible notebook workflow

---

## 📌 **Conclusion**

Across four National Parks, most species are not under conservation status, but key groups — especially **mammals, birds, and bats** — show elevated protection needs.
Statistical analysis confirms significant differences in conservation risk across categories, and Yellowstone stands out as a major park for protected bat species.

This work provides a data-driven foundation for understanding biodiversity risk and supporting conservation strategies.

---

## 🚀 **Future Enhancements**

* Add geospatial mapping (GeoPandas / Folium)
* Build an interactive dashboard (Plotly / Tableau)
* Predict conservation status using machine learning
