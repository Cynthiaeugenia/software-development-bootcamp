#Software Development Bootcamp

Este repositorio contiene mi progreso durante mi preparación intensiva como desarrollladora de sorftware

##Día 1 

Git y GitHub

## Sección de Tecnología 

Descripción de conceptos de Git / GitHub 

Repsitory: Espacio donde podemos trabajar y realizar nuestras actualizaciones o modificaciones en el.

Git: Sistema de control de versiones que nos permite hacer modificaciones, registrar y administrar cambios en proyectos de manera local.

GitHub: Repositorio Remoto en la nube donde varias personas pueden trabajar a la vez en un mismo proyecto y realizar diversas acciones.

Commit: Foto o versión que se queda cada que realizamos modificaciones a nuestros proyectos conectados a Git. Para ejecutar este comando antes es necesario preparar los cambios de nuestros archivos con Add antes de ejecutar Commmit.

Add: Se ejecuta una vez que tengamos listos y estemos conformes con los cambios se ejecuta antes de commit ya que este es el que prepara los archivos con los cambios realizados.

##Git WorkFlow
En esta sección explicare como es el proceso que se lleva para crear nuevos cambios en un repositorio de git desde otra rama que no sea la principal para no afectar con los cambios que hayamos realizado con el fin de cumplir con un flujo de trabajo de un entorno real y profesional, lo haremos de manera local en Git como de manera remota en GitHub.

Sigue los siguientes pasos para realizar cambios desde una nueva rama y fimalizar con merge en ambos repositorios:

1. En la terminal ejecuta git status, este nos ayudara a saber el estado de nuestro proyecto y ver en que rama estamos localizados.

2. Creamos una nueva rama la cual será sobre la que estemos realizando los cambios que se nos fuerón solicitados. 
Esta la nombraremos con un nombre profesional y relacionado a lo que cumplira dicha rama.

3. Una vez creada nuestra rama ejecutamos git branch que nos dará la rama en la que actualmente nos encontramos, 
si nos encontramos en la nueva rama que creamos nos quedamos ahi y si no es así ejecutamos git switch (nombre de la rama), para que nos cambie a la rama sobre la que trabajaremos.

4. Cuando ya nos encontremos sobre la rama en la que queremos trabajar realizamos todoas las modificaciones e implementaciones al código.

5. Una vez que tengamos nuestro código completamernte listo y estemos seguros de ello, guardamos el documento y ejecutamos git status, para ver la rama en la que nos encontramos y nos mostrara los cambios que hemos hecho y de los cuales tenemos pendiente hacer add y commit.

6. Enseguida ponemos en nuestra terminal git add "nombre del documeto(s)", esto nos ayudará a preparar nuestros archivos sobre los que hicimos cambios para antes de hacer commit.

7. Ejecutamos git commit -m ("Comentario sobre lo que hiciste") para guardar los cambios que hemos hecho en esta versión.

8. Comprobamos con git add remote "URL de nuestro repositorio de GiHub", que estemos conectados.

9. Creamos nuestra rama en el repositorio remoto ejecutando el siguiente comando en la terminal git push -u origin (Nombre de la rama)

9. Una vez que vericamos que estamos correctamente conectados, ponemos en la terminal git push y nos vamos para Gnuestro repositorio de GitHub.

10. En GitHub nos apareceran los cambios que hemos realizado y los cammits que tenemos, al igual que los Files Changed que hemos echo y que podemos revisar para verificar todos nuestros cambios.

11. Aqui en GitHub presionamos Pull request e ingresamos la documentación de nuestra Pull Request, donde tiene que responder a las preguntas de, ¿Qué fue cambiado?, ¿Por qué? y ¿cómo fue probado?, esto tiene que redactarse de manera clara y consisa en ingles renpondiendo de manera rápida y breve, lo publicamos.

12. Aqui debemos de esperar a que un Reviewer nos apruebe los cambios que hemos realizado y que nos de luz verde para hacer el Merge, si es que el Reviewer nos dice que hagamos ciertos cambios los debemos de realizar siguiendo el mismo flujo pero sobre la misma Pull Request (no hace falta abrir otra).

14. Cuando ya nos dijierón que nuestro código y la documentación de la Pull Request estan bien para poder hacer Merge, en GitHub nos vamos a Merge confirmamos y ya tendriamos listo nuestro Merge en GitHub.

15. Limpiamos nuestro repositorio remoto para tener eficiencia y evitar confusiones, nos vamos a la sección de branches y borramos la rama que creamos ya que ahora esta enlazada a la rama Main y esa rama ya tiene los cambios, así que ya no hace falta la otra.

16. Nos dirigimos de nuevo hacia Visual Studio Code hacia nuestra terminal podemos obsertvar que aquí no tenemos el Merge hecho aún, ejecutamos git status, para verificar en que rama estamos y si no estamos en nuestra rama principal nos cambiamos a la rama principal con switch.

17. Una vez que nos encontramos en nuestra rama principal damos git pull y de esta manera ya tenemos nuestros dos repositorios sincronizados y ya en ambos esta el merge realizado.

18. Hacemos la limíeza en el repositorio local con git branch -d (Nombre de la rama), borramos la rama que cremos porque los cambios ya se encuentran implementados en la Main Brach.

19. Listo así es como tenemos de manera exitosa nuestro nuevos cambios incororados a la Main brach sin romper nada de ella y siguiendo un flujo 100% profesional.