# Excel_Project
Vrinda Store Annual Report 2022  - Interactive dashboarb  (automatics sales report)
![Excel Project-1](https://github.com/GOURAV1630/Excel_Project/assets/146067299/0dff90a0-44a0-47f7-9c03-22c974b14d00)

## Objective
Vindra store wants to create an annual sales report for 2022. So that, Vrinda can understand their customers and grow more sales in 2023.
 
### Data Processing -
Adding Age Group column for relationship between gender and age. If age is between 30 and 50than they are adults , if age is less than 30 they are teenagers. If age is 50 and above they are Seniors.
Formula used - IF(E2>=50, "Senior", IF(E2>=30, "Adult",, "Teenager"))

Adding Month column . To extract month we use formula   TEXT(G2,"mmm")
Highlighting the new columns added with yellow colour.

### Data analysis
Making Pivot tables according to different sample questions and making pivot charts cleamn for reading.
1. Orders Vs Sales (line chart)
2. Men vs Women (pie chart)
3. Order Status (Pie chart)
4. Sales: Top 5 states (Horizontal Bar)
5. Age and Gender (Column Chart)
6. Channels (Pie Chart)

Inserting Slicer(slicer can only be inersted if we have a pivot table). Adding 3 slicer that month,channel and category. Then sync all the pivot tables with slicers. Applying filter to any one slicer will show data at pivot tables.

### INSIGHTS
1. Maximum sales was in March.
2. Another insights is in men and women maximum shopping was done by women so salles in women is high.
3. In order status most of the items was delivered, which shows that sales is good.
4. In top 5 states we have Maharastra , karnataka, UP, telangana and tamil nadu.
5. Maximum shopping was done by women in adult category..
6. In channels 35% sales was done by Amazon alone then we have flipkart.

### Final Comclusion to improve sales:
Target women customers of age group(30-49 yrs) living in Maharashtra, Karnataka and Uttar Pradesh by showing ads/offers/coupons available on Amazon, Flipkart and Myntra.

#### This is how the raw data looked like.
![Excel proh](https://github.com/GOURAV1630/Excel_Project/assets/146067299/b454105d-5c7d-4910-b846-4e68c6a8b084)





