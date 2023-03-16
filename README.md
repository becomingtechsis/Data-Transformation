# Data Cleaning & Transformation

## Introduction.
In this project, my main focus is transforming and cleaning data while referring to the business demand overview, and the business request. I like to start off by identifying which tables I need based on the user stories, business demand overview, and business request before getting into the actual data cleaning and transformation.

## Dataset
AdventureWorks Database is a Microsoft product sample for an online transaction processing (OLTP) database. The AdventureWorks Database supports a fictitious, multinational manufacturing company called Adventure Works Cycles.


## Highlight
Referring back to the email, I’m able to identify tables I’ll need for this report transformation.
-	[Internet sales](https://github.com/becomingtechsis/Adventure-Works-DB/blob/main/Fact_Internet%20sales.csv)
-	[Customer table](https://github.com/becomingtechsis/Adventure-Works-DB/blob/main/DIM_Customers.csv)
-	[Product table](https://github.com/becomingtechsis/Adventure-Works-DB/blob/main/DIM_Products.csv)
-	[Calendar table](https://github.com/becomingtechsis/Adventure-Works-DB/blob/main/DIM_Calendar.csv)

# Tables

### 1. DIM_Date Table
- DB Table
![image](https://github.com/becomingtechsis/Adventure-Works-DB/blob/main/Calendar-raw.png)

- script
![image](https://user-images.githubusercontent.com/100530199/225642030-7313301f-dbb8-4c92-8afc-09f92978b5c9.png)

- Transformed Table
![image](https://user-images.githubusercontent.com/100530199/225641516-26baa66d-c74d-4559-9f46-13e84722ba16.png)


### 2. DIM_Customer Table
- DB Table
![image](https://user-images.githubusercontent.com/100530199/225641756-eb9aee20-9cab-4655-8a2e-8fa53a04ab8e.png)

- script
![image](https://user-images.githubusercontent.com/100530199/225642497-9efc79e6-a695-4b5c-9a3e-af701d18ce8e.png)

- Transformed Table
![image](https://github.com/becomingtechsis/Adventure-Works-DB/blob/main/cleaned%20customer.png)

### 3. DIM_Product Table
- DB Table
![image](https://user-images.githubusercontent.com/100530199/225644921-a6c80639-92b9-4724-bc3f-239902ad2175.png)

- script
![image](https://user-images.githubusercontent.com/100530199/225644674-99b35002-95d8-45ab-bb94-c205c94b6ce2.png)

-Transformed Table
![image](https://user-images.githubusercontent.com/100530199/225645391-031ef2f9-4bfc-4f88-afa6-4bc8bef70e25.png)

### 4. Fact_InternetSales Table
- DB Table
![image](https://user-images.githubusercontent.com/100530199/225646009-df97fd8b-d510-4062-aed8-23f3588821c1.png)

-script
![image](https://user-images.githubusercontent.com/100530199/225646273-9465e480-2e7b-4c6a-b649-98124d1fab32.png)

-Transformed Table
![image](https://user-images.githubusercontent.com/100530199/225646486-2588d383-bd60-4b5c-b9b0-ddcc5228f6f5.png)
