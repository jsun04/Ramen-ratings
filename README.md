# Ramen-ratings paper
# 1.Introduction

Without any arguments, Ramen is one of the most convinents food not only in Asian countries, but also in mant western countries as well. For this project, our team found an interesting dataset in Kaggle, which contains the data from Ramen Rater website. This dataset contains 2580 variables with 5 varibales:
* `Brand`: brand for ramen


* `Variety`: ramen specificed variety


* `Style`: the style of ramen as pack, bowl, tray, box, cup and etc.


* `Country`: the source country of ramen


* `Stars`: stars of ratings given to ramen

And our team wants to foucs on exploring these following questions:
* 1.What is the most popular kind of ramen noodles?
* 2.What are the top 3 countries which have high average ramen ratings?
* 3.Do the styles of ramen noodles have any impact on the ratings? 
* 4.Do countries have a big impact on the ratings?

To get a better understanding of those SMART questions above, we would like to apply hypothesis tests and simple linear regression models to to accomplish this task.

Data describing Ramen and opinions about it can be found on a website dedicated to this issue - theramenrater.com. We have information about almost 2600 ready-made ramen, which we can buy in various places around the world. Today we'll look at these dishes depending on the continents they come from. The variables about the continents cannot be found in the database, but it can be created based on information about the country of origin, which we group into continents.  

# 2.Exploritory Data Analysis

Before the data analysis, we dropped 2 variables: Review and Top ten, because no observation in top ten were recorded and review were lables. And then we turned the variables of Stars into numeric. Heatmap and barplots are used to make exploritory data analysis. From the barplot of top 10 average Ramen ratings by countries, we can see the top rating is Brazil, and the average rating is 4.35. From the barplot and the chart of ratings by styles, we can see there are total of 7 styles of ramen noodles in this research, and there are some unknown, which we will eliminate those during our analysis. The one that most popular is bar, which has 5 stars rating.


# 3. Regression Analysis

Firstly, we see that the country Brazil, Cambodia, Canada, Hong Kong, Indonesia, Japan, Malaysia, Mexico, Myanmar, NetherlandsBaraȀak, Singapore, South Korea, and Taiwan are significant. The overall model is significant.
Secondly, we found that none of the style is significant Ȁhich means people do not have a preference to style. Style is not an important factor for people to give rate for ramen.


# 4. Conclusion

Overall, styles have some impact to the ratings because the p value is small. The most popular kind of ramen noodles are bar, because many people still prefer to dine in at the restaurant. In general, countries also have some impact to the ratings due to small p values and the top 3 countries which have a high average ramen ratings are “Brazil”, “Cambodia” and “Fiji”. Ramen ratings issued by users are indeed different due to the continent. The best grades are given in Asia, but reviewers from South America also willingly to give high marks. Strongly negative ratings are frequently appear in Europe and North America. On average, reviewers from Australia gave the lowest ratings. Out of 2580 ramens, more than half can be purchased as a package. The cup and bowl are also popular, too. When it comes to continents, about 75% of the products come from Asia, and Asia was also the continent produces ramens. The differences between the continents and styles are small. Particularly, bowl packaging only observed in Asian ramen. We see that that in our data, the company ' Nissin' dominates in our sample with more than 350 different products in our dataset.

# 5. Bibliography

Dataset available: https://www.kaggle.com/residentmario/ramen-ratings

The Ramen Rater: https://www.theramenrater.com
