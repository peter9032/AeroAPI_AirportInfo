![Example Map](https://github.com/peter9032/AeroAPI_AirportInfo/assets/129965664/5c0c5fdb-57cc-4de3-b564-b5e0ed83404b)

# Description

This Jupyter Notebook serves as a simple tool for querying individual airports using FlightAware's AeroAPI. The primary objective is to visualize the geographical location of a selected airport on a map of the United States, accompanied by basic information.

To initiate a query, input the airport's identification code (e.g., DFW for Dallas Fort Worth International). It is essential to note that the current configuration exclusively supports airports within the United States, as the map is confined to this region. Attempting to query airports beyond the United States may result in accurate information retrieval but may not yield correct plotting on the map.

This functionality provides a focused and efficient means of extracting location-based insights for airports within the United States, offering a pragmatic tool for aviation data exploration within a confined geographic scope.

# Requirements

To run this project, you'll need the following dependencies:

- Python 3.x
- Jupyter Notebooks
- Flight Aware AeroAPI credentials
- The following Python libraries:
  - `os`
  - `pandas`
  - `geopandas` 
  - `shapely.geometry` (`Point` from `shapely.geometry`)
  - `matplotlib.pyplot`
  - `aeroapi_python` (AeroAPI Python library)

You can install the necessary Python libraries using the following command:

```bash
pip install <specific_library>
