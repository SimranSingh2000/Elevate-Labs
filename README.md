```python
# Netflix Titles Dataset Cleaning

This project involved cleaning and preparing the `netflix_titles.csv` dataset to ensure it is ready for analysis.

## 🧹 Cleaning Steps Performed

1. **Loaded the dataset**
   - Used Pandas to read the raw CSV file.

2. **Handled missing values**
   - Filled missing values in `country` and `director` with `'Unknown'`.

3. **Removed duplicate rows**
   - Ensured no duplicate records exist.

4. **Standardized text fields**
   - Trimmed whitespaces and standardized text case (e.g., title case for `country`, upper case for `rating`).

5. **Parsed and formatted dates**
   - Converted the `date_added` field to proper `datetime` format (`YYYY-MM-DD`).

6. **Cleaned and renamed column headers**
   - Converted all column names to lowercase and replaced spaces with underscores.

7. **Ensured correct data types**
   - Cast `release_year` as integer.

8. **Saved the cleaned dataset**
   - Output saved as `netflix_titles_cleaned.csv`.

## 📁 Files

- `netflix_titles.csv`: Original raw dataset.
- `netflix_titles_cleaned.csv`: Cleaned version of the dataset.

```
