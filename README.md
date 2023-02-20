# Comandos GIT

Esta es una breve guia con algunos de los comandos basicos para trabajar en GIT

## Tabla de contenidos
- [Git status](#git-status)
- [Git init](#git-init)
- [Git remote add origin](#git-remote)
- [Git fetch origin main](#git-fetch)
- [Git pull origin main](#git-pull)
- [Git add .](#git-add)
- [Git commit -m " "](#git-commit)
- [Git push -u origin main](#git-push)



#Git status<a name="git-status"></a>

Muestra la lista de los archivos que se han cambiado junto con los archivos que están por ser preparados o confirmados.

`git status`
```
git status
```
    
#Git init<a name="git-init"></a>

El comando git init crea un nuevo repositorio de Git. 
Puede utilizarse para convertir un proyecto existente y sin versión en un repositorio de Git, o para inicializar un nuevo repositorio vacío.

`git init`
```
git init
```
#Git remote add origin<a name="git-remote"></a>

El comando git remote add se utiliza para agregar un nuevo repositorio remoto a un repositorio local de Git. 

Este comando toma dos argumentos:

El nombre del repositorio remoto que se está agregando (por ejemplo, "origin" es el nombre común para el repositorio remoto principal).


La URL del repositorio remoto, que es la dirección del repositorio remoto en la red, donde se enviarán y recibirán los cambios.

`git git remote add origin https://github.com/usuario/repo.git`
```
git git remote add origin https://github.com/usuario/repo.git
```

#git fetch origin main<a name="git-fetch"></a>

git fetch es un comando de Git que permite traer los cambios de un repositorio remoto al repositorio local sin mezclarlos con los cambios locales.

`git git remote add origin https://github.com/usuario/repo.git`
```
git git remote add origin https://github.com/usuario/repo.git
```

#git pull origin main<a name="git-pull"></a>
#git add .<a name="git-add"></a>
#Git commit -m " "<a name="git-commit"></a>
#Git push -u origin main<a name="git-push"></a>
