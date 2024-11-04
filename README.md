### RabbitMQ Ejemplos

Para que los ejemplos funcionen debe estar levantado el proceso de RabbitMQ en el puerto 5672.
Una de las formas más simples de desplegar localmente RabbitMQ es a través de un contenedor de Docker, cuya imagen oficial la pueden encontrar en el siguiente [link](https://hub.docker.com/_/rabbitmq "link").

El ejemplo "Simple communication" busca mostrar la integración desacoplada entre dos procesos; mientras que el ejemplo de "Worker Queues" pretende mostrar cómo funcionan los Wokers. 
- Para el primer caso se debe levantar en primer lugar el receptor y luego el emisor.
- Para el segundo caso, es necesario levantar en primer lugar dos instancias de worker y luego el productor.
