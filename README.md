# Ejercicio-1 respuestas

- ¿Qué comando utilizaste en el paso 11? ¿Por qué? 
Utilice el comando “git reset -- hard” ya que lo que pide el enunciado es que se pierdan los cambios realizados en el working copy


- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
Utilice el comando “git reflog” para ver el listado de movimientos que ha habido en nuestro repositorio y asi encontrar el hash del commit que habiamos deshecho en el paso anterior.
Entonces en este caso utilizamos, tambien, el comando “git reset —hard f6280e0” que nos devuelve al commit que habiamos deshecho


- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué? 
No causó ningun conflicto


-  El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?  
  
Si, causó un conflicto, debido a que el mismo fichero “git-nuestro.md” al hacer el merge, tiene distinto contenido en las mismas lineas del mismo fichero


- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?  
El merge del paso 21 no causo ningun conflicto debido a que era un merge fast forward, por lo tanto era como un “commit nuevo”


-  ¿Qué comando o comandos utilizaste en el paso 25?  
Se usa el comando “git log —graph”


-  El merge del paso 26, ¿Podría ser fast forward? ¿Por qué? 
Si, el merge podia ser fast forward, ya que no se habia continuado trabajando en la rama “master”, por lo tanto no era necesario crear un commit especifico para el merge de ambos (master-title)


-  ¿Qué comando o comandos utilizaste en el paso 27? 
uso el comando “git reset HEAD~1”


-  ¿Qué comando o comandos utilizaste en el paso 28? 
  git restore git-nuestro.md 
  
  
-  ¿Qué comando o comandos utilizaste en el paso 29?
git branch -D title


-  ¿Qué comando o comandos utilizaste en el paso 30? 
git checkout 15f7787 y luego git branch title (crear la rama de nuevo) y git merge --no-ff title


-  ¿Qué comando o comandos usaste en el paso 32? 
git checkout 7009b9c


-  ¿Qué comando o comandos usaste en el punto 33? 
git checkout 5a7246f
