# git_practica
Practica GIT del bootcamp

-�Qu� comando utilizaste en el paso 11?
git reset --hard HEAD~1
 �Por qu�? 
git reset HEAD~1 vuelve 1 vez atr�s

-�Qu� comando o comandos utilizaste en el paso 12? �Por qu�? 
git reflog para coger el "id" al que quiero volver
git reset "id"
git checkout -- git-nuestro.md para descartar cambios

-El merge del paso 13, �Caus� alg�n conflicto? �Por qu�?
No causa conflicto porque styles es hijo de master.

-El merge del paso 19, �Caus� alg�n conflicto? �Por qu�? 
Si, porque 'htmlify' y 'styles' tienen diferente contenido

-El merge del paso 21, �Caus� alg�n conflicto? �Por qu�? 
No, "master" absorbe a "styled" y se queda con sus cambios

-�Qu� comando o comandos utilizaste en el paso 25? 
git log --graph

-El merge del paso 26, �Podr�a ser fast forward? �Por qu�?
S�, porque forman una lista.

-�Qu� comando o comandos utilizaste en el paso 27?
git reset HEAD~1

-�Qu� comando o comandos utilizaste en el paso 28?
git checkout -- git-nuestro.md

-�Qu� comando o comandos utilizaste en el paso 29?
git branch -D title

-�Qu� comando o comandos utilizaste en el paso 30?
git reflog para coger el "id" al que quiero volver
git reset "id"
git checkout -- git-nuestro.md para descartar cambios

-�Qu� comando o comandos usaste en el paso 32?
git reflog para coger el "id" al que quiero volver (el del commit inicial)
git reset "id"

-�Qu� comando o comandos usaste en el punto 33?
git reflog para coger el "id" al que quiero volver (donde se puso el titulo)
git reset "id"