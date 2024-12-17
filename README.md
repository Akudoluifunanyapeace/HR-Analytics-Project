# HR Analytics Dashboard
## INTRODUCTION
This is a Power BI project that provides insight into a comprehensive HR Analytics Dashboard. The Dashboard provides actionable insight into an organization’s workforce focusing on key metrics such as employee demographics, Job levels, Service year, promotion eligibility, Organizational statistics (that is the number of Employees in the organization and the ratio of male to female Employees in the organization).

The goal of the project is to provide actionable insight into the organization workforce and then provide Data driven decisions that will improve the growth of the organization.

### DATA SOURCE
-	The Data set used in this Project was sourced from” KAGGLE” 
-	The Data set was stored in a CSV file.

### SKILLS DEMONSTRATED FOR THIS PROJECT
-	 Data cleaning -Power Query
-	Data visualization- Power-Bi
-	Data Modeling - Power Bi
-	Critical Thinking
-	Problem Solving

### DATA TRANSFORMATION/ CLEANING
I cleaned and transformed the messy data with Power Querry editor in Power BI
Some of the steps applied include.
1)	Making first row header
2)	Changing data types
3)	Clean the unclean data using split column by delimiter (Tab)
- ![split by delimeter](https://github.com/user-attachments/assets/7c5fcac6-09d4-43de-9c51-f119c3a8bc32)
  
    	
4)	Added 13 Measures to show, Total Employee, % Due for promotion, % Not due for promotion, % female, %male, %lay off, layoff, %on service, due for promotion, etc.

   ![Total emplo](https://github.com/user-attachments/assets/059fcd96-877b-422e-9074-d10f6833c854)


![due for pro](https://github.com/user-attachments/assets/762076d9-6ea2-4319-a706-267dce6b65e6)

![%not due](https://github.com/user-attachments/assets/a709f866-0fad-44b1-8c95-46138257a938)

![% female](https://github.com/user-attachments/assets/7d77eb42-018e-4cfe-a90f-3e72370c715b)

![%male](https://github.com/user-attachments/assets/6d1f4ce6-5806-4457-ad45-ee9d7c26ded4)

![on service](https://github.com/user-attachments/assets/15035298-bc85-4cb9-bfb9-814a724522ff)  

##### ETC...


### DATA MODELLING
Data Modeling was done to show the relationships between the Two tables, that is relationship between HR Employee Data and HR Analytics Data. And they are linked together through the Employee Number (Primary key). 

![DAata modelling pic](https://github.com/user-attachments/assets/528a503c-b80e-4ef9-937c-0bb0ea7a3ee4)

### EXPLORATORY DATA ANALYSIS

EDA involved exploring the HR Analytics Data and the HR Employees Data to answer key questions such as

Total employee

Total number of Males and their percentage 

Total number of Females and their percentage

Those due for promotion and their percentage

Those not due for promotion and their percentage

Number of years an employee has worked in the company

Knowing the employee demographics status. That is those who stay very close, close and very far from the company.

Knowing the Retrenchment status of an employee base on the number of years he/she has worked in the company.


### ANALYSIS AND VISUALIZATION

I created a very simple and easy to understand visuals using two colors (yellow and blue) to show different insights gotten from the data set. 

The color used for this visual are bold, eye-catching and can be understood by anyone, even those with eye defect 

I created a number of visuals to show the Total employee, Job level view, Service year etc.


#### The Dashboard comprises of these visuals:

- Total employee: the company has over 1470 Employee

![visual te](https://github.com/user-attachments/assets/7be47ca5-5505-4cbf-9965-45317d368913)


- Total number of Males and their percentage: recorded 882 no of Males which covers 60% of total employee.

![vix male](https://github.com/user-attachments/assets/34e070c8-38d4-4eef-a1c2-092fa2e3ee1e)



- Total number of Females and their percentage: recorded 588 no of Females which covers 40% of total employee. 

![vix female](https://github.com/user-attachments/assets/34b364f2-e6ae-4480-90ad-4d65ad5cedfb)


- Those due for promotion and their percentage: 72 Employees are due for promotion which covers 5% of total employees.

- Those not due for promotion and their percentage: 1398 Employees are not due for promotion which covers 95% of total employees


![vix due for pro   not due for pro](https://github.com/user-attachments/assets/c2e9eb0f-34b2-4e12-abd2-640445e71aa3)


- Number of years an employee has worked in the company (Service Years): 196 employees have stayed in the company for 5years, 171 employees have stayed in the company for 1 years, 128 employees have stayed in the company for 3 years etc.  

![SERVICE YEAR](https://github.com/user-attachments/assets/0be31d30-cd36-4cb5-b876-a49346038840)


- Knowing the employee demographics status. That is those who stay very close, close and very far from the company (Distance from home): 940 employees stay very close to the company, 326 employees stay close to the company and 204 employees stay very far from the company.

![vix distance from home](https://github.com/user-attachments/assets/bc9293b6-33ec-400c-b27f-d499d2c246c6)


- Knowing the Retrenchment status of an employee base on the number of years he/she has worked in the company. (Active worker and Layoff): Total no of 1353 employees are active worker while 117 employees are going to be laid off base on their Retrenchment status.


![vix active work](https://github.com/user-attachments/assets/df0aa45b-b7be-4631-bd96-4fa314fdc96c)                ![vix layoff](https://github.com/user-attachments/assets/0130e19e-9ceb-44db-9780-ef27d65c7c8e)




### HERE IS THE PICTURE OF THE DASHBOARD

![Github px For HR Dashboard](https://github.com/user-attachments/assets/64f421a9-322e-4f29-b2f4-7b8ef75bbb32)



### FINDINGS AND RECOMMENDATION
Base on the Analysis I found out that

-	 What dertermines whether an employee will be laid off or not, is the number of years an employee has worked in the company. Employees with service year (18 years and above) are been laid off while those from 17 years and below are actively working.

-	 What determines whether an employee will be due for promotion or not, is the number of years since last promoted. Employees from 10 years and above will be due for promotion while Employees from 9 years below will not be due for promotion.
     
-	Most employee stay very close to the company, which is a good thing because it could increase work flow and stability for an employee.


Base on the Analysis I recommend that

-	Promotional status of an employee shouldn’t be base off only on the number of years he/she has worked in the company. It could also be base on the level of contribution/input an employee has put into the company or the number of sales or profit an employee has brought into the company. This will help encouraged others to sit up and put in the work, if they want to be promoted.

  
-	Employee/ Staff quarters should be built in order to encourage those employees who stay very far to move closer to the company. This will help enhance work flow, productivity and give stability to the employee.

  
-	Laying an employee off shouldn’t only be based off on the number of years he/she has worked in the company. It could also be based on misconduct, theft, or any ill-mannered behavior coming from the employee etc.. 




![thank you](https://github.com/user-attachments/assets/94ef0605-24e7-4528-bf68-110417bb3a5c)













































