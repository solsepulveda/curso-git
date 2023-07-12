# Comandos de git

#### Comandos para inicializar el proyecto en git

```
    git init
```

#### Comandos para "guardar"

```
git add .   => los añade área de stagging, Se usa . porque hace referencia
a la carpeta en donde estoy, por lo que se guardan los archivos de ésta.
```

```
git add -A => agrega absolutamente todos los archivos, no solo los de la carpeta
```

```
git commit  =>te los guarda en el repositorio
```

```
git push    =>subir al repositorio
```

#### Comando para ver commits

```
git log
```

#### Comandos para ramas

```
git branch <nombre-rama> =>crear rama
```
```
git branch -D <nombre-rama> =>eliminar rama
```
```
git branch => enlistar rama
```
```
git checkout <nombre-rama> => cambiar de rama
```
```
git switch <nombre-rama> => cambiar de rama
```
```
git switch -c <nombre-rama> => crear rama y cambiarse a esta simultaneamente
```
```
git checkout -b <nombre-rama> => crear rama y cambiarse a esta simultaneamente
```

#### Ramas y github
```
git push -u origin <nombre-rama> Subir rama al repositorio por primera vez
```
```
git merge <nombre-rama> => Merge a la rama
```
```
git checkout -b <nombre-rama> => crear rama y cambiarse a esta simultaneamente
```

#### Comandos importantes
```
git status => muestra el estado del directorio de trabajo
```
```
git log --oneline => muestra la información de confirmación en una única línea
```
```
git status -s =>
```
```
git restore <nombre-archivo>
```
```
git revert 1105103
```
```
Git diff => permite comparar cambios en archivos, ramas y
commit
```
```
git fetch => Es un comando principal que se usa para descargar contenidos
desde un repositorio remoto
```
```
git clone <URL del proyecto>
```

#### Git reset

```
git reset --soft
```
```
git reset --mixed
```
```
git reset --hard
```



