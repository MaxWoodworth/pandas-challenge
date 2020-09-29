# Imports Dependicies
Declare and Read CSV File (display head to makesure it worked correctly)
# Player Count
Sort data by 'SN' to drop duplicates then count to get accurate(unique) total number of players.
# Purchasing Analysis
Use count sum and mean funtions then create a DF to display these results to show the # of Items, Purchases as well as Net Income and Average Price
# Gender Demographics
Created a separate table titled demo that just pulled certain columns and dropped duplicates.
used this table to pull gender totals using vlaue counts function and calculate percentages of total.
Created a new DF titled Demographics, rounded to 2 and dropped null values(took me some time to realize not dropping null values was causing me to show all rows with genders at the bottom)
#Purchasing Analysis
Very similar to above Gender Demographics
Used count, mean and sum functions on Price in the original csv but used grouped the data by gender and created a new DF titled Summary_Purchasing to round by 2 and display the summary.
#Age Demographics
Created Bins and a output to mirror the assignment image.
Used cut to divide the bins with age into the age group.
Declared "age" to group by "Age Group" and find unique SNs to calculate the percentage of players by age by dividing the earlier established count function.
Finally created a new DF to dsiplay this summary data and clean it to display percentage as percent and round by 2.
# Purchasing Age
Used "age" from above to continue to use the Bin Index
Then simply used count, mean, and sum functions to find values and divided price by members from above to return the average purchase total by person.
Created a new DataFrame to display the information.
# Top Spenders 
Grouped by SN again to use functions on the Price column to find the desired outputs for the top spenders.
Created a new DF to display the top spenders.
# Most Popular Items
Declared id to group the original CSV by Item ID
Created names to group by Item ID and Item Name and make sure they are unique and made them strings.
Used count and Sum to find total purchase values based on the number of times the Item was counted.
Created a new DF to display in ascending=false i.e. DESCENDING value.
# Most Profitable Items
Set a new name equal to the previus dataframe to change the value sort by Total Purchase and again used the ascending=false to dsiplay the same data in descending order by the new paramater.

#Issues
The one specific Issue I had then I never really resolved was with formating. I had issues formating in the $ sign for a few DF's. I noticed that when I did this at times it would completely change the values and outputs. I belive this is because some of my vlaue types were not correctly set.
