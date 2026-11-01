# 🏎️ F1 Speed Visualization – Charles Leclerc

### How fast do Formula 1 cars really go around a circuit?

An exploratory data visualization project analyzing Charles Leclerc's speed and telemetry during the **2024 Italian Grand Prix Qualifying at Monza** using Python and real-world Formula 1 data.

## 📌 About the Project

Ever wondered how an F1 car behaves while navigating a racing circuit?

This project explores Charles Leclerc's telemetry data to understand speed variations, acceleration, braking patterns, and track positions throughout a selected lap at Monza.

Using Python, I transformed raw telemetry data into visual insights to better understand Formula 1 car performance.

## 🎯 Project Objectives

- Analyze speed variations throughout a lap.
- Visualize the Monza circuit using positional coordinates.
- Identify high-speed sections and braking points.
- Understand acceleration and deceleration patterns.
- Explore real-world Formula 1 telemetry data.

## 🛠️ Tech Stack

- **Python** – Data analysis
- **Pandas** – Data manipulation
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Requests** – API data retrieval
- **Google Colab** – Development environment
- **OpenF1 API** – Formula 1 telemetry data

## 📊 Project Visualizations

### 1. Speed vs. Elapsed Time

Analyzing how Charles Leclerc's speed changes throughout the selected lap.

![Speed vs Time](images/speed%20vs%20time.png)

### 2. Monza Circuit – Speed Distribution

A colour-coded circuit map showing speed variations across different track sections.

![Monza Circuit Speed Map](images/monza%20ckt%20speed%20map.png)

### 3. Speed Map with Braking Zones

Visualizing recorded braking positions along the circuit.

![Speed Map with Braking Zones](images/speed%20map%20with%20braking%20zones.png)

## 📡 Dataset

Data collected using the [OpenF1 API](https://openf1.org/).

- Driver: Charles Leclerc
- Driver Number: 16
- Season: 2024
- Grand Prix: Italian Grand Prix
- Circuit: Monza
- Session: Qualifying
- Matched telemetry samples: 321

## 📈 Analysis Performed

- Speed analysis and distribution.
- Track position visualization.
- Speed vs. elapsed time analysis.
- Braking activity identification.
- Telemetry data cleaning and integration.

## 🚀 How to Run the Project

1. Clone this repository:

   ```bash
   git clone https://github.com/GayatriPalodkar/F1-Speed-Visualization.git
   ```

2. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib requests
   ```

3. Open `Charles_Leclerc_F1_Analysis.ipynb` in Google Colab or Jupyter Notebook.

4. Run the notebook cells in sequence.

## 💡 Key Learnings

- Working with real-world API data.
- Cleaning and processing telemetry datasets.
- Combining time-series data from different sources.
- Creating visualizations using Matplotlib.
- Exploring Formula 1 performance through data analysis.

## 🔮 Future Improvements

- Compare telemetry between multiple F1 drivers.
- Analyze different circuits and racing sessions.
- Create interactive circuit visualizations.
- Explore throttle, gear and braking patterns in greater detail.

## 👩‍💻 Author

**Gayatri Palodkar**

[GitHub Profile](https://github.com/GayatriPalodkar)

---

⭐ If you find this project interesting, consider giving the repository a star!
