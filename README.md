# United-Nation-Global-Terrorism-using-EDA-Analysis

<img width="300" height="168" alt="image" src="https://github.com/user-attachments/assets/75a41a18-c9aa-4b68-bf81-a4a7cb39c588" />

## Project Overview

This project focuses on **Global Terrorism Analysis using Exploratory Data Analysis (EDA)** to study worldwide terrorist incidents and identify meaningful patterns, trends, and insights from the dataset.

The main objective is to understand how terrorism incidents vary across years, countries, regions, attack types, target groups, and casualty counts. The analysis helps in understanding high-risk regions and supports better security planning, risk assessment, and counter-terrorism strategies.

An additional metric called **Impact Score** was created by combining fatalities and injuries to better measure the severity of terrorist incidents.

---

## Dataset Details

The dataset used in this project is the **Global Terrorism Dataset**, which contains historical records of terrorist attacks across the world.

### Important Features Included

- Year of incident
- Country
- Region
- City
- Attack type
- Target type
- Weapon type
- Number of people killed
- Number of people wounded
- Group responsible
- Success/failure of attack
- Casualty details

### Data Preprocessing Performed

- Loaded dataset using Pandas
- Checked dataset shape and structure
- Identified missing values
- Handled null values using:
  - Median for numerical columns
  - Mode for categorical columns
- Removed duplicate values
- Selected important features for analysis
- Created a new feature called **Impact Score**
- Performed data cleaning for better visualization and analysis

This preprocessing improved data quality and made the dataset suitable for deeper analysis.

---

## Approach

The project follows a step-by-step EDA workflow:

### Step 1: Data Understanding

- Loaded the dataset
- Viewed first few rows
- Checked rows and columns count
- Analyzed data types using `info()`
- Checked duplicate values
- Checked missing values

### Step 2: Data Cleaning

- Treated missing values
- Removed duplicates
- Selected useful columns
- Created impact score using casualties

### Step 3: Univariate Analysis

- Distribution of attacks over years
- Most affected countries
- Most affected regions
- Most common attack types
- Most common target types

### Step 4: Bivariate Analysis

- Relationship between attack type and casualties
- Region-wise attack comparison
- Country vs attack frequency
- Target type vs attack severity

### Step 5: Multivariate Analysis

- Correlation heatmap
- Pair plot analysis
- Feature interaction analysis

### Step 6: Insight Generation

- Identified terrorism hotspots
- Found major attack patterns
- Analyzed severity of incidents
- Generated strategic security insights

---

## Results & Insights

The EDA revealed several important findings:

- Certain regions experienced significantly higher terrorist activity than others
- Some countries were repeatedly affected and identified as high-risk zones
- Bombings and armed assaults were among the most common attack types
- Government, military, and civilians were major target categories
- Some attacks caused extremely high casualties and had major impact scores
- A clear trend of terrorism growth was observed during specific periods
- Casualties and injuries strongly influenced incident severity
- Regional patterns helped identify areas requiring stronger security measures

These findings can support governments and security agencies in improving prevention strategies and resource planning.

---

## Tools / Technologies Used

### Programming Language

- Python

### Development Environment

- Jupyter Notebook
- Google Colab

### Libraries Used

- Pandas
- NumPy
- Matplotlib
- Seaborn

### Visualization Techniques

- Bar Charts
- Count Plots
- Histograms
- Boxplots
- Correlation Heatmap
- Pair Plot
- Comparative Visualizations

These tools helped in data cleaning, analysis, visualization, and insight generation.

---

## Conclusion

This project successfully performs Exploratory Data Analysis on the Global Terrorism Dataset to understand terrorism patterns across the world. The analysis helps identify affected regions, common attack types, major targets, and casualty trends.

The insights generated from this project can support better decision-making for security planning, threat management, and counter-terrorism policy development.
