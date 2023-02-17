## Data:

- *Churn* — la cancelación para el mes en cuestión
- Campos de dataset actuales:
    - Datos de usuario del mes anterior
        - *gender*: El genero del usuario.
        - *Near_Location* — si el usuario vive o trabaja en el vecindario donde se encuentra el gimnasio
        - *Partner* — si el usuario es un trabajador de una compañía asociada (el gimnasio tiene empresas asociadas cuyos empleados obtienen descuentos; en esos casos el gimnasio almacena información sobre los empleadores de los clientes)
        - *Promo_friends* — si el usuario originalmente se inscribió mediante una oferta "trae a un amigo" (se utilizó el código promocional de un amigo cuando pagaron el primer abono)
        - *Phone* — si el usuario aportó el número de teléfono
        - *Age*: la edad del usuario
        - *Lifetime* — el tiempo (en meses) desde que el usuario llegó por primera vez al gimnasio
- Datos del registro de visitas y compras y datos sobre el estado actual de la membresía
    - *Contract_period* — 1 mes, 3 meses, 6 meses o 1 año
    - *Month_to_end_contract* — los meses que faltan hasta que expire el contrato
    - *Group_visits* — si el usuario participa en sesiones grupales
    - *Avg_class_frequency_total* — frecuencia media de visitas por semana a lo largo de la vida del cliente
    - *Avg_class_frequency_current_month* — frecuencia media de visitas por semana en el mes anterior
    - *Avg_additional_charges_total* — cantidad total de dinero gastado en otros servicios del gimnasio: cafetería, productos deportivos, cosméticos, masajes, etc.


## Goal:

El objetivo de este proyecto es desarrollar una estrategia de interacción con el cliente basada en datos analíticos para la cadena de gimnasios Model Fitness, con el fin de combatir la cancelación de clientes. 

## Libraries used:

pandas

numpy

matplotlib.pyplot

seaborn

sklearn.preprocessing

sklearn.model_selection

sklearn.linear_model

sklearn.ensemble

sklearn.cluster

sklearn.metrics

scipy.spatial.distance

scipy.cluster.hierarchy

scipy.stats
