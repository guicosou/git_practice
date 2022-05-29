### Comandos linux


#### Crear ficheros
    - Para crear un fichero vacio utilizamos el comando "touch".

#### Eliminar directorios
    - Para eliminar un directorio vacio utilizamos "rmdir".
    - Para eliminar un directorio con archivos dentro utilizamos "rm -r".

#### Comando Git
Para cualquier comando que sea de git debe comenzar con "git".

### Establecer conexión
    Para establecer la primera conexión debemos escribir "git init".
    Para vincular un repositorio debemos escribir lo siguiente:
        git remote add origin <Url del repositorio de Github>

### Seleccionar ficheros al repositorio
    - Para agregar ficheros a un repositorio de Git utilizaremos el comando "git add".

### Crear un punto de ruptura/info de los ficheros seleccionados.
    - Para agregar los ficheros que hemos seleccionados utilizamos el comando: "git commit -m "<Una descripción si se desea>".

### Subir los ficheros precargados
    - Para subir los ficheros finalmente utilizaremos el siguiente comando:
        "git push origin <linea de trabajo (Master, develop, etc...)>".

### Ramas
    - Para crear una nueva rama utilizamos "git branch <nombre de la nueva rama>".
    - Para cambiar de rama utilizramos "git checkout <nombre de la rama>".
    - Para comprobar que en rama estamos utilizamos "git status".