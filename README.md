**Project Overview**
This project aims to help individuals compare cities based on their accessibility and popularity, assisting in decisions like job relocations. Using data-driven analysis, the project calculates a popularity score for cities by evaluating the proximity and type of venues in neighborhoods. The methodology was applied to New York City and Toronto as a case study.

**Features**
Comparative analysis of city neighborhoods based on venue data.
Popularity score calculated using proximity, venue type, and clustering methods.
Visual representation of venues using Folium maps.
Data-driven recommendations for choosing between cities based on the score.
Methodology

**Data Extraction and Cleaning:**
Fetched location data for New York City and Toronto using the Geopy library.
Retrieved venue information using Foursquare APIs.
Cleaned and transformed the data into structured pandas DataFrames.

**Exploratory Data Analysis:**
Categorized venues into four buckets: Scenic, Parks, Entertainment, and Necessities.
Assigned scores to venue categories and normalized them by their distance from the city center.
Visualized venue distribution and clustering with Folium maps.

**Modeling:**
Used the KMeans algorithm to cluster venues based on proximity.
Calculated a normalized popularity score for each city.

**Evaluation:**
New York City scored 135.9, while Toronto scored 125.7, showing New York City as more popular by 10%.
Results were visualized with clustered maps and data tables.

**Tools and Technologies**
**Programming Languages:** Python
**APIs:** Foursquare
**Libraries:**
Data Processing: pandas, numpy
Geolocation: geopy
Visualization: folium, matplotlib
Clustering: scikit-learn

**Results**
New York City was found to have more accessible and higher-scoring venues than Toronto.
Insights can guide decision-making for relocation based on city amenities.

**Future Scope**
Expand the methodology to include more cities worldwide.
Integrate additional factors, such as cost of living and salary, for a comprehensive analysis.
Refine scoring and weighting methods for more accurate results.
