# J124 Final Project: A Look Into Fertility Rates Through Data Anaylisis & Visualization 
### Madison Lee
## Story Introduction 

In more recent decades, fertility rates have been a rather overlooked but important issue. There has been over a 50% world-wide decline in fertility rates over the last 70 years. To provide some context, fertility rates refers to the average number of children a women births in the time of their reproductive years; in order to mantain a relatively stable population in any given area, an average fertility rate of around 2.1 is required. 
## Data Analysis Process
- Downloaded the Fertility rates data table, through the Full Indicator Data, as a csv. file. Then, I uploaded the csv. file into a new Google Sheets document. 
## Data Analysis 
### **Question 1: Which countries have had the highest fertility rates on average since 1960? Which countries have had the lowest average fertility rates?**
1. My first step in finding my answer was to create a pivot table.
2. Afterwards, I placed "Location" for the columns and "Value" for the values.
3. Then, I changed the "value summarize by" to count the average for each country.
4. Then, I changed the "sort by" under the Location to "AVERAGE of value". 
5. To find the countries with the highest average fertility rates, I changed the "order" under Location to "Descending".
#### The countries with the highest average fertility rates:
!['Screenshot','Pivot Table 1'](/1.1.png)   
#### The countries with the lowest average fertility rates:
!['Screenshot','Pivot Table 1'](/1.2.png)  
### **Question 2: Since 1960 to 2021, which countries have had the highest percent change in fertility rates? Which countries had the lowest percent change?**
1. I started this question off by cleaning my data slightly to make it easier to analyze.
    1. I did this by adding a slicer into the TIME column to show only 1960 and 2021.
2. Then, I inserted a new row labeled "Percent Change"
3. I used the formula =(G2-G63)/G2 to calculate the percent change from 1960 to 2021 for the first country.
    1. I then autofilled this formula for the rest of the countries.
4. I then cleaned up the data by getting rid of any calculations that were made for 2021.
5. Afterwards, I created a pivot table with the "Location" in the columns and "Percent Change" in the values.
6. Then, I changed the "sort by" under location to SUM of Percent Change"
7. To find the countries with the highest percent change in fertility rates, I changed the "order" under Locaiton to "Descending".
#### The countries with the highest percent change in fertility rates:
!['Screenshot','Pivot Table 2'](/2.2.png)   
#### The countries with the lowest percent change in fertility rates:
!['Screenshot','Pivot Table 2'](/2..1.png)  
### **Question 3: From 1960 to 2021, what year had the lowest fertility rates across all countries? Which year had the highest?**
1. I began by creating a pivot table with "time" set for the rows and "Value" set for the values.
2. I changed the "value summarize by" to AVERAGE.
3. Then, I changed the "sort by" under Time to "AVERAGE of value".
4. In order to see the years with the highest fertility rates across all countries, I changed the order under time to "Descending".
#### The years with the highest fertility rates:
!['Screenshot','Pivot Table 3'](/3.2.png)   
#### The years with the lowest fertility rates:
!['Screenshot','Pivot Table 3'](/3.1.png)  
### **Question 4: In 2021, which countries had a fertility rate less than 1?**
1. I started to answer this question by creating a pivot table with "Location" for the rows and "Values" for the value.
2. Becuase I only wantted to look at 2021, I added a filter for TIME, and under "filter by values", I cleared all, then selected 2021.
3. I created another filter, this time with Value, and under "filter by condition", I selected "value is less than or equal to" and then typed in 1.
#### The countries with fertility rates less than 1 in 2021:
!['Screenshot','Pivot Table 4'](/4.1.png) 
### **Question 5: In the past 5 years, which countries are seeing the highest percent decline in their fertility rates?**
1. To respond to this question, I began by creating a new row on my data table and labeled it "Percent Change In The Past 5 Years."
    1. Then, I added a filter for the "TIME" column, where I cleared all values and only selected 2017 and 2021.
    2. Next, I added the formula: =(G59-G63)/G59 for the first country
       !['Screenshot','Percent Change Table'](/5.3.png) 
    4. Afterwards, I autofilled this formula for the remaining countries. 
