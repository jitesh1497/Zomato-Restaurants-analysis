
# Zomato Restaurant Analysis using Python



**Problem Statement :**

Zomato has an average of 17.5 million monthly transacting customers for its food delivery business. The average monthly active food delivery restaurant partners on Zomato's platform have also increased by 8.7% year-on-year, from 2,08,000 to  2,26,000. We have a dataset of customers.At zomato, there is need to analyze the data , perform EDA (Exploratory Data Analysis ) and visualization and give valuble insights to the company.  

## Snapshot of Zomato data 

![Screenshot 2024-08-12 151613](https://github.com/user-attachments/assets/aa86f29f-d431-44cd-804f-58bef0b04d12)

(This is just a snapshot and not a complete table)



# Case Study Questions:

Q1) What type of restaurant do the majority of customers order from ? 

Q2) How many votes has each type of restaurant received from customers?

Q3) What are the ratings that the majority of restaurants have received?

Q4) Zomato has observed that most couples order most of their food online. What is their average spending on each order?

Q5) Which mode (online or offline ) has received the maximum rating?

Q6) Which type of restaurant received more offline orders,so that zomato can provide those customers with some good offers?



# Insights
 
 Before answering the questions. I have cleaned the data first .

 i) Making a User defined function named "handleRate" to split the "rate" column.

ii) I have checked if there is no nulll value in the data. 

iii) For every question i have tried to use different graph , most suitable according to question.

### i) Most prefferd type of Restaurants :

 To explain this , I have used "Count plot".

 Where Dining Restaurant are the most prefferd choice with over 100+ counts followed by cafes with 20+ counts then others and buffets. 

### ii) Votes received by each type of restaurant from coustomers : 

To explain this , I have used "Linear graph ".

Where Dining Restaurants have highest votes i.e. 20000+ followed by others i.e. approx 10000 then cafes with 6500+ votes.

### iii) Ratings received by majority of restaurants :

To explain this , I have used "Histogram".

The majority of restaurants received ratings ranging from 3.75 to 4.00 i.e. 50+ followed by 3.4 to 3.75 i.e 40+

### iv) Most couple's averge spending :

To explain this , I have used "Count plot".

The majority of couples spend around 300 rupees on restaurants bills.

### v) Online orders receive higher ratings than offline orders :

To explain this , I have used "Box plot".

Rating's while ordering food online lies in the range of 3.75 to 4.15 whereas rating while ordering food offline is 3.15 to 3.75 , which is lesser as compared to rating of ffod ordered online.  

### vi)Dinning Restaurants received more offline orders, these are coustomers to be targeted :

To explain this , I have used "Heat Map".

Dinning restaurants primarily acccepts offline orders, whereas cafes primarily receive online orders. This suggest that Coustomers prefer to place orders in person at restaurants, but prefer online ordering at cafes. so, the Coustomers who prefer to go to Dinning restaurants are the one who should be targeted by giving them additional coupons for such restaurants. 

