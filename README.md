#  Restaurant Recommendation System

##  Objective
Create a recommendation system that suggests restaurants based on user preferences.

##  Recommendation Criteria
- Cuisine Preference
- Price Range
- Votes (Popularity)
- Aggregate Rating

##  Approach
- Cleaned dataset and handled missing values
- Extracted primary cuisine from multiple cuisines
- Applied filtering based on user input
- Ranked restaurants using a score combining rating and votes

##  Features Used
- Cuisines
- Price Range
- Votes
- Aggregate Rating
- City

##  How It Works
1. User enters preferences (cuisine, price, etc.)
2. System filters matching restaurants
3. Restaurants are ranked based on rating and popularity
4. Top recommendations are displayed

##  Sample Output
Restaurant Name | City | Cuisine | Rating  
----------------------------------------  
ABC Restaurant | Delhi | North Indian | 4.5  
XYZ Cafe       | Mumbai | Cafe | 4.4  

##  Conclusion
The system effectively recommends restaurants based on user preferences using a content-based filtering approach. Combining rating and votes improves recommendation quality.

##  Tech Stack
- Python
- Pandas
