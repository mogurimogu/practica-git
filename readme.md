Práctica GitHub
===
* ¿Qué comando utilizaste en el paso 11? ¿Por qué?

  `$ git reset --hard HEAD~1`
        
        de esta forma se puede deshacer el ultimo commit perdiendo los cambios realizados en el working copy.

* ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?

  `$ git reflog`

  `$ git reset --hard 18acd13`

        Con esto puedo ver el último comit realizado y rehacerlo.

* El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?

  `$ git merge master`

        Estando dentro de la rama *styled* conseguimos que *master* sea absorbida
        Este paso no provocó ningún conflicto.

* El merge del paso 19, ¿Causó algún conflicto? ¿Por qué? 

  `$ git merge htmlify`

        Estando dentro de la rama *styled* conseguimos que *htmlify* sea absorbida
        Este paso si que provocó un conflicto dado a que econcontró cambios que chocaban en el archivo git-nuestro.md.

* El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?

  `$ git checkout styled`

  `$ git merge styled`

        Primero debemos cambiar a la rama master para despues poder hacer el merge de la rama styled dentro de master.
        Este proceso no provocó conflictos.

* ¿Qué comando o comandos utilizaste en el paso 25?

  `$ git log --graph`

        Con esto podemos ner un gráfico donde encontraremos el estado de nuestras distintas ramas y su evolución.

* El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
  
  `$ git merge --no-ff title`

        De esta forma podemos hacer un merge *Fast forward* de nuestra rama.

* ¿Qué comando o comandos utilizaste en el paso 27?

  `$ git reset HEAD~1`

        De esta forma podemos volver al punto anterior pero sin haber perdido los cambios del working copy.

* ¿Qué comando o comandos utilizaste en el paso 28?

  `$ git restore git-nuestro.md`

        Con esto restauraremos el archivo en la versión actual y perdiendo el working copy anterior.

* ¿Qué comando o comandos utilizaste en el paso 29?

  `$ git branch -D title`

        De esta forma podremos elinar esta rama ya que conteniene cambios que la rama master no tiene.

* ¿Qué comando o comandos utilizaste en el paso 30?

  `$ git reflog`
  
  `$ git reset --hard 1229908`

        De esta forma podemos rehacer los cambios realizados volviendo al último estado.

* ¿Qué comando o comandos usaste en el paso 32?

  `$ git reflog`
  
  `$ git reset --hard 48d4a1c`

        De esta forma podemos deshacer todos los cambios realizados volviendo al punto de la creación del poema


* ¿Qué comando o comandos usaste en el punto 33?

  `$ git reflog`
  
  `$ git reset --hard 1229908`

        De esta forma podemos rehacer los cambios realizados volviendo al último estado donde el título del pohema está creado.

