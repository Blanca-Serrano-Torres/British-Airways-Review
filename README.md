# British-Airways-Review - Tableau Visualization Project

## Project Overview
This project is a guided Tableau project aimed at building an interactive dashboard that visualizes British Airways reviews. The dashboard enables users to explore various metrics like overall ratings, food ratings, and entertainment ratings with a few clicks. The goal is to learn to apply key concepts of data visualization providing insightful and user-friendly visualizations for better data understanding.

## Data Sources
There are two main files that are:

· British Airways Reviews: A CSV file containing review metrics such as:
  - Seat comfort
  - Cabin Staff Service
  - Food & beverages
  - Ground service
  - Value for money
  - Entertainment
  - Data, seat type, traveler type, and aircraft details

· Countries Dataset: A CSV file containing data on countries associated with the reviews.

## Main Insights from British Airways reviews 
## 1. Overall Satisfaction 

  - Average Overall Rating: 4.2/5. Passengers are generally satisfied with British Airways services.

## 2. Top-Rated Service

  - Cabin Staff Service Rating: 4.5/5. The airline's cabin crew is highly rated, suggesting excellent customer service.

## 3. Lowest-Rated Service

  - Seat Comfort Rating: 3.6/5. Seat comfort is the weakest area, indicating a common passenger complaint.

## 4. Class-Based Ratings 
  - Economy Class Rating: 3.8/5
  - Business Class Rating: 4.4/5
  - First Class Rating: 4.6/5

Passengers in higher classes are generally more satisfied than economy passengers.

## 5. Regional Differences
  - European Travelers' Rating: 4.1/5
  - North American Travlers'Rating: 3.9/5

European travelers rate British Airways slightly higher than north American travelers.

## 6. Satisfaction Over Time
  - Rating Improvement: 3.9/5 in 2019 to 4.3/5 in 2023. Customer satisfaction has been steadly improving over recent years.

## 7. Traveler Type Insights
  - Solo Travlers'Rating: 4.1/5
  - Family Travelers'Rating: 3.7/5

Families tend to be less satisfied compared to solo travelers.

## 8. Aircraft Ratings
  - Airbus A380 Rating: 4.4/5
  - Boeing 777 Rating: 3.9/5

Some aircraft models, like the Airbus A380, receive higher ratings than others.

## 9. Factors Affecting Ratings 
  - Top Positive Factor: Cabin Staff Service
  - Top Negative Factor: Seat Comfort

## 10. Review Distribution by Region. Most reviews come from European passengers, followed by North American travelers.


## Detailed Functionality
## 1. Interactive filters
The dasboard includes a variety of filters, allowing users to drill down into the data to extract insights based on their preferences:

  - Metric Selection: Users can choose from different metrics such as overall rating, food quality, entertainment, seat comfort, and more. This enables a detailed 
    exploration of specific areas of interest within the reviews.
  
  - Date filter: Allows filtering reviews by date, enabling users to see how ratings and feedback have changed over time. This is particularly useful for analyzing 
    trends and spotting improvements or declines in services during specific periods.
  
  - Seat Type: Filters data by seat class, such as economy, business, or first class. This help users understand the experience differnces across various seating 
    options.
  
  - Traveler Type: The dashboard includes a filter for traveler types, such as solo traveler, families, couples, and business travelers, enabling users to segment 
    feedback and visualize how experiences vary depending on the type of traveler.
  
  - Aircraft Type: This filter lets users refine the data by specific aircraft models, providing insights into whether different airplanes yield different passenger 
    experiences.
  
  - Continent Filter: Users can filter reviews based on the geographic origin of the flights, giving insights into regional experiences with British Airways.

## 2. Dynamic Visuals as Filters
All visuals on the dashboard are interactive and function as filters themselves. For example:

  - Clicking on a bar chart segment showing food ratings automatically updates the entire dashboard to display data only for reviews with that specific food rating.
  - Selecting a region on the map filters reviews from that specific region or country, allowing users to see how experience vary geographically.

This interconnectedness of the visuals creates a seamless exploration experience, making a data discovery intuitive and user-friendly.

## 3. Summary Metrics
At the top of the dashboard, there are summary metrics that provide a high-level view of key data points:

  - Average Overall Rating: Displays the average rating across all reviews, giving users an instant understanding of general satisfaction.
  - Top Positive and Negative Aspects: Highlights common praises (e.g. cabin staff service) and criticisms (e.g. seat comfort) based on the review data.
  - Number of Reviews: Shows the total count of reviews within the selected filters, giving context to the visualizations.

## 4. Detailed Visualizations
The dashboard also offers detailed, focused views on specific aspects of the review data: 

  - Bar Charts: Visualize specific metrics like seat comfort or entertainment, breaking them down by other dimensions (e.g. seat type, traveler type).
  - Line Charts: Show trends over time, helping users identify changes in overall satisfaction or specific aspects of the service over different time periods.
  - Maps: A geographic view of reviews, with data points representing the countries and regions of the passengers, allowing users to analyze feedback by origin.

## 5. Calculated Fields & Parameters
To enhance interactivity and customization, the project uses calculated fields and parameters: 

  - Calculated Fields: These fields allow for more complex metrics to be displayed, such as weighted ratings, comparisions between various seat types, or customer 
   satisfaction indices.
  - Parameters: Users can dynamically between different metrics (e.g. overall rating, food, entertainment) by using parameters, creating a tailored data exploration 
    experience.

## 6. User-Friendly Navigation
The dashboard includes a clean and intuitive interface that facilitates ease of use. Tooltips, labels, and a well-organized layout make it accesible even for those who may not be familiar with Tableau or Data Analysis.

## Steps to Recreate the Project

 1. Connect to Data: Load the provided British Airways reviews and countries CSV files into Tableau.
 2. Set Realtionships: Establish relationships between the two datasets.
 3. Create Dynamic Fields: Use calculated fields and parameters to enable interactive metric selection.
 4. Build Visuals: design visuals, including maps, summary metrics, and interactive charts.
 5. Add Filters: Enable interactive filters to refine the visualization by seat type, travler type, and more.
 6. Format & Style: Customize the look and feel of the dashboard for a professional presentation.

## Customization 

Feel free to add your own customizations! You can modify the visuals, tweak metrics, or even connect additional datasets to expand the insights provided.
  - Tableu Dashboard Link:
  - Data Files:
