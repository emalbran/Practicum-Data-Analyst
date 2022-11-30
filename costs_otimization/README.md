## Data:

Son tres tablas:

*visits*
- *Uid*: identificador único del usuario;
- *Device*: dispositivo del usuario;
- *Start Ts*: fecha y hora de inicio de la sesión;
- *End Ts*: fecha y hora de término de la sesión;
- *Source Id*: identificador de la fuente de anuncios de la que proviene el usuario.

*orders*
- *Uid*: identificador único del usuario que realiza un pedido;
- *Buy Ts*: fecha y hora del pedido;
- *Revenue*: ingresos de Y.Afisha de este pedido.

*costs*
- *source_id*: identificador de la fuente de anuncios
- *dt*: fecha;
- *costs*: gastos en esta fuente de anuncios en este día.


## Goal:

La idea es estudiar cómo la gente usa el producto, cúando empiezan a comprar, cúanto dinero trae cada cliente y si las estrategias de marketing utilizadas son rentables o no.
Este proyecto se divide en 3 partes:
- Estudio del producto
- Ánalisis de las ventas
- Revisión de las estrategias de Marketing

## Libraries used:

Pandas

Matplotlib

Numpy

Scipy.stats

Seaborn
