#Barkeley Machine Learning and AI Prefessional Certification
This is 1st Practical Application Assignment as part of Module 5.1

This practical application assignment focuses on using data analysis skills, in an effort to seek answer to the question based on survey results, “Will the Customer Accept the Coupon?”.
All aspect of data visualization has been done using Jupyter Notebook. The link of Notebook is 
https://github.com/vikashsinha72/UCBMLAI/blob/main/prompt.ipynb
prompt.ipynb

Data Used: This data comes to us from the UCI Machine Learning repository and was collected via a survey on Amazon Mechanical Turk. Data file coupon.csv is availble as part of assignment.
 

General findings:

A total '13370' null values, spread across 6 columns and of which 'car' column has the most number of null values.
car                     12576
Bar                       107
CoffeeHouse               217
CarryAway                 151
RestaurantLessThan20      130
Restaurant20To50          189

Except car, other null values are negiligible in comparision to total data observation available. Car data has been normalized aand others are ignored during clean-up process.



Bar Coupon acceptance visualization against various dataset:

a) ~57% of the total observations chose to accept the coupon. This means coupon had been some what effective marketing tools for sales promotion.

b) most of the observation has been taken when temperature was as ~70-80

c) Coffee House has offered highest no of coupon whereas costlier restaurant has least no of coupon offer.

d) Bar coupon has been moderate acceptance as ~41%.

e) The most frequent Bar visitor driver have more acceptance of the coupons as ~76% as compared to the less frequent bar visitor driver had shown less interest in coupon acceptance (~37%).

f) The 'frequent elderly visitors' to bar have high acceptance(69%) of the coupon as compared to 'less frequent young visitors' who have showed only less interest (34%).

g) The 'frequent elderly visitor drive with adult passanger and job other than farming/fishing/forestry job' to bar have higher acceptance(~71%) of the coupon as compared to 'less frequent or having child passanger or farming/fishing/forestry job' visitor driver who have showed only less interest (~30%).

h) The 'frequent younger visitors' to bar have accepted the coupons to the most (39%) compared to 'frequent visitors that are elder and widowed' who have slightly less interest (37%) or 'frequent visitors to cheap restaurants with low income' who have even less interest (24%).

h) The Driver visiting frequently to bar and having elder passenger and not widow , has similar acceptance rate for coupon ( ~71%) as driver having high frequent visit and younger age (~72%). However low income driver visiting frequently to cheap restaurant had shown least interest in coupon acceptance(~46%)

In conclusion, Most frequent Bar visitors drivers, are taking advantage of the coupon and acceoting the same more as compare to anyone else.

Evediently, Drivers who are within low income or use cheap restaurants does not much care about the bar coupons.


Independent Investigation: 
Since Coffee House has offered highest no of coupon whereas costlier restaurant has least no of coupon offer, It would be significant investigattion to visualize thier coupon acceptance. 

a) Coffee Coupon Acceptance:
Coffee Coupon is highest amonst all coupon type.
Coffee Coupon has overall highest acceptance by visitors than any other coupon type.
Coffee coupons were accepted relatively more when driver visiting with Friend(s) as passanger whereas low acceptance in case of visiting alone.

Income and Gender have no significant effect to coffee coupon acceptance.

It is evedent that the young drivers with age below 21 has higher acceptance for coffee coupons, whereas elderly population with 50 plus shows slightly low acceptance.

Weather has no significant influence in coffee consumption. The coupon acceptance was slightly low when snowy which indicate that the driving in comfortable weather is favourable.

Coffee House is having ~50% of coupon acceptance. Hence perfornace of coupon acceptance is moderate.


b) Restaurant(20-50) Coupon Acceptance:

Restaurant(20-50) is having ~45% of coupon acceptance. Hence perfornace of coupon acceptance is moderate.

It is evident that Highest No of coupon type have similar performance as Lowest No of coupon type. Hence Offering of coupon is an average marketing tool to increase sales, if other variables are normalized.


In general, Coffee House coupon is overall most accepted by visitor.

