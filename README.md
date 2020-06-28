# Study on Relationship between New York Taxi Night Rides and Investment Bank Resignation Rates

## Dataset
### New York Taxi Data
Included in the New York yellow taxi data dataset (2012/01/01-2016/06/30) are each taxi trip's pick- up and drop-off times, pick-up and drop-off GPS coordinates, 
distance, passenger count, fare, tip and manner of payment, inter alia. The yellow taxi data was downloaded from the NYC website link below:
https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page

### Job postings data and investment bank locations
Job postings data.csv : We collected recruitment information for these investment banks in New York and counted the number of job postings that the investment bank posted on the recruitment website monthly.
Month column: for example, "12-Jan" means January 2012.

The total number of job postings column: The total number of job postings released by a particular investment bank monthly.

The company column: Name of the investment bank.

Investment bank locations.csv: We identified 16 investment banks in New York (including branches). GPS data comes from Google map, which you can use to locate these investment banks.

### Stock Price Data
This stock price data was collected using Yahoo!Finance's API. However, not all the data for UBS is available on Yahoo!Finance, so additional data was collected and kept in "UBSG_historical_price.csv".
