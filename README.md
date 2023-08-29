# RM-CLASS-TASK
STEPS FOLLOWED IN ANALYSING THE DATA 
Load cereal data from an Excel file
#to load amd display first 10 data
#to describe the data types values
#to count the no of empty spaces
# to describe the top,freq,count ,unique value
# manufacturers (mfr) and cereal types (Type)
#LabelEncoder for categorical label encoding
#bar plot to visualize the distribution of encoded type
# Create a new column 'Calories_new' with binned categories
#to representation of scatter plot of calories vs rating
# tp visualize with correlation heatmap
#to show average sugar content with shelf placement

1.Cross-Tabulation of Manufacturers and Cereal Types (Counts):
The cross-tabulation of manufacturers (mfr) and cereal types (Type) will show the counts of each type of cereal produced by each manufacturer.

2.Distribution of Encoded Cereal Types:
The bar plot will show the distribution of encoded cereal types  across their ratings.  and the height of the bars will represent the number of cereals of that type in the dataset.

3.Binned Calories and New 'Calories_new' Column:
The DataFrame will be displayed with an additional column Calories_new, where each cereal's calorie count has been binned into one of the specified ranges ("Calories_under_43", "Calories_under_86", etc.)

4.Scatter Plot of Calories vs Rating:
This scatter plot will visualize the relationship between the calories and ratings of cereals. Each point on the plot represents a cereal, with its x-coordinate indicating calories and y-coordinate indicating rating.

5.Correlation Heatmap:
The heatmap will show the correlations between different numerical columns in your dataset. Darker colors indicate stronger correlations  between pairs of columns. This helps you understand how various features are related to each other.

6.Average Sugar Content by Shelf Placement:
This bar plot will show the average sugar content for cereals grouped by their shelf placement. Each bar represents a shelf, and the height of the bars represents the average sugar content of cereals on that shelf.
