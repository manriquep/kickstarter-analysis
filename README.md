# Kickstarting with Excel

## Overview of Project

### Background

Louise, our client asked us to do research in kickstarting a fundraising campaign. Her goal is to 
fund the play she wrote called Fever. Louise’s estimated raising amount is over $10,000 to cover 
her production.

### Purpose   

To use launch dates and funding goals to evaluate the outcomes of theater campaigns.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

By converting the data into a multiple line chart with markers, we can see that May had the highest 
successful rate. While the failed rate line remained consistent between 40 and 50 throughout the year. 
We also notice that the canceled rate line was low, barely surpassing 10.

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/74743437/108917857-687b8300-75fe-11eb-8444-16938a2c1524.png)
 
 ### Analysis of Outcomes Based on Goal

By using a line chart, we can clearly see the failed rate is at its highest at $45000 to $49000, bringing 
successful rate to $0. The successful rate and failed rate are mirroring each other. If successful rate goes 
up then the failed rate goes the opposite direction, and vice versa. We also see that canceled rate 
stayed at an even zero.

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/74743437/108917963-952f9a80-75fe-11eb-97db-af223d2aa366.png)

 ### Challenges and Difficulties Encountered

A challenge encountered was in the categories for the “Theater Outcomes Based on Launch Date” chart 
were not lining up correctly, giving me the line levels all over the place. There are 4 categories in the 
pivot chart fields, which are Filters, Legend, Axis and Values. My mistake was not putting my cell data 
in the correct categories. Once I realized this, I corrected the chart by adding my Goal data into the axis 
category and Sum of Percentage Successful, Failed and Deleted into the Values category. Then the chart 
filled up appropriately to represent my data.

Another challenge that came up was in the “Outcomes Based on Goal” chart. The Data in the X-Axis was 
out of order and as a result the graph did not match the module’s example. I corrected this by right 
clicking on the item on X-Axis that I wanted to move, and moved it left or right to get it in order. 
Once done the chart clicked into place, matching the module’s example.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

The first conclusion drawn from the Outcomes Based on Launch Date is that the month of May 
has the most successful campaigns with 111 completed. The second conclusion is that on the month of 
December you have an even chance for your campaign to succeed or fail.

- What can you conclude about the Outcomes based on Goals?

The first conclusion from Outcomes Based on Goal is that $45000 to $50000 has an extremely 
high failure rate. The second conclusion is that between $500 to 15000 and $35000 to $40000 you have a 
better chance of having your campaign succeed.

- What are some limitations of this dataset?

There are some limitations of the dataset. For instance, where the campaigns launched in low-income 
areas or high-income areas or both. This data would greatly change the result analysis.  
The dataset also hinders from some campaigns that are still active. Whether they succeed or fail it will greatly change 
the results of our dataset.

- What are some other possible tables and/or graphs that we could create?

Some other possible tables would be setting the Theater outcomes Based on Launch Date table to 
represent years instead of months. The Outcomes Based on Goal table to represent number counts 
instead of percentage. We can also use a bar graph in both 3D or plain. We can also use a chart 
for each individual month for Theater Outcomes Based on Launch Date.
