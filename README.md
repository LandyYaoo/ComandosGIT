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

git status es un comando de Git que muestra el estado actual del repositorio local. 

Proporciona información sobre los cambios realizados en el directorio de trabajo y el área de preparación, así como sobre la rama actual y su relación con el repositorio remoto.

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

`git remote add origin https://github.com/usuario/repo.git`
```
git remote add origin https://github.com/usuario/repo.git
```


#git fetch origin main<a name="git-fetch"></a>

git fetch es un comando de Git que permite traer los cambios de un repositorio remoto al repositorio local sin mezclarlos con los cambios locales.

`git fetch origin main`
```
git fetch origin main
```


#git pull origin main<a name="git-pull"></a>

Al ejecutar git pull, Git descarga los cambios más recientes del repositorio remoto y los combina automáticamente con la rama local actual.

`git pull origin main`
```
git pull origin main
```


#git add .<a name="git-add"></a>

Es un comando de Git que agrega todos los cambios en el directorio de trabajo actual al área de preparación de Git. Esto significa que los cambios se preparan para ser confirmados en el repositorio Git.

`git add .`
```
git add .
```


#Git commit -m " "<a name="git-commit"></a>

git commit -m es un comando de Git que permite confirmar los cambios en el repositorio local con un mensaje que describe los cambios realizados.

`git commit -m "Tu commit aqui"`
```
git commit -m "Tu commit aqui"
```


#Git push -u origin main<a name="git-push"></a>

git push -u origin main es un comando de Git que se utiliza para enviar los cambios confirmados en el repositorio local al repositorio remoto en una rama específica.

`git push -u origin main`
```
git push -u origin main
```

###End
