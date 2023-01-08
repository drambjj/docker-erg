FROM mongo

COPY port.geojson /port.geojson
CMD mongoimport --host mongodb --db reach-engine --collection port --type json --file /port.geojson --jsonArray