# Data Ingestion and Processing- Hive
## Objective
The New York City Taxi & Limousine Commission (TLC) has provided a dataset of trips made by the taxis in the New York City. The detailed trip-level data is more than just a vast list of taxi pickup and drop off coordinates. 
<br> Analysis-I
- Compare the overall average fare per trip for November and December.
- Explore the ‘number of passengers per trip’ - how many trips are made by each level of ‘Passenger_count’? Do most people travel solo or with other people?
- Which is the most preferred mode of payment?
- What is the average tip paid per trip? Compare the average tip with the 25th, 50th and 75th percentiles and comment whether the ‘average tip’ is a representative statistic (of the central tendency) of ‘tip amount paid’. Hint: You may use percentile_approx(DOUBLE col, p): Returns an approximate pth percentile of a numeric column (including floating point types) in the group.
- Explore the ‘Extra’ (charge) variable - what fraction of total trips have an extra charge is levied?
<br> Analysis-II
- What is the correlation between the number of passengers on any given trip, and the tip paid per trip? Do multiple travellers tip more compared to solo travellers? Hint: Use CORR(Col_1, Col_2)
- Segregate the data into five segments of ‘tip paid’: [0-5), [5-10), [10-15) , [15-20) and >=20. Calculate the percentage share of each bucket (i.e. the fraction of trips falling in each bucket).
- Which month has a greater average ‘speed’ - November or December? Note that the variable ‘speed’ will have to be derived from other metrics. Hint: You have columns for distance and time.
- Analyse the average speed of the most happening days of the year, i.e. 31st December (New year’s eve) and 25th December (Christmas) and compare it with the overall average. 
## Steps Followed
- Reading Data
- Cleaning Data
- Creating final table
- Answering all the required question through analysis
## Details of files given
- Data Ingestion and Processing - Assignment.txt : Text file of the commands used in Hive
- yellow_tripdata_2017.zip : Data worked on
- data_dictionary_trip_records_yellow_taxi.pdf : Data Dictionary

