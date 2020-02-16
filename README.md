# Respuestas

## ¿Qué comando utilizaste en el paso 11? ¿Por qué?

`git reset —hard HEAD~1`

Un git reset normal mantiene lo que hay en el working copy.

## ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?


`git reflog`

`git reset --hard 854a0e1`

## El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?

No causa conflicto porque no hay cambios en master del fichero git-nuestro.md que no estén ya en la rama styled

## El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?

Si causa conflicto porque hay cambios en htmlify del fichero git-nuestro.md que no estan en la rama styled

## El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?

No causa conflicto porque no hay cambios en master del fichero git-nuestro.md que no estén ya en la rama styled

## ¿Qué comando o comandos utilizaste en el paso 25?

`git log --graph`

## El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?

Si porque el histórico entre las ramas master y title es lineal

## ¿Qué comando o comandos utilizaste en el paso 27?

`git reset HEAD~1`

## ¿Qué comando o comandos utilizaste en el paso 28?

`git checkout -- git-nuestro.md`

## ¿Qué comando o comandos utilizaste en el paso 29?

`git branch -D title`

## ¿Qué comando o comandos utilizaste en el paso 30?

`git reflog`

`git reset --hard 58ffb1e`

## ¿Qué comando o comandos usaste en el paso 32?

`git reset --hard 51649a8e1e2d8642d4b2bfc32448be7df0f4da3b`

## ¿Qué comando o comandos usaste en el punto 33?

`git reflog`

`git reset --hard 58ffb1e`
