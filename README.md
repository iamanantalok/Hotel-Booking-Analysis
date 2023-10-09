# Hotel-Booking-Analysis
This repository presents an extensive Exploratory Data Analysis (EDA) of hotel reservation data, offering valuable insights and practical knowledge for the hospitality sector and data enthusiasts. Our aim is to unveil trends, patterns, and meaningful observations within hotel reservation data, providing assistance to hotel proprietors, market analysts, and data scientists in making well-informed decisions.



![image](https://github.com/iamanantalok/Hotel-Booking-Analysis/assets/117917485/d6cfd60a-295a-4676-b059-16a17511e337)



Have you ever pondered about the ideal time of the year to make a hotel booking? Or the optimal duration of a stay to secure the most favorable daily rates? Perhaps you've contemplated predicting whether a hotel is likely to receive an unusually high number of special requests? This dataset of hotel reservations can serve as your resource to investigate these inquiries!

This dataset encompasses reservation details for both city and resort hotels, encompassing information such as reservation dates, length of stay, guest demographics, and more. It's worth noting that all personally identifiable information has been meticulously removed from the dataset to safeguard privacy.

## Dataset Information

- Number of instances: 119,390
- Number of attributes: 32

## Features Information

The dataset contains various features, including:

- **hotel**: H1 = Resort Hotel, H2 = City Hotel
- **is_canceled**: 1 if the booking was canceled, 0 if not
- **lead_time**: Number of days between booking and arrival
- **arrival_date_year**: Year of arrival date
- **arrival_date_month**: Month of arrival date
- **arrival_date_week_number**: Week number of arrival date
- **arrival_date_day**: Day of arrival date
- **stays_in_weekend_nights**: Number of weekend nights stayed
- **stays_in_week_nights**: Number of week nights stayed
- **adults**: Number of adults
- **children**: Number of children
- **babies**: Number of babies
- **meal**: Type of meal opted for
- **country**: Country code
- **market_segment**: Customer segment
- **distribution_channel**: Booking distribution channel
- **is_repeated_guest**: 1 if the guest is a repeated guest, 0 if not
- **previous_cancellations**: Number of previous cancellations
- **previous_bookings**: Count of previous bookings
- **reserved_room_type**: Reserved room type
- **assigned_room_type**: Assigned room type
- **booking_changes**: Count of changes made to booking
- **deposit_type**: Type of deposit made
- **agent**: Booking agent
- **days_in_waiting_list**: Number of days in the waiting list
- **customer_type**: Type of customer
- **required_car_parking**: 1 if car parking is required, 0 if not
- **total_of_special_req**: Number of additional special requirements
- **reservation_status**: Reservation status
- **reservation_status_date**: Date of reservation status

## Prerequisites

- Basic understanding of Python and its libraries, including NumPy, Pandas, Matplotlib, and Seaborn.

## Technologies Used

- Integrated Development Environment (IDE): Google Colab

## Project Workflow

1. **Importing Libraries**: We begin by importing the necessary Python libraries.

2. **Loading the Dataset**: The dataset is loaded for analysis.

3. **Data Cleaning**: Data cleaning techniques are applied to ensure data quality.

4. **Handling Outliers**: Any outliers in the dataset are addressed.

5. **Data Visualization**: We use Matplotlib and Seaborn to create visualizations that provide insights into the data.

6. **Conclusion**: We summarize our findings and draw conclusions based on the analysis.

## Conclusion

Our analysis reveals that the maximum number of bookings occur between May and August, suggesting an opportunity for hotels to provide attractive deals during the off-season to increase bookings. Additionally, as there are relatively few repeated guests, hotel management should consider gathering customer feedback and improving facilities to encourage repeat visits.

## Visualizations done on tableau

https://public.tableau.com/views/HotelBookingAnalysis_16936407379790/Dashboard1?:language=en-GB&:display_count=n&:origin=viz_share_link
