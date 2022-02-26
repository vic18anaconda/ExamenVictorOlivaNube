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

primero se tiene que abrir el visual code y exportar el archivo con las 2 carpetas. 
el archivo de docker-compose.yml que pertenece al servicio web, se tiene que abrir una terminal y ejecutar el comando: "docker-compose up" 
luego abrir la aplicación de docker desktop para comprobar que el servidor  este en la nube. 

ahora se tiene que subir el otro archivo docker-compose.yml que contiene el código para montar la base de datos y se va a escribir el comando "docker-compose up -d servidorbd" y con eso estaría montada la base de datos 

se ejecuta un último comando que sería "cd cont_hub", Para ver la base de datos en el localhost se tiene que abrir el gestor de base de datos preferido y ponerle el mismo puerto y la misma contraseña que se puso en el código para que pueda abrir, despues solo se tiene que ir al navegador de su preferencia y escribir localhost seguido de 2 puntos y el puerto que se esté utilizando.

-Para ejecutar el cont_dockerfile, serían los mismos pasos que el cont-hub, solo que como paso extra, ahí se tendría que ejecutar el archivo dockerfile
