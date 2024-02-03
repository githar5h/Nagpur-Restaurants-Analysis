# Nagpur-Restaurants-Analysis
This project involves conducting exploratory data analysis (EDA) on a Kaggle-sourced dataset featuring restaurants available on the Swiggy app in Nagpur city. The main goal is to gain insights into various aspects of the restaurant data, including ratings, categories, costs, and delivery options.

## Steps Taken
1. Dataset Pre-processing using Excel:
   - Removed restaurants with unavailable ratings using Excel filters.
   - Deleted empty rows using the COUNTA function.
   - Manually adjusted categories served based on personal experience and online data.
   - Broadened locality data by consolidating similar locations, such as combining "Loha Pul, Pind" and "Loha Pul, Moody" into a single entry for "Loha Pul."
   - Unified locality names by standardizing variations like laxminagar, LAXMINAGAR, and laxmi nagar, ensuring consistency and clarity in the dataset.

2. Data Analysis in Python:
   - Utilized Python libraries, including Pandas, Matplotlib.pyplot, and Seaborn, for comprehensive data analysis and visualizations.
   - Implemented the following EDA ideas:
     * Regional Analysis
     * Cuisine and Category Insights
     * Rating and Cost Analysis
     * Vegetarian vs. Non-vegetarian Preferences
     * Long Distance Delivery Analysis

## Tools Used
- Pandas: For data manipulation and analysis.
- Matplotlib.pyplot: For creating visualizations such as scatter plots and bar plots.
- Seaborn: For enhancing the aesthetics of visualizations.

## Dataset Source
The dataset used for this analysis was obtained from Kaggle, and the link for the same can be found [here](https://www.kaggle.com/datasets/chinmayshanbhag/swiggy-nagpur-restaurants).

## Results

### Analysis 1: Regional Analysis

#### Restaurant Distribution Across Areas:

Upon analyzing the dataset, it is evident that certain areas in the city stand out in terms of restaurant density. Notably, areas like Sadar, Dharampeth, and Bajaj Nagar boast the highest number of restaurants, aligning with personal observations and the city's bustling culinary scene. Conversely, areas like Chhaoni, Cotton Market, and Besa have fewer restaurants, indicating potential opportunities for culinary exploration in these locales.

#### Average Cost and Street Food Hotspots:

Exploring the correlation between area and average cost revealed intriguing insights into the city's culinary landscape. Restaurants in Dighori, Besa, and Shankar Nagar Square emerged as some of the costliest, possibly reflecting a more upscale dining experience. On the flip side, areas like Kharbi, Futala, and Lakadganj showcased more budget-friendly options, suggesting the prevalence of popular street food destinations in these regions.

#### Area-wise Ratings and Culinary Excellence:

Diving into the average ratings of restaurants across different areas uncovered distinct patterns. Restaurants in Ajni, Ganesh Peth Colony, and Gandhibag earned the highest average ratings, indicating a concentration of culinary excellence in these regions. Conversely, Lokmat Chowk, Loha Pul, and Narendra Nagar registered lower average ratings, signaling areas where the dining experiences may require further attention or improvement.
  
### Analysis 2: Cuisine and Category Insights

#### Popularity of Food Categories:
Multi-cuisine establishments emerge as the most prevalent in Nagpur, showcasing the city's diverse culinary landscape. In contrast, Mexican cuisine seems to be less common, reflecting a lower representation among the city's restaurants.

#### Average Ratings Across Food Categories:
Desserts lead in terms of average ratings, indicating a collective appreciation for sweet indulgences among patrons. Thalis, while offering a variety of options, receive the lowest average ratings, suggesting potential room for improvement or diversification in this category.

#### Average Cost for Two Based on Food Categories:
Restaurants serving multi-cuisine dishes tend to have the highest average cost for two, pointing to a likely upscale and diverse dining experience. Mexican cuisine emerges as the most budget-friendly option, providing an accessible culinary experience for those conscious of their budget.

### Analysis 3: Ratings and Cost Analysis

#### Correlation Between Cost and Ratings:
A direct correlation was observed between increasing cost for two and higher rating ranges (low, medium, high). This suggests that, on average, higher-priced restaurants tend to receive better ratings in Nagpur.
While a general trend of higher ratings with increased cost is evident, it's important to note the presence of outliers. Outliers may represent unique cases where lower-cost establishments achieve exceptional ratings or higher-cost ones fall below expectations.


### Analysis 4: Vegetarian vs. Non-vegetarian Preferences

#### Distribution of Restaurant Types:
28.1% of restaurants in Nagpur exclusively serve vegetarian cuisine. A significant majority, 71.9%, offer a mix of vegetarian and non-vegetarian options.

#### Ratings Distribution Based on Pure Veg Status:
Pure vegetarian places exhibit a positive trend, with no ratings below 2.5. Restaurants serving both veg and non-veg have a broader distribution, including lower ratings. However, the highest ratings are comparable for both types of establishments.

#### Prices Distribution Based on Pure Veg Status:
Places offering both veg and non-veg dishes can vary significantly in cost, ranging from the lower end to a high of 1400 for two people. Pure vegetarian restaurants generally have a more constrained price range, extending from the lower end to around 900 for two people.

### Analysis 5: Long-Distance Delivery Analysis

#### Average Rating Comparison:
Upon comparing the average ratings, it was noted that there is virtually no difference between restaurants with and without long-distance delivery options. This observation suggests that the city's local dining scene is robust, with quality options available in most areas. Residents may not feel the necessity to order from restaurants located far away.

#### Average Cost Comparison:
Similar to the rating analysis, the average cost for restaurants with long-distance delivery support showed nearly no difference compared to those without. The marginal cost implications suggest that the convenience of long-distance delivery does not significantly impact the overall cost of dining.

## Conclusion

This  analysis of Nagpur's dining landscape reveals a city with diverse and dynamic culinary preferences. Geographically, areas like Sadar and Dharampeth thrive with a high density of restaurants, while multi-cuisine options dominate the culinary scene. Desserts stand out as the highest-rated category, contrasting with lower ratings for thalis. Pure vegetarian establishments coexist with those serving both veg and non-veg, showcasing a city where vegetarian options are prevalent. Interestingly, the presence of long-distance delivery options shows minimal impact on both ratings and costs, indicative of a well-established local dining scene. Overall, Nagpur has a variety of dining experiences, offering residents and visitors a range of dining experiences from local favorites to international flavors.
