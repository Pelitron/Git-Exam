# Git-Exam
Examen de Git


- ¿Qué comando utilizaste en el paso 11? ¿Por qué?

  git reset --hard HEAD~1. Se pedia perder los cambios del working copy
  
- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
  
  git reflog, git reset --hard 35936f8. Primero miro el historil y busco a la posición que me quiero mover. Copio y pego el hash en el git reset --hard <hash del commint>
  
- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
  
  git merge main. No genera conflicto debido a que no se solapan los cambios producidos
  
- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
  
  Si, porque hay dos posibles cambios y al comparar el archivo (por detrás hay una especie de diff) entra en conflicto y la máquina pide al humano que por favor seleccione el cambio que le interese
  
- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
  
  No se hace un fast-forward desde la rama main a una subrama
  
- ¿Qué comando o comandos utilizaste en el paso 25?
  
  git log --graph --decorate --pretty=oneline
  
- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
  
  Si, porque une title desde main
  
- ¿Qué comando o comandos utilizaste en el paso 27?
  
  git reset HEAD~1
  
- ¿Qué comando o comandos utilizaste en el paso 28?
  
  git checkout .
  
- ¿Qué comando o comandos utilizaste en el paso 29?
  
  git branch -D title
  
- ¿Qué comando o comandos utilizaste en el paso 30?
  
  git reflog
  git checkout 7302d92
  
- ¿Qué comando o comandos usaste en el paso 32?
  
  git reflog
  git reset --hard c5e38f1
  
- ¿Qué comando o comandos usaste en el punto 33?
  
  git reset --hard 21b7224

- Comandos de los tags
  
  git tag inicial c5e38f1
  
  git tag styled 35936f8
  
  git tag htmlify baa9809
  
  git tag title 7302d92

- Comando para subir ramas
  
  git push --all origin

- Comando para subir tags
  
  git push --tags origin

-Comando para crear y moverse a una rama

  git checkout -b <nombre de la rama nueva>

