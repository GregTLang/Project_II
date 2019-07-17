# Project_II
Occupational Data and Automation Risk

ETL Summary

Extract: 
  Data Source #1: May 2018 National Occupational Employment and Wage Estimates 2018
    File Type: XLSX
    https://www.bls.gov/oes/current/oes_nat.htm
  Data Source #2: Automation Risk and State Work Populations
    File Type: CSV
    http://www.oxfordmartin.ox.ac.uk/downloads/academic/The_Future_of_Employment.pdf
  
 Transform:
  Join both data sources through occupation codes (as a string)
  
 Load:
  Final database Relational
    SQL (pgadmin)
    Benefits of Relational: Support to Operations Set on Theory/Dynamic Views
      There are a lot of ways to cut the data included in this set depending on the focus of your analysis suggesting that a relational database would be most effective
