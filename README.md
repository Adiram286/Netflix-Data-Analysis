# Netflix-Data-Analysis

## 📌 Overview

This project performs **Exploratory Data Analysis (EDA)** on the Netflix titles dataset using Python. The analysis focuses on understanding Netflix's content based on type, ratings, release years, countries, genres, and movie duration.

## 📊 Dataset

The dataset contains **8,807 records and 12 columns**.

| Column         | Description                 |
| -------------- | --------------------------- |
| `show_id`      | Unique ID of the title      |
| `type`         | Movie or TV Show            |
| `title`        | Title name                  |
| `director`     | Director of the title       |
| `cast`         | Cast members                |
| `country`      | Country of production       |
| `date_added`   | Date added to Netflix       |
| `release_year` | Original release year       |
| `rating`       | Content rating              |
| `duration`     | Movie duration / TV seasons |
| `genre`        | Genres/categories           |

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Jupyter Notebook

## 🔍 Analysis Performed

* Dataset inspection and statistical analysis
* Missing value analysis
* Duplicate data checking
* Data cleaning and preprocessing
* Feature engineering
* Movie vs TV Show analysis
* Rating distribution
* Release year analysis
* Top countries by content
* Genre analysis
* Netflix content addition trends
* Movie duration analysis

## 📈 Visualizations

The notebook includes visualizations for:

1. Movies vs TV Shows
2. Top content ratings
3. Release year distribution
4. Content added to Netflix by year
5. Top 10 countries
6. Top 15 genres
7. Movie duration distribution

## 🧹 Data Cleaning

Missing values were handled by:

* Replacing missing `director`, `cast`, and `country` values with **"Unknown"**
* Filling missing `rating` values using the mode
* Removing records with missing `duration`
* Converting dates and extracting useful features such as year and month
* Creating numerical duration, primary country, and primary genre features

## 📁 Project Structure

```text
Netflix-Data-Analysis/
│
├── Netflix_Data_Analysis.ipynb
├── netflix_titles.csv
└── README.md
```

## 🚀 How to Run

Install the required libraries:

```bash
pip install pandas numpy matplotlib jupyter
```

Then open:

```text
Netflix_Data_Analysis.ipynb
```

Make sure `netflix_titles.csv` is in the same directory as the notebook.

## 📝 Conclusion

This project demonstrates how **Python-based data analysis and visualization** can be used to explore and understand the Netflix content catalog, identify trends, and extract useful insights from raw data.
