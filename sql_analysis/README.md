## Data:

En este proyecto nos entregaron las siguientes cinco tablas:

*books*: Contiene datos sobre libros
  - *book_id*: Identificación del libro
  - *author_id*: Identificación del autor o autora
  - *title*: Título
  - *num_pages*: Número de páginas
  - *publication_date*: Fecha de la publicación
  - *publisher_id*: Identificación de la editorial

*authors*: Contiene datos sobre autores
  - *author_id*: Identificación del autor o autora
  - *author*: El autor o la autora

*publishers*: Contiene datos sobre editoriales
  - *publisher_id*: Identificación de la editorial
  - *publisher*: La editorial

*ratings*: Contiene datos sobre las calificaciones de usuarios
  - *rating_id*: Identificación de la calificación
  - *book_id*: Identificación del libro
  - *username*: El nombre del usuario que revisó el libro
  - *rating*: Calificación

*reviews*: Contiene datos sobre las reseñas de los y las clientes
  - *review_id*: Identificación de la reseña
  - *book_id*: Identificación del libro
  - *username*: El nombre del usuario que revisó el libro
  - *text*: El texto de la reseña


## Goal:

Con los datos datos sobre libros, editoriales, autores y calificaciones de clientes y reseñas de libros se intentará generar una propuesta de valor para un nuevo producto.


## Libraries used:

pandas

sqlalchemy