3. Then, I created a pivot table, where I put "Location" for the rows and "Percent Change" for the value.
4. Next, I added a filter for the TIME so that it would only show me the year 2017. 
5. I added another filter for the Percent Change In The Past 5 Years, where I pressed "filter by condition" and then clicked greater than, and then typed in 0.
6. Finally, I changed the "sort by" under the Location to show the Sum of the Percent Change In The Past 5 Years, and clicked desceding for the order. 
#### The countries with a decline in fertility:
!['Screenshot','Pivot Table 4'](/5.1.png) 
## Data Visualization
!['Average Fertility Rate','Line Chart](/AverageFertilityRate.png) 
https://www.datawrapper.de/_/RcWZr/ 
!['Fertility Rate By Country In 2021','Chloropleth Map](/DataViz2.png) 
https://www.datawrapper.de/_/a4NIA/
## Story Pitch
As the imapcts of fertility rates are not linear, nor do they have the same effects on different countries, this story aims to highlight and explore which countries have been and which countries are currently the most vulnerable to this growing issue. Through this data analysis there are a couple of factors that stand out. Particullarly in relation to Question 4, Korea is the only country with a fertility rate less than 1. Not only does this number not reach the reccomended 2.1 fertility rate to mantain a population, it also means that less babies are given birth to for every one woman in Korea. As shown in the data analysis, Korea scores high in terms of percent change (1st), as well as percent decline in the past five years (2nd). This is rather alarming considering historically, they have not had low fertility rates — ranked 33rd in terms of countries with the lowest fertility rates from 1960-2021. This means that their problems regarding fertility are rather recent. From this data, one could take a deeper dive into the factors that are placing Korea in a vulnerable state in terms of fertility rates and population. This could include aspects such as rising costs of living or changes in lifestyle preferences. Furthermore, this story could look into what ways the Korean government has taken action to rectify this growing issue, as well as what steps the government could take moving on. 
## Resources
**Andrew Yeo** is a Professor of Politics and Director of Asian Studies at The Catholic University of America. Yeo focuses teaching in topics including, Asian security, narratives and discorse, Korean politics, and North Korea. 
  <br>    - Email: yeo@cua.edu
   <br>  - Phone: 202-319-6223
      <br>  - Professor Andrew Yeo is also a senior fellow at the Brookings Institution’s Center for East Asia Policy Studies, and has done extensive research on the issue of Korea's declining fertility rate. I believe that Professor Yeo would be an important addition to the story as he has and can provide more information on the politics surrounding fertility rates in Korea. Yeo also can provide insight on the factors that have led to this drastic decline thus far. 
      <br>  
**Professor John Ermisch**
is a specialist Emeritus Professor of Family Demography. Ermisch's research primarily centers the structure and dynamics of families and their interaction with wider society.
     <br>    - Email: john.ermisch@sociology.ox.ac.uk
   <br>  - Phone: 01865-281921
      <br>     - Professor John Ermisch has done research specifically on the correlation between education level and fertility rates. I believe that education would be a very interesting and important factor when exploring the topic of the declining fertiltiy rate in Korea. Especially given the heavy emphasis on education in Korea, education would be imperative to explore in addition to factors such as Korean society adn economics. I believe that creating this addition to the story would allow for a more holistic exploration into Korea's fertility issue. 
## Further Research
   [Low fertility trend in the Republic of Korea and the problems of its family and demographic policy implementation](https://populationandeconomics.pensoft.net/article/37938/)
      <br>    - This source is a report by Population and Economics; it would be helpful for further research, as it covers Korea's fertility rate, and more importantly, the economic and societal factors that impact this low rate. 
     <br>    - Additionally, this report provides specific data on not only the Korea's past and present fertility rates, but it also provides projections for the following decades as well. This would be especially usefull in exploring ways and solutions for Korea's fertility rate issue. 
       <br>  
          [South Korea has the world's lowest fertility rate, a struggle with lessons for us all](    https://www.npr.org/2023/03/19/1163341684/south-korea-fertility-rate )
      <br>    - This source is an article by NPR, which provides an interview with a Korean woman who is unable to have children due to the economic burden. NPR also discusses expert opinions on the current subsidies and plans provided by the Korean government in efforts to alleviate this issue, as well as further suggestions the government could take. 
     <br>    - This report would be especially useful in understanding why the fertility rate is so low in Korea, especially given there is a first-person story included. Furthermore, this source also can provide more information in terms of the cultural burdens of having a child in Korea. 
