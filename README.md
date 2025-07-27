
# 🌦️ Real Estate Ranking by Weather & Disasters

This project analyzes real estate data alongside weather and natural disaster variables to understand their impact on property value and safety. The goal is to rank locations or properties based on environmental risks and climate conditions, helping stakeholders make data-driven investment or relocation decisions.

---

## 📌 Project Objectives

- Integrate weather and disaster data with real estate information  
- Analyze how factors like temperature, rainfall, and disaster frequency affect property desirability  
- Rank or score regions based on weather and safety metrics  
- Provide visual insights into environment-driven property evaluation

---

## 📊 Features and Workflow

- **Data Cleaning & Preparation**
  - Handling missing values
  - Renaming and reformatting columns for consistency

- **Weather-based Analysis**
  - Average temperature, humidity, rainfall, etc.
  - Assigning weather-based rankings to locations

- **Disaster Risk Assessment**
  - Incorporating disaster frequency/severity data
  - Penalizing high-risk areas in the ranking logic

- **Property Ranking Logic**
  - Combined score based on both weather and disaster impact
  - Sorting and displaying top and bottom-ranked areas

- **Visualization**
  - Bar plots and ranking tables to present findings clearly

---

## 📂 Dataset

- Real estate details (location, price, property type, etc.)
- Weather metrics (temperature, humidity, rainfall)
- Natural disaster data (historical events per region)

> *Note: The actual data was pre-merged or simulated for analysis. External APIs or government portals can be used for live updates.

---

## 🛠 Tools & Technologies

- **Python**  
  - `Pandas`, `NumPy` for data manipulation  
  - `Matplotlib`, `Seaborn` for visualization  
- **Jupyter Notebook** for exploratory analysis

---

## 📈 Results & Insights

- Identified regions with optimal weather and minimal disaster risk
- Built a reliable ranking system for real estate evaluation
- Provided visual evidence supporting how environmental conditions affect property attractiveness

---

## 📷 Sample Visualizations

### 📍 Top Ranked Locations Based on Weather and Safety
![Top Ranked Locations](images/top_ranked_locations.png)

### 🌪️ Risk Score Distribution by Region
![Risk Score Distribution](images/risk_score_distribution.png)

> 📌 *Save your plots as `.png` using `plt.savefig("images/filename.png")` and include them in a folder named `images/` inside your repository.*

---

## 🚀 How to Run

1. Clone the repository  
   ```bash
   git clone https://github.com/yourusername/real-estate-weather-ranking.git
   cd real-estate-weather-ranking
Install the required libraries

bash
Copy
Edit
pip install pandas numpy matplotlib seaborn
Launch the Jupyter Notebook

bash
Copy
Edit
jupyter notebook Rank_by_weather_property.ipynb
📌 Future Improvements
Integrate live weather APIs (OpenWeatherMap, IMD)

Use machine learning models to predict price impact from climate risk

Add a dashboard (Power BI / Streamlit)

🧠 Author
Rambabu Bevara
Data Analytics Trainee at Socialprachar, Hyderabad
