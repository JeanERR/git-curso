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
#git tag <nombre_etiqueta>
agrega una etiqueta al ultimo commit que se hizo
#git tag <nombre_etiqueta> <nombre_hash>
agrega una etiqueta en el hash seleccionado
#git branch <nombre>
crea una rama 
#git checkout <rama>
cambia de rama, por lo general la rama principal es el master 

Esta linea fue creada en la rama master
#git merge <rama>
fusiona la rama con la rama en la que se encuentra
#git merge rama1
fusiona la rama universo1 con la rama master (rama en la que estoy )
#git merge --abort
cancela la fusion de la rama por si arroja algun error
#git branch -d <rama>
borra una rama, pero asegurese de que se fusiono con la rama principal
sino se borrara todo desde que se inicio esa rama
