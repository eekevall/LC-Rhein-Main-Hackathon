# LC-Rhein-Main-Hackathon
## GitHub repository for members participating in the March 2023 Deustsche Bahn Bikesharing Data hackathon.

The [original data set](https://github.com/eekevall/LC-Rhein-Main-Hackathon/tree/main/Original_DB_Data) was downloaded from the [Deutsche Bahn website](https://data.deutschebahn.com/dataset/data-call-a-bike.html)

Deutsche Bahn provides historical data for its bike sharing service "Call a Bike" under an open license (Creative Commons Attribution 4.0 International CC BY 4.0.) covering the years 2016/2017.

The detailed data description can be found in the data dictionary [HACKATHON_CATEGORY_CALL_A_BIKE](https://github.com/eekevall/LC-Rhein-Main-Hackathon/blob/main/HACKATHON_CATEGORY_CALL_A_BIKE.pdf) which contains

Vehicle data:
* Manufacturer (e.g. Ford)
* Model (e.g. Fiesta)
* Type (e.g. 1.6 Diesel 70KW NAVI)
* KW
* Fuel type (e.g. diesel)
* fuel capacity
* Designation of the tariff class (without stored prices)
* Accessories, if maintained (e.g. parking sensors)

Station data:
* station name
* city of the station
* country of station

Occupancy numbers:
* start of booking
* end of booking
* Service or customer booking indicator
* Booking duration and availability per vehicle and day calculated in seconds

Allocation plan data:
* Bookings (reservations) are extracted up to 180 days in the future
* Booking duration and availability per vehicle and day are calculated 180 days in the future in seconds

Start and finish position:
* Start and end station is available (no information about the route in between)

Call a Bike dates:
* Bike type (e.g. Panther bike or pedelec Panther bike)
* All the information already mentioned is also available for CaB (except POI to the station).

The scope of data is from 01/01/2014 to the key date 06/09/2016.
