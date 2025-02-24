# RTGIS
In this repository you'll find a POC for a use of case of a real time system geographical information system (RTGIS).

# Needed libraries and its purpose
- GeoPandas: Extends the pandas library by adding support for geospatial data, making it easier to work with geographic information and perform spatial operations.
- Shapely: A library for the manipulation and analysis of planar geometric objects, using functions from the GEOS library.
- Dash: A framework for building interactive web applications using Python, integrating Plotly for visualizations and React for the front-end.
- Plotly: An open-source graphing library that makes interactive, publication-quality graphs, supporting a wide range of chart types including statistical, financial, geographic, and 3D visualizations.
- DotEnv: Reads key-value pairs from a .env file and sets them as environment variables, helping manage application configuration in a secure and convenient way.
- pyicloud: A module that allows interaction with iCloud web services, enabling access to iCloud data such as calendars, contacts, and Find My iPhone.
- Pandas: A powerful data analysis and manipulation library that provides flexible data structures like DataFrames, making it easy to work with structured data.


# Run
### Install necessary libraries
```
pip install -r requirements.txt
```

### Create and save a ```.env``` file at same notebook level with following 2 values:
```
USER: "icloud_account@yourdomain.com"
PASSWORD: "y0ur_1cl0ud_p4ssw0rd"
```

### Go to Jupyter notebook and run the 4 cells
![image](https://github.com/user-attachments/assets/7714236a-8e29-4753-b550-7b4d3b2ecb22)

### Go to your favourite browser and go to http://localhost:8050/


#### Optional:
At the end of the 4th cell, the main directive it's there. In the ```run_server``` method, you can chage the port of the web app. By default, the app runs on port 8050.
