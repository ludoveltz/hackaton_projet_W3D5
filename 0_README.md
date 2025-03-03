# Foodie Analysis: Popular Dishes Across the Globe

#everything is in the analyse-des-données branch, and that the CSV files we generated are in the dataset folder.


## Project Overview  
Foodie Analysis is a data-driven project that explores global food trends by analyzing popular dishes, ingredient availability, and nutritional values across different cuisines.  

By integrating datasets from public sources, APIs like USDA FoodData, and web-scraped recipes, we provide valuable insights into how cuisine varies by region, what ingredients are most commonly used, and the health implications of different diets.  

## Problem It Solves  
Many global dishes vary in popularity and availability based on regional ingredient access. Additionally, nutritional values differ significantly, affecting public health and food industry decisions.  

This project helps:  
- **Identify food trends** and compare global eating habits.  
- **Assess health scores** of different cuisines.  
- **Predict ingredient demand** based on dish popularity.  

## Features  
- **Global Popularity Ranking**: Lists the most popular dishes per country.  
- **Ingredient Availability Analysis**: Shows which ingredients are locally accessible.  
- **Nutritional Value Assessment**: Provides health scores based on standard dietary recommendations.  
- **Data-Driven Insights**: Helps businesses, nutritionists, and policymakers make informed decisions.  

## How to Run the Project  

### Prerequisites  
- Install Python (3.8+)  
- Install dependencies using pip:  
  ```sh
  pip install -r requirements.txt
  ```  

### Running the Analysis  
1. Clone the repository:  
   ```sh
   git clone https://github.com/your-repo/foodie-analysis.git
   cd foodie-analysis
   ```  
2. Run the main script:  
   ```sh
   python main.py
   ```  
3. View results in the output folder.  

### Expected Output  
- CSV files containing dish rankings, ingredient availability, and health scores.  
- Visualizations comparing cuisines and ingredient usage.  

## Additional Notes  
- Ensure access to API keys if fetching live data.  
- Dataset files should be placed in the `DATASET/` folder before running.  
