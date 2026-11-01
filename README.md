# F1 Speed Visualization – Charles Leclerc

## Project Overview

This project analyzes Formula 1 telemetry data to understand how car speed changes throughout a lap. Using data from Charles Leclerc's qualifying session at the 2024 Italian Grand Prix at Monza, the project visualizes speed variations across the circuit and identifies braking zones.

The analysis uses telemetry data retrieved from the OpenF1 API and visualized using Python.

## Objectives

- Analyze speed variations throughout a qualifying lap.
- Visualize speed distribution across the Monza circuit.
- Identify braking zones using telemetry data.
- Understand how drivers manage speed around different sections of a circuit.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Requests
- OpenF1 API
- Google Colab

## Dataset Details

| Parameter | Details |
|---|---|
| Driver | Charles Leclerc |
| Driver Number | 16 |
| Season | 2024 |
| Grand Prix | Italian Grand Prix |
| Circuit | Monza |
| Session | Qualifying |
| Telemetry Samples | 321 matched samples |

## Visualizations

### Speed vs. Time

Shows how the car's speed changes throughout the selected lap.

![Speed vs Time](images/speed%20vs%20time.png)

### Circuit Speed Map

Displays speed variations across different sections of the Monza circuit.

![Monza Circuit Speed Map](images/monza%20ckt%20speed%20map.png)

### Speed Map with Braking Zones

Highlights sections where braking activity was detected during the lap.

![Speed Map with Braking Zones](images/speed%20map%20with%20braking%20zones.png)

## Key Analysis

The project explores the relationship between vehicle speed, track position, and braking activity. The visualizations help identify high-speed sections, slower corners, and changes in driving behaviour throughout the lap.

## How to Run

1. Open `Charles_Leclerc_F1_Analysis.ipynb` in Google Colab.
2. Run the notebook cells sequentially.
3. Retrieve telemetry data using the OpenF1 API.
4. Process and merge the location and car telemetry data.
5. Generate the visualizations.

## Data Source

[OpenF1 API](https://openf1.org/)

## Future Improvements

- Compare telemetry data from multiple drivers.
- Analyze additional Formula 1 circuits.
- Include throttle, gear, and braking analysis.
- Compare qualifying and race performance.

## Author

**Gayatri Palodkar**

GitHub: [GayatriPalodkar](https://github.com/GayatriPalodkar)
