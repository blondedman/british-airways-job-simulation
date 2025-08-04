# British Airways Job Simulation
this repository contains a Jupyter Notebook that performs exploratory data analysis, feature engineering, and classification modeling to predict whether a customer will complete a flight booking

---

## 📂 DATASET

the dataset used is `customer-booking.csv` and contains various features related to flight bookings, including:

- `num_passengers`: number of passengers
- `sales_channel`: booking channel (e.g., online, travel agent)
- `trip_type`: type of trip (round trip, one way, etc.)
- `purchase_lead`: days between booking and travel
- `length_of_stay`: days at destination
- `flight_hour`, `flight_day`: time of flight
- `route`: route of the flight
- `booking_origin`: booking country
- `wants_extra_baggage`, `wants_preferred_seat`, `wants_in_flight_meals`: optional services selected
- `flight_duration`: flight time in hours
- `booking_complete`: target variable
