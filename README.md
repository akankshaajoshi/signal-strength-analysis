# Mobile Data Signal Strength Analysis Survey

This repository contains the code and resources for analyzing mobile data signal strength across different models, manufacturers, and service providers at various locations. The project highlights trends in network performance, device capabilities, and location-based signal variations.

## Table of Contents
- [Overview](#overview)
- [Key Features](#key-features)
- [Data Cleaning and Preprocessing](#data-cleaning-and-preprocessing)
- [Data Visualization](#data-visualization)
- [Findings](#findings)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Contributing](#contributing)
- [License](#license)

## Overview

This project aims to evaluate mobile signal performance using survey data collected from multiple users. The survey captures information about device models, service providers, signal strength, and geolocations.

## Key Features
- Comprehensive data cleaning and preprocessing.
- Visualization of signal strength trends across manufacturers and service providers.
- Heatmaps and scatter plots for in-depth performance analysis.
- Location-based signal quality mapping using folium.
- Statistical insights into ASU (Absolute Signal Unit) and signal strength correlation.

## Data Cleaning and Preprocessing

The dataset was cleaned to:
1. Handle missing values and duplicates.
2. Normalize string values and geolocation coordinates.
3. Consolidate inconsistent data entries.
4. Encode signal metrics for consistent analysis.

## Data Visualization

- **Signal Strength Trends:** Plots comparing performance across manufacturers and locations.
- **Heatmaps:** To visualize signal strength variations.
- **Location Analysis:** Folium maps displaying signal quality by latitude and longitude.
- **ASU vs Signal Strength:** Scatter and joint plots revealing linear correlations.
- **Service Provider Performance:** Box and violin plots illustrating variability and trends.

## Findings

- **Device Performance:** Variability in signal strength across models and manufacturers.
- **Service Providers:** Airtel and Jio showed stronger, more consistent signals compared to others.
- **Location Insights:** Coverage strength was significantly higher in urban locations.
- **ASU Correlation:** A strong linear relationship with signal strength validated ASU's reliability as a metric.

## Technologies Used
- **Python:** Data analysis and visualization.
- **Pandas & NumPy:** For data manipulation and cleaning.
- **Matplotlib & Seaborn:** For creating detailed visualizations.
- **Folium:** To map geolocations with signal strength overlays.

## Getting Started

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/signal-strength-analysis.git
   cd signal-strength-analysis
   ```

2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Add your survey dataset to the project directory.

4. Run the analysis:
   ```bash
   python main.py
   ```

## Contributing

We welcome contributions to improve the analysis, visualizations, and insights:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-name`).
3. Commit changes (`git commit -m 'Add feature-name'`).
4. Push to your branch (`git push origin feature-name`).
5. Submit a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---
