
# 🎬 Netflix Data Analysis Project

This project explores and analyzes the **Netflix Titles Dataset (2021)** using Python libraries such as Pandas, Matplotlib, and Seaborn. The goal is to extract insights and trends from the dataset, such as content type, release trends, and country-wise distributions.

---

## 📁 Dataset

- Source: [Netflix Titles Dataset 2021](https://www.kaggle.com/datasets)
- Contains information about TV shows and movies available on Netflix up to 2021.

---

## 🛠️ Tools & Libraries

```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
from IPython.display import Image
```

---

## 🔍 Project Overview

### 1) Understanding the Dataset

```python
netflix = pd.read_csv("netflix_titles_2021.csv")
netflix.head()
netflix.tail()
netflix.sample()
netflix.columns
netflix.info()
netflix.shape
```

### 2) Visual Analysis

Includes various visualizations such as:
- Distribution of Movies vs TV Shows
- Country-wise content availability
- Content added by year
- Duration analysis

---

## 📊 Key Insights

- Netflix has more movies than TV shows.
- The US and India have the most Netflix content.
- Majority of the content was added in recent years.
- Most TV Shows are listed as "Seasons", while movies are measured in minutes.

---

## 📌 How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/yourusername/netflix-analysis.git
   ```
2. Open the `NETFLIX.ipynb` file using Jupyter Notebook.
3. Run all cells to see the analysis and visualizations.

---

## 👩‍💻 Author

**Chandrika Chavva**  
Passionate about Data Science, AI, and Data Analytics  
[LinkedIn] : https://www.linkedin.com/in/chandrika508/

---
