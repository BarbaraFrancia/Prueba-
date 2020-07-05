ls = listado de archivo
cd = moverse entre directorio
pwd = indica el lugar donde estas
clear = borra todo lo de la terminal
history = muestra todo lo que se borra
mkdir = crea una carpeta o directorio
con la fecha hacia arriba, se puede ver lo ultimo que usaste en la terminal
rm = remover o borrar
cat = para ver archivos
cat nombrearchivo > copiaarchivo = copiar archivo 
more = para ver archivos en bloque


**Clase de GitHub**

git init = inicializar repositorio
git add . = agregar todos los archivos que queremos enlistar (solo si usamos el punto suben todos, sino solo podemos colocar el nombre del archivo y va subir el que queremos)
git commit -m = se usa para subir y le agregas un comentario
git log = es para revisar todos los commit hechos 
git checkout -- nombre de archivo = no guardar y volver al último commit
git reset --soft (id de git log) = volver a commit anterior sin borrar cambios
git reset --hard (id de git log) = volver a commit anterior borrando todo
git branch = listar ramas
git checkout -b nombre de rama = cambio y creación de rama
git rebase + nombre de rama = unifica los cambios pero los commit de la rama se pierden
git merge + nombre de rama = unifica los cambios manteniendo los commit en la rama 