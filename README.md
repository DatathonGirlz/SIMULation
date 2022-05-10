# SIMULation
### ***Team Members:-***
- Varnika Vasisth (Team Representative)
- Anjali Gupta 
- Tanisha Gupta

### ***Objective:-***
To predict flight delay at the destination airport using open sourced data collected from the Bureau of Transportation Statistics, Govt. of the USA.

This dataset could be used to predict the flight departure/arrival delay for the upcoming years in the month of January.

This dataset has been collected from Kaggle.

**Link to the dataset :- 
https://www.kaggle.com/datasets/divyansh22/flight-delay-prediction**

There are more than 600,000 flights in the month of January itself throughout the United States.

### ***Features Description :-***

1. **DAY_OF_MONTH :**  Day of Month
2. **DAY_OF_WEEK  :**  Day of Week starting from Monday
3. **REPORTING AIRLINE :**  Unique Carrier Code. When the same code has been used by multiple carriers, a numeric suffix is used for earlier users
4. **DOT_ID_REPORTING_AIRLINE :**  An identification number assigned by US DOT to identify a unique airline (carrier)
5. **IATA_REPORTING_AIRLINE :**  Code assigned by IATA and commonly used to identify a carrier. As the same code may have been assigned to different carriers over time, the code is not always unique.
6. **TAIL_NUM :**  The alphabetical prefix of a tail number is indicative of an airplane’s country of origin. All United States-based tail numbers begin with “N,” Canadian planes begin with “C,” German with “D” and so on.
7. **FLIGHT_NUMBER_REPORTING_AIRLINE :**   flights are usually numbered based on their direction of travel. For example, north and eastbound flights are assigned even numbers, while south and westbound flights are numbered odd. Can’t be more than 4 digits. Different flights of different carriers can have the same flight no.
8. **ORIGIN_AIRPORT_ID         :**  Origin Airport, Airport ID. An identification number assigned by US DOT to identify a unique airport
9. **ORIGIN_AIRPORT_SEQ_ID :**  Origin Airport, Airport Sequence ID. An identification number assigned by US DOT to identify a unique airport at a given point of time.
10. **ORIGIN_AIRPORT :**  Origin Airport
11. **ORIGIN_CITY_NAME :** City of origin airport
12. **ORIGIN_STATE :** State code of origin airport
13. **ORIGIN_STATE_FIPS :** FIPS codes are numbers which uniquely identify geographic areas. The number of digits in FIPS codes vary depending on the level of geography. State-level FIPS codes have two digits. (FIPS - Federal Information Processing Standards)
14. **ORIGIN_STATE_NAME :** State of origin airport
15. **ORIGIN_WAC :** Origin airport, world area code
16. **DEST_AIRPORT_ID :**  Destination Airport, Airport ID
17. **DEST_AIRPORT_SEQ_ID :**  Destination Airport, Airport Sequence ID
18. **DEST_AIRPORT :**  Destination Airport
19. **DEST_CITY_NAME :** City of destination airport
20. **DEST_STATE :** State code of destination airport
21. **DEST_STATE_FIPS :** FIPS codes of destination airport
22. **DEST_STATE_NAME :** State of destination airport
23. **DEST_WAC :** Destination airport, world area code
24. **CRS_DEP_TIME :**  (CRS- Computer reservation systems) Scheduled departure time.
25. **DEP_TIME :**  Departure Time (Actual)
26. **DEP_DELAY :** Time difference between scheduled and actual departure time.
27. **DEP_DELAY_MINUTES :** Only the positive time difference between actual and scheduled departure time and rest are marked 0.
28. **DEP_DEL15 :**  Departure Delay Indicator, 15 Minutes or More (1=Yes, 0=No)
29. **DEPARTURE_DELAY_GROUPS :** Groups of 15 minutes, -1= (-15, -1), 0 = (0,15), 1= (16, 20) and so on
30. **DEP_TIME_BLK :**  Departure Time Block, Hourly Intervals
31. **TAXI_OUT :** Duration between actual off block time and actual take off time where actual off block time is the time at which aircraft vacated parking position.
32. **WHEELS_OFF :** Actual take off time
33. **WHEELS_ON :** Actual landing time
34. **TAXI_IN :** Duration between actual landing time and actual in block time where actual in block time is the time of arriving at parking position.
35. **CRS_ARR_TIME :** Scheduled arrival 
36. **ARR_TIME :** Actual arrival Time
37. **ARR_DELAY :** Time difference between scheduled and actual arrival time.
38. **ARR_DELAY_MINUTES :** Only the positive time difference between actual and scheduled arrival time and rest are marked 0.
39. **ARR_DEL15 :**  Arrival Delay Indicator, 15 Minutes or More (1=Yes, 0= No)
40. **ARRIVAL_DELAY_GROUPS :** Groups of 15 minutes, -1= (-15, -1), 0 = (0,15), 1= (16, 20) and so on
41. **ARR_TIME_BLK :** Arrival Time Block, Hourly Intervals
42. **CANCELLED :**  Cancelled Flight Indicator (1=Yes, 0=No)
43. **DIVERTED :**  Diverted Flight Indicator (1=Yes, 0=No)
44. **CRS_ELAPSED_TIME :** Estimated time taken from leaving origin parking position to arriving at destination parking position.
45. **ACTUAL_ELAPSED_TIME :** Actual time taken from leaving origin parking position to arriving at destination parking position.
46. **AIR_TIME :** Time between take off and landing.
47. **DISTANCE :**  Distance Between two Airports (in miles)
48. **CARRIER_DELAY :** Examples of occurrences that may determine carrier delay are: aircraft cleaning, aircraft damage, awaiting the arrival of connecting passengers or crew, baggage, bird strike, cargo loading, catering, computer, outage-carrier equipment, crew legality (pilot or attendant rest), damage by hazardous goods, engineering. (In short any kind of delay caused by airport and the flight)
49. **WEATHER_DELAY :** Any kind of extreme weather disruptions like hurricane, thunder- lightning etc.
50. **NAS_DELAY :** (NAS- National Aviation System) These include delays due to airport operations, non-risky weather conditions, high air traffic volume and air traffic control delays.
51. **SECURITY_DELAY :** Delays due to security checks
52. **LATE_AIRCRAFT_DELAY :** Arrival delay at an airport due to the late arrival of the same aircraft at a previous airport. 
