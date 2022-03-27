For making the analysis, R was used

First, the listings and calendar AirBNB files from the city of Amsterdam were imported.
Then, the dollar sign was filtered out of the price column so the column could be used in the analysis.

After filtering out the NA variables, the mean price of the whole dataset was calculated (which came out to about €163 (this means that, on average, the price of an AirBnB in Amsterdam was €163))

Then, a table was made to see how many AirBnB's were available per neighbourhood in Amsterdam.
Because the assumption was made that the amount of listings were a sign of popularity we could now see which neighbourhoods were the most popular. 

After making this table, a new dataset was made containing only the price and the neigbourhoods. Then the mean per neighourhood was calculated to see, on average, how expensive a night in the different neighbourhoods was. 

But, ofcourse, we wanted to see if the popularity of certain neighbourhoods increased, or decreased over the year. Because the listings dataset containted the neighbourhoods, AirBnB id, and price we wanted to merge this dataset with the calendar dataset (which dit nog include the neighbourhoods, but did include the price per night and the AirBnB id). 

We changed the name of the column of the calendar dataset to match the listings dataset. Then, we were aible to merge both datasets so we now could also see which neighbourhoods corresponded to the listings and daily prices. 

Because there were a lot of variables in the dataset, we filtered out only the ones we needed (so, for example, adjusted price was filtered out because we only looked at the 'normal' price (also, the adjusted price was almost always the same as the 'normal' price. We also filtered out the availability column, and the min/max nights, because this was not interesting for our analysis.

Then, we went on to filter out every single neighbourhood by making subsets. Then we calculated an average price per day for every neighbourhood.

New datasets were made for each neighbourhoods, with new column names.
The columns were called Price_NeighbourhoodnumberNeighourhoodabbreviation (so, for example: for the10th neighbourhood, which was Gaasperdam-Driemond this meant the column was called Price_10GD)

This meant there were 22 apart datasets containing information, which we needed to merge together. 

After merging all 22 datasets together, we had a nice overview dataset which was called All_Neighbourhoods

Then, we made an example of the plot of only one neighbourhood so that, if needed, we could easily replicate the plot to see the graph of only one neighbourhood. We only needed to change small parts of the code to see it for a different neighbourhood.

Then, a big plot was made to have a graphical representation of the different neighbourhoods and the average change in prices over a year for them.

A correlation matrix between all the neighbourhoods prices was also made, excluding the date column.


A new column was made for a new All_Neighbourhoods_without_date. This column included the total average prices per day.


Then, in order to draw a conclusion, the % change was calculated for every neighbourhood of the beginning of the year compared to the end of the year. To make this calculation a bit more robust, we did not take the first and last day over the course of the year, but instead we took the average price of the first week and the last week, and compared these with each other.
The output and the conclusion can be found in the main file.






