# GITHUB: 

	* Repositorio de control de versiones y compartición  


01.- Los repositorios pueden ser públicos o privados y nos servirán como carta de presentación. 
 
02.- Crear un repositorio offline antes de vincularlo, por ejemplo, con GITHUB: git init <nombre>  

03.- Se recomienda clonar el repo github web en local, bien para trabajarlo de forma interna o bien como copia de seguridad antes de realizar un "pull" a local desde el repositorio web de GitHub, por si se hubieran realizado cambios vía web.  

	* Command: git clone https://github.com/arodmas/master_data_science.git [dir_clone]    

04.- Si el directorio en el que estamos el prompt presenta un +-, estamos en repo git.  

05.- Crear un repositorio offline antes de git init <nombre> = creamos un repositorio offline antes de vincularlo con GITHUB por ejemplo
en los GIT no se meten binarios. SON LAS DIFERENCIAS (solo ficheros de texto)

05.- Si el directorio en el que estamos el prompt presenta un +-, estamos en repo git.  

06.- Tipeamos git status y git log para ver el estado de nuestro repo y los metadatos de los últimos cambios realizados.  

	* Origin es el repositorio remoto

	* Si la cabecera que muestra en comando: git log; (HEAD -> master, origin/master, origin/HEAD) no estuviera en la misma línea, tendríamos cambios sin sincronizar con GITHUB (web).  

07.- Utilizamos un editor de texto compatible con nuestro sistema (preferiblemente Linux) en el que poder guardar ficheros de tipo ".md"  

08.- Un ejemplo de "MARCAS DEL MARKDOWN" para formateo de trabajo en git desde cualquier formato plano, es:  

	# kkkkkk que es interpretable como el titulo kkkkkk  

09.- Es recomendable realizar cambios pequeños y frecuentes para trabajar en equipo.  

10.- Los cambios en local no son instantáneos en git, tenemos que hacerlo concientemente.  

11.- Una vez salvados los cambios en el fichero correspondiente, debemos marcarlo para subir con el comando: git add <file_name>

12.- Comprobamos de nuevo el estado del repositorio: git status

13.- Ahora, validamos los cambios en el repo local con: git commit (nos abrirá el editor nano para documentar los cambios realizados), o bien typeamos: git commit -m "mensaje de los cambios realizados".  

	* Si utilizamos el editor nano, para guardar las explicaciones pulsamos CTRL+O, RETURN y CTRL+X para salir.  

14.- El siguiente paso es publicar el cambio en el repo del GITHUB, con el comando: git push  

	* IMPORTANTE: Se publicarán todos los cambios versionados. Es decir, lo ultimo y toda la historia anterior.  

		      De no querer publicar todo el contenido, la solución pasaría por sobreescribir el REPO.  

15.- Tanto los PULL, como los PUSH, se recomiendan que sean frecuentes.  

