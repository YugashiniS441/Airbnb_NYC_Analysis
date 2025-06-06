# Airbnb Listings Analysis

## Project Overview
This project aims to Airbnb listings data to understand how prices, availability, and reviews vary across different neighborhoods. Using Python for data analysis and Power BI for creating easy-to-understand dashboards, the goal is to find useful insights that can help hosts set better prices, guests find good places to stay, and others understand the rental market better.

## Tools & Technologies Used
- Python (Pandas, Matplotlib, Seaborn, WordCloud)  
- Power BI (Interactive dashboards and charts)  
- Jupyter Notebook  
- VS Code  
- CSV (Dataset format)  

## Dataset Description
- **Source:** [Inside Airbnb](https://insideairbnb.com/get-the-data/)  
- **Format:** CSV  

### Files and Rows:
- `listings.csv`: ~37,019 listings  
- `reviews.comments.csv`: ~971,380 reviews  

### Key Columns in listings.csv:
- `id`, `name`, `host_id`, `neighbourhood_group`, `price`, `number_of_reviews`, `availability_365`  
- **Geolocation:** `latitude`, `longitude`  
- **Text fields:** `room_type`  

### Key Columns in reviews.comments.csv:
- `listing_id`, `date`, `reviewer_id`, `comments`  

## Exploratory Data Analysis (Python)
The notebook (`airbnb_preprocessing_and_eda.ipynb`) includes:
- Preprocessing 
- Descriptive statistics  
- WordCloud from reviews  
- Histograms and price distribution  
- Correlation heatmap  

**Saved charts location:**  
`Output/charts/`

## Power BI Dashboard
Interactive visuals built in Power BI include:
-  Geo-mapping of listings  
-  Price comparison by neighborhood  
-  Room type trends  
-  Monthly Listing Trends 
-  Neighborhood Popularity Metrics

**Screenshot:** `Output/Dashboard_Screenshot/Airbnb_Activity_NYC.png`  
**PBIX file:** `Source_Code/PowerBI_Insights/Airbnb_Dashboard.pbix`

## How to Run This Project

1. **Clone the repository** using Git, or **download and unzip** the project folder to your local machine:
   ```bash
   git clone https://github.com/YugashiniS441/Airbnb_NYC_Analysis.git

2. Open the notebook file `airbnb_preprocessing_and_eda.ipynb` using:
   - **VS Code** (with Jupyter extension), or  
   - **Jupyter Notebook**, or  
   - **Google Colab**

3. **Install the required Python libraries** by running:
   ```bash
   pip install -r requirements.txt

4. **To explore the Power BI Dashboard**:
   - Make sure **Power BI Desktop** is installed.
   - Open the file:
     ```
     Source_Code/PowerBI_Insights/Airbnb_Dashboard.pbix
     ```
   - Interact with the visuals to explore insights by neighborhood, price, reviews, and room type.

## Results Summary
   - Manhattan and Brooklyn lead in listings and guest reviews, making them the most active boroughs.
   - Entire homes are the most common room type, while private rooms receive more reviews.
   - Average listing price is $201, with most listings priced under $500.
   - Review activity peaks in May, showing seasonal guest interest.
   - Guest feedback commonly includes “clean”, “great stay”, and “location” as top themes.
   - Map visualizations show Manhattan and Brooklyn as Airbnb hotspots.
