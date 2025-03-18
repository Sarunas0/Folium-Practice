import numpy as np  # useful for many scientific computing in Python
import pandas as pd # primary data structure library


import folium

print('Folium installed and imported!')


# define the world map
world_map = folium.Map()

# display world map
world_map



# define the world map centered around Canada with a low zoom level
world_map = folium.Map(location=[56.130, -106.35], zoom_start=4)

# display world map
world_map



# create a Cartodb dark_matter map of the world centered around Canada
world_map = folium.Map(location=[56.130, -106.35], zoom_start=4, tiles='Cartodb dark_matter')

# display map
world_map



# create a Cartodb positron map of the world centered around Canada
world_map = folium.Map(location=[56.130, -106.35], zoom_start=4, tiles='Cartodb positron')

# display map
world_map



# 3) Define Mexico's geolocation coordinates
mexico_latitude = 23.6345
mexico_longitude = -102.5528

# 4) Create a map centered around these coordinates
#    Make sure the tile name matches Folium's recognized style, e.g. "CartoDB positron"
mexico_map = folium.Map(location=[mexico_latitude, mexico_longitude],
                        zoom_start=6,
                        tiles='CartoDB positron')

# 5) Display the map in a Jupyter environment
mexico_map
