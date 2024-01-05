# Cigna-Offers-Analysis-Report
Analysis report for offers given by Cigna Dental.

Converted PDF files to excel format using data retrieval tool in Microsoft Excel.
Data cleaning and transformation to proper 3 column style (Procedure code, description, and fees).
  - When given a new fee schedule, must be in tab delimited file with procedure code, description, and rates in that order to import in Open Dental database.

VLOOKUP formula to reference other sheets to find correlating procedure codes (specific codes/most commonly used procedures) and rates

Used [Procedres-by-Procedure-Codes](https://github.com/and33zy/Procedures-by-Procedure-Code/blob/main/Procedures%20By%20Procedure%20Code.csv) to only compare rates with important procedures only. 

Compare current Cigna fees to 1rst, 2nd, 3rd, and 4th offers. 

Also included Careington's platinum fee schedule as they can possibly pickup Cigna as a third party carrier and pay by the platinum fee schedule. 

*Connection Dental recently (July 2023) announced partnership with Cigna dental, can possibly become another 3rd party carrier other than Careington.*

- Final report recommends to terminate direct contract and allow room for Careington to pickup Cigna's agreement to pay office at the highest rate. 
