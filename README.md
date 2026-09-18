# Basketball Injury Analysis Project

<img width="678" height="452" alt="Image" src="https://github.com/user-attachments/assets/47b6a246-7376-41ae-9fdb-5552a6603032" />

## Project Overview

This project analyses injury and rehabilitation data from 100 basketball players using Microsoft Excel.

The purpose of the project is to identify patterns in basketball injuries, injury severity, rehabilitation programmes, rehabilitation duration, injury recurrence, and rehabilitation efficiency.

The analysis uses descriptive statistics, PivotTables, correlation analysis, regression analysis, and data visualisation.

---

## Objectives

The main objectives of this project are to:

- Analyse the characteristics of basketball players in the dataset.
- Examine the distribution of different injury types.
- Investigate injury severity among players.
- Analyse the rehabilitation programmes used.
- Examine rehabilitation time in weeks.
- Investigate injury recurrence.
- Explore relationships between injury severity and rehabilitation outcomes.
- Examine relationships between rehabilitation time and rehabilitation efficiency.
- Analyse the relationship between rehabilitation programmes and rehabilitation outcomes.
- Present findings using tables and visualisations.

---

## Dataset

The dataset contains information for 100 basketball players.

### Variables

| Variable | Description |
|---|---|
| `Player_ID` | Unique identification number for each player |
| `Age` | Age of the player |
| `Height_cm` | Player height in centimetres |
| `Weight_kg` | Player weight in kilograms |
| `Position` | Basketball playing position |
| `Injury_Type` | Type of injury sustained |
| `Injury_Severity` | Severity of the injury |
| `Rehabilitation_Program` | Rehabilitation programme assigned |
| `Rehabilitation_Time_weeks` | Number of weeks required for rehabilitation |
| `Injury_Recurrence` | Indicates whether the injury recurred |
| `Date_of_Injury` | Date on which the injury occurred |
| `Rehabilitation_Efficiency_Score` | Numerical score representing rehabilitation efficiency |

---

## Injury Categories

### Injury Types

The dataset contains five main injury types:

- Ankle Sprain
- Shoulder Dislocation
- ACL Tear
- Knee Injury
- Hamstring Strain

### Injury Severity

Injuries are classified as:

- Mild
- Moderate
- Severe

### Rehabilitation Programmes

Four rehabilitation programmes are included:

- Physiotherapy
- Strength Training
- Balance Training
- Flexibility Exercises

---

## Key Dataset Statistics

The dataset contains:

- **100 players**
- Age range: **18–34 years**
- Average age: **25.48 years**
- Height range: **170–209 cm**
- Average height: **190.06 cm**
- Weight range: **70–109 kg**
- Average weight: **92.07 kg**
- Rehabilitation time range: **2–11 weeks**
- Average rehabilitation time: **6.92 weeks**
- Injury recurrence rate: **25%**

### Player Positions

| Position | Number of Players |
|---|---:|
| Center | 36 |
| Guard | 35 |
| Forward | 29 |

### Injury Types

| Injury Type | Number |
|---|---:|
| Ankle Sprain | 27 |
| Shoulder Dislocation | 25 |
| ACL Tear | 21 |
| Knee Injury | 15 |
| Hamstring Strain | 12 |

### Injury Severity

| Severity | Number |
|---|---:|
| Severe | 42 |
| Moderate | 31 |
| Mild | 27 |

### Rehabilitation Programmes

| Programme | Number |
|---|---:|
| Strength Training | 30 |
| Physiotherapy | 28 |
| Balance Training | 22 |
| Flexibility Exercises | 20 |

---

## Excel Analysis

The project was completed using Microsoft Excel and contains several analytical worksheets.

### Data

The `Data` worksheet contains the original basketball injury dataset for the 100 players.

### Questions

The `Questions` worksheet contains the questions addressed by the project.

### Pivot Analysis

PivotTables were used to summarise and compare rehabilitation outcomes across different injury severity categories.

The average rehabilitation time was approximately:

| Injury Severity | Average Rehabilitation Time |
|---|---:|
| Mild | 6.96 weeks |
| Moderate | 7.10 weeks |
| Severe | 6.76 weeks |
| Overall | 6.92 weeks |

### Correlation Analysis

The correlation worksheets use numerical and indicator variables to examine relationships between injury severity and rehabilitation outcomes.

Pearson correlation was used to assess the strength and direction of relationships between variables.

### Regression Analysis

Regression analysis was used to examine relationships between rehabilitation programmes and rehabilitation outcomes.

Dummy variables were created for:

- Balance Training
- Flexibility Exercises
- Physiotherapy
- Strength Training

Multiple regression analysis was performed using Microsoft Excel's Data Analysis tools.

### Result Interpretation

The `Result Interpretation` worksheet presents interpretations of the statistical findings and explains what the results mean in relation to basketball injury rehabilitation.

### Visualisation

The `Visualization` worksheet presents the findings using charts and graphs to make the results easier to understand.

### Executive Summary

The `Executive Summary` worksheet provides a concise overview of the main findings from the project.

---

## Statistical Methods

### Descriptive Statistics

Descriptive statistics were used to summarise:

- Player demographics
- Injury types
- Injury severity
- Rehabilitation programmes
- Rehabilitation duration
- Injury recurrence

### PivotTables

PivotTables were used to organise and compare data across different categories.

### Correlation Analysis

Pearson correlation was used to investigate the strength and direction of relationships between numerical or encoded variables.

### Regression Analysis

Multiple regression was used to investigate whether rehabilitation programme categories were associated with variation in rehabilitation outcomes.

One regression model assessing rehabilitation programme categories against rehabilitation efficiency produced an R² of approximately **0.018**.

A separate regression examining rehabilitation time produced an R² of approximately **0.0065**.

These results indicate that the variables included in these models explained only a small proportion of the variation in the respective outcomes.

---

## Tools Used

- Microsoft Excel
- Excel Formulas
- PivotTables
- Correlation Analysis
- Regression Analysis
- Charts and Data Visualisation
- Descriptive Statistics

---

## Project Structure

```text
Basketball-Injury-Analysis/
│
├── README.md
│
└── 3rd Russell J Project analysis Basket ball injury.xlsx
    │
    ├── Data
    ├── Questions
    ├── Pivot Analysis
    ├── Corralation Question 1 and 5
    ├── Regression Question 3 and 5
    ├── Result Interpretation
    ├── Visualization
    └── Executive Summary
