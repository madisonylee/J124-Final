# J124 Final Project: A Look Into Fertility Rates Through Data Anaylisis & Visualization 
## Madison Lee
### Data Analysis 
### **Question 1: Which countries have had the highest fertility rates on average since 1970? Which countries have had the lowest average fertility rates?**
1. My first step in finding my answer was to create a pivot table.
2. Afterwards, I placed "Location" for the columns and "Value" for the values.
3. Then, I changed the "value summarize by" to count the average for each country.
4. Then, I changed the "sort by" under the Location to "AVERAGE of value". 
5. To find the countries with the highest average fertility rates, I changed the "order" under Location to "Descending".
#### The countries with the highest average fertility rates:
!['Screenshot','Pivot Table 1'](/1.1.png)   
#### The countries with the lowest average fertility rates:
!['Screenshot','Pivot Table 1'](/1.2.png)  
### **Question 2: Since 1970 to 2021, which countries have had the highest percent change in fertility rates? Which countries had the lowest percent change?**
1. I started this question off by cleaning my data slightly to make it easier to analyze.
    1. I did this by adding a slicer into the time row to show only 1970 and 2021.
2. Then, I inserted a new row labeled "Percent Change"
3. I used the formula =(G2-G63)/G2 to calculate the percent change from 1970 to 2021 for the first country.
    1. I then autofilled this formula for the rest of the countries.
4. I then cleaned up the data by getting rid of any calculations that were made for 2021.
5. Afterwards, I created a pivot table with the "Location" in the columns and "Percent Change" in the values.
6. Then, I changed the "sort by" under location to SUM of Percent Change"
7. To find the countries with the highest percent change in fertility rates, I changed the "order" under Locaiton to "Descending".
#### The countries with the highest percent change in fertility rates:
!['Screenshot','Pivot Table 1'](/2.2.png)   
#### The countries with the lowest percent change in fertility rates:
!['Screenshot','Pivot Table 1'](/2..1.png)  
### **Question 3: From 1970 to 2021, what year had the lowest fertility rates across all countries? Which year had the highest?**
1. I began by creating a pivot table with "time" set for the rows and "Value" set for the values.
2. I changed the "value summarize by" to AVERAGE.
3. Then, I changed the "sort by" under Time to "AVERAGE of value".
4. In order to see the years with the highest fertility rates across all countries, I changed the order under time to "Descending".
#### The years with the highest fertility rates:
!['Screenshot','Pivot Table 1'](/3.2.png)   
#### The years with the lowestfertility rates:
!['Screenshot','Pivot Table 1'](/3.1.png)  
### **Question 4: In 2021, how many countries had a fertility rate of more than 1? How many countries had a fertility rate of less than 1?**
1. I started to answer this question by cleaning my data so that I could focus only on 2021. 
