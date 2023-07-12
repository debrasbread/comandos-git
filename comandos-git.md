# Introducción a Git

1. Este comando en git se utiliza para verificar la version instalada de git

```
git version
```

2. Este comando nos permite ver informacion sobre los comandos

```
git help
```

3. Estos comandos se utilizan para configurar el usuario

```
git config --global user.name <nombre-usuario>
```

```
git config --global user.email <ejemplo@correo.com>
```

3. Este comando sirve para agregar el archivo modificado al area de staging o area de preparación

```
git add <archivo-modificado-
```

4. Con este comando se inicia el repositorio/proyecto y se crea la carpeta oculta .git

```
git init
```

5. Con este comando se puede verificar el estatus de los archivos del proyecto y en que fase se encuentran

```
git status
```

6. Con este comando podemos agregar todos los archivos modificados al Staging Area (en el directorio dónd nos encontremos)

```
git add .
```

7. Con este comando podemos crear un commit

```
git commit -m "Mensaje del commit"
```

8. Con este comando podemos ver una lista de commits con información descriptiva (id, author, mensaje, hora y fecha) desde el más reciente al más antiguo

```
git log
```
9. Con este comando puedo restaurar el archivo que modifique

```
git restore <nombre-archivo>
```
10. Con este comando podemos cambiar de rama

```
git switch <nombre-rama>
```

11. Con este comando podemos guardar los cambios temporalmente en memoria, cuando aún no queremos realizar un commit
```
git stash
```

12. Con este comando podemos guardar los cambios temporalmente en memoria y le podemos asignar un mensaje
```
git stash save "mensaje"
```

13. Con este comando podemos traer de vuelta los cambios que teníamos guardados en el último stash
```
git stash pop
```

14. Con este comando se puede ver un listado de registros de commits con hash corto y el mensaje descriptivo de cada uno

```
git log --oneline
```