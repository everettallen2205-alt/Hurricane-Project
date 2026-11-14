# Hurricane-Project

# Dataset Overview
The dataset chosen for this assignment contains 125 rows and eight columns of hurricane data.
The columns in question are:
* Year: Contains the year the hurricane occured.
* Name: This column contains the name for each hurricane.
* Category: The category for each hurricane (TS stands for "Tropical Storm").
* Rain Inch: The total rain inches caused by each hurricane.
* Highest wind speed: Highest wind speed reached by a hurricane.
* Damage(USD): The total amount of damage in USD.
* Fatalities: Total lives lost to each hurricane.
* Affected Areas: A list of all areas affected by each hurricane.

# Summary of Steps Taken in Cleaning and Transforming the Data
1. fixing in a typo in the Damage(USD) column.
2. Imputing the mean for NaNs in Damage(USD) and Rain Inch columns
3. No sorting was necesary because the data was sorted by year.
4. A subset of the data was created by selecting all entries where Fatalities was greater than 50 (This was used in two of the visualizations)

# Visualizations
<img width="733" height="567" alt="image" src="https://github.com/user-attachments/assets/24f23c6b-22b8-4260-8123-17ea90bf262d" />
<img width="722" height="565" alt="image" src="https://github.com/user-attachments/assets/50a92070-e574-497e-b427-257d4041042c" />
<img width="706" height="567" alt="image" src="https://github.com/user-attachments/assets/6950f180-928d-496e-aa2a-6d4a3d0638ea" />

# Correlation Table and Insights
Correlation table
<img width="1000" height="282" alt="image" src="https://github.com/user-attachments/assets/2f079936-4f2c-409a-ae2d-f2b9fa476aa5" />
* The wind speed to category correlation is because category is defined by wind speed.
* I'm surprised to find that 'Damage' and 'Fatalites' only have a moderate correlation. I'm guessing this is because of varying evacuation efforts.
* Fatalities seems to be connected to something not in the dataset, but if I were to investigate this further I would check how country GDP correlates with fatalities.
