# vgsales_online_game.

![image](https://github.com/user-attachments/assets/6ed03052-6083-441d-ae6a-e8f6786b4b1e)

## Data Description

• Rank: A unique integer identifier that ranks the video games based on a specific criterion (likely sales).

• Name: The name of the video game.

• Platform: The gaming platform on which the video game was released (e.g., PS4, Xbox One, PC).

• Year: The year the game was released. This column has some missing values, with 16,327 non-null entries out of 16,598.

• Genre: The genre of the video game (e.g., Action, Sports, RPG).

• Publisher: The company that published the video game. There are a few missing values, with 16,540 non-null entries.

• NA_Sales: Sales in North America, measured in millions of units.

• EU_Sales: Sales in Europe, measured in millions of units.

• JP_Sales: Sales in Japan, measured in millions of units.

• Other_Sales: Sales in regions other than North America, Europe, and Japan, measured in millions of units.

• Global_Sales: The total global sales of the video game, measured in millions of units.

## Information of the dataset:
* columns=11
  
* rows=16598
  
* Data types (float =6 integer = 1 object = 4)
  
* Occur Null values (Year = 271 Publisher = 58)
  
* no duplicates
  
## Feature Engineering
* calculate the total sales ratio across different regions (North America, Europe, Japan, and others) and store the result in a new column in a DataFrame?
* calculate the age of games in your dataset based on the release year
## Remove a column
* remove a specific column from a DataFrame in place, without creating a new DataFrame?
## Filter and sort
* Filter games released in a specific year
* Filter games from a specific genre
* Filter games with Global Sales greater than 50 million units
* filter and sort the vgsales_online_game dataset to find all games released in 2014, displaying their name, platform, publisher, and total sales ratio, sorted by platform in ascending 
  order and total sales ratio in descending ?
* Filter for games by a specific publisher with Global Sales over 1 million units
* retrieve the first six rows of the DataFrame, selecting the columns from 'Game_Name' to 'Publisher', and then sort these rows by the 'Year' column in descending order
* Select specific rows and columns by index
* Select the last row
* Example of Combination of loc and iloc:
  Filter sports games and then select the first 5 rows of specific columns ['Name', 'Global_Sales']
* Filter games released in 2010 and belonging to the racing genre
* Filter games with Global Sales over 10 million units in either Europe or Japan
* filter the vgsales_online_game dataset to find all games with 'Kids' in their title?
* filter the DataFrame to display only the rows where the 'Game_Name' column contains the word 'Women'
* isin():
  filter the dataset to find all games published by 'Inti Creates', 'Takuyo', 'Interchannel-Holon', or 'Rain Games'?
* create a new DataFrame that excludes all rows where the 'Platform' column contains any of the values 'PS', 'PS2', 'PS3', or 'PS4'
## pivot_table()
* create a pivot table that shows the sum of global sales for each genre across different years?
## groupby()
* group the dataset by both game name and year, and then calculate the maximum total sales ratio and minimum global sales for each game in each year?
* group the dataset by game name and platform, and then calculate the maximum, minimum, mean, and total North American sales for each combination?
## idxmax()
* find the game with the highest maximum total sales ratio in the dataset?
* find the game with the lowest minimum total sales ratio in the dataset?
## cut()
* categorize global sales into different ranks such as 'low', 'medium', 'high', and 'very high' based on specific sales ranges?
