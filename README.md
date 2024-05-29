# Power-BI

tengo que bajarme el mapa de qgis directamente como un .geojson
luego subo esa capa acá a github
luego desde el main en github, entro al archivo y me fijo si me deja ver la opción de verlo RAW, hago click copio el link y pego ese link en powerbi -> iconMapV3 -> GeoJSON -> URL.

en caso que NO me deje hacer click en RAW, simplemente copiar el final del nomrbe del link donde estoy parado y en el link de abajo, reemplazar [NOMBRE] con el nombre del archivo que figure en el link de donde estoy parado o sea la última parte.
https://raw.githubusercontent.com/MaxEPEC/Power-BI/main/[NOMBRE]

Por ejemplo si estoy parado en el archivo "red mt dist aer 2024", el link dentro de github va a ser este:
https://github.com/MaxEPEC/Power-BI/blob/main/red%20mt%20dist%20aer2024.geojson

y si quiero ver la forma raw de ese archivo tendría que poner esto:
https://raw.githubusercontent.com/MaxEPEC/Power-BI/main/red%20mt%20dist%20aer2024.geojson
