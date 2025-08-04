# netflix-movies-

# 📊 Netflix Movies and TV Shows CSV Cleaner

This Python script loads and cleans a CSV file from a ZIP archive containing Netflix movies and TV shows data. It performs basic preprocessing to prepare the dataset for analysis or machine learning tasks.

---

## 🚀 Features

- Automatically detects and loads a CSV file from a ZIP archive
- Removes duplicate rows
- Strips whitespace from string fields
- Fills missing values with `"Unknown"`
- Converts all text columns to lowercase for consistency

---

## 📁 File Structure
Netflix_movies_and_tv_shows_clustering.csv.zip └── Netflix_movies_and_tv_shows_clustering.cs


---

## 🧪 Requirements

- Python 3.x
- pandas
- zipfile (standard library)

Install dependencies (if needed):

```bash
pip install pandas

Usage
Run the script to load and clean the dataset:
from your_script import load_and_clean_csv_from_zip

df = load_and_clean_csv_from_zip()
print(df.head())

You can also specify a custom ZIP path or CSV filename:
df = load_and_clean_csv_from_zip(zip_path="path/to/your.zip", csv_filename="your_file.csv")



📌 Notes
- If multiple CSV files exist in the ZIP, the first one will be selected by default.
- Cleaned data is returned as a pandas DataFrame for further analysis.

