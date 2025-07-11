
git grep [texto]
<!-- Busca todas las líneas que contengan una palabra en el proyecto -->
git grep [texto] -- [archivo]
<!-- Busca solo en archivos específicos -->
git grep [texto] HEAD
<!-- Busca en el ultimo commit -->
git grep [texto] [hash]
<!-- Busca en un commit específico -->
git grep [texto] [rama]
<!-- Busca en una rama especifica -->
git grep -i [texto]
<!-- Ignora mayúsculas/minúsculas -->
git grep -w [texto]
<!-- Coincidencias exactas de palabras -->
git grep --count [texto]
<!-- Muestra solo la cantidad de coincidencias por archivo -->

git stash
<!-- Guarda todos los cambios actuales y limpia el directorio -->
git stash push -m [mensaje]
<!-- Guarda cambios con un mensaje personalizado -->
git stash pop
<!-- Aplica y elimina el stash más reciente -->
git stash apply stash@{[numero]}
<!-- Aplica los cambios de un stash específico (pero no lo borra de la pila) -->
git stash drop stash@{[numero]}
<!-- Elimina un stash específico -->
git stash list
<!-- Muestra todas las stashes guardadas -->
git stash show
<!-- Muestra los cambios del stash más reciente -->
git stash clear
<!-- Elimina todos los stashes guardados -->