# 🚦 Jakarta Traffic Congestion Analysis

This project explores traffic congestion patterns in Jakarta using a dataset that includes vehicle counts, average speed, location, road type, weather condition, and time-based features. The goal is to uncover insights that can help improve traffic management and urban planning.

---

## 📊 Objectives

- Identify peak congestion hours and locations
- Understand the impact of weather and weekends on traffic flow
- Visualize traffic trends and anomalies
- Summarize data for further dashboarding or modeling

---

## 🗂️ Project Structure
jakarta-traffic-analysis/
├── data/ # Raw data files
├── notebooks/ # Jupyter Notebook for exploration and EDA
├── src/ # Python scripts (e.g. preprocessing)
├── output/ # Charts, summaries, and generated data
├── requirements.txt # Python dependencies
├── .gitignore # Ignore unnecessary files from Git tracking
└── README.md # Project documentation (this file)

## 🧰 Tools & Libraries

- **Python 3.9+**
- [pandas](https://pandas.pydata.org/)
- [numpy](https://numpy.org/)
- [matplotlib](https://matplotlib.org/)
- [seaborn](https://seaborn.pydata.org/)
- [Jupyter Notebook](https://jupyter.org/)

Install all dependencies with:
```bash
pip install -r requirements.txt

📁 Dataset
jakarta_traffic_data.csv

Features include:

Date, Hour, Location

Vehicle_Count, Average_Speed_kmh

Weather_Condition, Is_Weekend, Road_Type

The dataset is stored in the data/ folder. More details are available in data/README.md.

📈 Key Visualizations
Hourly traffic volume by location

Speed patterns by weather and day type

Heatmaps of congestion

Bar plots of average speed by road type

Sample outputs are stored in the output/charts/ folder.

📌 Next Steps
 Add interactive dashboard (Metabase / Streamlit)

 Expand dataset with holiday/event flags

 Apply predictive modeling for traffic forecasting

✍️ Author
Mohd Milzon
📫 GitHub: @milzon1010

📄 License
This project is licensed under the MIT License.
Feel free to use or modify for learning and non-commercial purposes.
