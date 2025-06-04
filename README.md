# Customer Personality Analysis - Data Cleaning Report

## Overview
This project involves cleaning a raw dataset containing customer information to prepare it for analysis. The original data included issues such as missing values, inconsistent formatting, and unstandardized text fields.

---

## Cleaning Steps Performed

1. **Loaded the Dataset**  
   - Read the CSV file using `pandas`.

2. **Removed Duplicates**  
   - Identified and removed duplicate rows using `.drop_duplicates()`.

3. **Handled Missing Values**  
   - Filled 24 missing values in the `Income` column with the median income using `.fillna()`.

4. **Converted Date Format**  
   - Converted the `Dt_Customer` column to a standard datetime format (`dd-mm-yyyy`) using `pd.to_datetime()`.

5. **Renamed Columns**  
   - Standardized column headers by converting them to lowercase and replacing spaces with underscores.

6. **Standardized Text Values**  
   - Applied consistent formatting to `Education` and `Marital_Status` fields using `.str.strip()` and `.str.title()`.

7. **Validated Data Types**  
   - Ensured correct data types for all columns (e.g., date as datetime, numerical columns as int/float).

8. **Exported Cleaned Dataset**  
   - Saved the final cleaned dataset to a new file named `cleaned_customer_personality.csv`.

---

## Output
- 📁 **Cleaned File**: `cleaned_customer_personality.csv`
- ✅ Ready for further analysis or modeling.

# Customer Personality Analysis - Data Cleaning Report

## Overview
This project involves cleaning a raw dataset containing customer information to prepare it for analysis. The original data included issues such as missing values, inconsistent formatting, and unstandardized text fields.

---

## Cleaning Steps Performed

1. **Loaded the Dataset**  
   - Read the CSV file using `pandas`.

2. **Removed Duplicates**  
   - Identified and removed duplicate rows using `.drop_duplicates()`.

3. **Handled Missing Values**  
   - Filled 24 missing values in the `Income` column with the median income using `.fillna()`.

4. **Converted Date Format**  
   - Converted the `Dt_Customer` column to a standard datetime format (`dd-mm-yyyy`) using `pd.to_datetime()`.

5. **Renamed Columns**  
   - Standardized column headers by converting them to lowercase and replacing spaces with underscores.

6. **Standardized Text Values**  
   - Applied consistent formatting to `Education` and `Marital_Status` fields using `.str.strip()` and `.str.title()`.

7. **Validated Data Types**  
   - Ensured correct data types for all columns (e.g., date as datetime, numerical columns as int/float).

8. **Exported Cleaned Dataset**  
   - Saved the final cleaned dataset to a new file named `cleaned_customer_personality.csv`.

---

## Output
**Cleaned File**: `cleaned_customer_personality.csv`

