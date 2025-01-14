# Hotel booking Data Exploration

In this repository, we intend to extract data from the mentioned dataset and display everything that seems interesting.

If you want to know about used dateset <a href="#about_ds">Click Here!</a>

also you can watch the plots <a href="#plots">Here!</a>

and these are our steps in this __Data Extraction__:

1. Importing modules like pandas, matplotlib and numpy.
2. Reading the dataset as DataFrame object.
3. Getting the information about our DataFrame.
4. Finding missing value percentage in DataFrame. 
5. Deleting the unuseable column and data.
6. management the of outliers.
7. Management the Data and extraction new data from old data.
8. Drawing diagrams of the problem.


<h2 id="plots">Plots:</a>

---

<img src='plots/lead_time_bin.png' width=80%>

<img src='plots/Percentage_of_Arrival_Date_Month_for_Family_0.png' width=80%>

<img src='plots/Percentage_of_Arrival_Date_Month_for_Family_1.png' width=80%>

<img src='plots/Percentage_of_Cancellations_for_City_Hotel.png' width=80%>

<img src='plots/Percentage_of_Cancellations_for_Resort_Hotel.png' width=80%>




<h2 id="about_ds">About Dataset</h2>

---

Since the original dataset was a real hotel dataset, of real customers, all the elements pertaining hotel or costumer identification were deleted.

All the values of the columns: 'name', 'email', 'phone number' and 'credit_card' have been artificially created using a python and filled into the dataset.

Column Descriptions for Hotel Booking Dataset

This dataset contains information on hotel bookings, encompassing details about guests, their reservations, and hotel attributes. It's a valuable resource for analysing and predicting trends in the hospitality industry.

+ ***hotel:*** The type of hotel, either "City Hotel" or "Resort Hotel."

+ ***is_canceled:*** Binary value indicating whether the booking was cancelled (1) or not (0).

+ ***lead_time:*** Number of days between booking and arrival.

+ ***arrival_date_year:*** Year of arrival date.

+ ***arrival_date_month:*** Month of arrival date.

+ ***arrival_date_week_number:*** Week number of arrival date.

+ ***arrival_date_day_of_month:*** Day of the month of arrival date.

+ ***stays_in_weekend_nights:*** Number of weekend nights (Saturday or Sunday) the guest stays.

+ ***stays_in_week_nights:*** Number of weekday nights (Monday to Friday) the guest stays.

+ ***adults:*** Number of adults.

+ ***children:*** Number of children.

+ ***babies:*** Number of babies.

+ ***meal:*** Type of meal booked.

+ ***country:*** Country of origin.

+ ***market_segment:*** Market segment designation.

+ ***distribution_channel:*** Booking distribution channel.

+ ***is_repeated_guest:*** Binary value indicating whether the guest is a repeated guest (1) or not (0).

+ ***previous_cancellations:*** Number of previous booking cancellations.

+ ***previous_bookings_not_canceled:*** Number of previous bookings not cancelled.

+ ***reserved_room_type:*** Code of room type reserved.

+ ***assigned_room_type:*** Code of room type assigned at check-in.

+ ***booking_changes:*** Number of changes/amendments made to the booking.

+ ***deposit_type:*** Type of deposit made.

+ ***agent:*** ID of the travel agency.

+ ***company:*** ID of the company.

+ ***days_in_waiting_list:*** Number of days in the waiting list before booking.

+ ***customer_type:*** Type of booking.

+ ***adr:*** Average daily rate.

+ ***required_car_parking_spaces:*** Number of car parking spaces required.

+ ***total_of_special_requests:*** Number of special requests made.

+ ***reservation_status:*** Reservation last status.

+ ***reservation_status_date:*** Date of the last status.

Explore this dataset to gain insights into booking trends, cancellations, and guest behaviour in the hotel industry.