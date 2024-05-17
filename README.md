# World Life Expectancy Project (Data Cleaning)

This project focuses on cleaning the data in a table named world_life_expectancy to prepare it for further analysis. 

**The script addresses three main areas of data cleaning:**

**Duplicate Removal:**
- It identifies and removes potential duplicate entries in the table. This ensures each record represents unique data.
  
**Missing Data Handling:**
- It addresses missing values in the "Status" column. The script attempts to assign a status (either "Developed" or "Developing") to entries with blank values, potentially based on assumptions or existing data.
  
**Missing Data Handling (Attempted):**
- The script also includes commented-out sections that attempt to address missing values in the "Life expectancy" column. This part is commented out, possibly because the approach might not be ideal or could introduce data integrity issues.

By cleaning the data, this project lays the groundwork for the next stage: exploratory analysis of life expectancy patterns and trends. The cleaned data will allow for more accurate calculations, visualizations, and exploration of relationships between life expectancy and other factors like GDP, BMI, and development status


# Project: World Life Expectancy Analysis (Exploratory Data Analysis)

 This project aimed to gain insights into life expectancy patterns and its relationship with various factors using a dataset named world_life_expectancy.

**Key Insights:**

__**Life Expectancy Trends:**__ 
- The script identified countries with the greatest increase in life expectancy over time, potentially indicating positive health trends. 
- It also calculated average life expectancy by year, allowing for observation of general trends across the entire dataset.

**Life Expectancy vs. Other Factors:**
- **GDP:** The analysis explored the correlation between a country's GDP and its average life expectancy. This might reveal potential links between economic development and life expectancy. The script also compared life expectancy in high- vs. low-GDP countries (based on a chosen threshold).
- **BMI:** The script investigated the relationship between a country's average BMI and its life expectancy, providing clues about how body mass index might influence life expectancy across different populations.
- **Development Status:** The analysis compared life expectancy between developed and developing countries, offering insights into potential differences based on a country's development level.

**Adult Mortality (for 'United' Countries):**
- This specific analysis focused on countries named "United" (e.g., United States, United Kingdom). 
- It calculated a rolling total of adult mortality alongside life expectancy for each year within these countries. This allows for visualization of how adult mortality accumulates over time in these specific nations.


Overall, this exploratory data analysis provided a foundation for further investigation into life expectancy and its influencing factors. 
