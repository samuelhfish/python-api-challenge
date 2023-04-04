# python-api-challenge
Module 6 Challenge - Python and APIs

VacationPy solution located here: VacationPy/VacationPy_SamCode.ipynb

WeatherPy solution located heere: WeatherPy/main.ipynb

Scatter plots, regression and CSV located here: WeatherPy/output_data


Having trouble with a push/pull and my project. Will re-submit if neccessary. Here is the last line of code.

# Configure the map plot
map_plot_hotel_data = hotel_df.hvplot.points(
    "Lng",
    "Lat",
    geo = True,
    tiles = "OSM",
    frame_width = 800,
    frame_height = 500,
    size = "Humidity",
    scale = 1.1,
    alpha = 0.8,
    color = "City",
    hover_cols = ['Hotel Name', 'Country']
)

# Display the map
map_plot_hotel_data

