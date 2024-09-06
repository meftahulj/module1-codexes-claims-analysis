Questions: 
The steps you took in your analysis.
  1. Loaded in data from CMS for "inpatient" Medicate fee-for-service claims data: https://data.cms.gov/collection/synthetic-medicare-enrollment-fee-for-service-claims-and-prescription-drug-event
  2. Separated the data fields with delimiter (|)
  3. Printed a random sample of data and listed all column names
  4. Identified relevant columns for analysis: (ICD_DGNS_CD1, CLM_DRG_CD, and HCPCS_CD).
  5. Calculated the frequency of unique values present in each codex column
  6. Checked for missing or null data in the selected columns
  7. Printed the top 5 most common codes for each codex to summarize findings
  8. Conducted aditional analysis by identifying if certain DRG codes are more common when IDC codes are specific values (ex. 'E11' for Type 2 Diabetes)

The purpose of each part of your code.
  1. To important relevant dataset for analysis
  2. To assist the system in differentiationg different columns in the dataset
  3-4. To understand the dataset's structure and identify which columns are relevant for analysis
  5. To determine the most common codes in each codex, revealing which conditions were most prevalent
  6. To increase the level of accuracy by accounting for missing or null data in the dataset
  7. To summarize and print the most common codes which identifies most common conditions present in the dataset
  8. To conduct aditional analysis by investigating specific patterns.

Key findings from your analysis, including any patterns or anomalies you discovered.
  - The most frequent ICD codes were Z73.3 (stress), Z60.8 (problems related so social environment), and T74.32X (child psychological abuse).
  - The most frequent DRG codes were 951.0, 950.0, and 949.0
  - The most frequent HCPCS codes were 99221, G0444, 96156

Any challenges you faced and how you overcame them.
  - The most challenging part was that the dataset contained mixed data types and the dtype parameter returned false results. To overcome this barrier, I use the printed random sample of the dataset to identify relevant columns for analysis

Reflect on the implications of your findings for healthcare providers and policy makers.
  - The frequency analysis of ICD, DRG, and HCPCS codes can help healthcare providers understand the most common diagnoses and treatments which is relevant for resource allocation, and patient care strategies. These findings could be used to support data-driven decisions in both clinical practice and healthcare policy. 
