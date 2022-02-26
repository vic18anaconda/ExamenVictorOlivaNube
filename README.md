En este trabajo el objetivo era levantar por medio de la herramienta de docker
un servidor web en la cual podamos cargar ya sea nuestros programas hechos en php o
diversas aplicaciones que tengamos creadas. 

ademas de poder agregarle una base de datos complementaria para poder guardar datos
y consultarlos en la pagina o servidor web que se levantara por medio de la 
herramienta de docker y heididb

para poder levantar la pagina web, debes de ejecutar el siguiente comando en la terminal
- docker-compose up . En los archivos docker que tienen los elementos de services y servidor web.



total de comandos necesarios para poder levantar los contenedores. 
para poder levantar 
docker-compose up 
docker-compose up -d servidorweb     para poder levantar el servidor web ya asignandole su puerto
docker-compose up -d servidorbd      para poder levantar la base de datos y conectarla a la pagina web. 

ejecutar el comando de contender de docker compose up 