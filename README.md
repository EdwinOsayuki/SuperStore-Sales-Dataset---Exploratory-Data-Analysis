# SuperStore-Sales-Dataset---Exploratory-Data-Analysis


Exploratory Data Analysis is a technique used to understand the different aspects of a dataset. Its main objective is to give a through understand of the data. It is used to summarize the main characteristics of a dataset, to examine data before building model, find patterns, relations and anomalies in data using statistical graphs and other visualization, identify faulty points in data, understand relationship between variables while it's goal is to help businesses understand their customer behaviour/characteristics, business growth, and help make better decisions. Exploratory Data Analysis process is not usually a formal or linear process with a set of rules. There is no common method to perfom EDA.

![image](https://user-images.githubusercontent.com/68012849/149427276-203f25ea-9ba0-413b-a272-4af9707fabd6.png)

**To perform EDA on a dataset, you have to; **

1. Understand the variables in the dataset
2. Clean the data from redundancies
3. Analyze relationship between variables
4. Explore and visualize relationships

Charts and plots such as Histograms, Scatterplots, PMFs and CMFs (to visualize distributions), Boxplots, Line graphs are used for plotting in EDA.

Here's an Exploratory data analysis process on the superstore dataset. The following code is written in Python and mainly uses Pandas, NumPy, Matplotlib and Seaborn libraries.

   1. Importing the necessary libraries, the dataset and visualizing the first 5 rows
   
 ![image](https://user-images.githubusercontent.com/68012849/149427383-c465098f-0d3b-4cfc-bf34-f4e265b79e9e.png)


  2. Visualizing the last five rows and explaining the columns available in the dataset
  
![image](https://user-images.githubusercontent.com/68012849/149427425-dd478d71-1449-441b-8f5c-3bae99823cbd.png)


  3. Listing the columns and checking the data info

![image](https://user-images.githubusercontent.com/68012849/149427474-78694730-c8ef-4eef-81f8-9174a591f3d4.png)


  4. Listing the number of distinct observation in the dataset and describing the data

![image](https://user-images.githubusercontent.com/68012849/149427519-b5e091dd-f65d-46be-995e-74653e5082d1.png)

  5. Dropping the unnecessary columns

![image](https://user-images.githubusercontent.com/68012849/149427585-962ff6ca-d5a9-4cec-a31f-814e128f0083.png)


  6. Checking for null values and dropping them

![image](https://user-images.githubusercontent.com/68012849/149427626-eee89523-f031-4b7e-9625-d7072b981106.png)


  7. Converting the datetime tp pandas datetime and creating the year and month column

![image](https://user-images.githubusercontent.com/68012849/149427661-b98af187-ce37-4dc2-afbf-54a37223174b.png)


  8. Visualizing outliers in the sales column using boxplot

![image](https://user-images.githubusercontent.com/68012849/149427700-3ca38bb6-6725-4b83-96c1-cb2b733755f0.png)


  9. Visualizing the correlation between variables using a heatmap

![image](https://user-images.githubusercontent.com/68012849/149427745-2aba0bf8-8e52-4956-b952-8288f87db935.png)

  10. Calculated the total revenue and sales per month using the sales column

![image](https://user-images.githubusercontent.com/68012849/149427791-38a8664e-8adb-40a6-84db-a4baff44a154.png)


  11. Visual representation of sales per month and calculation of sales grouped by year

![image](https://user-images.githubusercontent.com/68012849/149427837-3517318d-9123-4f2e-bb31-c4c687054acf.png)


  12. Visualizing sales grouped by year

![image](https://user-images.githubusercontent.com/68012849/149427872-fc228e51-d76b-4c95-8973-2408ca083b16.png)

  13. Total Sales grouped by segment

![image](https://user-images.githubusercontent.com/68012849/149427919-74070c76-1a36-4414-aa8c-0b2713c15f7e.png)


  14. Total Sales grouped by top 10 cities

![image](https://user-images.githubusercontent.com/68012849/149427959-0ed65e43-b031-4573-b5fc-2b316921596a.png)

  15. Visualizing sales by top 10 cities
![image](https://user-images.githubusercontent.com/68012849/149428054-9f22932e-03b9-4673-ab12-b416c620f331.png)

  16. Total sales by top 10 states
![image](https://user-images.githubusercontent.com/68012849/149428084-def90aee-ea98-48a6-8e90-e215f511586e.png)

  17. Visualizing sales by top 10 states
![image](https://user-images.githubusercontent.com/68012849/149428101-b9741adb-f425-4b17-832b-26988f1ba7ea.png)

  18. Total sales grouped by region
![image](https://user-images.githubusercontent.com/68012849/149428134-5181e3b2-40b9-442e-80df-1046c7b35756.png)

  19. Total sales grouped by categories
![image](https://user-images.githubusercontent.com/68012849/149428149-39ab7fa8-71f0-46f7-86cd-00399cdab565.png)

