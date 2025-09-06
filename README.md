# Global-Real-Time-Weather-Data-Collection-using-Web-Scraping

This project demonstrates how to fetch **real-time weather data** from multiple global cities using the [WeatherAPI](https://www.weatherapi.com/) service.  
The data is collected through a Python script, processed, and stored in a structured format (CSV), making it useful for analysis, visualization, and further applications such as weather dashboards or predictive models.

---

## 📌 Project Description

Monitoring weather across cities in real-time is crucial for decision-making in areas like **agriculture, transportation, health, and disaster management**.  
This project automates weather data collection by connecting to the WeatherAPI service, retrieving information such as:

- 🌡️ Temperature (°C & °F)  
- ☁️ Weather condition (Sunny, Clear, Cloudy, etc.)  
- 💧 Humidity (%)  
- 🌬️ Wind speed (kph)  
- 📊 Pressure (mb)  
- 🤔 Feels-like temperature (°C)  

The collected data is then **exported into a CSV file**, which can be easily reused for analytics and visualization.

---

## 🎯 Aims of the Project

1. Automate fetching of real-time weather data across multiple cities.  
2. Extract and organize key weather attributes for each city.  
3. Save the data in a **CSV format** for accessibility and further analysis.  
4. Build a reusable script that can be scaled to more cities or integrated with real-time dashboards.  

---

## 🛠️ Tools and Libraries Used

- **Python 3.x**  
- `requests` → for API calls  
- `csv` → for data export  
- `pandas` → for formatting and CSV handling  
- `datetime` → for timestamping  

---

## 🔑 Getting the WeatherAPI Key

1. Visit [WeatherAPI official site](https://www.weatherapi.com/).  
2. Sign up for a **free account**.  
3. After signing in, navigate to the **API section**.  
4. Copy your **unique API key**.  
5. Replace it in the project code:  

```python
API_KEY = "your_api_key_here"

```
---


## 🚀 How to Run the Project
### 1. Clone the Repository

```bash
git clone https://github.com/your-username/weather-data-fetcher.git
cd weather-data-fetcher
```


---

### 2. Install Dependencies
```bash
pip install requests pandas
```

---

### 3. Configure Cities
In the script, update the list of cities you want to fetch weather data for:

```python
cities = ["London", "New York", "Tokyo", "Sydney", "Paris", "Mumbai", "Lagos", "Cairo", "Moscow", "Toronto"]
```

---
### 4. Run the Script
```bash
python weather_fetcher.py
```
---

### 5. Output

- Data is saved into a timestamped CSV file.

- Sample preview of CSV output:
- 
![CSV Output Preview](https://github.com/Uzo-Hill/Global-Real-Time-Weather-Data-Collection-using-Web-Scraping/blob/main/DataFrame.PNG)





![CSV Output Preview](https://github.com/Uzo-Hill/Global-Real-Time-Weather-Data-Collection-using-Web-Scraping/blob/main/csv.PNG)

---



## 📊 Results
- Real-time data from 10 global cities successfully fetched.

- Data saved in CSV format for future use.

- Can be visualized with tools like Excel, Power BI, or Python (matplotlib, seaborn).

---


## ✅ Summary and Importance

This project showcases a practical web scraping + API integration pipeline for weather data.

Importance:

- Provides real-time insights into global weather conditions.

- Can support climate monitoring, disaster preparedness, and urban planning.

- Serves as a foundation for predictive modeling in meteorology.

- Can be extended into dashboards or mobile apps for continuous monitoring.





