[Palmoria Group emp-data.csv](https://github.com/user-attachments/files/21054322/Palmoria.Group.emp-data.csv) 
# DSA-CAPSTONE-PROJECT
My project work in assessing my digital skill in Microsoft Power BI.

# Project Topic: Palmoria Group HR Analysis

## Project Overview:
The Data Analysis Project aims to analyse the company data and generate insights that the Palmoria management team would need to address.

## Data Source:
The primary data source used here is Palmoria Group emp-data.csv and Palmoria Group Bonus Rules.xlsx this is an open source data that can be freely downloaded from an open source online or from any other data repository site . Attention was paid to the extension of the file while getting it from the data source.

## Tools Used:
-Microsoft Power BI [Download here](https://www.microsoft.com/en-us/download/details.aspx?id=58494) ( For creating a report)

-Text/CSV (For Querying and Analysis)

-Excel Workbook (For Querying and Analysis)

-MS Powerpoint (For Presentation)

-MS Excel for Data Cleaning [Download here](https://www.microsoft.com)
- For Data Collection
- For Data Cleaning
  1. For Data Manipulation
  2. For Data Munching
 
## Data Cleaning and Preparation:
In the initial phase of the data cleaning and preparations, the following actions were performed. 
- Data loading and inspection; The company's data was uploaded and inspected to transform
- Handling missing variables; On gender Column, undisclosed gender was replaced by a generic gender status 'No gender'.
- Data Cleaning and formatting; Employees without salaries and departments indicated as "NULL" were taken out.

## Exploratory Data Analysis (EDA):

1. What is the gender distribution in the organization? Distil to regions and
departments?
### Gender Distribution Analysis:

(a.) Create a bar chart:
 - Axis: Region by Department
   
   
![Count Region by Department](https://github.com/user-attachments/assets/2f28c371-039f-4697-9aab-5320a79e4962)

Region/Department: 
  
     
    i. Product Management: 89
   
    ii. Human Resource: 82
     
    iii. Services: 82
    
    iv. Support: 81
    
    v. Business Development: 81 
    
    vi. Sales: 80 
  
    vii. Engineering: 80 
  
    viii. Training: 77 
  
    ix. Research and Development: 74 
  
    x. Accounting: 67 
  
    xi. Marketing: 65 
    
    xii. Legal: 88 
  




- Value: Count of Employees by Gender

  
     ![Count Employee by Gender](https://github.com/user-attachments/assets/c05fd3a1-d0e0-408b-a532-4459fea66341)

    i. Male: 465
   
    ii. Female: 441
   
    iii. No gender: 40
  

(b.) Use a slicer to filter by Region/department

- Region/Department: (No gender, Male, Female)
  
    i. Product Management: 89 (No gender-1, Male-47, Female-41)

    ii. Human Resource: 82 (No gender-3, Male-38, Female-41)
  
    iii. Services: 82 (No gender-3, Male-37, Female-42)
  
    iv. Support: 81 (No gender-4, Male-42, Female-35)
  
    v. Business Development: 81 (No gender-3, Male-37, Female-41)
    
    vi. Sales: 80 (No gender-4, Male-40, Female-36)
  
    vii. Engineering: 80 (No gender-6, Male-36, Female-38)
  
   viii. Training: 77 (No gender-3, Male-38, Female-36)
  
    ix. Research and Development: 74 (No gender-5, Male-31, Female-38)
  
   x. Accounting: 67 (No gender-2, Male-37, Female-28)
  
    xi. Marketing: 65 (No gender-1, Male-33, Female-31)
    
  xii. Legal: 88 (No gender-5, Male-34, Female-49)
  

### Visualization  
- Visualize the overall gender distribution using a pie chart 


  ![Overall Gender distribution (Pie Chart)](https://github.com/user-attachments/assets/943dd43e-9d83-4625-b344-6df7cf4718ae)




- Bar Chart: "Gender Distribution by Location"

  ![Gender Distribution by region Bar Chart](https://github.com/user-attachments/assets/36ff4598-abd5-42bc-8aa9-fefb6390f288)

  
  
### Measures:

- Gender Count = COUNT ('Employee' [Gender])
- Gender Percentage = DIVIDE (CALCULATE(COUNT('Employee'[Gender])),  CALCULATE(COUNT( 'Employee'[Gender]), ALL('Employee'[Gender])))
  
  


  

2. Show insights on ratings based on gender:
   
   (a.)  Create a histogram/box plot:
   
         -Male: 49%
   
         -Female: 46%
   
         -No gender: 4%
    
      
4. Analyse the company’s salary structure. Identify if there is a gender pay gap. If
there is, identify the department and regions that should be the focus of
management:
Based on the value distribution of the salary column there is no gender pay gap, employees are payed based on assigned roles and not gender.

5. A recent regulation was adopted which requires manufacturing companies to pay
employees a minimum of $90,000. Does Palmoria meet this requirement? No, it does not meet the requirement because some of the employees received below $90,000.

6. Show the pay distribution of employees grouped by a band of $10,000. For example:

7. How many employees fall into a band of
   - $10,000 – $20,000,none
   - $20,000 – $30,000,none

 This was also visualized by regions

 Calculate the amount to be paid as a bonus to individual employees
● Calculate the total amount to be paid to individual employees (salary inclusive of
bonus)
● Total amount to be paid out per region and company-wide




### Data Analysis



[Palmoria Group Bonus Rules.xlsx](https://github.com/user-attachments/files/21054349/Palmoria.Group.Bonus.Rules.xlsx)
