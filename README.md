# 🧱 LEGO Sets Data Analysis

This project analyzes a dataset of LEGO sets released over the years. Using data visualization techniques in Python, we explored how LEGO has evolved in terms of set quantity, complexity, and popular themes.

## 📊 Dataset Overview

The dataset includes:
- `set_number`: Unique identifier for each set
- `set_name`: Name of the LEGO set
- `year_released`: Year the set was released
- `number_of_parts`: Number of parts in the set
- `image_url`: URL to an image of the set
- `theme_name`: Theme category the set belongs to

Data source: [LEGO Sets Themes CSV](https://raw.githubusercontent.com/cheribeda/datamining/main/LEGO_Sets%20_Themes%20.csv)

## 🧩 Questions Explored

1. **How has the number of LEGO sets released evolved over the years?**
2. **Which themes have been the most prevalent in LEGO set releases?**
3. **Is there a relationship between the number of parts in a LEGO set and its release year?**

## 📈 Key Visualizations

### 1. Evolution of LEGO Set Releases Over Time
- Line plot shows a steady increase in set releases since 1996
- Peak release year: **2021**

### 2. Top 20 LEGO Themes
- **Star Wars** and **Technic** are the most prevalent themes
- Other entries include merchandise-based themes like books and costumes

### 3. Number of Parts vs. Year of Release
- Scatter plot suggests a trend of increasing complexity
- Notable outlier: *World Map* (2021) with **11,695** pieces

## 🧠 Key Takeaways

- LEGO's set production has increased significantly since the mid-90s
- Strategic partnerships like *Star Wars* have driven theme popularity
- Modern sets are more intricate, with higher piece counts over time

## 🛠 Tools Used

- Python (Pandas, Matplotlib)
- Jupyter Notebook
