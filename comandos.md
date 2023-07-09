# BASICO

    git add ARCHIVO // agregamos en staged
    git rm nombreArchivo //removemos y lo ponemos en el staged
    cat archivo // nos muestra contenido del archivo
    git mv nombreArchivo NuevoNombreArchivo // tambien podemos cambiar su ubicacion
    git diff //vemos los cambios que estamos haciendo
    git log // vemos el historial pero a detalle
    git log --oneline // lo anterior pero mas simple

# BRANCH

    git branch // nos muestra las ramas y en cual nos encontramos
    git checkout -b nombreRama
    git checkout nombreRamaAMoverse
    git merge nombreRama // se tiene que hacer desde la rama main

# STATUS

    git status
    git status -s  //detalles mas simples

# QUITAR CAMBIOS QUE TENEMOS EN staged y recuperar archivos

    git restore --staged nombreArchivo //lo quitamos de staged
    git restore nombreArchivo //nos regresa el archivo  a como estamos ahorita

# COMMIT

    git commit -m "cambios"
    git commit // se abre un archivo donde escribimos los cambios

# IGNORAR archivos

debemos crear un archivo .gitignore y poner sus archivos y carpetas, se estara subiendo en el commit
