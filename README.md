# 📊 What Drives Book Popularity? — Goodreads Analysis

## 🔍 Overview

This project explores the relationship between **book length, reader ratings, and thematic elements** using a curated Goodreads dataset.

The goal was to identify patterns in:

* Page count distribution
* Rating behaviour
* Popularity concentration
* Theme frequency and impact on ratings

The analysis combines **Python (data processing & EDA)** with **Tableau (interactive visualisation)**.

---

## 🛠️ Tech Stack

* Python (Pandas, NumPy, Matplotlib)
* Jupyter Notebook
* Tableau Public
* Git & GitHub

---

## 📁 Project Structure

```
book-trope-analysis/
│
├── data/                      # Cleaned dataset
├── notebook/
│   └── book_tropes_analysis.ipynb
├── README.md
```

---

## 📊 Key Insights

### 1. Page Count Distribution

Most books cluster between **300–400 pages**, with a long tail of significantly longer books.

### 2. Ratings Distribution

Ratings are tightly concentrated between **3.5–4.2**, suggesting limited variance in perceived quality.

### 3. Page Count vs Rating

There is a **weak positive correlation** between book length and rating — longer books are not significantly better rated.

### 4. Theme Frequency

**Romance dominates** the dataset, appearing far more frequently than other themes.

### 5. Popularity Concentration

A small number of titles account for a **disproportionate share of total ratings**, indicating strong popularity concentration.

### 6. Theme vs Rating

Theme presence has **minimal impact on average rating**, with only slight variations across categories.

---

## 📈 Tableau Dashboard

👉 [View Interactive Dashboard](https://public.tableau.com/app/profile/ulla.angell/viz/Book_Trope_Analysis/WhatDrivesBookPopularityGoodreadsAnalysis?publish=yes)

---

## 📓 Notebook

👉 [View Jupyter Notebook](https://github.com/ullasunangell/book-trope-analysis/blob/main/notebook/book_tropes_analysis.ipynb)

---

## ⚙️ Methodology

* Data cleaned and structured using Pandas
* Feature engineering for theme detection (keyword-based)
* Exploratory data analysis using Matplotlib
* Dashboard built in Tableau for visual storytelling

---

## 🚀 Key Takeaways

* Book popularity is driven more by **visibility and engagement** than content length
* Ratings are **highly standardised**, limiting differentiation
* Themes influence exposure more than quality perception

---

## 📌 Future Improvements

* Use NLP for more accurate theme extraction
* Include genre-level segmentation
* Add time-based analysis (publication trends)
* Incorporate additional engagement metrics (reviews, shelves)

---

## 👤 Author

Ulla Angell
Data Analyst | Python | SQL | Tableau
