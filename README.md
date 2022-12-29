# recibodigital

Recibo.Info es un estándar para recibos digitales en formato JSON que consta de las siguientes partes:

id (string): ID único de la transacción.
date (string): Fecha y hora de la transacción en formato ISO 8601.
total (number): Costo total de la transacción.
concepts (array): Matriz de objetos que representan los artículos comprados en la transacción. Cada objeto tiene las siguientes propiedades:
name (string): Nombre del artículo.
quantity (number): Cantidad del artículo comprado.
price (number): Precio del artículo.
receptor (object): Objeto con las siguientes propiedades:
name (string): Nombre del cliente.
email (string): Correo electrónico del cliente.
emisor (object): Objeto con las siguientes propiedades:
name (string): Nombre de la tienda.
location (string): Ubicación de la tienda.
metadata (object): Objeto que contiene información adicional sobre la transacción. Tiene las siguientes propiedades:
payment_method (string): Método de pago utilizado en la transacción.
reference_number (string): Número de referencia asociado a la transacción.

Recibo.Info es un proyecto de código abierto que proporciona un estándar para el intercambio de recibos digitales. Su objetivo es facilitar la gestión de transacciones y hacerlas más seguras y transparentes para todas las partes involucradas.
