-Lo primero que se tiene que hacer es abrir el visual code y exportar el archivo con las 2 carpetas. 

-Luego en el archivo de docker-compose.yml que pertenece al servicio web, se tiene que abrir una nueva terminal y ejecutar el siguiente comando: "docker-compose up" y cuando finalice la carga, abrir la aplicación de docker desktop para verificar que el servidor ya se haya subido a la nube. 

-Una vez realizado el paso anterior, ahora se tiene que subir el otro archivo docker-compose.yml que contiene el código para montar la base de datos y se va a escribir el comando "docker-compose up -d servidorbd" y con eso ya estaría montada la base de datos en la nube. -Luego se ejecuta un último comando que sería "cd cont_hub" ya para grardarlo todo. 

-Para ver la base de datos en el localhost solo se tiene que abrir el gestor de base de datos preferido y ponerle el mismo puerto y la misma contraseña que se puso en el código para que pueda abrir, despues solo se tiene que ir al navegador de su preferencia y escribir localhost seguido de 2 puntos y el puerto que se esté utilizando.

-Para ejecutar el cont_dockerfile, serían los mismos pasos que el cont-hub, solo que como paso extra, ahí se tendría que ejecutar el archivo dockerfile
