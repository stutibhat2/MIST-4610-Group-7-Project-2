# MIST-4610---Group-Project-2

**Team Members:**
Ryan Dyals [@RyanDyals](https://github.com/RyanDyals/MIST-4610---Group-Project-2)
Branon Yum [@BrandonYum](https://github.com/BRANDONYUM/MIST-4610-Group-7-Project-2)
Stuti Bhat[@StutiBhat2](https://github.com/stutibhat2/MIST-4610-Group-7-Project-2)
Matthew Vega[@mtv38865](https://github.com/mtv38865/MIST-4610-Group-7-Project-2.git)
Eujin Kang[@EujinKang](https://github.com/eujinkang/MIST-4610-Group-7-Project-2 )

**Link To Data Set**
(https://hub.arcgis.com/datasets/6b52792b667d4056bddd358cc25fbfc6_0/explore?location=60.256230%2C15.403105%2C5.52)


**Description of Data Set**

This data set was obtained from the United States Department of Transportation or DOT. The title of this data set is 2021 Fatal Motor Vehicle Accidents. This data set contains over 39,000 instances of fatal accidents in 2021 in every state, recording the following information: geospatial data(state and coordinates), number of fatalities, lighting conditions, weather conditions, type of roads, cause of accident, damage done, date, time, and hospital arrival information.


**Question 1**

“Are there states that have more fatalities due to poor lighting conditions than others?”

**Why is this important?**

From the perspective of the Department of Transportation, federal grants are given out every year to states in need of funding for improved roadways, light conditions, traffic lights, and truck check-in/weighing stations. Knowing which states are suffering from the most fatalities due to poor lighting is important to decide which states are in the most need for federal grant funds regarding lighting.


**Question 2**

“What weather conditions have the most deaths in Washington? What months do they occur and where do they occur in the State?”

The State of Washington is known for its heavy rain and snow. The State would like to track which months of the year have the most deaths due to different weather conditions. Specifically, if there are more deaths due to adverse weather conditions in these months to know if they need to put out more signage when these conditions occur and what time of the year these deaths are highest. This is significant as during these months the state can put up more warning signs for residents, prep the road (add salt for snow), and have more EMS staff on standby during these time periods. More importantly, the state can also see where they occur within the state to target these areas.


**Manipulations to The Data**

 There were some data points in the set that were not descriptive and had a lot of null values such as no weather conditions information or missing the number of fatalities in the accident. These points were removed so it would be easier to see the relevant data in the visualization. Filters were applied to the data in Tableau to create the visualizations, filtering by lighting conditions in Question 1. Question 2 also required filtering by state and weather conditions. Some data types were changed to accommodate for geospatial visualizations as well. 




**Visualization For Question 1**
<img width="1133" alt="Screenshot 2024-04-28 at 7 55 45 PM" src="https://github.com/RyanDyals/MIST-4610---Group-Project-2/assets/134531824/54d3257d-dd33-435f-9a0b-d533b2cbac36">

**Visualizations For Question 2**

<img width="1131" alt="Screenshot 2024-04-28 at 7 59 02 PM" src="https://github.com/RyanDyals/MIST-4610---Group-Project-2/assets/134531824/ee629fc2-57af-4575-932a-d184231f32e5">

<img width="1135" alt="Screenshot 2024-04-28 at 7 59 51 PM" src="https://github.com/RyanDyals/MIST-4610---Group-Project-2/assets/134531824/413f80a7-ab11-4b2a-a50f-4d40586ece84">

**Analysis and Results**

After analyzing the map visualization to answer question number one, it is evident that the states with the top three fatalities due to dark conditions with no lighting are Texas, California, and Florida in descending order. These states have larger populations, but also large areas where lighting is not provided in a lot of fatal accidents. This shows the DOT that these states should be audited to see if they are in need of federal grant money to improve lighting conditions and hopefully result in less poor lighting related deaths.

Regarding question number two, contrary to what was expected the State of Washington actually had significantly more fatal car accidents in clear conditions in comparison to adverse weather conditions in every month except months during the winter. This finding implies that inclement weather related deaths should be focused on more in the winter months and during the rest of the year they are not as much of a concern. The State of Washington economically speaking, should be more concerned with preparing for accidents in the winter time than heavy rains in the summer.

Further, the map showing accident location by weather type shows that accidents typically are aggregated around certain cities. The state can take this data and analyze these cities further to see if there are unsafe roads, improper traffic signage, or lack of preparation of roads for the weather in order to reduce fatal accidents in Washington.
