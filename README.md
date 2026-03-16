PRACTICAL -3
Definition- this practical focuses on analyzing CEO   and W orker salary data across industries using Power Bi. The objective is to prepare , clean ,and visualize data from multiple tables to extract insights on pay ratios, industry trends and differrent CEO name.
Outcomes- Learned advanced data preparation and tranformation techniques in Power Query ,including data cleaning , handling columns and creatinng calculated fields.developed skills in building comparative visualization and using dax to analyze salary multiples etc.

Required Tools- Power Bi desktop(with Power Query editor , report view and visualization tools).
Working- imported and appended three datasets related to CEO salaries , first name counts, and industry salaries summaries . cleaned data by removing blanks and duplicates standardized data types and tranformed columns as per requirements .used dax to create new calculated column and catagories, then built interactive charts and graphs.
Dataset Review


The given datasets  includes information about CEO’s their salary ,median pay worker ,and industry details across varios companies. One dataset summarize per CEO first name and theif frequency, another contains detailed record for salary analysis  per company and industry, and the third offers industry-wise aggregated matrices.
STEP-1;Importing CEO_Merged pay Data and industry data directly into Power Bi
Impored all three datasets (ceo dataset and industry datset) directly into power bi using the “Get Data” option.


STEP-2:Performing Transformation of datasets(all three datasets)
Used Power Bi query editor to transform the data i.e-removed blank rows, duplicate rows ,promoted headers,changed datatypes using locale(applied in all datsets).

STEP-3:Replace Value (removing noise(encoded characters )from the industry column
Replaced “ %20” with blanks from the industry columnn by clicking replace value option and also changed the datatypes.%20 is also defined by the noise value.
                                                                 
STEP-4:Adding conditional column
In Power query ,go to Add column-conditional column.name the new column category.Set the first condition:if median worker pay<15000,then output “Low”. Add another condition: if Median worker pay is between 15000 and100000. Tgen output “Medium”.finally set last Condition; if Median worker pay>100000 , then output  “High”.

STEP-5:Grouping column
by industry In Power query, use Group  by with industry as the column and switch to advanced mode, create avg CEO salary by averaging the salary column and max median worker pay by taking the maximum of median pay . summarizing data.

STEP-6: Performing Visualization

Designed a comprehensive Power Bi dashboard presenting key insights into CEO compensation and industry trends. The dashboard displays;
1-A bar chart comparing average CEO salary and average median worker pay by industry.
2- A column chart showing the average CEO  salary multiple across sectors.
3- A treemap highlighting the CEO earning the highest salary.
4- A summary table listing CEO first names repeated maore than 10 times.
5- a matrix showing the number of companies by industry.



