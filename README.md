# Airbnb Listings Bangkok Data Analysis
# Background and Problem Statement

**Background**

Airbnb has emerged as one of the most popular accommodation rental platforms worldwide, including in Bangkok, Thailand. This city is renowned as an attractive tourist destination, featuring a variety of attractions, a rich cultural heritage, and a vibrant nightlife. With the increasing number of travelers seeking alternative accommodations, many property owners in Bangkok have begun to utilize the Airbnb platform to rent out their spaces, whether they be apartments, houses, or private rooms. However, with the abundance of options available, competition among hosts has intensified. Consequently, property owners need to understand the factors that influence rental prices across different neighborhoods and room types, making accurate pricing essential for attracting guests and maximizing revenue.

**Problem Statement**

Despite the fact that many property owners in Bangkok have registered on Airbnb, there remains a gap in their understanding of how rental prices are affected by location and room type. The primary question that arises is: 

**"How does the relationship between pricing in various neighborhoods and room types assist hosts in optimizing their listings and pricing strategies?"** 

This problem statement encompasses several key aspects, such as the variation in prices across different neighborhoods that can influence demand and rental rates, as well as the types of rooms offered that contribute to pricing. By comprehending the relationship between location, room type, and pricing, property owners can develop more effective pricing strategies that not only attract more guests but also enhance revenue. This research aims to provide valuable insights for property owners in Bangkok to optimize their listings and improve their competitiveness in the Airbnb market.

# Data Information

Airbnb Listings Bangkok Data Dictionary:
- id = Airbnb's unique identifier for the listing.
- name = Name of the listing.
- host_id = Airbnb's unique identifier for the host/user.
- host_name = Name of the host. Usually, just the first name(s).
- neighborhood = geocoded using the latitude and longitude against neighborhoods.
- latitude = Uses the World Geodetic System (WGS84) projection.
- longitude = Uses the World Geodetic System (WGS84) projection.
- room_type = Four types of room; Entire home/apt, Private room, Shared room, Hotel.
- price = Daily price in local currency.
- minimum_nights = The minimum number of night stays for the listing.
- number_of_reviews = The number of reviews the listing has.
- last_review = The date of the last/newest review.
- calculated_host_listings_count = The number of listings the host has in the current scrape in the city/region geography.
- availability_365 = The calendar determines the availability of the listing x days in the future. Note a listing may be available because it has been booked by a guest or blocked by the host.
- number_of_reviews_ltm = The number of reviews the listing has (in the last 12 months).
