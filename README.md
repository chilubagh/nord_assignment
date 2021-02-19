Data Engineer Programming Assignment
We've provided a source file, btc.csv, which contains several years of Bitcoin pricing data.
Please provide a solution which filters and summarises this data. The original pricing is in USD but as a European organisation we'd like to view summaries in Euros.
There are three outputs expected
1. A new file with the past year's data
2. A short summary table to the standard output 3. A line chart of the past year's price
Providing the Solution
You can use any environment for your solution implementation. If in doubt though, the Python tooling is a good choice. Please provide the solution as if this was part of a project you were working on with your team.
Summary File
Please output a new csv file. The summary file should contain the following:
Past year's data
Columns: Date, Volume.
New Columns: Low (EUR) & High (EUR) converted to Euro.
The daily USD to EUR conversion rate can be assumed as 0.87 for this example.
Please note that whenever we mention past year, we mean the past 365 days from the last data point's date in the csv file provided.
Summary Output
Print the following on the standard output:
Min, max and mean for the following metrics in the past year:
    Volume in Billions. 
    Low (EUR)
    High (EUR)
 
Line chart
Plot a line-graph (export as an image file) of the Bitcoin price (Low & High) in the past year.
