Este proyecto se realizó en tres pasos:

## Paso 1: 
Escribir un código para analizar los datos sobre el clima en Chicago en noviembre de 2017 desde el sitio web:
https://code.s3.yandex.net/data-analyst-eng/chicago_weather_2017.html

## Libraries used:
pandas

BeautifulSoup

## Data:
Una base de datos con información sobre viajes en taxi en Chicago:

tabla neighborhoods: datos sobre los barrios de la ciudad
- *name*: nombre del barrio
- *neighborhood_id*: código del barrio

tabla cabs: datos sobre los taxis
- *cab_id*: código del vehículo
- *vehicle_id*: ID técnico del vehículo
- *company_name*: la empresa propietaria del vehículo

tabla trips: datos sobre los viajes
- *trip_id*: código del viaje
- *cab_id*: código del vehículo que opera el viaje
- *start_ts*: fecha y hora del inicio del viaje (tiempo redondeado a la hora)
- *end_ts*: fecha y hora de finalización del viaje (tiempo redondeado a la hora)
- *duration_seconds*: duración del viaje en segundos
- *distance_miles*: distancia del viaje en millas
- *pickup_location_id*: código del barrio de recogida
- *dropoff_location_id*: código del barrio de finalización

tabla weather_records: datos sobre el clima
- *record_id*: código del registro meteorológico
- *ts*: fecha y hora del registro (tiempo redondeado a la hora)
- *temperature*: temperatura cuando se tomó el registro
- *description*: breve descripción de las condiciones meteorológicas, por ejemplo, "lluvia ligera" o "nubes dispersas"


## Paso 2:
Análisis exploratorio de datos

## Language used:
SQL

## Paso 3: 
Análisis exploratorio de datos 

## Language used:
Python

## Goal:

La idea es obtener información para es encontrar patrones en la información disponible. 
Queremos comprender las preferencias de los pasajeros y el impacto de los factores externos en los viajes.
Además, se busca descubrir si la duración promedio de los viajes desde el *Loop* hasta el *Aeropuerto Internacional O'Hare* en Chicago cambia los sábados lluviosos.


## Libraries used:

Pandas

Matplotlib

numpy

scipy.stats
