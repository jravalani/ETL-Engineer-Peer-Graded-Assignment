# ETL-Engineer-Peer-Graded-Assignment
A basic ETL program
It inlcudes the following
- Extrating the rate of GBP from exchange_rates.csv
- Transforming the given rate of a .csv file from USD to GBP and rounding off the data to 3 decimal places
- Loading it into another .csv file

For some reason glob.glob("*.json") was giving me trailing data error so instead of using that i directly passed the two files
