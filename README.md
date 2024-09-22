# 🏡 Exploratory Data Analysis about AirBnB in Seville (Spain)
Welcome to the Exploratory Data Analysis (EDA) project for the accommodation company.
This project aims to perform an EDA to understand the data better and extract meaningful insights. The analysis will help in identifying patterns, trends, and anomalies in the dataset.

## 📊 Data Description
The dataset contains information about advertisements for accommodations. The key features include:
- **'id'**: Airbnb's unique identifier for the listing;
- **'name'**: Name of the listing;
- **'host_id'**: Airbnb's unique identifier for the host/user;
- **'host_name'**: Name of the host. Usually just the first name(s);
- **'neighbourhood_group'**: This column does not contain any valid/reported values;
- **'neighbourhood'**: Name of the neighborhood where the property is located;
- **'latitude'**: Property latitude coordinate using the World Geodetic System (WGS84) projection;
- **'longitude'**: Property longitude coordinate using the World Geodetic System (WGS84) projection;
- **'room_type'**: Informs the type of room/rental type offered by the host;
- **'price'**: Daily price in local currency. NOTE: the $ sign is a technical artifact of the export, please ignore it;
- **'minimum_nights'**: Minimum number of night stay for the listing (calendar rules may be different);
- **'number_of_reviews'**: The number of reviews the listing has;
- **'last_review'**: The date of the last/newest review;
- **'reviews_per_month'**: The average number of reviews per month the listing has over the lifetime of the listing;
- **'calculated_host_listings_count'**: The number of listings the host has in the current scrape, in the city/region geography;
- **'availability_365'**: The availability of the listing 365 days in the future as determined by the calendar. Note a listing may not be available because it has been booked by a guest or blocked by the host;
- **'number_of_reviews_ltm'**: The number of reviews the listing has (in the last 12 months);
- **'license'**: The licence/permit/registration number.

## 🚀 Usage
jupyter notebook EDA_accommodation.ipynb

## 🔍 Data Source
In this analysis regarding the hosting service of AirBnB in Seville (Spain), data related to the advertisements were obtained from the
[Inside Airbnb - Sevilla](https://insideairbnb.com/sevilla/)
