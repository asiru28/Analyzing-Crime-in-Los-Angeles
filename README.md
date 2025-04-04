# Analysing-Crime-in-Los-Angeles

# Overview/Introduction

Los Angeles, known as the "City of Angels" and the "Entertainment Capital of the World," is a bustling metropolis with a diverse population. However, like any large city, it faces challenges with crime. This project analyzes crime data provided by the Los Angeles Police Department (LAPD) to identify patterns in criminal behavior. The insights gained will help the LAPD allocate resources effectively to tackle various crimes in different areas.

# Objectives

1. Analyze crime patterns in Los Angeles to identify high-crime areas and times.
2. Explore the demographics of crime victims, including age, gender, and descent.
3. Identify trends in crime types and their frequency.
4. Provide actionable insights to help the LAPD optimize resource allocation and crime prevention strategies.

# Data Source

The dataset, crimes.csv, is a modified version of publicly available data from Los Angeles Open Data. It includes the following columns:
   - DR_NO: Division of Records Number (unique identifier).
   - Date Rptd: Date reported (MM/DD/YYYY).
   - DATE OCC: Date of occurrence (MM/DD/YYYY).
   - TIME OCC: Time of occurrence (24-hour military time).
   - AREA NAME: Geographic area or patrol division.
   - Crm Cd Desc: Description of the crime committed.
   - Vict Age: Victim's age in years.
   - Vict Sex: Victim's sex (F: Female, M: Male, 0: Unknown).
   - Vict Descent: Victim's descent (e.g., A: Other Asian, B: Black, H: Hispanic/Latin/Mexican, W: White).
   - Weapon Desc: Description of the weapon used (if applicable).
   - Status Desc: Crime status.
   - LOCATION: Street address of the crime.

# Tools Used

  - Python Libraries: Pandas, NumPy, Matplotlib, Seaborn
  - Data Visualization: Seaborn for count plots and histograms.
  - Data Cleaning: Handling missing values and transforming data for analysis.

# Insights

1. Crime Timing:
    - The highest volume of crimes occurs during midday, with a peak at 12 PM.
    - Nighttime crimes (between 10 PM and 3:59 AM) are most frequent in the Central area.
2. Victim Demographics:
    - The majority of victims are aged 26-34, followed by 35-44 and 18-25.
    - Victims aged 0-17 are the least affected by crime.
3. Geographic Trends:
    - The Central area has the highest number of nighttime crimes, followed by Southwest and 77th Street.
4. Crime Types:
    - The dataset includes various crime types, with theft being one of the most common.

# Key Findings

1. Peak Crime Hours:
    - The highest volume of crimes occurs at 12 PM, with a significant drop during late-night hours.
  
   ![d1](https://github.com/user-attachments/assets/ccdeb2cc-1842-4662-9f54-7c3ddb64f36c)

2. Nighttime Crime Hotspots:
    - The Central area has the highest number of nighttime crimes (14,944), making it a priority for resource allocation.
3. Victim Age Groups:
    - Victims aged 26-34 are the most affected, accounting for 47,470 incidents.
  
      ![d2](https://github.com/user-attachments/assets/391ee464-9a74-41bf-a876-ce7db7547101)

4. Geographic Distribution:
    - Crime is concentrated in areas like Central, Southwest, and 77th Street, which may require increased patrols and preventive measures.

# Recommendations

1. Resource Allocation:
    - Increase police presence in high-crime areas like Central and Southwest, especially during peak crime hours.
2. Community Programs:
    - Implement community outreach programs in areas with high crime rates to address underlying issues.
3. Crime Prevention:
    - Focus on preventive measures for crimes targeting victims aged 26-34, such as awareness campaigns and safety workshops.
4. Data-Driven Strategies:
    - Use data analytics to predict crime trends and allocate resources dynamically based on real-time data.

# How to Use This Repository

1. Clone the repository.
2. Install the required Python libraries (pandas, numpy, matplotlib, seaborn).
3. Run the Jupyter Notebook (Analyzing Crime in Los Angeles.ipynb) to reproduce the analysis.
4. Explore the dataset and modify the code to conduct further analysis or generate additional insights.
