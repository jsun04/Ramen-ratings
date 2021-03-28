# Ramen-ratings paper
# 1.Introduction

Without any arguments, Ramen is one of the most convinents food not only in Asian countries, but also in mant western countries as well. When we do not know what to eat, ramen is a good choice not only because it's tasty, but also it’s easy to cook. Especially, when instant noodles were invented by Momofuku Ando in 1958, ramen became quick and easy to cook only with boiled water. For this project, our team found an interesting dataset in Kaggle, which contains the data from Ramen Rater website. This dataset contains 2580 variables with 5 varibales:
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

There are 3 main reasons that made our team decided to do this project:

1. Our team only know Ramen from China and Japan, so we want to explore the Ramen industry all around the world. 
2. We also want to know what are some factors that impact the ratings for different kinds of ramen. 
3. It is also nice to know if different style of ramen can also affect the ratings. 


To get a better understanding of those SMART questions above, we would like to apply hypothesis tests and simple linear regression models to to accomplish this task.

Data describing Ramen and opinions about it can be found on a website dedicated to this issue - theramenrater.com. We have information about almost 2600 ready-made ramen, which we can buy in various places around the world. Today we'll look at these dishes depending on the continents they come from. The variables about the continents cannot be found in the database, but it can be created based on information about the country of origin, which we group into continents.  

# 2.Exploritory Data Analysis

Before getting into the deep analysis about this dataset, we first cleaned the dataset by dropping 2 variables: Review and Top ten, because there is no data contains in top ten and review were random lables, which is meaningless for our analysis. 

And then we turned the variables of `Stars` into numeric variables. We want to use Heatmap and Barplots to make exploritory data analysis (EDA). 

First, our team looked at all the countries contain in this dataset by creating a heatmap. From the map, we can see that worldwidely, there are almost 50% of the countries have been covered for this research. And the color represents the ratings for each country, the darker the color is, the higher the rate is. Just by looking at the plot, we can see that China, and United States are the two countries with darker color. But we can make the conclusion for our question, because we still need futhur analysis to ensure our assumption. 

Secondly, we used barplot to show the top 10 average Ramen ratings by countries, we can see the top rating is Brazil, which has an average rating 4.35. From the barplot and the chart of ratings by styles, we can see there are total of 7 styles of ramen noodles in this research, and there are some unknown, which we will eliminate those during our analysis. The one that most popular is `bar`, which has 5 stars rating. This result is not supring for us, because from the research we know many Asian people still love to eat ramen in a physical resterant, and some of them may feel the taste is better comparing to eat ramen at home. In addition, many Japanese people are very serious about the cooking time for ramen, someone likes to eat harder ramen so they often cook for 2 minitues, but some likes to eat softer ramen and they always cook it for 3-4 minitues. This kind of complicated process may not be done by ourselves at home, but the ramen shop can do all of those. Therefore, the `bar` has the highest rating. 

# 3. Regression Analysis

Firstly, we see that the country Brazil, Cambodia, Canada, Hong Kong, Indonesia, Japan, Malaysia, Mexico, Myanmar, NetherlandsBaraȀak, Singapore, South Korea, and Taiwan are significant. The overall model is significant.
Secondly, we found that none of the style is significant Ȁhich means people do not have a preference to style. Style is not an important factor for people to give rate for ramen.


# 4. Conclusion

Overall, styles have some impact to the ratings because the p value is small. The most popular kind of ramen noodles are bar, because many people still prefer to dine in at the restaurant. In general, countries also have some impact to the ratings due to small p values and the top 3 countries which have a high average ramen ratings are “Brazil”, “Cambodia” and “Fiji”. Ramen ratings issued by users are indeed different due to the continent. The best grades are given in Asia, but reviewers from South America also willingly to give high marks. Strongly negative ratings are frequently appear in Europe and North America. On average, reviewers from Australia gave the lowest ratings. Out of 2580 ramens, more than half can be purchased as a package. The cup and bowl are also popular, too. When it comes to continents, about 75% of the products come from Asia, and Asia was also the continent produces ramens. The differences between the continents and styles are small. Particularly, bowl packaging only observed in Asian ramen. We see that that in our data, the company ' Nissin' dominates in our sample with more than 350 different products in our dataset.

# 5. Bibliography

Dataset available: https://www.kaggle.com/residentmario/ramen-ratings

The Ramen Rater: https://www.theramenrater.com
