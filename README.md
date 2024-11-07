# PrimerRepoGithub
Actividad 1 Parte 4
PARTE 4
1. Crear un repositorio en GitHub con el nombre PrimerRepoGithub
    1 New
    2 Teclear nombre
    3 Activar README
    4 Click en el botón Create Repository

2. Clonarlo en una carpeta de nuestro repositorio local.
    0 desde el cmd de nuestra carpeta
    1 git clone https://github.com/Alfredo4549/PrimerRepoGithub.git

3. Crear un archivo descripción.txt y hacer un commit. Hacer el push al repositorio de GitHub.
    git add.
    git commit -am "mensaje"
    git push

4. Comprobar los cambios en la web del repositorio.

5. Crear una rama con el nombre RamaDesarrolloFront y movernos a ella.
    git branch
    git branch RamaDesarrolloFront
    git checkout RamaDesarrolloFront

6. Crear un archivo index.html y hacer un commit. Hacer un push de la rama al repositorio de GiHub.
    git add .
    git commit -am "index.html creado"
    git push origin RamaDesarrolloFront

7. Comprobar la existencia de la rama y su contenido en la web del repositorio.

8. Hacer el merge de la rama RamaDesarrolloFront a la rama master. Hacer un push de la rama al repositorio de GitHub.
    git checkout main
    git merge RamaDesarrolloFront
    git push
    
9. Eliminar la rama RamaDesarrolloFront. Hacer un push de la rama al repositorio de GiHub y comprobar el resultado en la web del repositorio.
    git branch -d RamaDesarrolloFront
    git push origin --delete RamaDesarrolloFront

10. Etiquetar la versión actual de la rama main y actualizar la etiqueta en Github.
    git tag v1.0.0
    git push origin v1.0.0 