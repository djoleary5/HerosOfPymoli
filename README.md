# heroes_of_pymoli

The task is to analyze data from an independent gaming company's most recent fantasy game, Heroes of Pymoli. Like many others in its genre, the game is free-to-play, but players are encouraged to purchase optional items that enhance their playing experience. The company would like you to generate a report that breaks down the game's purchasing data into meaningful insights.

## Data
A set of poll data called [purchase_data.csv](election_results/Resources/purchase_data.csv), which is composed of seven columns: `Purchase ID`, `SN`, `Age`, `Gender`, `Item ID`, `Item Name`, and `Price`.

## Steps Taken
* Calculated the total number of players. `There are 576 unique players.`
* Calculated the number of unique items, average purchase price, total number of purchases, and total revenue then organized them into a dataframe `totals`.
* Created a dataframe of gender demographic data `genderCount` that includes percentage and count of male, female, and other/non-disclosed players who made in-game purchases.
* Created a dataframe `genAn` of purchasing analysis broken down by gender that includes the purchase count, average purchase price, total purchase value and average purchase total per person.

