# Healthcare Claims Data Analysis Assignment

## Project Description
This project analyzes simulates the common analysis task needed to performed daily by healthcare data analysts. Using a sample of prospective claims data from Stony Brook University Hospital from May 2024, analyze the billing patterns to identify billing paterns, common diangoses and procedure, payer relationships to support operational decision-making.

## Data Source:
- **Header File**: Claim-level information
- **Line File**: Service Line details
- **Code File**: Diagnosis codes associated with each claim

## How to run

1. **Clone and install:**
   ```bash
   git clone <your-repository-url>
   cd claims_analysis
   pip install -r requirements.txt
   ```

2. **Launch Jupyer Notebook**

3. **Run analysis**
    - Open "notebooks/claims_analysis.ipynb"
    - Run all cells 

## Key Findings
1. **Provider Workload** The top 5 providers handle majority of claims with the top provider having exponentially more than the rest
2. **Payer Distribution**: Medicare handles a significant amount of claims
3. **Common Diagnoses**: Respiratory and chronic conditions dominate diagnosis code
4. **Specailization**: Identified key provider that specalizes in acute respiratory distress

## Required Libraries
- pandas >= 1.5.0
- matplotlib >= 3.6.0
- jupyter >= 1.0.0





