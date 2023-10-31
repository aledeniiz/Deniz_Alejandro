# Deniz_Alejandro
1º Explica que es un “Pull Request”:
Una pull request es una solicitud que se hace a un repositorio para descargar informacion que este contiene, y a su vez tener acceso a él.

2ª ¿Qué es un conflicto de fusión (merge conflict) en Git? 
Un merge confilct es un porblema que git bash u otra consola ha tenido al tratar de mezclar dos archivos, commits... para mezclar sus informaciones; pero git ha detectado que no se puede mezclar porque en esas informaciones hay caracteres que nos compatibles con el proceso. 
Yo lo que haría sería primero de todo poner git status y ver que está fallando exactamente. De ahí intentaria hacer nano a la información que trato de mergear o mezclar para eliminar partes de él que yo vea innecesarias o que sobren. En caso de que esto no funcione haría un git merge --continue para tratar de forrzarlo a finalizar el merge.

3º Imaginemos que tenemos dos ramas, la principal llamada “main” y la rama “examen_parcial”. ¿Qué procedimiento se debería seguir para fusionar (merge) ambas ramas?
Lo que hará ería desde la rama main hacer un git checkout examen parcial para entrar a la rama examen parcial y de ahí escribiría git merge main, para mezclar ambas ramas desde la rama examen_parcial. Después volvería a la rama main y pondria git merge examen_parcial para tambien hacer la mezcla desde ahí .

4º Has realizado un commit, pero luego descubres un error importante en los cambios que has incluido. Necesitas revertir este último commit para regresar tu proyecto al estado anterior, pero deseas mantener los cambios realizados en tu área de trabajo. 
Utilizaría el comando git reset --hard, seguido del codigo alfanumérico del commit. Así daría a entender a git que debe revertir los cambios en ese commit, incluyendo la información de sus archivos.

5º ¿Cómo se realiza un fork de un repositorio en GitHub y para qué se utiliza comúnmente esta acción?
Fork de un repositorio de github se realiza desde la misma plataforma de github con un  botón muy intuitivo. Lo que hace esto es editar un repositorio ajeno a ti y hacer una version de él por tu cuenta, realizandole cambios. El propietario del documento puede ver que se le ha hecho un fork.

7º Te han asignado la tarea de trabajar en un proyecto de código abierto alojado en GitHub. Como nuevo colaborador, se espera que sigas las mejores prácticas para el manejo del código fuente utilizando Git.
1 b) git clone
2 a) git branch
3 c) git checkout
4 b) git add
5 b) git commit
6 b) git push
7 c) git pull
8 d) git merge
9 a) git reset --hard
10 c) git log

8º Lo primero que haría sería un git merge desde la rama develop hasta la rama matemáticas y Diseño UX. Utilizaria git status en caso de tener algún problema y editaría algun archivo conflictivo. Desde ahí haría un git rebase para organizar los commits y haría pick o edit a los que fueran necesarios para dejar toda la información recopilada de la mejor manera posible.

9º C) Añadiste el botón "x^4" al archivo "index.html" en tu repositorio local, creaste un commit con los cambios y luego subiste el repositorio local al remoto en la rama principal (master).
