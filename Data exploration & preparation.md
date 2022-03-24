# **Data Exploration & Preparation**

### Content
1. Data exploration

   1.1 Raw data

   1.2 Definition of variables

2. Data preparation


## **Data Exploration**
#### 1.1 Raw data

The original dataset (listings.csv.gz) contains 5556 observations, representing all of Amsterdam's detailed listings. In Amsterdam, there are a total of 22 separate neighborhoods. The graphs below show the various neighborhoods and the frequency with which each occurs in absolute values.

<img width="600" alt="image" src="https://user-images.githubusercontent.com/98963939/159903792-a1dc1c3b-33ac-4612-b588-0a1b37010de7.png">

#### Missing values

The variable "neighbourhood_cleansed" contains no NA's (= missing values). 

#### 1.2 Definition of variables

Neighbourhood_cleansed: the neighbourhood where the specific listings from Amsterdam are established, such as 'Slotervaart' or 'Centrum-Oost'. In total, there are 22 neighbourhoods that exist in Amsterdam.

Price: the actual price of the listing that is paid by the customer for the specific date he/she booked the listing.

Date: the actual date for which the customer has booked the listing (only from 12/20 until 12/21 is included in this dataset).

## **Data Preparation**

In the data exploration, it was found that the prices of the listings had a '$' sign in it. This sign had to be removed before it was possible to filter all the data. Moreover, the NA's of the variable 'price' had to be removed as well. After removing the NA's it was possible to calculate the mean prices of the listings of the dataset.

Furthermore, a new dataset was created with only the variables that were needed: id, data, price, neighbourhood_cleansed. 

