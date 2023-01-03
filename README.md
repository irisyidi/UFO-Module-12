# UFO-Module-12
## Overview of Project 

Dana;s webpage and dynamic table are to provide a more in-depth analysis of UFO sightings. Through filtering for multiple criteria (such as date, city, state and country), the qualified data of UFO are selected for different uses. 


## Results 

### Description of How to Perform a Search, with Images

In the JavaScript, there are three functions, buildTable, updateFilters and filterTable. When we input the criteria, the changed element including the value and its id will be saved in the filters. Through the if-statement, the value changed will be checked. If the value was changed, the element's value and id will be added to the filters variable. If it is not changed, the element will be cleared. After updating the filtering data, code is written to filter table based on the user's input that has been stored in the filters variable. Through using a loop, the qualified data is filtered and stored that matchese the filter values in the fiter variables. A new table is rebult with the filtered data by passing the variable created. 

### Example on How to Search 
Before input of filters, all the data is displayed in a table. (See Picture 1). 

![S1](https://github.com/irisyidi/UFO-Module-12/blob/main/S1.png)

If we want to select the UFO information in Jan 1st, 2010, we can input 1/1/2020 in the date column. After inputing the date, the table is rebuilt by selecting the data with date 1/1/2020. (See Picture 2)

![S2](https://github.com/irisyidi/UFO-Module-12/blob/main/S2.png)

If we narrow down UFO information eligible by adding more criteria, for example the UFO information in California in Jan 1st 2020 with the light shape, besides entering 1/1/2010 in date column, we can input ca, us, light into State, Country and Shape columns, respecitvely. After that, the UFO information of California US in 1/1/2010 with the light shape is displayed in the table area. (See Picture 3)

![S3](https://github.com/irisyidi/UFO-Module-12/blob/main/S3.png)

If we want to search the light-shape UFO information in Bonita California in 1/1/2010, we can add one more filter, bonita in City Column. After the input the UFO information is shown in the table (See Picture 4)

![S4](https://github.com/irisyidi/UFO-Module-12/blob/main/S4.png)


## Summary 
### Drawback of the Webpage

The criteria applied to search the UFO dat are limited. In this table we can only filter the data by date, city, state, country and shape rather than by duration and comments. The analysis is restricted into the geographical factors. Other comparison such as the duration time cannot be searched and filtered in this webpage. Besides, the table is not visualized compared with the graph, which means that more analysis need to be done to get the conclusions. 


### two recommendations for further development

- Standarlize the duration data and add the duration filter 

The duration data can be transferred into the type of number with the same measurement unit. By standarlizing the duration data, the duration can be applied as a filter to provide more information to the users. 

- Add charts to present the insights more visibly 
Line charts or bar charts can be used to present the trend of the number of UFO in different time period or in different cities or states. Therefore, the webpage is more vivid for users to get the insights of the data. 
