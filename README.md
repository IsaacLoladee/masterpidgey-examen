# Exámen Entonos de desarrollo

# Enunciado ejercicios básicos de Git, GitHub (Parte 1)

## Clonar repositorio

Para realizar la clonación de mi respositorio en local he realizado un git clone https://github.com/IsaacLolade/masterpidgey-examen.git
 
## Crear README

Para crear el README, primeramente me he dirigido a la ruta en la que se encuentra mi repositorio local con el comando cd masterpidegey-examen y una vez dentro he hecho uso del comando nano README.md

## Commit inicial

Una vez guardado y editado nuestro archivo de markdown hare un git add README.md para añadir el archivo para realizar el commit.

Utilizaremos el comando git commit -m "commit inicial" cargar los cambios realizados

## Push inicial

Para realizar el push iniicial haremos uso del comando git push origin main

## Ignorar archivos

### Crear en el repositorio local un fichero llamado privado.txt.

Haremos uso del comando nano privado.txt para crear el archivo.txt y realizaremos los mismos pasos que antes git add del archivo, commit
y el push

### Crear en el repositorio local una carpeta llamada privada.

Haremos uso del comando mkdir privada para crear el directorio y realizaremos los mismos pasos que antes git add del directorio, commit y el push

### Realizar los cambios oportunos para que tanto el archivo como la carpeta sean ignorados por git.

Haremos uso del comando nano .gitignore y una vez dentro pondremos el nombre de los archivos que queremos. Al igual que antes deberemos de realizar tanto el git add como el commit, en micaso he decidido subir el commit juntado los dos pasos anteriores.

### Añadir fichero 1.txt en el repositorio local

Haremos uso del comando nano 1.txt para crear el archivo.txt.

### Crear tag

Utilizaremos el siguiente comando para poder crear un tag git tag v0.1

### Subir tag

Para subir el tag haremos uso el comando de git push origin v0.1

### Crear una tabla

| NOMBRE | GITHUB |
| ------ | ------ |
| Máximo Fernández Riera| (https://github.com/maximofernandezriera)       |

### Crear una rama

Para crear una nueva rama, he utilizado el comando `git branch <nombre de la rama>`.

## Cambiar a la rama creada

Para cambiar a la nueva rama, he utilizado el comando `git checkout <nombre de la rama>`.

git remote -v (Para ver los repositorios en remoto)

para añadir más repositorios en remoto utilizaremos el comando `git remote add nombre-rama enlace-del-repositorio-a-forkear`

para sincronizar los repositorios en remoto haremos uso de `git fetch upstream`

para realizar el merge utilizar primeramente haremos un `git checkout main` y luego un `git merge upstream/main`

### Fotos de pullrquest

![Crear Pull Request (1)]()

![Crear Pull Request (2)]()
