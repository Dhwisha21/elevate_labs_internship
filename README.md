
Elevate labs internship - Task 1 - Netflix dataset

<!-- overview -->
In this task , I have selected dataset on Netflix shows and movies 2025 where firstly i have loaded data using pandas and further data preprocessing like replacing values,checking datatypes,drop duplicate value.Therefore, here mainly part was of cleaning raw data using Pandas and further analysis data.

<!-- Task performed -->
- Dropped `duration` column due to 100% missing values
-  Filled missing values in `director`, `cast`, `country`, `genres`, and `description` columns with `"Unknown"`
-  Converted `date_added` to `datetime` format using `pd.to_datetime`
-  Removed duplicate rows using `drop_duplicates()` (though none were found)
-  Renamed all column headers to `snake_case` for consistency
- Verified and corrected data types
- stored cleaned data into new csv file

Technologies Used 
- Python 3
- Pandas
- Jupyter Notebook




