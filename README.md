Propuesta de Proyecto 
Tecnologías Web
“Armador de equipos para League of Legends”


	League of Legends es un juego en donde participan 5 personas por equipo, y el juego se desarrolla entre dos equipos. Cada equipo cuenta con 5 posiciones diferentes:
Top
Jungler
Mid
Bot
Support

	El rankeo de los jugadores va dependiendo de su desempeño en las partidas, los rangos en los que los jugadores pueden ser acomodados son los siguientes (de mayor a menor)
Challenger
Master
Diamond
Platinium
Gold
Silver
Bronze

	La idea de la página es que cada jugador se pueda dar de alta con su nombre que usa en el juego (nombre de invocador/summoner name). Además de indicar la posición que juega y el rango que tiene.

	Entonces cada persona registrada tendrá esos tres campos. Por ejemplo:
Summoner Name: Valbor
Position: Jungler
Rank: Diamond

	De esta manera la página ayudará a ese jugador a que encuentre “equipo” buscando entre los jugadores dados de alta a 4 personas que complementen las posiciones faltantes y estén en el mismo rango que el jugador.

	La página tendrá un botón de “buscar equipo”. Cuando el jugador pulse esta opción la página mostrará automáticamente el nombre de los 4 jugadores restantes, considerando las restricciones mencionadas, para que el usuario los busque dentro del juego y pueda hacer equipo con ellos.

	Podrán hacer log in los 5 tipos diferentes de usuarios dependiendo de su rol dentro del juego. Estos usuarios solo podrán buscar más jugadores y modificar su perfil.

	Otro tipo de usuario será el administrador, que podrá modificar o eliminar perfiles a su disposición. 

	HTML y CSS serán utilizados para el frontend de la página. Tendremos una pantalla de inicio con la opción de hacer log in o sign up. Después entraremos en la página principal que es donde el jugador podrá buscar a otros participantes. También tenemos la parte del perfil, donde el jugador verá su información.

	JS, PHP y MYSQL serán utilizados en la parte de la base de datos, en los registros, modificaciones y eliminaciones de cuentas de usuarios, también los utilizaremos para hacer las búsquedas de jugadores utilizando las especificaciones necesarias. PHP nos permite insertar las búsquedas dentro del mismo HTML, lo cual es indispensable para encontrar la información necesaria para cada jugador.
