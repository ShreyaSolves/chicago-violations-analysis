# Chicago Violations Analysis (AD699 Assignment 1)

## Overview  
This project, part of **AD699 Assignment 1 (Section A2, Spring 2025)**, analyzes building-related ordinance violations in Chicago, Illinois (2008–present) using the `chicago_violations.csv` dataset. The goal is to explore violation patterns, calculate mean imposed fines for the top 5 violation types, and visualize these findings to understand fine variations and their implications for public safety and compliance.  

---

## Objectives  
- **Data Loading**: Import and inspect the dataset.  
- **Data Cleaning**: Filter for the top 5 violation descriptions.  
- **Exploratory Data Analysis (EDA)**: Calculate mean fines.  
- **Visualization**: Bar plot of mean fines by violation description.  
- **Interpretation**: Relate fine variations to safety, severity, and repair costs.  

---

## Dataset  
- **Source**: `chicago_violations.csv`  
- **Columns**: 22 (ID, DOCKET NUMBER, ADDRESS, WARD, VIOLATION DESCRIPTION, IMPOSED FINE, etc.)  

### Key Features Analyzed  
- **VIOLATION DESCRIPTION**: Categorical – type of violation.  
- **IMPOSED FINE**: Numerical – fine amount (USD).  

---

## Methodology  
1. **Data Loading**: Loaded CSV with pandas and inspected structure.  
2. **Data Cleaning**: Filtered to top 5 violation descriptions.  
3. **EDA**: Grouped by violation type, calculated mean fines, sorted results.  
4. **Visualization**: Created bar plot (seaborn/matplotlib) with labels and readability adjustments.  
5. **Interpretation**: Analyzed differences in fines, linking high fines to safety and repair urgency.  

---

## Key Findings  
- **Highest Fines**:  
  - *Replace window pane* (~$1500)  
  - *Repair/replace defect* (~$1200)  
  → Both tied to immediate safety hazards.  

- **Lower Fines**:  
  - *Inspection* and *Address* (~$800)  
  → Likely procedural or administrative issues.  

- **Fine Variations**: Reflect safety impact, repair costs, and urgency.  
- **Safety Focus**: High-risk violations (e.g., broken windows) receive higher penalties to enforce compliance.  

---

📌 *This analysis highlights how fine structures in Chicago’s building ordinance system prioritize safety and compliance, penalizing hazardous violations more heavily.*  
