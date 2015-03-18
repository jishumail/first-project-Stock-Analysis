# first-project-Stock-Analysis
NYSE Stock Analysis
This is the first project for Hadoop Map Reduce with java. We have to concatenate the files in a sorted way from the mapper so that the 
reducer can process them. The files are the eod data from NYSE. Each line has 7 attributes. 1st, 2nd, and 6th is our field of interest. 
They represent company symbol, date of transaction and closing price.
For each symbol we have to find highest closing price.
Then reducer should emit symbol, highest price and corresponding date.
