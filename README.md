# Hotel Booking Cancellation Analysis

## Project Overview

This project analyzes hotel booking data to understand customer reservation behavior and identify patterns related to booking cancellations.

The main goal is to explore:
- Cancellation trends
- Differences between Resort Hotels and City Hotels
- Booking patterns using visualizations
- Key factors influencing cancellations
- The analysis is done using Python data analysis libraries and visualization tools.

## Ojectives

- Perform data cleaning and preprocessing
- Convert and handle date-time features
- Analyze cancellation percentage
- Compare cancellation rates by hotel type
- Create insightful visualizations (bar charts, pie charts, etc.)
- Generate business insights from data

## Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Dataset Features (Examples)

hotel → Hotel type (City / Resort)
is_canceled → Booking cancellation status
adr → Average Daily Rate
reservation_status_date → Reservation status date
Other booking-related features

## Project Workflow
### 1️⃣ Data Cleaning

- Handling missing values
- Fixing data types
- Converting date columns using pd.to_datetime()

### 2️⃣ Exploratory Data Analysis (EDA)

- Cancellation percentage analysis
- Hotel-wise reservation comparison
- Distribution analysis of bookings

### 3️⃣ Data Visualization

- Created visualizations such as:
- Count plots
- Pie charts
- Bar charts with labels
- Hotel-wise cancellation comparison

## Sample Insights

- City Hotels show higher cancellation rates compared to Resort Hotels.
- Cancellation trends vary based on booking characteristics.
- Visualization helps clearly identify customer behavior patterns.

## Key Learnings

- GroupBy operations in pandas
- Handling datetime columns
- plot customization with seaborn & matplotlib
- Adding labels to charts using bar_label()
- Data storytelling through visualization

## Future Improvements

- Build interactive dashboard (Power BI / Tableau)
- Apply predictive modeling for cancellation prediction
- Feature engineering for deeper insights
