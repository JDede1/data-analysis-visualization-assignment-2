# Data Analysis and Visualization — Assignment 2

**Course:** Data Analysis and Visualization (INFO 526)  
**Program:** Master’s in MIS/ML, University of Arizona  
**Assignment Window:** Week 3 — Graded Assessment 2  
**Submission Type:** Individual Work (no collaboration allowed)  
**Points:** Graded Assessment  

---

## Scenario

**Dataset:** COVID-19 Vaccinations by Age (Maricopa County)  
**Source:** Maricopa County Department of Public Health  

**Questions to answer:**
1. How do the vaccination totals between age groups compare?  
2. How have the average vaccination totals changed over time in Maricopa County?  

---

## Assignment Tasks

### Task 1: Pretty Plots
- **Bar Chart:** Vaccination totals by age group.  
  - Clean, professional formatting (title, axis labels, informative caption).  
  - Shows variation in uptake across age demographics.  

- **Line Plot:** Average vaccination totals over time.  
  - Monthly averages to smooth daily fluctuations.  
  - Clear upward trend in vaccinations with proper caption and grid for readability.  

### Task 2: Ugly Plots
- **Pie Chart:** Vaccination totals by age group with intentional errors:  
  - Incorrect/misleading labels  
  - Inconsistent slice sizes  
  - Poor color choices / low contrast  
  - Overlapping annotations  
  - Bad caption formatting  

- **Doughnut Chart:** Average vaccination totals over time with errors:  
  - Excessively long title  
  - Overlapping text labels  
  - Poor font scaling  
  - Misleading visualization choice  
  - Incorrect percentage formatting  

---

## Deliverables

- **Main Report (PDF):**  
  - Pretty plots (bar + line) with captions.  
  - Ugly plots (pie + doughnut) with intentional errors.  
  - Code appendix for full replication.  
  - File naming convention: `Week 3 - Graded Assessment 2_Dedenuola.pdf`  

- **Repository Contents:**  
  - `data/COVID-19_Vaccinations_by_Age_(Maricopa_County).csv` (raw dataset)  
  - `notebooks/Week3_Graded_Assessment2.ipynb` (analysis and plot code)  
  - `docs/Week 3 - Graded Assessment 2.pdf` (final deliverable)  
  - `README.md` (this file)  
  - `.gitignore`  

---

## Repository Structure
```
data-analysis-visualization-2/
├── .gitignore
├── README.md
├── data/
│   └── COVID-19_Vaccinations_by_Age_(Maricopa_County).csv
├── docs/
│   └── Graded Assessment 2.pdf
└── notebooks/
    └── Week3_Graded_Assessment2.ipynb
```
---


---

## Notes

- Pretty plots demonstrate professional visualization practice.  
- Ugly plots deliberately include **5+ different errors** to illustrate bad visualization practices.  
- Data cleaning included:  
  - Fixing missing values (`median` imputation for numeric columns).  
  - Converting `StartDate` and `CreateDate` to datetime.  
  - Ensuring replicability of preprocessing steps.  
- Captions for plots are provided as text in the PDF (not embedded in images).  

---

## How to Reproduce

1. Place the dataset (`COVID-19_Vaccinations_by_Age_(Maricopa_County).csv`) in the `data/` folder.  
2. Open and run `notebooks/Week3_Graded_Assessment2.ipynb`.  
3. This will:  
   - Clean and preprocess the vaccination dataset.  
   - Generate pretty plots (bar + line).  
   - Generate ugly plots (pie + doughnut with errors).  
   - Save all plots to `output/` folder.  
4. Assemble into the final PDF following the required structure.  

---
