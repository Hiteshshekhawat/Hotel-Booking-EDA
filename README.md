# HOTEL BOOKING ANALYSIS

We are going to analyze HOTEL BOOKING DATA to find out
valuable insights to increase the revenue of hotels. This dataset contains real-world data on city hotels as well as resort hotels from 2015 to 2017.

#### Programming Language: python
#### Libraries used: numpy, pandas, matplotlib, seaborn
#### Notebook: google colab
#### Data source: Almabetter themselves

## OBJECTIVE

The main objective of this study is to perform the EDA of a given hotel booking dataset and draw useful conclusions about the trends in hotel booking and how the factor control hotel booking.
## DATASET

Dataset link: https://drive.google.com/file/d/1C9AxF9fcVzMw0Bgs0NaRrNML2WwX1Ehm/view?usp=sharing

Total number of rows in data: 119390

Total number of columns: 32

## DATA CLEANING

(1) Handling Null Values

    Null values in columns children and agent were replaced by 0.

    Null values in column country were replaced by 'others'.

    Dropping the company columns

    Dropping all 166 rows in which the addition of adults, children, and babies is 0. That simply means no bookings were made.


(2) Removing duplicated values

    Removing/ dropping all duplicated values in the dataset

(3) creating new columns

    Creating a new column Total_stay by adding stays_in_weekend_nights+stays_in_week_nights.

    Creating a new column Total_people by adding adults+children+babies.

    
## Exploratory Data Analysis(EDA)

Performed EDA and tried to answer these questions below:

    1. Which type of hotel is mostly preferred by the guests?

    2. Highest booking made by any agent?

    3. Let's find out the percentage of cancellations of bookings?

    4. The percentage of repeated guests?

    5. Most preferred guest type of food by guests?

    6. Most preferred room by guests?

    7. Which month have the highest number of booking?

    8. Which is the most busiest month?
 
    9. Getting the number of all national and international guests?

    10. Find out the cancellation rate of hotel booking?

    11. Quick analysis for both the hotels for the meal and stay?
  
    12. Parking space in both hotels?

    13. Number of bookings with the country?

    14. Booking of hotels according to the market segment?

    15. Preference of hotel booking by customer type?

Mainly performed using Matplotlib and Seaborn library and the following graph and plots had been used:

Bar Plot.

Count Plot.

Pie Chart.

Line Plot.

Heatmap.
    



## CHALLENGES: 

(1) Lot of duplicate data.

(2) Lot of null values were present in the dataset.

(3) Data type of some Data was in the wrong format.

(4) Which visualization techniques to use was a challenge?
