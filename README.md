# Pablo Márquez López

## Este es el link del repositorio donde se encuentran las respuestas del examen: https://github.com/pablomarquezuax/Marquez_Pablo.git

1) Un **pull request** es una función de GitHub utilizada normalmente por desarrolladores que trabajan en grupo, ya que hace mucho más facil la colaboración entra distintos programadores que están trabajando en un mismo proyecto o código. Cuando un progrmamador edita el código de un repositorio de otra persona (tanto desde local como desde el propio GitHub), puede mandar los cambios mediante el pull request. Al hacerlo, el dueño del repositorio puede ver que cambios ha realizado en los diferentes archivos o si ha añadido otros. Si el trabajo del desarrollador está bien, el dueño del repositorio puede elegir aprobar el pull request y hacer un merge para que este trabajo quede añadido al repositorio.

2) Al hacer un **merge**, es posible que exista un conflicto de fusión entre el fichero original y el que se pretende integrar. Esto se puede dar porque algunas partes se hayan sobrescrito o por otras muchas razones. Para poder solucionarlo, solo es necesario abrir un editor de texto para poder ver qué conflictos se han creado y poder solucionarlos manualmente. Una vez estos conflictos se hayan solucionado, el merge podrá ser llevado a cabo sin problema.

3) Existen varias opciones de cara a hacer un merge de diferentes ramas dentro de un mismo repositorio. Si lo queremos ejecutar desde el terminal, debemos ejecutar primero el comando "git checkout main" para situarnos en la rama main. Seguidamente, debemos ejecutar "git merge examen_parcial". Después, hacemos "git push" y, si no ha surgido ningún conflicto, el merge se habría realizado correctamente. Por otro lado, el merge de dos ramas se puede hacer también desde GitHub desktop si elegimos que rama queremos mergear dentro de la otra y haciendo el push desde la propia aplicación.

4) A través del comando "git reset" es posible eliminar los cambios realizados. Por otro lado, si el error se encuentra en el nombre del commit, también se puede ejecutar el comando "git commit --amend"

5) Cuando se pretende realizar cambios en un repositorio que no es tuyo, es necesario realizar un Fork, esto se hace entrando en el repositorio desde GitHub y pulsando el botón de "Fork", que se encuentra en la esquina superior derecha. Mediante esta función, se copiará dicho repositorio en tu cuenta de GitHub, donde se pueden hacer los cambios pertinentes y seguidamente realizar un pull request al repositorio original si se pretende que el autor del repositorio incluya las cambios en su código.

6) A) Dado que el archivo "archivo.txt" está dentro del directorio "UAX", este es el directorio al que se pretende acceder. Por lo tanto, el comando que se debe ejecutar en el terminal es "cd UAX", el cual nos llevará directamente a dicho directorio. Se trata de una ruta absoluta, dado que estamos pasando por todos los directorios existentes en la ruta absoluta para llegar a "UAX".

   B) Dentro del directorio Universidad, también se podría utilizar el comando "cd UAX", el cual nos llevaría al directorio que contiene el archivo "archivo.txt". Esto se trata de una ruta relativa, puesto que no se parte del directorio raíz.

7)
  1. b) git clone
  2. a) git branch
  3. c) git checkout
  4. b) git add
  5. b) git commit
  6. b) git push
  7. c) git pull
  8. d) git merge
  9. a) git reset --hard
  10. c) git log


8)
 - En primer lugar, antes de realizar el merge, es imprescindible asegurarse de que no se ha eliminado información importante, ni se van a introducir archivos corruptos a la rama de desarrollo, que puedan arriesgar la integridad del programa.
  
   - Seguidamente, de cara a empezar a realizar el merge, habría que ejecutar el comando "git checkout develop", para situarse en la rama en la cual se pretende integrar la nueva rama.
     
   - Después, se debe ejecutar el comando "git merge diseño-UX", mediante el cual se intentaría realizar la función de merge. No obstante, si no es un merge fast-forward, cabe la posibilidad de que puedan surgir conflictos en la integración de las ramas.
     
   - Si esto sucede, se debe abrir el editor de texto y arreglar manualmente los posibles conflictos, dado que es un código importante y no se puede ejecutar el "merge --hard", puesto que no se puede correr el riesgo de la posible pérdida de información.
     
   - Una vez todos los conflictos han sido solucionados, se puede llevar a cabo el "git push", que haría que estos cambios se guarden en el repositorio remoto.
     
   - Finalmente, con el fin de comprobar que no ha habido ningún error en los cambios, se puede ejecutar "git diff", el cual mostraría los cambios que han sucedido en el codigo, lo cual haría mas facil la identificación de posibles errores sucedido en el merge.
  
9) C) Añadiste el botón "x^4" al archivo "index.html" en tu repositorio local, creaste un commit con los cambios y luego subiste el repositorio local al remoto en la rama principal (master).
