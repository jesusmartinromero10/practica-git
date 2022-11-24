- ¿Qué comando utilizaste en el paso 11? ¿Por qué?
        Utilice el comando git reset --hard HEAD~1
        Porque el --hard hace que se pierda lo que habia en el working copy

- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
        Primero hice un git reflog y luego un git reset y el id del commit al que queremos ir

- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
        No porque hicimos una restauracion con la perdida de la informacion asi que en ese punto 
tienen los dos la misma informacion

- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
        si hay conflictosolo han agregado codigo html y eso al parecer se considera cambio

- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
        No causo conflicto porque ya eran iguales anteriormente

- ¿Qué comando o comandos utilizaste en el paso 25?
        git log --graph

- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
        si porque estan en el mismo commit
        
- ¿Qué comando o comandos utilizaste en el paso 27?
        git reset head~1

- ¿Qué comando o comandos utilizaste en el paso 28?
        git checkout -- git-nuestro.md

- ¿Qué comando o comandos utilizaste en el paso 29?
        git branch -D title

- ¿Qué comando o comandos utilizaste en el paso 30?
        git reflog y luego git reset e id del commit

- ¿Qué comando o comandos usaste en el paso 32?
      git log y luego git reset y id commit primero


- ¿Qué comando o comandos usaste en el punto 33?
        git reflog y busco crear titulo y luego git reset e id commit
