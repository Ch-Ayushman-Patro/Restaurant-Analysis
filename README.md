# Restaurant Analysis

## Project Overview
This project involves an exploratory data analysis (EDA) of a restaurant dataset aimed at understanding various aspects such as cuisine popularity, restaurant ratings, city-wise restaurant distribution, price ranges, online delivery availability and restaurant chains’ performance.

---

## Dataset Description
The dataset contains information on 9551 restaurants with the following columns:
- Restaurant ID
- Restaurant Name
- Country Code
- City
- Address
- Locality
- Locality Verbose
- Longitude
- Latitude
- Cuisines
- Average Cost for two
- Currency
- Has Table booking
- Has Online delivery
- Is delivering now
- Switch to order menu
- Price range
- Aggregate rating
- Rating color
- Rating text
- Votes

There are 21 columns including location, pricing, rating, and service information.

---

## Key Insights

### Cuisine Analysis
- The top three most common cuisines are:
  - North Indian (9.8%)
  - North Indian, Chinese (5.35%)
  - Chinese (3.7%)
- The dataset contains 1825 unique cuisine combinations.
- Certain cuisines like *World Cuisine* and *Vegetarian* tend to have higher average ratings.

### City and Ratings
- The city with the highest number of restaurants is **New Delhi**.
- The city with the highest average restaurant rating is **Inner City**.
- Average aggregate ratings vary significantly across cities.

### Pricing
- Price range distribution among restaurants:
  - Range 1: 46.53%
  - Range 2: 32.59%
  - Range 3: 14.74%
  - Range 4: 6.14%
- Visualization of price ranges shows that most restaurants fall into the lower price categories.

### Online Delivery & Ratings
- About 25.66% of restaurants offer online delivery.
- Restaurants with online delivery have a higher average rating (3.25) compared to those without (2.46).

### Ratings & Popularity
- The average number of votes per restaurant is approximately 157.
- Higher rated restaurants tend to receive more votes.

### Restaurant Chains
- Chains like Cafe Coffee Day, Domino's Pizza, Subway, Green Chick Chop and McDonald's are present in multiple locations.
- Detailed analysis of chains shows variation in their average ratings and total votes received.

---

## Visualizations

- Histogram of price range distribution.
- Bar plots showing city-wise average ratings.
- Scatter plots of restaurant locations based on longitude and latitude.
- Interactive geo plot of restaurant distribution.

---

## Tools and Libraries Used
- Python with pandas, numpy for data manipulation
- seaborn and matplotlib for visualization
- plotly.express for interactive maps

---

## How to Use This Repository
1. Load the dataset `'Restaurant Dataset.csv'`.
2. Run the notebooks or scripts to reproduce the analysis.
3. Review visualizations for insights on price ranges, cuisine popularity and restaurant distribution.
4. Use grouped statistics to understand restaurant ratings by city and cuisine.

---

## Next Steps
- Further analysis on the impact of online delivery on restaurant popularity.
- Sentiment analysis of customer reviews if available.
- Expanding the study to include temporal trends in restaurant ratings.

---

## Dataset Information
| Attribute                 | Description                    |
|---------------------------|--------------------------------|
| Restaurant ID             | Unique identifier for each restaurant |
| Restaurant Name           | Name of the restaurant          |
| Country Code              | Numerical code for country      |
| City                      | City where restaurant is located|
| Address                   | Physical address                |
| Locality & Locality Verbose| Neighborhood details            |
| Longitude & Latitude      | Geographical coordinates        |
| Cuisines                  | Types of cuisines offered       |
| Average Cost for two      | Average cost for two people     |
| Currency                  | Currency code                  |
| Has Table booking         | Availability of table booking   |
| Has Online delivery       | Online delivery service availability |
| Is delivering now         | Currently delivering status     |
| Switch to order menu      | Online order menu availability  |
| Price range               | Price category (1-4)            |
| Aggregate rating          | Average rating score            |
| Rating color & text       | Visual indicator of rating quality |
| Votes                     | Number of votes                 |

---

## Contact
For questions or suggestions, please reach out to me on [LinkedIn](https://www.linkedin.com/in/ch-ayushman-patro).

