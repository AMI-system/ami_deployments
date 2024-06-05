# AMBER project AMI Deployments

## Installation and usage 

Clone the repository using the command line or the GitHub desktop app.
```sh
git clone https://github.com/AMI-system/ami_deployments
```

Install the dependencies.
```sh
pip install folium
```

## Create a new map

1. Download the geojson file from the country you would like to create the new map using this [repository](https://github.com/glynnbird/countriesgeojson/tree/master).

2. Duplicate one of the map creators python files and rename it.

3. Update the code to use the right geojson file and the right file from the files folder. 

4. Run the map creator python script and a new html file would be created. 