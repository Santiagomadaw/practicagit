Ejercicio 1
Se deberá crear un repositorio y realizar una serie de operaciones desde la consola de
comandos sobre el mismo para posteriormente subir el repositorio a Github.
Se deberá entregar a través del formulario de prácticas indicando la URL del repositorio. En el
repositorio, deberá existir un archivo readme.md con las respuestas a las siguientes preguntas:

- ¿Qué comando utilizaste en el paso 11? ¿Por qué?
    > ```git reset --hard HEAD~1```  
    Para hara volver al estado de cambios anterior y que estos se viesen reflejados en el area de trabajo

- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
    > ```git reflog```
    > Para poder ver el id del commit que quiero recuperar.

    > ```git reset --hard fd6b782```
    > Me coloco en ese commit usando --hard para que afecte a mi working area
- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
    > No, no puede causar ningun conflicto ya que al ser un commit hijo el que absorbe al comit padre
    
    > no hay cambios que incorporar. En caso contrario si se hubiese producido un merge fast fordward
- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
    > Si, al ser 2 ramas con cambios en las mismas lineas se produce un conflicto que hay que resolver
    > para poder completar el merge
- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
    > En este caso la rama main incorpora los cambios de styled. Por defecto este es un fast fordware y no 
    > crea un nuevo commit 
- ¿Qué comando o comandos utilizaste en el paso 25?
    >```git log --graph```
- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
    >```git merge --no-ff title```
    > Si, al title es hijo directo de de main se podria hacer un FF

- ¿Qué comando o comandos utilizaste en el paso 27?
    >```git reset HEAD~1```
- ¿Qué comando o comandos utilizaste en el paso 28?
    >```restore git-nuestro.md```
- ¿Qué comando o comandos utilizaste en el paso 29?
    >```git branch -D title```
- ¿Qué comando o comandos utilizaste en el paso 30?
    > ```git reset --hard 4673389```
- ¿Qué comando o comandos usaste en el paso 32?
    >```git reset b343294f3555fb8e5287397c2551bf1d12ee4982```

    >El caso de querer que cambie el working area

    >```git reset --hard b343294f3555fb8e5287397c2551bf1d12ee4982```
- ¿Qué comando o comandos usaste en el punto 33?
    > ```git reset 467338974d8d2694ff1a8a35405927bd0f17530c```
    
    > En caso de haber usado --hard en el paso anterior

    > ```git reset --hard 467338974d8d2694ff1a8a35405927bd0f17530c```