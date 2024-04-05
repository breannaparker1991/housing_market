 Here we will be looking at the changes in the housing market, and seeing if we can find out what the best course of action is and if things will change in the future. The first dataset found is from the redfin website and goes over the housing sales prices, listing numbers, etc over the last decade. More data will probably be needed to get the full scope of what is currently happening on the marketplace. Overall analysis of the data collected shows that prices of homes have increased at an alarming rate over the last decade, but also that the number of homes available has hugely decreased. As long as therer aren't very many homes, they'll continue to get bought up quickly, at prices way above asking, causing even fewer people and businesses the ability to buy homes.

Now it was time to run our models. I ran three different models to see which was the
most accurate. I ran RandomForestClassifier, LinearRegression, and DecisionTreeClassifier.
Out of these three, the LinearRegression model had the highest r2 value. The r2 value
represents the goodness of fit of a regression model, meaning that the predicted value and the
actual value are very close, the closer the number is to 1. The number that I got was 0.98 so I
continued testing with this model. Another reason why this is the best model out of the three is
the mean absolute error number. This number represents the magnitude of difference between
the prediction and true value of the data. This number was the lowest for the LinearRegression
model out of all three. The last number that was looked at was the rmse. RMSE is measuring
the quality of the predictions. It shows how far the predictions fall from the measured true values
using the Euclidean distance. The LinearRegression model had the lowest number out of all
three models.

Lastly, I looked at the the Select K Best features for the dataset. These are the features
that have the biggest impact on the median home price. The features that appear to have the
biggest impact on the median home price are going to be the number of homes sold, the
number of new listings, the inventory, the days of the market, and the year. It’s interesting to
note that mortgage rate and interest rate are not in the top five things that affect the sales price.
So, even though there has been a raise in mortgage rates, which was supposed to slow down
the increase in housing prices, this may not have as large of an effect as previously thought.
What seems to have the most in common with the sale price, looks like the number of homes on
the market.

In conclusion, businesses who are in the market to buy homes right now, might want to
wait a little longer while the market stabilizes, mortgage rates drop, and housing price increases
slow down. However, for a business that wants to sell homes, this is the perfect time. The
supply is not meeting the demand. However, we don’t know how long this will last. So, now is
the perfect time to buy up land, build new homes, and sell them for a huge profit. Other factors
to look into will be the cost of lumbar and labor. However, since large homes are becoming too
unaffordable for people, a business could build a larger number of smaller homes and sell them
much more quickly. There is a huge outcry on social media for affordable homes. If nice homes,
that might be a little small, get put on the market, they will sell very quickly. However, since the
above data is done on a national level, the same numbers should be rerun by region to find out
where the biggest demand is for new houses.
