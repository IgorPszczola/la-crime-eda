# 🕵️‍♂️ Los Angeles Crime Data - Exploratory Data Analysis (EDA)

*Note: The code comments and detailed insights inside the Jupyter Notebook are written in Polish.*

## 📌 About the Project
This project presents a comprehensive Exploratory Data Analysis (EDA) of crime incidents in Los Angeles. The primary goal of this analysis is to uncover hidden patterns regarding the time of crimes, victim demographics, and the geographical distribution of incidents across different city areas.

## 📊 Dataset
The analysis uses the official **Crime Data from 2020 to Present** dataset obtained from the US government open data portal (data.gov).
- **Scope:** Crime incidents reported in Los Angeles.
- **Key Features:** Time of occurrence, victim's age and descent, type of crime, and geographical area (`AREA NAME`).
- *Note: Due to GitHub's file size limits, the raw `.csv` file is not included in this repository. You can download it directly from data.gov.*

## 🛠️ Technologies Used
- **Language:** Python
- **Data Manipulation:** `pandas`, `numpy`
- **Data Visualization:** `matplotlib`, `seaborn` (bar plots, line plots, box plots, heatmaps)

## 📈 Key Insights
1. **Temporal Patterns (Time of Danger):** Crime rates rise steadily throughout the day, reaching a clear peak during evening hours (5:00 PM – 7:00 PM). This correlates with commuting hours and increased street traffic.
2. **Data Artifacts:** A highly unnatural spike in reported crimes was detected exactly at 12:00 PM (noon). This was identified as a data artifact—likely a default time entered into the system when the exact time of the incident is unknown.
3. **Demographics vs. Geography:** Box plot analysis revealed a significant anomaly in the **Southwest** area. The median age of victims there is roughly 10 years lower than in the rest of the city (approx. 30 years vs. 40 years). This is because the Southwest district includes major university campuses (like USC), making students and young adults the primary demographic of victims in that area.

## 🚀 How to Run Locally
1. Clone this repository: `git clone https://github.com/YourUsername/la-crime-eda.git`
2. Download the dataset from data.gov and place the `.csv` file in the project's root directory.
3. Open and run the `la_crime_eda.ipynb` notebook using Jupyter Notebook, VS Code, or any preferred environment.
