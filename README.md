# 🏡 Airbnb Listings – Exploratory Data Analysis & Visualization with Pandas

This project explores an Airbnb dataset to uncover trends in pricing, availability, guest accommodation, and host performance using Python libraries like Pandas, Matplotlib, and Seaborn. The dataset includes detailed information about listings such as host details, geographic location, pricing, amenities, safety rules, and more.

---

## 📦 Dataset

**Source:** [Kaggle - Airbnb Dataset](https://www.kaggle.com/datasets/ashishjangra27/airbnb-dataset)  
The dataset contains detailed information about Airbnb listings including host details, pricing, availability, amenities, reviews, and other listing attributes.

---

## 🔑 Important Columns Explained

- `id`: Unique identifier for each listing
- `name`: Title of the listing
- `host_name`, `host_id`: Host details
- `address`: Listing's address
- `features`: Features available in the listing (e.g., air conditioning, pool)
- `amenities`: Amenities available at the listing (e.g., Wi-Fi, Kitchen)
- `safety_rules`: Safety rules provided by the listing
- `house_rules`: House rules provided by the listing (note: spelling error corrected in analysis)
- `img_links`: Image links for the listing
- `price`: Price per night in USD
- `country`: Country of the listing
- `bathrooms`: Number of bathrooms in the listing
- `beds`: Number of beds in the listing
- `guests`: Number of guests the listing can accommodate
- `toilets`: Number of toilets in the listing (note: spelling error corrected in analysis)
- `bedrooms`: Number of bedrooms in the listing
- `studios`: Whether the listing is a studio apartment
- `checkin`: Check-in time for the listing
- `checkout`: Check-out time for the listing
- `amenity_count`: Count of amenities available in the listing
- `luxury_flag`: Flag to indicate if the listing is considered "luxury" (price > $500 and amenity_count > 10)
- `city`: Extracted city name from the `address` column for further analysis
- `checkin_hour`: Extracted check-in hour (based on check-in time)
- `checkout_hour`: Extracted check-out hour (based on check-out time)
- `family_friendly`: Flag indicating if the listing is family-friendly (guests >= 4 and beds >= 2)
- `safety_review_flag`: Flag indicating if the listing has missing safety rules and needs review

---

## Tools & Technologies

- **Python**
- **Pandas**, **Matplotlib**, **Seaborn**

---
