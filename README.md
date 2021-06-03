# Boston Airbnb

### Libraries Used in this Notebook:

Pandas, Numpy, Matplotlib, Seaborn, FuncTools, Collections, NLTK, RegexpTokenizer, RegexpTokenizer, WordNetLemmatizer, Stopwords


### Motivation

As someone who has used Airbnb before, I personally know that it can be a little overwhelming at times to try to narrow down on which Airbnb would be perfect to stay in for a few days for a vacation. So, I wanted to focus on which neighborhoods would be best to choose from in Boston, mainly based on their average user score, what was said about them in the comments, and how much they go for in terms of price.


## Data Description

The data is comprised of three separate csv files:

Reviews - Contains the user reviews people have left for homes based on listing_id.

Listings - Contains data on all of the Airbnb homes. Such data includes descriptions, house rules, price, neighborhood, score, and much more.

Calendar -  Includes the listing id, price, and the availability for that day.


## File Description

The folder Boston_Airbnb_Vis contains the main visualizations that are present in the Jupyter Notebook for this project. They are the results of the data analysis, such as neighborhoods that have the most Airbnb's, average scores of homes based on their neighborhood, and common phrases found in the user reviews.

## Findings (Summarized)

Most homes tend to score on average above 80% (with the exception of homes in Cambridge). So to help narrow down what you'd might want to look for in a home to rent, it was dicsovered that homes with an average score above 90% seemed to include phrases like *comfortable*, *house*, and *recommend*, than those homes that scored on average below 90%.
It is also important to note the average pricings for homes in specific neighborhoods. If you're not looking to spend too much money, you'd might want to stay away from homes in Harvard Square. If you want to find something that is reasoonably priced but not so ridiculously cheap, you could find homes in between the nighborhoods of the Leather District and North End (see chart below).

<img src="https://github.com/andrew-alarcon17/Boston_Airbnb/blob/main/Boston_Airbnb_Vis/Average_Prices_by_Neighbourhood.png" width="500">
