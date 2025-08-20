# 🌞 Asian UV Index Data Analysis Projects

A collection of beginner-friendly data analysis projects exploring the **Asian UV Index dataset for 2024**.
This repository is designed for practicing data analysis and visualization skills using Python.

---

## 📂 Repository Structure

```
Asian_UV_Index_Analysis/
│
├── data/
│   └── asian_uv_index_dataset_2024.csv   # Dataset
│
├── scripts/
│   ├── project_basic_statistics.py       # Basic descriptive stats
│   ├── project_city_trends.py            # City-wise UV trends
│   ├── project_country_avg_uv.py         # Country-wise average UV
│   ├── project_uv_cloud_correlation.py   # UV vs Cloud Cover correlation
│   └── project_max_uv_per_city.py        # Maximum UV per city
│
├── README.md                             # Project description & instructions
└── requirements.txt                      # Required Python libraries
```

---

## 📊 About the Dataset

**File:** `asian_uv_index_dataset_2024.csv`

| Column       | Description                                                |
| ------------ | ---------------------------------------------------------- |
| Date         | Date of observation                                        |
| City         | Name of the city                                           |
| Country      | Country of the city                                        |
| Latitude     | Latitude coordinate                                        |
| Longitude    | Longitude coordinate                                       |
| UV\_Index    | UV Index reading                                           |
| Risk\_Level  | Categorized UV risk level (Low, Moderate, High, Very High) |
| Cloud\_Cover | Cloud cover percentage                                     |

---

## 🚀 Projects

### 1️⃣ Basic Statistical Analysis (প্রাথমিক ডেটা বিশ্লেষণ)

* **Goal:** Understand the basic statistics and distribution of UV Index and Cloud Cover.
* **Techniques:** `.describe()`, histograms, bar plots, count plots.
* **Script:** `project_basic_statistics.py`

---

### 2️⃣ City-wise UV Trend Analysis (শহর অনুযায়ী UV প্রবণতা)

* **Goal:** Visualize UV Index changes over time for selected cities.
* **Techniques:** Line plots, multi-city comparison, filtering by city.
* **Script:** `project_city_trends.py`

---

### 3️⃣ Country-wise Average UV Index (দেশ অনুযায়ী গড় UV সূচক)

* **Goal:** Identify countries with the highest average UV Index.
* **Techniques:** `.groupby()`, mean calculations, bar charts.
* **Script:** `project_country_avg_uv.py`

---

### 4️⃣ UV Index vs Cloud Cover Correlation (UV বনাম মেঘের পরিমাণ)

* **Goal:** Analyze the relationship between Cloud Cover and UV Index.
* **Techniques:** Scatter plots colored by Risk Level, correlation matrix.
* **Script:** `project_uv_cloud_correlation.py`

---

### 5️⃣ Maximum UV Index per City (শহর অনুযায়ী সর্বোচ্চ UV সূচক)

* **Goal:** Find the maximum UV Index recorded for each city in 2024.
* **Techniques:** `.groupby()`, max calculation, bar plots.
* **Script:** `project_max_uv_per_city.py`

---

## 🛠️ Tools, Libraries, and Software Used

**Programming Language:** Python 3.8+

**Python Libraries:**

* `pandas` – Data manipulation and analysis
* `numpy` – Numerical computations and statistics
* `matplotlib` – Static, animated, and interactive plotting
* `seaborn` – Statistical data visualization

**Software & IDEs:**

* **Python** – [Download](https://www.python.org/downloads/)
* **Jupyter Notebook** (optional, for interactive analysis)
* **VS Code / PyCharm** – For writing and running Python scripts
* **Git** – Version control

**Operating System:** Windows 10/11, macOS, or Linux

**requirements.txt**

```
pandas>=1.5.0
numpy>=1.24.0
matplotlib>=3.7.0
seaborn>=0.12.0
```

---

## ⚡ How to Run the Projects

1. **Clone the repository**

```bash
git clone https://github.com/yourusername/Asian_UV_Index_Analysis
```

2. **Navigate to the project directory**

```bash
cd Asian_UV_Index_Analysis
```

3. **Install required libraries**

```bash
pip install -r requirements.txt
```

4. **Run any project script**

```bash
python scripts/project_basic_statistics.py
python scripts/project_city_trends.py
python scripts/project_country_avg_uv.py
python scripts/project_uv_cloud_correlation.py
python scripts/project_max_uv_per_city.py
```

