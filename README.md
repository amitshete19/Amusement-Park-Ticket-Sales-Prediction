# Amusement-Park-Ticket-Sales-Prediction
There is an amusement park in the Wonderland around the year 2068, and the park author- ities are willing to make predictions about the number of purchased tickets. They have an available dataset, which we can use to learn the corresponding models. The dataset contains the following variables as the input features:
– TimeStamp: a variable containing a date and a time specifying the date and the time the experiment was carried out. For instance, you may observe a TimeStamp of “4/18/2068 3:00:00 AM”, which indicates the time the sample was collected. Note that you may also obtain the day of the week, or the season information from this dataset. For instance, if we look up the 2068 calendar (search it on Google), you would see that “4/18/2068” is a Wednesday.
– StandardTemperature: This is a variable that represents the weather temperature in some specific metric system.
– Humidity: This is the percentage of the weather humidity. 1
 
– Wind: This is the wind speed on the day/time of the experiment. The output features (technically the response variables) are:
– Ticket1: The number of tickets for registered park customers (as a multiple of 100, for instance a value of 16 indicates 1600 purchased tickets)
– Ticket2: The number of tickets for unregistered park customers, who are basically general park visitors (as a multiple of 100, for instance a value of 16 indicates 1600 purchased tickets)
