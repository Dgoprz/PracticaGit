# Practica Git
## Respuestas

---

* ¿Qué comando utilizaste en el paso 11? ¿Por qué?
  * git reset --hard HEAD~1
  * Con el comando empleado volvemos al commit anterior y recuperamos el working copy del mismo

* ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
  * git reflog
  * git reset --hard d3aaaed
  * Empleado el reflog localizo el identificador del commit deseado y vuelvo a el con el reset 

* El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
  * En mi caso no ha causado pero entiendo de deberia haber pasado, ya que el paso 10 git-nuestro tenia un contenido distinto al del paso 4 que es donde apunta master.

* El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
  * Si, el conflicto es causado porque el git-nuestro en la rama styled tiene un contenido distinto al de htmlify en la mismas lineas

* El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
  * No, git-nuestro en ese punto esta sin cambios en mismas lineas

* ¿Qué comando o comandos utilizaste en el paso 25?
  * git log --graph --pretty=oneline

* El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
  * No, perderia acceso a un nodo del grafo

* ¿Qué comando o comandos utilizaste en el paso 27?
  * git reflog
  * git reset 8e67d9c

* ¿Qué comando o comandos utilizaste en el paso 28?
  * git reflog
  * git reset --hard 8e67d9c

* ¿Qué comando o comandos utilizaste en el paso 29?
  * git branch -D title

* ¿Qué comando o comandos utilizaste en el paso 30?
  * git reflog
  * git reset --hard 15075e1

* ¿Qué comando o comandos usaste en el paso 32?
  * git reflog
  * git reset f94a294

* ¿Qué comando o comandos usaste en el punto 33?
  * git reflog
  * git reset acfbbe2