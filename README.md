# Aircraft Safety Risk Analysis

This project analyzes aircraft incident data from the **NTSB (National Transportation Safety Board)** to assess flight safety, identify contributing risk factors, and provide data-driven insights into aviation safety trends. Using Tableau and data preprocessing in Excel/Google Sheets, we built visual dashboards and calculated custom risk scores to guide insights.

---

## Business Contex

This project focuses on identifying **least-risky aircraft makes**, **influential incident factors**, and **historical safety trends** using publicly available data.

---

## Data

The dataset used originates from the **NTSB Aircraft Accident Database**, and includes:

- Aircraft makes, models, and registration
- Number of persons aboard and injury severity
- Weather conditions and flight purpose
- Dates and locations of incidents
- Outcome (fatalities, injuries, survival)

Data was cleaned and merged in Excel Sheets and analyzed visually in Tableau.

---

## Process Steps

1. **Data Cleaning**
   - Removed duplicates, blanks, irrelevant fields
   - Converted columns to proper data types (dates, integers)
   - Merged multiple data sources

2. **Feature Engineering**
   - Created `risk_score` combining fatalities and serious injuries
   - Calculated `injury_rate = (total injuries / total aboard)`

3. **Visualization**
   - Built scatter plots (e.g. injury vs survival)
   - Designed dashboards showing aircraft risk by make

4. **Exploratory Analysis**
   - Segmented by aircraft make, weather, purpose, time of day, etc.
   - Evaluated survival and injury rates per segment

## Results & Business Application

### Key Insights Summary

| Factor               | Insight                                                                 |
|----------------------|-------------------------------------------------------------------------|
| **Aircraft Make**    | Boeing had lowest risk scores and highest survival rate.                |
| **Weather**          | Accidents occurred even in clear weather; not always a direct cause.    |
| **Flight Purpose**   | Personal flights showed highest risk; commercial flights were safer.    |
| **Time of Day**      | Nighttime incidents had slightly higher severity.                       |
| **Trend Over Time**  | Safety has improved over time—recent years show fewer severe accidents. |

### Recommendation
Based on the dataset and scoring method, **Boeing appears to be the least risky make** overall. Additional validation with broader datasets is encouraged.

## 📬 Contact Information

**Analyst**: Dennis Irimu
**Tools Used**: Excel, Google Sheets, Tableau, Python 
**Data Source**: [NTSB Aviation Accident Database](https://www.ntsb.gov)

#### Tableau link - https://public.tableau.com/app/profile/dennis.irimu/viz/AirlineRiskAnalysis/Dashboard1?publish=yes
