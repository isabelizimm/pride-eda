# DataFrame Overview

The dataset contains information about LGBTQIA+ legislation with 1,606 total rows and the following columns:

1. **State** (object)
   - 1606 non-null values (no missing values)
   - Contains 50 unique states
   - Most frequent state is Texas (appears 140 times)

2. **Bill Name** (object)
   - 1606 non-null values (no missing values)
   - Contains 1,372 unique bill names
   - Most common bill is "HB 183" (appears 3 times)

3. **Issues** (object)
   - 1606 non-null values (no missing values)
   - Contains 120 unique issue categories
   - Most common issue is "Other anti-LGBTQ bills" (appears 228 times)

4. **Status** (object)
   - 1560 non-null values (46 missing values)
   - Contains 4 unique status types
   - Most common status is "Defeated" (appears 848 times)

5. **Status Detail** (object)
   - 1545 non-null values (61 missing values)
   - Contains 235 unique status detail descriptions
   - Most common detail is "Legislative session ended" (appears 460 times)

6. **Status Date** (object)
   - 1560 non-null values (46 missing values)
   - Contains 234 unique dates
   - Most recent/common date is "02/29/2024" (appears 76 times)

7. **Month** (Int64)
   - Derived from Status Date
   - Contains values 1-12 representing months

8. **Day** (Int64)
   - Derived from Status Date
   - Contains values 1-31 representing days of the month

9. **Year** (Int64)
   - Derived from Status Date
   - Contains years (e.g., 2024)

All columns are of type 'object' in pandas besides Month, Day, Year, suggesting they are stored as strings. The datasettracks LGBTQIA+ related legislation across the United States, including bill information, their current status, and temporal data. 