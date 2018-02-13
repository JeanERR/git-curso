#git add <file>
Agrega archivos a la zona de preparacion(stage)
#git commit -m "Descripcion de commit"
HAce el commit del archivo del stage o lo valida
#git rm <file>
Borra un archivo desde Git
#git mv <old_file> <new_file>
Renombra un archivo
#git commit --amend -m "Nueva descripcion del archivo"
Renombre el ultimo commit que se realizo
#git status
Muestra los archivos que se realizo alguna accion
#git reset HEAD <file>
saca el archivo del stage y lo devuelve al directorio
#git checkout -- <file>
Descarta las modificaciones al archivo
#git checkout <hash del commit>
vuelve hasta el punto del commit hecho deshaciendo los archivos que se crearon a partir de ese commit
#git checkout master
regresa al actual commit 