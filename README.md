# API-INTEGRATION-AND-DATA-VISUALIZATION

**Company:** Code Tech IT Solutions  
**Name:** Ayush Patil  
**Intern ID:** CT06DN877  
**Domain:** Python Development  
**Duration:** 6 weeks  
**Mentor:** Neela Santosh  

---

## Weather Data API Integration & Visualization

This project demonstrates how to fetch real-time weather data for multiple cities using the OpenWeatherMap API and visualize the results using Python libraries such as Matplotlib and Seaborn.

### Features

- **API Integration:** Fetches current temperature and humidity for 70 major cities worldwide using latitude and longitude.
- **Data Processing:** Stores weather metrics in a structured list and DataFrame.
- **Data Visualization:** 
  - Horizontal bar charts for temperature and humidity (clear and readable for many cities)
  - Scatter plot for temperature vs. humidity
  - Pie chart for temperature distribution
  - Line plot for sorted temperature trends
  - Heatmap for comparative weather metrics

### Technologies Used

- Python
- Jupyter Notebook
- Requests (for API calls)
- Pandas (for data manipulation)
- Matplotlib & Seaborn (for visualization)

### How It Works

1. **Fetch Data:**  
   The script uses the OpenWeatherMap API to retrieve weather data for each city based on its latitude and longitude.

2. **Process Data:**  
   The temperature and humidity for each city are extracted and stored in a list of dictionaries.

3. **Visualize Data:**  
   Multiple plots are generated to compare and analyze weather metrics across all cities. Special care is taken to ensure city names are readable, even with a large number of cities.

### Usage

1. **Set Up API Key:**  
   Replace `"YOUR_API_KEY"` in the script with your actual OpenWeatherMap API key.

2. **Run the Notebook:**  
   Execute all cells in the Jupyter Notebook to fetch data and generate visualizations.

3. **Explore Visualizations:**  
   - Horizontal bar charts for clear comparison of temperature and humidity.
   - Scatter plot for temperature vs. humidity.
   - Pie chart for temperature distribution.
   - Line plot for sorted temperature trends.
   - Heatmap for a comprehensive view of all metrics.

### Example Visualizations

- ![Temperature Bar Chart Example](example_temp_bar_chart.png)
- ![Humidity Bar Chart Example](example_humidity_bar_chart.png)
- ![Heatmap Example](example_heatmap.png)

### Customization

- **Add/Remove Cities:**  
  Modify the `CITIES` list to include any cities of your choice with their latitude and longitude.
- **Add More Metrics:**  
  Extend the script to fetch and visualize additional weather parameters as needed.

### Credits

- **Intern:** Ayush Patil  
- **Mentor:** Neela Santosh  
- **Company:** Code Tech IT Solutions

---

*This project is part of a 6-week Python Development internship focused on real-world API integration and data visualization.*

