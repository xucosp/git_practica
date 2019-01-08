# git_practica
Practica GIT del bootcamp

-¿Qué comando utilizaste en el paso 11?
git reset --hard HEAD~1
 ¿Por qué? 
git reset HEAD~1 vuelve 1 vez atrás

-¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué? 
git reflog para coger el "id" al que quiero volver
git reset "id"
git checkout -- git-nuestro.md para descartar cambios

-El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
No causa conflicto porque styles es hijo de master.

-El merge del paso 19, ¿Causó algún conflicto? ¿Por qué? 
Si, porque 'htmlify' y 'styles' tienen diferente contenido

-El merge del paso 21, ¿Causó algún conflicto? ¿Por qué? 
No, "master" absorbe a "styled" y se queda con sus cambios

-¿Qué comando o comandos utilizaste en el paso 25? 
git log --graph

-El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
Sí, porque forman una lista.

-¿Qué comando o comandos utilizaste en el paso 27?
git reset HEAD~1

-¿Qué comando o comandos utilizaste en el paso 28?
git checkout -- git-nuestro.md

-¿Qué comando o comandos utilizaste en el paso 29?
git branch -D title

-¿Qué comando o comandos utilizaste en el paso 30?
git reflog para coger el "id" al que quiero volver
git reset "id"
git checkout -- git-nuestro.md para descartar cambios

-¿Qué comando o comandos usaste en el paso 32?
git reflog para coger el "id" al que quiero volver (el del commit inicial)
git reset "id"

-¿Qué comando o comandos usaste en el punto 33?
git reflog para coger el "id" al que quiero volver (donde se puso el titulo)
git reset "id"