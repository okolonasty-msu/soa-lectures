FROM python:3.9
ADD working_map_baseline.py .
ADD Russia_regions.geojson .
ADD Sessions_by_City_2023_06_21.csv .
ADD Russia_regions_and_cities.csv .
RUN pip install pandas dash plotly.express
CMD ["python", "./working_map_baseline.py"]