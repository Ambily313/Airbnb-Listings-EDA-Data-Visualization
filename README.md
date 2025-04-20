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
- `hourse_rules`: House rules provided by the listing (note: spelling error corrected in analysis)
- `img_links`: Image links for the listing
- `price`: Price per night in USD
- `country`: Country of the listing
- `bathrooms`: Number of bathrooms in the listing
- `beds`: Number of beds in the listing
- `guests`: Number of guests the listing can accommodate
- `toiles`: Number of toilets in the listing (note: spelling error corrected in analysis)
- `bedrooms`: Number of bedrooms in the listing
- `studios`: Whether the listing is a studio apartment
- `checkin`: Check-in time for the listing
- `checkout`: Check-out time for the listing

---

## 🧹 Data Cleaning & Preprocessing

- **Renamed Columns**: Corrected `hourse_rules` to `house_rules` and `toiles` to `toilets`.
- **Dropped Columns**: Removed irrelevant columns such as `Unnamed: 0`.
- **Handling Missing Data**: Replaced missing values in key columns like `reviews` with 0, and handled other missing data appropriately.
- **Data Transformation**: Converted `price` from string to float and handled non-numeric `rating` values.

---

## 📊 Analysis & Insights

### Descriptive Statistics & Exploration

- Analyzed the average price of listings, top-rated listings, and the distribution of pricing by country.
- Investigated the number of listings with ratings above 4.8 and identified the most expensive listings.
- Explored the average number of beds, bathrooms, and guests accommodated by listings.

### Grouping & Aggregation

- Aggregated data by country to find the average price, total number of listings, and average rating.
- Computed the total reviews per host and found the host with the highest number of listings.
- Identified the top 5 countries with the highest average price.

### String & List Parsing

- Parsed the `amenities` column to find how many listings offer Wi-Fi, kitchen, or washer facilities.
- Created new columns like `amenity_count` to track the number of amenities per listing.
- Flagged luxury listings based on price and amenities.

---

## 📈 Visualizations

- Plotted histograms, bar charts, boxplots, and scatterplots to gain insights into the distribution of prices, ratings, and reviews.
- Created pie charts to visualize the distribution of studio vs non-studio listings.

---

## Tools & Technologies

- **Python**
- **Pandas**, **Matplotlib**, **Seaborn**

---

⭐ Star this project if you find it useful!
