# Cuestionario

A) ¿Qué comando utilizaste en el paso 11? ¿Por qué?  

> `git reset --hard HEAD~1`

> Porque el "hard" es para perder los cambio del working copy y el "HEAD~1" es para volver a la ùltima actualización.

B) ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?    
> `git reset (hash code de commit)`

> Así vuelvo al paso exacto que quiero llegar, en caso de hacer el clear, podemos usar el `git reflog`para recuperar todos los pasos.

C) El merge del paso 13, ¿Causó algún conflicto? ¿Por qué? 
> No causó ningún problema, porque el styled ya está encima del main.

D) El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
> No causó ningún problema, porque en dos ramas no hay cambios en el mismo lugar o fila.

E) El merge del paso 20, ¿Causó algún conflicto? ¿Por qué?
> No causó ningún conflicto, porque igual que antes, en dos ramas no hay cambios en el mismo lugar o fila.

F) El merge del paso 24, ¿Podría ser fast forward? ¿Por qué? 
> Se puede, porque no existe conflícto.

G) ¿Qué comando o comandos utilizaste en el paso 25? 
> `git reset --soft HEAD~1`

> Uso el --soft para no perder los cambios del working copy. 

H) ¿Qué comando o comandos utilizaste en el paso 26? 
> `git reset (hash code de commit) --hard 

I) ¿Qué comando o comandos utilizaste en el paso 27? 
> `git branch -d title` 

J) ¿Qué comando o comandos utilizaste en el paso 28? 
>  `git reset (hash code de commit)`

K) ¿Qué comando o comandos utilizaste en el paso 30? 
> `git reset (hash code de commit) -- hard`
> `git tag` 