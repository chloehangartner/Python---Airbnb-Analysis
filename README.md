# Python - Airbnb Analysis

### Context
Airbnb has disrupted the traditional hospitality industry as more travelers decide to use Airbnb as their primary means of accommodation. Based in San Francisco, California, Airbnb operates an online marketplace focused on short-term homestays and experiences. The company acts as a broker and charges a commission from each booking. The company was founded in 2008 by Brian Chesky, Nathan Blecharczyk, and Joe Gebbia.

### Data
The data for this project is open-sourced and available at the following URL:
https://www.kaggle.com/datasets/kritikseth/us-airbnb-open-data

### Limitations
-	Host name information had to be removed due to PII issues
-	Data only includes information from 2020, so it will be harder to predict market changes from year to year

### Data Cleaning/Consistency Checks
-	No duplicates found
-	Mixed type data was addressed
-	48,602 missing values found in reviews_per_month column
o	Column mean value was imputed for the missing values to avoid removal of all rows or the column entirely
-	Nothing abnormal in the descriptive statistic summary
