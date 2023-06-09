# Flight Data Exploration


<p align="center">
  <img src="https://i.pinimg.com/564x/1f/e2/39/1fe2398e5886acf0407820ffc392274a.jpg" alt="Alt Text">
</p>


`Dataset Description`

The dataset consists of observations of US domestic flights in the year 2013. It contains the following fields:
- Year: The year of the flight (all records are from 2013)
- Month: The month of the flight
- DayofMonth: The day of the month on which the flight departed
- DayOfWeek: The day of the week on which the flight departed - from 1 (Monday) to 7 (Sunday)
- Carrier: The two-letter abbreviation for the airline.
- OriginAirportID: A unique numeric identifier for the departure aiport
- OriginAirportName: The full name of the departure airport
- OriginCity: The departure airport city
- OriginState: The departure airport state
- DestAirportID: A unique numeric identifier for the destination aiport
- CRSDepTime: The scheduled departure time
- DepDelay: The number of minutes departure was delayed (flight that left ahead of schedule have a negative value)
- DelDelay15: A binary indicator that departure was delayed by more than 15 minutes (and therefore considered "late")
- CRSArrTime: The scheduled arrival time
- ArrDelay: The number of minutes arrival was delayed (flight that arrived ahead of schedule have a negative value)
- ArrDelay15: A binary indicator that arrival was delayed by more than 15 minutes (and therefore considered "late")
- Cancelled: A binary indicator that the flight was cancelled




`Examples`

The Jupyter Notebook **flight_data_exploration.ipynb** contains code examples for exploring the dataset. Some of the examples include:
- Descriptive statistics of the dataset
- Histograms and box plots of the numerical variables
- Bar plots and pivot tables of categorical variables




`Acknowledgements`

The dataset used in this repository was obtained from the **Bureau of Transportation Statistics**.
