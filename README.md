# Programacion Movil TAV - 001 

## Comandos de Git

### 1. **`git add .`**
Este comando agrega todos los archivos modificados y nuevos al área de preparación (staging area) para que puedan ser incluidos en el próximo commit. El punto (`.`) indica que se agregarán todos los cambios en el directorio actual y subdirectorios.

### 2. **`git commit -m "escribir los cambios realizados"`**
Crea un nuevo commit con los cambios que se han agregado al área de preparación. El mensaje entre comillas (`"escribir los cambios realizados"`) describe brevemente los cambios realizados en el commit.

### 3. **`git push origin RamaPropia`**
Este comando envía (empuja) los cambios locales de tu rama (`RamaPropia`) al repositorio remoto llamado `origin`. Esto actualiza la rama remota con los commits que has hecho localmente.

### 4. **`git rebase main`**
Este comando aplica los cambios de la rama `main` sobre la rama actual. Es decir, se mueve la base de tu rama actual al final de la rama `main`, lo que permite que los commits de la rama `main` se apliquen antes que tus propios cambios. Este comando es útil cuando se quiere mantener un historial limpio y evitar los merges conflictivos.

### 5. **`git branch nombre_de_Rama`**
Crea una nueva rama llamada `nombre_de_Rama`. Este comando no cambia la rama actual en la que te encuentras, solo la crea.

### 6. **`git checkout nombre_Rama`**
Cambia a la rama especificada (`nombre_Rama`). Después de usar este comando, todos los cambios que realices serán en esa rama, no en la rama anterior.

---
**Nota:** Recuerda siempre hacer un `git pull` antes de realizar un `git push` para asegurarte de que tu rama esté actualizada con la versión más reciente del repositorio remoto.
