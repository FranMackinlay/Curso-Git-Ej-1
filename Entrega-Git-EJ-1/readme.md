- ¿Qué comando utilizaste en el paso 11? ¿Por qué?
Usé el comando “git reses —hard HEAD~1” ya que me permite deshacer el último commit y al mismo tiempo perder los cambios realizados en el working copy.
 - ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
Usé “git reflog” para buscar el identificador de commit que había deshecho y después “git reset —hard <identificador>” para volver al commit deshecho.
 - El merge del paso 13, ¿Causó algún conflicto? ¿Por qué? 
No causo ningún conflicto ya que las dos ramas se encontraban en forma de lista y no se modifico el mismo archivo en dos lineas iguales.
- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué? 
Causo conflicto ya que existían dos versiones del mismo archivo en ramas distintas pero en la misma linea.
- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué? 
No causo conflicto, por que master se movió en la misma linea hasta styled ya que formaban una lista.
- ¿Qué comando o comandos utilizaste en el paso 25?
Usé el comando “git log —graph” (como es poca información decidí no usar “—pretty=oneline”)
 - El merge del paso 26, ¿Podría ser fast forward? ¿Por qué? 
No, por que se perdería el trabajo hecho en la rama styles.
- ¿Qué comando o comandos utilizaste en el paso 27?
Usé el comando “git reset HEAD~1” 
- ¿Qué comando o comandos utilizaste en el paso 28? 
Usé el comando “git checkout — git-nuestro.md”
- ¿Qué comando o comandos utilizaste en el paso 29? 
Usé el comando “git branch -D title”
- ¿Qué comando o comandos utilizaste en el paso 30? 
Usé “git reflog” para encontrar el identificador del merge deshecho y después
“git reset —hard <identificador>”
- ¿Qué comando o comandos usaste en el paso 32? 
Usé “git reflog” para buscar el identificador del commit inicial y después
“git checkout <identificador>”.
- ¿Qué comando o comandos usaste en el punto 33? 
Usé “git reflog” para buscar el identificador del commit inicial y después
“git reset —hard <identificador>”.
