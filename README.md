# pruebadiagnostico 


API application programming interface

estructurar un backend con un conjunto de funciones, los cuales van a servir para interactuar con el cliente.
el cliente lo que va hacer es consumir el API, o servicios web, el API se encarga todo la lógica de negocio y la interacción de la base de datos y datos así estaría bien segmentado, el cliente y el servidor, en donde se harán algunas peticiones entre cliente y servidor deben ser lo más limpias posibles para el intercambio de información simple y estructurado, en este caso en el formato json 
la arquitectura que se va a utilizar va ser Rest-API la cual es una transferencia de estado representacional, el cual está dirigido en un protocolo cliente-servidor. Este es un conjunto de operaciones bien definidas en donde tiene sintaxis universal para identificar recursos. 
las operaciones bien definidas Rest-API son las operaciones para crear, leer, actualizar, y eliminar, o bien conocidas como CRUD, las cuales  están relacionadas a métodos de http. Se creó un Rest-API para usuarios, se creó una clase de usuarios, donde se hace un registro de usuarios .
El rest API, se de forma escalable y estén bien segmentado.
En los API se colocan todas las peticiones del cliente, y se generó un archivo llamado usuarios.php en donde se van a recibir todas las peticiones del usuario.
Se genera el localhost, el puerto, es decir la ruta del proyecto, y se gestiona toda la parte de las peticiones de los usuarios
En class-usuarios.php se hizo las operaciones básicas de API, en donde se generó algunas funciones como de ;
•	guardar usuario
•	obtener usuario
•	actualizar usuario
•	eliminar usuario
en usurios.php se va a usar para recibir las peticiones del usuario. es decir. Recibir peticiones del usuario como:
•	crear
•	obtener un usuario
•	obtener todos los usuarios
•	actualizar un usuario
•	eliminar un usuario
Primero se debe conocer el método HTTP de la petición que hace el usuario para tomar decisiones y saber que acción tomar
•	GET
•	POST
•	PUT
•	DELETE

para saber se coloca un echo "metodo HTTP:".$_SERVER['REQUEST_METHOD']; el cual es un arreglo asociativo, en el cual podemos obtener mucha información con respecto a la petición 
nos retorna algún método de HTTP, normalmente la petición que se hace es el GET. 
