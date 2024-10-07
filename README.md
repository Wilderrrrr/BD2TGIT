# BD2TGIT
Wilder Fabián Valdés Cruz - 2262576



Taller - Git

Primer paso: ya contaba con una cuenta de Github por lo que el paso 0 lo he omitido, he creado el
proyecto, he configurado mi nombre de usuario y contraseña satisfactoriamente.

Segundo paso: he creado la rama feature (en mi caso, la rama master no se creó automaticamente
por lo que lo he hecho de forma manual) e hice los commits.

Tercer paso: se completó satisfactoriamente el 'merge' y el 'rebase'.

Cuarto paso: aqui, se utilizo de manual el 'cherry-pick' cómo especificaba en el documento (Más
adelante utilizo el 'reflog' y explico la solución del conflicto con ayuda de este comando).

Quinto paso: la creación del conflicto surgió a partir de intentar hacer cambios a un mismo archivo
desde dos ramas direfentes.



Solución del conflicto
Se utilizó el 'reflog' para mostrar el historial de las acciones que se habian hecho dentro del proyecto
e identificar la parte exacta donde se habia presentado el conflicto, el conflicto estaba en el archivo
conflicto.txt por lo que se editó manualmente, se guardo, se añadió nuevamente y se le hizo el commit.

Otra alternativa más directa con 'reflog' era hacer un checkout en la acción anterior al conflicto para
evitarlo utilizando el comando: 'git checkout' y la acción exacta.

Una vez hecho esto, ya tenemos solucionado el conflicto. En el "log.txt" ejecuto algunos comandos extras
para asegurarme de que no hayan problemas.
