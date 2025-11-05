### 1. Crear un repositorio en GitHub
### Ve a https://github.com/new
### Nombre: practica-git-remoto
### Descripción: Repositorio para practicar Git con remotos
### Público (para que puedas compartirlo)
### NO inicializar con README, .gitignore, o license  ESTO NO ES POSIBLE REALIZAR DEBE TENER EL PROYECTO ALGO PARA SER INICIALIZADO Y PUEDA SER SUBIDO A GITHUB, es decir, no se puede subir el proyecto vacio al repositorio remoto.


Este es un proyecto para practicar Git con repositorios remotos



### Subir el proyecto a GitHub

Ejecuta los siguientes comandos en tu terminal para inicializar el repositorio y subirlo a GitHub:

```bash
git init
git add .
git commit -m "feat: crear proyecto de versiones 3 y crear primer commit"
git branch -M main
git remote add origin https://github.com/RodolfoParada/practica-git-remoto.git
git push -u origin main
```

![Mi foto](/assets/img/ComandoClone.png)

Creé el proyecto y luego lo cloné en mi equipo local. Posteriormente, desarrollé el ejercicio y realicé la tarea de crear tres ramas, efectuando distintos commits en los archivos correspondientes. Para ello, utilicé los siguientes comandos:

# Crear una nueva rama
```
git checkout -b feature/nombreRama
```

#Enviar rama al remoto
```
git push origin feature/saludo-personalizado
```

# Cambiar a una rama
```
git checkout feature/nombreRama o main
```
# ver la lista de ramas 
```
git branch -a
```

# Agrega todos los archivos del proyecto al área de preparación
```
git add .
```

# Importante usar prefijos y un comentario descriptivo del cambio
```
git commit -m "first commit"
```

