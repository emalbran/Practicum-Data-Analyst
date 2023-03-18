## Data:

En este proyecto nos entregaron los siguientes cuatro archivos:
- *ab_project_marketing_events_us.csv*: El calendario de eventos de marketing para 2020
- *final_ab_new_users_upd_us.csv*: Todos los usuarios que se registraron en la tienda en línea desde el 7 hasta el 21 de diciembre de 2020
- *final_ab_events_upd_us.csv*: Todos los eventos de los nuevos usuarios en el período comprendido entre el 7 de diciembre de 2020 y el 1 de enero de 2021
- *final_ab_participants_upd_us.csv*: Tabla con los datos de los participantes de la prueba

Estructura de los archivos: 
ab_project__marketing_events_us.csv:
  - *name*: El nombre del evento de marketing
  - *regions*: Regiones donde se llevará a cabo la campaña publicitaria
  - *start_dt*: Fecha de inicio de la campaña
  - *finish_dt*: Fecha de finalización de la campaña
final_ab_new_users_upd_us.csv:
  - *user_id*
  - *first_date*: Fecha de inscripción
  - *region*
  - *device*: Dispositivo utilizado para la inscripción
final_ab_events_upd_us.csv:
  - *user_id*
  - *event_dt*: Fecha y hora del evento
  - *event_name*: Nombre del tipo de evento
  - *details*: Datos adicionales sobre el evento (por ejemplo, el pedido total en USD para los eventos purchase)
final_ab_participants_upd_us.csv:
  - *user_id*
  - *ab_test*: Nombre de la prueba
  - *group*: El grupo de prueba al que pertenecía el usuario


## Goal:

Retomar una prueba A/B abandonada, analizar las especificaciones técnicas y los resultados dejados por el equipo anterior y sacar conclusiones apropiadas de los datos encontrados.

## Libraries used:

pandas

numpy

matplotlib.pyplot

seaborn

scipy.stats

datetime

plotly

math
