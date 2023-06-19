# Hotel-Reservation-Prediction
## Context
It is important for hotels to be able to predict customer cancellations to optimize their operations and revenue management. By accurately forecasting cancellations, hotels can adjust their inventory, allocate resources efficiently, and offer vacant rooms to potential guests, reducing revenue loss and maximizing occupancy rates. Additionally, predictive cancellation models can help hotels improve customer satisfaction by proactively managing reservations and providing alternative options in case of cancellations, ensuring a seamless experience for all guests.

The dataset contains 36,275 instances and 19 attributes, of which 14 are quantitative input variables, 4 are qualitative input variables, and 1 qualitative output variable. Furthermore, the dataset contains no missing values and is in raw form.

## Content
The feature set includes:
* Booking_ID: Unique identifier of each booking.
* no_of_adults: Number of adults.
* no_of_children: Number of children.
* no_of_weekend_nights: Number of weekend nights - Saturday or Sunday.
* no_of_week_nights: Number of week nights - Monday to Friday.
* type_of_meal_plane: Type of meal plan booked by the customer.
* required_car_parking_space: Does the customer require a car parking space? - 0: No, 1: Yes.
* room_type_reserved: Type of room reserved by the customer.
* lead_time: Number of days between the date of booking and the arrival date.
* arrival_year: Year of arrival date.
* arrival_month: Month of arrival date.
* arrival_date: Date of the month.
* market_segment_type: Market segment designation.
* repeated_guest: Is the customer a repeated guest? - 0: No, 1: Yes.
* no_of_previous_cancellations: Number of previous bookings that were canceled by the customer prior to the current booking.
* no_of_previous_bookings_not_canceled: Number of previous bookings not canceled by the customer prior to the current booking.
* avg_price_per_room: Average price per day of the reservation, in euros; prices of the rooms are dynamic.
* no_of_special_requests: Total number of special requests made by the customer (e.g. high floor, view from the room, etc).
* booking_status: Flag indicating if the booking was canceled or not.
