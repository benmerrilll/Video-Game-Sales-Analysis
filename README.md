# Video-Game-Sales-Analysis
This project is a brief look at the Plotly library through some basic visualizations. 

# Visualization Tool - Plotly
Plotly (https://plotly.com/) is a front end data visualization library available in Python or R. It is a free, open-source library that makes publication quality data visualizations that are often interactive. This notebook highlights 3 types of common plotly visualizations: Time Series, Bar Chart, and Heat Maps. To install Plotly, 

Plotly can be installed using pip or conda, respectively:
 ```
 pip install plotly==4.12.0
 ```
 ```
 conda install -c plotly plotly=4.12.0
 ```
 
Plotly's interactive data widgets in Jupyter can be installed also by using pip or conda, respectively:
 ```
 pip install "notebook>=5.3" "ipywidgets>=7.2
 ```
 ```
 conda install "notebook>=5.3" "ipywidgets>=7.2"
 ```

# The Data
Our data will come from a static kaggle dataset here: https://www.kaggle.com/gregorut/videogamesales. This dataset covers all videogame sales from 1980 to 2016. It is sorted by Title, Platform, Year, Genre, Publisher, and Sales. We chose this simple and usable tabular dataset because it can provide simple insights into the life of consoles, the sales in the videogaming industry, and a breif view of the most and least successful consoles.

# Conclusion
After our analysis, we can conclude that the most successful consoles tend to have a longer lifetime than the least successful consoles. Consoles that have really heavy earnings made from games created in the inital years of release tend to have lower overall profit and a shorter lifecycle.
