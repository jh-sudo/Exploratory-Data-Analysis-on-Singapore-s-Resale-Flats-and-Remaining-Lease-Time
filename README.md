# 🏙️ Exploratory Data Analysis on Singapore’s Resale Flats and Remaining Lease Time

This project analyzes public housing data from Singapore with a focus on the relationship between remaining lease duration and resale flat prices. It offers a region-wise exploratory data analysis to uncover trends and disparities across the island.

---

## ✨ Features

- Visual analysis of resale HDB flats across Singapore
- Region-based filtering (Central, East, North, North-East, West)
- Lease remaining time distribution insights
- Correlation heatmaps, bar plots, and histograms
- Reference map showing Singapore regions

---

## ▶️ How to Run

1. Open the notebook:
   `Exploratory Data Analysis on Singapore's Resale Flats and Remaining Lease Time.ipynb`

2. Ensure the file `dataset.csv` is in the same directory.

3. Run with Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

4. Required Python libraries:
   - pandas
   - matplotlib
   - seaborn

---

## 📁 Project Structure

```
📂 singapore-resale-analysis/
├── dataset.csv
├── Exploratory Data Analysis on Singapore's Resale Flats and Remaining Lease Time.ipynb
├── singapore-states-and-capital-map.jpg
└── README.md
```

---

## 🛠️ Technologies Used

- Python 3
- Jupyter Notebook
- Pandas
- Matplotlib
- Seaborn
- CSV

---

## 💬 Developer Commentary

This project explored the impact of remaining lease years on HDB flat resale prices in Singapore. By cleaning and grouping the data by flat type and region, I discovered that:

- Flats in mature estates like Queenstown and Bukit Merah command higher prices even with shorter leases.
- The remaining lease length does influence pricing, but location is a stronger determinant.
- Visualization using Seaborn and Matplotlib brought regional differences into clear focus.

A reference map was also included to assist in contextualizing regional patterns. Overall, this project strengthened my skills in data wrangling, visualization, and extracting actionable insights from government housing data.

---

## 🎓 Educational Scope

This analysis was conducted as part of a data analytics coursework module. Learning outcomes include:
- Applying exploratory data analysis to real-world datasets
- Understanding Singapore’s public housing dynamics
- Enhancing technical proficiency with Python libraries for data science
- Translating raw data into meaningful geographic and economic insights
