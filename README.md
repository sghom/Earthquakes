# earthquakes
Earthquake Data Visualization
This repository contains Python scripts for visualizing earthquake data using Plotly. The data is sourced from JSON files and includes earthquake magnitudes, locations, and titles. The visualizations are generated as interactive HTML files, making it easy to explore and analyze global earthquake patterns.

1. File Descriptions
  - data_visualization.py
    Purpose: This script processes earthquake data from JSON files, extracts relevant information, and creates interactive maps.
      - Data Handling:
        - Reads earthquake data from JSON files located at specified file paths.
        - Converts the JSON data into a more readable format.
        - Extracts magnitude, longitude, latitude, and title for each earthquake.
    
      - Visualization:
        - Generates a scatter plot of earthquakes on a global map.
        - Earthquake magnitudes are visualized by the size and color of the markers.
        - The color scale represents the magnitude of each earthquake.
        - Saves the plot as an HTML file for interactive exploration.
      
2. Usage
  - Setup:
  Ensure that you have Python installed along with the necessary packages: json and plotly.
  
  - Data Files:
  Update the file paths in the script to point to your local JSON files containing earthquake data.
  
  Execution:
  - Run the script to process the data and generate an interactive HTML visualization of global earthquakes.
  - 
  Files Generated:
  global_earthquakes.html: An interactive map showing the magnitude and location of earthquakes.
  
  Example Output
  The script generates an interactive HTML file (global_earthquakes.html) where you can view a global map of earthquakes. 
  The size and color of each marker on the map correspond to the magnitude of the earthquake, allowing for a clear and informative visualization of global seismic activity.

Notes
Ensure that the JSON files you use have the expected structure with features, properties, and geometry fields.
Customize the script as needed to accommodate different data formats or additional features.
