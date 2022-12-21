# Hotel Booking Demand

This dataset consists of booking data from a city hotel and a resort hotel. It includes many details about the bookings, including room specifications, the length of stay, the time between the booking and the stay, whether the booking was canceled, and how the booking was made. The data was gathered between July 2015 and August 2017.

## Data Dictionary

_For binary variables: `1` = true and `0` = false._

| Column                                                                                 | Explanation                                                                                                                                                                       |
| -------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| is_canceled                                                                            | Binary variable indicating whether a booking was canceled                                                                                                                         |
| lead time                                                                              | Number of days between booking date and arrival date                                                                                                                              |
| arrival_date_week_number, arrival_date_day_of_month, arrival_date_month                | Week number, day date, and month number of arrival date                                                                                                                           |
| stays_in_weekend_nights, stays_in_week_nights                                          | Number of weekend nights (Saturday and Sunday) and weeknights (Monday to Friday) the customer booked                                                                              |
| adults, children, babies                                                               | Number of adults, children, babies booked for the stay                                                                                                                            | 
| is_repeated_guest                                                                      | Binary variable indicating whether the customer was a repeat guest                                                                                                                |                
| previous_cancellations                                                                 | Number of prior bookings that were canceled by the customer                                                                                                                       | 
| previous_bookings_not_canceled                                                         | Number of prior bookings that were not canceled by the customer                                                                                                                   |
| required_car_parking_spaces                                                            | Number of parking spaces requested by the customer                                                                                                                                |
| total_of_special_requests                                                              | Number of special requests made by the customer                                                                                                                                   |
| avg_daily_rate                                                                         | Average daily rate, as defined by dividing the sum of all lodging transactions by the total number of staying nights                                                              |
| booked_by_company                                                                      | Binary variable indicating whether a company booked the booking                                                                                                                   |
| booked_by_agent                                                                        | Binary variable indicating whether an agent booked the booking                                                                                                                    | 
| hotel_City                                                                             | Binary variable indicating whether the booked hotel is a "City Hotel"                                                                                                             |
| hotel_Resort                                                                           | Binary variable indicating whether the booked hotel is a "Resort Hotel"                                                                                                           |
| meal_BB                                                                                | Binary variable indicating whether a bed & breakfast meal was booked                                                                                                              |
| meal_HB                                                                                | Binary variable indicating whether a half board meal was booked                                                                                                                   |
| meal_FB                                                                                | Binary variable indicating whether a full board meal was booked                                                                                                                   |
| meal_No_meal                                                                           | Binary variable indicating whether there was no meal package booked                                                                                                               |
| market_segment_Aviation, market_segment_Complementary, market_segment_Corporate, market_segment_Direct, market_segment_Groups, market_segment_Offline_TA_TO, market_segment_Online_TA, market_segment_Undefined | Indicates market segment designation with a value of `1`. "TA"= travel agent, "TO"= tour operators |
| distribution_channel_Corporate, distribution_channel_Direct, distribution_channel_GDS, distribution_channel_TA_TO, distribution_channel_Undefined | Indicates booking distribution channel with a value of `1`. "TA"= travel agent, "TO"= tour operators, "GDS" = Global Distribution System |
| reserved_room_type_A, reserved_room_type_B, reserved_room_type_C, reserved_room_type_D, reserved_room_type_E, reserved_room_type_F, reserved_room_type_G, reserved_room_type_H, reserved_room_type_L | Indicates code of room type reserved with a value of `1`. Code is presented instead of designation for anonymity reasons |
| deposit_type_No_Deposit                                                                | Binary variable indicating whether a deposit was made                                                                                                                             |
| deposit_type_Non_Refund                                                                | Binary variable indicating whether a deposit was made in the value of the total stay cost                                                                                         |
| deposit_type_Refundable                                                                | Binary variable indicating whether a deposit was made with a value under the total stay cost                                                                                      |
| customer_type_Contract                                                                 | Binary variable indicating whether the booking has an allotment or other type of contract associated to it                                                                        |
| customer_type_Group                                                                    | Binary variable indicating whether the booking is associated to a group                                                                                                           |
| customer_type_Transient                                                                | Binary variable indicating whether the booking is not part of a group or contract, and is not associated to other transient booking                                               |
| customer_type_Transient-Party                                                          | Binary variable indicating whether the booking is transient, but is associated to at least another transient booking                                                              |




[Source](https://www.kaggle.com/jessemostipak/hotel-booking-demand/) and [license](https://creativecommons.org/licenses/by/4.0/) of data. The data is originally from an article called [Hotel booking demand datasets](https://www.sciencedirect.com/science/article/pii/S2352340918315191) by Nuno Antonio, Ana de Almeida, and Luis Nunes. It was cleaned by Thomas Mock and Antoine Bichat for [#TidyTuesday during the week of February 11th, 2020](https://github.com/rfordatascience/tidytuesday/blob/master/data/2020/2020-02-11/readme.md).

----------------------

## Don't know where to start?

**Challenges are brief tasks designed to help you practice specific skills:**

- 🗺️ **Explore**: Which family sizes are associated with the highest cancellation rate?
- 📊 **Visualize**: Create a plot that visualizes the cancellation rates of different times of the year.
- 🔎 **Analyze**: Are bookings with longer lead times more likely to result in a cancellation?

**Scenarios are broader questions to help you develop an end-to-end project for your portfolio:**

A chain of hotels has just hired you as a data analyst. They have noticed that the cancellation rate has risen in the past few years. This often leads to rooms that are left unrented for multiple days at a time.

Hotel management is interested in developing a model to predict the likelihood that a customer will cancel their reservation. If successful, this could be used to optimize their booking service and anticipate when cancellations will occur.

You will need to prepare a report that is accessible to a broad audience. It should outline your motivation, steps, findings, and conclusions.