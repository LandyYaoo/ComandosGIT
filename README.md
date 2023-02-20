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



#**Git status**<a name="git-status"></a>

git status es un comando de Git que muestra el estado actual del repositorio local. 

Proporciona información sobre los cambios realizados en el directorio de trabajo y el área de preparación, así como sobre la rama actual y su relación con el repositorio remoto.

`git status`
```
git status
```
<img width="570" alt="image" src="https://user-images.githubusercontent.com/85595613/220140154-8047a831-eda6-49a9-9d5c-8a5dfb2be7dd.png">
    
    
    
**# Git init**<a name="git-init"></a>

El comando git init crea un nuevo repositorio de Git. 

Puede utilizarse para convertir un proyecto existente y sin versión en un repositorio de Git, o para inicializar un nuevo repositorio vacío.

`git init`
```
git init
```
<img width="570" alt="image" src="https://user-images.githubusercontent.com/85595613/220140734-b06f25bb-c64d-4307-800e-342b4fd4da56.png">



**# Git remote add origin**<a name="git-remote"></a>

El comando git remote add se utiliza para agregar un nuevo repositorio remoto a un repositorio local de Git. 

Este comando toma dos argumentos:

El nombre del repositorio remoto que se está agregando (por ejemplo, "origin" es el nombre común para el repositorio remoto principal).


La URL del repositorio remoto, que es la dirección del repositorio remoto en la red, donde se enviarán y recibirán los cambios.

`git remote add origin https://github.com/usuario/repo.git`
```
git remote add origin https://github.com/usuario/repo.git
```
<img width="570" alt="image" src="https://user-images.githubusercontent.com/85595613/220141170-912cfb06-debb-4dc7-853a-8c33ea23663f.png">


**# git fetch origin main**<a name="git-fetch"></a>

git fetch es un comando de Git que permite traer los cambios de un repositorio remoto al repositorio local sin mezclarlos con los cambios locales.

`git fetch origin main`
```
git fetch origin main
```
<img width="570" alt="image" src="https://user-images.githubusercontent.com/85595613/220141241-cf391636-7b3a-4775-8856-9025a19e0b14.png">



**# git pull origin main**<a name="git-pull"></a>

Al ejecutar git pull, Git descarga los cambios más recientes del repositorio remoto y los combina automáticamente con la rama local actual.

`git pull origin main`
```
git pull origin main
```
<img width="570" alt="image" src="https://user-images.githubusercontent.com/85595613/220141346-48a15120-5985-4a3f-837e-56dbd3b75295.png">



**# git add .**<a name="git-add"></a>

Es un comando de Git que agrega todos los cambios en el directorio de trabajo actual al área de preparación de Git. Esto significa que los cambios se preparan para ser confirmados en el repositorio Git.

`git add .`
```
git add .
```
<img width="570" alt="image" src="https://user-images.githubusercontent.com/85595613/220141456-5166ef3f-d094-428d-883e-fc91e51ad767.png">



**# Git commit -m " "**<a name="git-commit"></a>

git commit -m es un comando de Git que permite confirmar los cambios en el repositorio local con un mensaje que describe los cambios realizados.

`git commit -m "Tu commit aqui"`
```
git commit -m "Tu commit aqui"
```
<img width="570" alt="image" src="https://user-images.githubusercontent.com/85595613/220141763-e2ed23d6-303d-47de-a5e9-669f453eb770.png">



**# Git push -u origin mai**n<a name="git-push"></a>

git push -u origin main es un comando de Git que se utiliza para enviar los cambios confirmados en el repositorio local al repositorio remoto en una rama específica.

`git push -u origin main`
```
git push -u origin main
```
<img width="570" alt="image" src="https://user-images.githubusercontent.com/85595613/220141913-42b84479-198a-431c-b375-8d3692efb8fa.png">



**###End**
