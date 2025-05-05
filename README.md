# 📊 Noise Pollution Mapping in Urban Areas

This project provides a complete workflow for mapping, visualizing, and analyzing noise pollution levels in urban areas using geospatial and machine learning techniques. It utilizes geo-tagged noise data to generate interactive maps and heatmaps that aid in understanding spatial noise variability, which is crucial for urban planning, public health, and environmental management.

---

## 🚀 Features

- 📍 Mapping of noise pollution levels using GPS-tagged sensor data.
- 🗺️ Interactive map with noise level markers using `folium`.
- 🌡️ Interpolated heatmap of noise distribution using K-Nearest Neighbors (KNN).
- 📈 Visual analysis of urban noise trends with `matplotlib`.
- 🧠 Machine learning-based spatial prediction of unmonitored areas.

---

## 📂 Project Structure

noise-pollution-mapping/
│
├── noise_pollution_mapping.py # Main script for mapping and interpolation
├── synthetic_noise_data.csv # Sample synthetic dataset (GPS + dB readings)
├── noise_pollution_map.html # Interactive folium map output
├── noise_pollution_heatmap.png # Interpolated heatmap output
└── README.md # Project documentation


---

## 📦 Requirements

Install the necessary Python packages:

```bash
pip install pandas geopandas folium matplotlib scikit-learn shapely

📥 Input Format

The input CSV file must include the following columns:

latitude,longitude,noise_level_dB
6.5244,3.3792,65
6.5278,3.3810,75
...

🛠️ How to Use

    Clone the repository or download the files.

    Replace noise_data.csv with your real-world data or use the provided synthetic_noise_data.csv.

    Run the main script:

python noise_pollution_mapping.py

    View:

        noise_pollution_map.html for the interactive map.

        noise_pollution_heatmap.png for the static heatmap.

📊 Use Cases

    Environmental noise assessment

    Urban planning and zoning

    Health impact studies

    Smart city and IoT sensor deployment

👤 Author

Ugochukwu Charles Akajiaku
GitHub Profile
LinkedIn
📜 License

This project is licensed under the MIT License - feel free to use and modify.


---

Would you like me to save this `README.md` file alongside the dataset as well?
