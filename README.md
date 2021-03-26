# Ramen-ratings paper
# 1.Introduction

This paper will discuss on Ramen ratings from The Ramen Rater website from Kaggle. Ramen is without arguing a popular 'fast food' not only in Japan but in many western countries as well but what differs between the many brands available what makes a certain type of ramen better than others, what features have the largest effect on the rating of the product, is it the company that produces the ramen? 

Thus we list 4 questions for when we exploring the dataset clearly:
* 1.What is the most popular kind of ramen noodles?
* 2.What are the top 3 countries which have high average ramen ratings?
* 3.Do the styles of ramen noodles have any impact on the ratings? 
* 4.Do countries have a big impact on the ratings?

Based on above questions, we would like to apply hypothesis testing and simple linear 
regression model to answer these questions.

Data describing Ramen and opinions about it can be found on a website dedicated to this issue - theramenrater.com. We have information about almost 2600 ready-made ramen, which we can buy in various places around the world. Today we'll look at these dishes depending on the continent they come from. The variable about the continent cannot be found in the database, but it can be created based on information about the country of origin, which we group into continents.  

⬩ 2580 Observations and five variables


⬩ [1] "Brand" "Variety" "Style" "Country" "Stars"



* `Brand`: brand for ramen


* `Variety`: ramen specificed variety


* `Style`: the style of ramen as pack, bowl, tray, box, cup and etc.


* `Country`: the source country of ramen


* `Stars`: stars of ratings given to ramen

# 2.Exploritory Data Analysis

# 3. Regression Analysis



# 4. Conclusion

Overall, styles have some impact to the ratings because the p value is small. The most popular kind of ramen noodles are bar, because many people still prefer to dine in at the restaurant. In general, countries also have some impact to the ratings due to small p values and the top 3 countries which have a high average ramen ratings are “Brazil”, “Cambodia” and “Fiji”. Ramen ratings issued by users are indeed different due to the continent. The best grades are given in Asia, but reviewers from South America also willingly to give high marks. Strongly negative ratings are frequently appear in Europe and North America. On average, reviewers from Australia gave the lowest ratings. Out of 2580 ramens, more than half can be purchased as a package. The cup and bowl are also popular, too. When it comes to continents, about 75% of the products come from Asia, and Asia was also the continent produces ramens. The differences between the continents and styles are small. Particularly, bowl packaging only observed in Asian ramen. We see that that in our data, the company ' Nissin' dominates in our sample with more than 350 different products in our dataset.

# 5. Bibliography

Dataset available: https://www.kaggle.com/residentmario/ramen-ratings
The Ramen Rater: https://www.theramenrater.com
