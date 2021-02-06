# Kickstarter-Analysis
Performing analysis on Kickstarter data to uncover trends. Program includes Excel and PNG images.
 
Tahira Hamed 

Bootcamp: UCB-VIRT-DATA-PT-01-2021-U-B-TTH 

Written Analysis 

Module 1 Challenge 

OVERVIEW 

The purpose of this analysis is to improve Louise's understanding of how to meet or exceed her fundraising goals by researching, “different campaign outcomes based on their launch dates and their funding goals" (Bootcamp: UCB-VIRT-DATA-PT-01-2021-U-B-TTH, Canvas: Module 1 Challenge, para. 2). Completing this analysis will provide Louise with two visual aids to view successful, failed, and canceled campaign outcomes in months and a percentage chart sharing outcomes based on funding goals. 

ANALYSIS AND CHALLENGES 

Analysis 

I performed my analysis by using various coding methods throughout the analysis process. To begin the process of my analysis, four steps were completed in Microsoft Excel. The project was named, a folder was created titled “resources” to hold tables/charts created in the analysis process, a new column "Years" was created, and the YEAR() function was used in the Years column to extract data from a previously created column "Date Created Conversion". 

To view how the YEAR() function is used in Excel, view the link below: 

https://support.microsoft.com/en-us/office/year-function-c64f017a-1354-490d-981f-578e8ec8d3b9?ui=en-us&rs=en-us&ad=us 

A pivot table was created in a new worksheet from data used in a previous worksheet named "Kickstarter". This new worksheet will now be viewed as "Theater Outcomes and Launch Date." A pivot table was focused on "Parent Category" and "Years". Columns created in the table were focused on "successful", "failed", and "canceled" plays. Rows created in the table were focused on the months the theaters succeeded, failed, and were canceled.

My pivot table appeared like the image shown below: 

https://courses.bootcampspot.com/courses/524/files/450147/preview

The "Row Labels" column show in the table shows twelve months of a year. This column was created by grouping the column to show the months of the year only, excluding days years. The website used to explain how to group columns is listed below: 

https://support.microsoft.com/en-us/office/group-or-ungroup-data-in-a-pivottable-c9d1ddd0-6580-47d1-82bc-c84a5a340725?ui=en-us&rs=en-us&ad=us 

The "Parent Category" shown in the table is filtered to show data for "theater", and the columns are sorted from highest to lowest data outcomes as shown in the table below: 

 https://courses.bootcampspot.com/courses/524/files/450148/preview

A line chart was created from the pivot table. This table was created to provide an image of the relationship between the outcome and the launch month by clicking onto the pivot table, clicking CTRL+1, and choosing the line chart as the preferred chart. Afterwards, a title is added to the chart “Theater Outcomes Based on Launch Date” as shown in the image below: 

 https://courses.bootcampspot.com/courses/524/files/450149/preview

Once creating a line chart and providing a title. The line chart must be saved into the resources folder as a PNG file. The first part of my analysis is now completed.  

In contrast, the second part of the analysis began with creating a new sheet labeled "Outcomes Based on Goals". This sheet contains eight columns: Goal, Number Successful, Number Failed, Number Canceled, Total Projects, Percentage Successful, Percentage Failed, and Percentage Canceled. 

The "Goal" column would contain dollar-amount ranges to provide projects analyzed to be reviewed as grouped based upon their goal amount. An example is shown below: 

https://courses.bootcampspot.com/courses/524/files/450150/preview 

The "Number Successful", "Number Failed", and "Number Canceled" columns will provide the COUNTIFS() function to provide data showing how many plays were successful, failed or canceled in accordance with the “Goal” column. The link below provides the equation to find a COUNTIFS() function. 

https://support.microsoft.com/en-us/office/countifs-function-dda3dc6e-f74e-4aee-88bc-aa8c2a866842?ui=en-us&rs=en-us&ad=us  

In addition, the "Total Projects" column provided the sum of the "Number Successful", "Number Failed" and "Number Canceled" columns by using the sum() function. Once the "Total Projects" column was completed, a line Chart was created titled "Outcomes Based on Goal". In this line chart the x-axis provides the relationship between goal-amount ranges, and the y-axis provides the percentage of successful, failed, and canceled projects. After the line chart completion, the chart was saved into the resources folder as a PNG file. The line chart is sprovided below: 

 

Challenges or Difficulties Encountered 

There were three challenges that I encountered while completing this analysis: solving the COUNTIFS() function, solving the percentage equation, an completing the percentage line chart.  

Solving the COUNTIFS() function was challenging because I misplaced information to collect data. To solve the function, I signed into Slack to receive help with a screenshot attached to understand how to improve my equation. In contrast, solving the percentage equation was challenging. I divided two cells by each other and divided the answer by 100. For example, divide cells A1 and B1 and divide the answer by 100. Additionally, highlight the entire column and turned the decimals into a percentage by clicking CTRL+1, and choose percentage with 0 decimals. Solving the percentage equation incorrectly may have altered my results to provide to Louise. 

Another challenge that I faced was matching the last Line Chart with the image in the module. My chart looked different than the chart in the module, and I was unsure if it was correct or not. In conclusion my flaws were, solving equations, matching charts, and knowing if I found the correct data by the equations that I made. 

 

RESULTS 

Two Conclusions About Theater Outcomes by Launch Date   

The first conclusion that can be made about Theater Outcomes by Launch Date is campaign outcomes reached a higher successful rating in contrast to failed and canceled ratings. For instance, successful ratings were between 111 to 234 with a grand total of 2185, failed ratings were between 102 to 150 with a grand total of 1530, and canceled ratings were between 20 to 43 with a grand total of 349. These rating provide an analysis that the theater outcomes by launch date had a successful campaign rate. 

The second conclusion that can be made about Theater Outcomes by Launch Date is the months analyzed for successful, failed, and canceled rating. For instance, February is a successful month for campaigns in contrast to the month of December with a low rate of successful campaigns. July is a month with higher ratings of failed campaigns, and April is a month with lower ratings of failed campaigns. July is a month with higher ratings of canceled campaigns, and October is a month with lower ratings of canceled campaigns. 

Conclusion About Outcomes Based on Goals  

What I can conclude about the Outcomes based on Goals is the successful goal had the highest data, and the canceled goal had the lowest data. According to the line chart, the successful goal was ranked at the highest data, the successful goal was met with failed goal at "Greater than 5000". Afterward, the successful goal decreased, failed goal increased, and canceled stayed the same at a rate of 0. 

What Are Some Limitations of This Dataset?  

Limitations of this dataset is there is not a reason behind the successful, failed, or canceled ratings based on outcomes. Each month the ratings change, however, there is not a reason behind the successful, failed, or canceled ratings. For instance, seasonal allergies, weather change, or holidays. In addition, there is not a comparison table/graph between Louise completed data and the data that she is analyzing. If Louise wants to analyze various campaign launch dates and funding goals, then a comparison table/graph will be valuable to provide for Louise to view her chart in comparison to the data she is analyzing to understand what areas she has met with the chart in comparison, and what does she need to improve. 

Other Possible Tables and/or Graphs 

As aforementioned, a possible table/graph that we could create for this analysis is a bar graph. Focusing on how Louise can meet and exceed the data she is analyzing. 

 

 
