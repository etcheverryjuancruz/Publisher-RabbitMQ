#  RabbitMQ - Basic Publisher 

Este proyecto es una prueba de conocepto para entender cómo funciona RabbitMQ. Basicamente,  consiste en 2 ejemplos que publican mensajes en una cola.

# Instalacion 
- Clonar el proyecto :  `git clone https://github.com/etcheverryjuancruz/Publisher-RabbitMQ.git'`
- Importar el proyecto como un 'Proyecto Maven'.

# Ejemplos

**Publicar un mensaje en una cola:**
Ejecutar como una Application Java el archivo `Sender.java` En este caso, se publica un mensaje simple 'Hello world'.

**Publicar  mensajes en una cola de tareas:**
En este ejemplo, se publican en una cola mensajes que son pasados como parametros. Para configurar los mensajes se debe ingresar a *Run Configuration > Java Application > NewTask > Arguments > Program Arguments*. Luego, ejecutar `NewTask.java` como Java Application.
