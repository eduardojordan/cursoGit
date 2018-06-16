11- Deshacer el último commit (perdiendo los cambios realizados en el working copy)
#### ¿Qué comando utilizaste en el paso 11? ¿Por qué?

```
git reset --hard HEAD~1

```
Este comando elimina sin conservar datos.


-
12.- Rehacer el último commit ( el que acabamos de hacer )
###¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?

```
git reflog
git checkout (+NumeroDeCommit)

```
-

13.- Hacer un merge con 'master' ( styled absorve a master )
### El merge del paso 13, ¿Causó algún conflicto? ¿Por qué? 

```
git merge master

```

No realmente, en source tree es muy sencillo aplicando control y click  sobre la rama despliega la opción de forma sencilla 

-
Hacer un merge "htmlify" en "styled" (styled absorbe a htmlify)

###El merge del paso 19, ¿Causó algún conflicto? ¿Por qué? 


```
git merge htmlify 
```
Si hubo conflicto por diferencia de formato

-

21.- Desde "master" , hacer un merge con "styled"

### El merge del paso 21, ¿Causó algún conflicto? ¿Por qué? - 

```
No hay conflicto, porque los nodos de las ramas forman una lista
```

-
-¿Qué comando o comandos utilizaste en el paso 25? 
###Este comando dibuja por consola las ramas, aunque source tree también es muy gráfico en esto

```
git log --graph 

```
-

26.- Hacer un merge “no fast-forward” de “title” en “master” (master absorbe a title)

###El merge del paso 26, ¿Podría ser fast forward? ¿Por qué? 

```
 git merge --no-ff title
```

La opcion de fast foward cambia el puntero y master y HEAD se mueven juntos

-
27.-Deshacer el merge ( sin perder los cambios del working copy)

### ¿Qué comando o comandos utilizaste en el paso 27? 

```
git reset HEAD~1
```

-
28) Descartar los cambios
### Qué comando o comandos utilizaste en el paso 28?

```
git checkout - - git-nuestro.md
```
-

###¿Qué comando o comandos utilizaste en el paso 29? 
En sourcetree simplemente se selecciona la rama y con control + click despliega las opciones Delete XXX


```
git branch -D title
```
-
###¿Qué comando o comandos utilizaste en el paso 30?
```
git reflog
git checkout (+NumeroDeCommit)
```
-
-32.- Volver al commit inicial cuando se creó el poema
###¿Qué comando o comandos usaste en el paso 32? 

Realmente no utilice ningún comando pues en sourcetree con pararte sobre la rama y ver a la vez que verificar el commit
pero puedo usar git log para ver y buscar el commit que necesite.

``` 
git reflog
git checkout (+NumeroDeCommit)
```

-

33) Volver al estado final, cuando pusimos título al poema
###¿Qué comando o comandos usaste en el punto 33? 


```
git reflog 

git checkout 
```