Este proyecto se divide en dos partes:
0.1  Priorizar hipótesis
0.2  Análisis de test A/B

## Data:

Con tres tablas:

*Hypotheses*
- *Hypotheses*: breves descripciones de las hipótesis
- *Reach*: alcance del usuario, en una escala del uno a diez
- *Impact*: impacto en los usuarios, en una escala del uno al diez
- *Confidence*: confianza en la hipótesis, en una escala del uno al diez
- *Effort*: los recursos necesarios para probar una hipótesis, en una escala del uno al diez. Cuanto mayor sea el valor Effort, más recursos requiere la prueba.

*visits*
- *date*: la fecha
- *group*: grupo del test A/B
- *visits*: el número de visitas en la fecha especificada para el grupo de test A/B especificado

*orders*
- *transactionId*: identificador de pedido
- *visitorId*: identificador del usuario que realizó el pedido
- *date*: fecha del pedido
- *revenue*: ingresos del pedido
- *group*: el grupo del test A/B al que pertenece el usuario


## Goal:

La primera parte consiste en analizar y prioritizar nueve hipótesis. Para ello, utilizaremos los frameworks ICE y RICE, compararemos los resultados y intentaremos encontrar la mejor entre ellas.
La segunda parte en cambio, obtuvimos los resultados de un test A/B. Con los datos recibidos, mediante gráficos y cálculos buscaremos sacar hipótesis que después intentaremos corroborar. 
De esta forma, analizaremos el test y determinaremos si este fue exitoso o no, y si es necesario continuarlo o no.

## Libraries used:

Pandas

Matplotlib

Numpy

Scipy.stats

Datetime
