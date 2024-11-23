# lego-data-analysis
## The Goal of This Analysis
This analysis aims to help a company decide which LEGO® sets to sell by examining a dataset with details such as target age ranges, reviews, piece counts, themes, and difficulty levels. By identifying popular and profitable products, the company can make data-driven decisions to optimize its selection. For this analysis, price information is not used, as the focus is on selecting the best sets, not determining their pricing. First choosing which products, pricing second is more reasonable and effective.



## About Dataset 
* Link to the lego dataset used in this project : https://www.kaggle.com/datasets/mterzolo/lego-sets
  
The dataset includes key attributes such as:  
* ages : The recommended age range for the LEGO set.  
* list_price : The price of the LEGO set in the corresponding country.  
* num_reviews	: The number of customer reviews the LEGO set has received. 
* piece_count : The total number of LEGO pieces included in the set.  
* play_star_rating : Average rating (out of 5 stars) given by customers for playability or fun factor.  (5 being the best)
* prod_desc : A short description of the LEGO set.    	
* prod_id	: A unique identifier number for the LEGO set.  
* prod_long_desc :  A detailed description of the LEGO set, often including features and additional details. 
* review_difficulty : Indicates how challenging the LEGO set is to build.  
* set_name : The name of the LEGO set.   	
* star_rating : Overall average rating (out of 5 stars) based on customer reviews.  	
* theme_name : The theme or category of the LEGO set. (e.g., "Star Wars," "Harry Potter," "City.").  
* val_star_rating : Average rating (out of 5 stars) for the perceived value of the LEGO set (customer satisfaction with the price-to-value relationship of the product).   
* country : The country in which the product was reviewed or is being sold.  


The most important attributes for the analysis, and the reason why they are important:
* Ages: Target age group for each LEGO set.
* Number of Reviews and Ratings: Indicators of popularity and overall satisfaction.
* Piece Count and Review Difficulty: Measures of set complexity, appealing to different customer segments.
* Theme and Product Description: Insights into themes and designs likely to attract interest.
 


## Libraries Used in This Analysis
* pandas: Data manipulation and analysis, used for handling data frames and performing operations on the dataset.
* numpy: Numerical operations, particularly for handling arrays and mathematical functions.
* matplotlib.pyplot: Data visualization, used for creating plots like scatter plots, bar charts, and box plots.
* seaborn: Statistical data visualization, provides higher-level interface for drawing attractive and informative plots.


## What Kind Of Analysis Were Performed In This Project?
Note: Detailed explanation of these steps are available on the notebook <br> <br>

* Data Preprocessing
  * Removing unnecessary columns
  * Categorizing Data
  * Removing Duplicates
  * Handling Missing Data
  * Data Type Converting
  * Outlier Detection
* Statistical Analysis
* Data Visualization




## Why This Analysis Might Be Useful And How Does It Achieves It's Goal? 
Why? <br>
It creates a solution for a spesific and detailed problem, helps a company on tactical planning : Which LEGO sets are the most profitable, popular and liked ones? 
After deciding to start selling LEGO products, a company must search for the most suitable LEGO sets. With the help of this broad and detailed analysis, it is possible to discover customer preferences and market demands. <br> <br>
How? <br>
* By identify LEGO sets that are highly rated and suitable for various customer demographics. 
* Focusing on themes and designs that match trending or popular preferences. 
* Avoiding products with low demand or negative reception. 

