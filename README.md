📬 PostMail - Proyecto de Programación Orientada a Objetos
Este proyecto es una API REST para gestionar envíos de paquetes utilizando créditos. Cada usuario puede comprar paquetes de créditos y usarlos para registrar envíos. También se pueden eliminar envíos, y en ese caso se devuelve una parte del crédito.

Funcionalidades principales
Ver créditos disponibles de un usuario.

Comprar paquetes de 30, 40 o 60 créditos.

Registrar nuevos envíos con costo dependiendo del peso y número de bultos.

Consultar envíos registrados por cada usuario.

Eliminar un envío y devolver parte del crédito según el peso.

Estructura del proyecto
api.js: contiene todas las rutas y lógica de la API.

models/Usuario.js: define el esquema del usuario y sus créditos.

models/Envio.js: define los datos de cada envío, incluyendo datos personales y del paquete.

models/Producto.js: define el objeto producto (peso, bultos, descripción, fecha de entrega), que está incluido en cada envío.

Tecnologías usadas
Node.js

Express

MongoDB

Mongoose


