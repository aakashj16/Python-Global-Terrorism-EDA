# Python-Global-Terrorism-EDA

## Description
This project provides an in-depth analysis of global terrorism data from 1970 to 2020. It includes visualizations that highlight trends, regions, countries, attack types, and the impact of terrorism over the last five decades.

A business report on this project is available on my [website](https://www.aakash.biz/projects/eda-project).

## Overview
The dataset used in this analysis is the Global Terrorism Database (GTD), which includes information on terrorist events worldwide. The analysis explores various aspects, such as:
- Total number of attacks and fatalities across years
- Attack frequency by region and country
- Most active terrorist groups and their methods
- Common attack methods and weapon types
- Specific analysis on the Taliban’s attacks and targets
- Usage of biological and radiological weapons

## Libraries Used
This project uses the following Python libraries:
- NumPy and Pandas for data manipulation
- Matplotlib and Seaborn for data visualization

## Data
The data can be downloaded from [start.umd.edu](start.umd.edu). Once downloaded, the dataset is read into a pandas DataFrame for analysis.

## Project Workflow
1.	Data Loading and Initial Exploration
    - The dataset is loaded from a CSV file and basic information is printed regarding the total number of terrorist attacks worldwide between 1970 and 2020, as well as for the year 2020.

2.	Visualizations
    - Terrorist Attacks by Year: The total number of terrorist attacks per year is visualized.
    - Terrorist Attacks by Region: A bar plot displaying the number of terrorist attacks by region.
    - Most Attacked Countries: The countries that suffered the most terrorist attacks between 1970 and 2020 are displayed.
    - Fatalities by Country: A bar plot showing countries with the highest number of fatalities due to terrorist attacks.
    - Most Active Terrorist Groups: A line plot tracking the most active terrorist groups from 1970 to 2020.
    - Fatalities by Active Terrorist Groups: A line plot showing the fatalities caused by the most active terrorist groups over time.
    - Common Methods of Attack: A line plot showing the most common types of attacks.
    - Fatalities by Attack Type: A line plot showing the fatalities caused by different attack types over time.
    - Common Weapon Types: A line plot illustrating the usage of different weapon types in terrorist attacks.
    - Taliban’s Methods of Attack: A focused analysis of Taliban attacks, visualizing their attack methods over time.
    - Taliban’s Most Frequent Targets: A line plot showing the Taliban's most frequent targets over time.
    - Use of Biological & Radiological Weapons: A count plot illustrating the usage of biological and radiological weapons by country.

## Conclusion
This project provides a comprehensive overview of terrorism trends worldwide, highlighting the evolution of terrorist attacks, their impact on countries, and the methods used by terrorist groups over the past five decades. It offers valuable insights into global security challenges and can serve as a foundation for more advanced research in this domain.