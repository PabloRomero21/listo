# Chuleta de Git

* `git status`: Muestra el estado del repositorio.
* `git log --oneline`: Muestra el historial de commits en una línea.
* `git add <archivo>`: Añade cambios al área de preparación (stage).
* `git commit -m "mensaje"`: Guarda un commit con su mensaje.
* `git push`: Sube los commits locales a GitHub.
* `git diff`: Muestra cambios en el directorio de trabajo respecto al stage.
* `git diff --staged`: Muestra cambios en el stage respecto al último commit.
* Mensajes de commit: Título corto en la primera línea, línea en blanco y cuerpo explicativo a continuación.
* `git commit -am "mensaje"`: Añade modificaciones de archivos ya seguidos y hace commit en un solo paso.
* `git add .`: Prepara todos los archivos modificados y nuevos del directorio actual.
* `.gitignore`: Archivo para definir patrones de nombres de archivos que Git debe ignorar.
* `git restore <archivo>`: Descarta los cambios locales en el directorio de trabajo.
* `git restore --staged <archivo>`: Saca un archivo del área de preparación (stage) sin perder los cambios.
* `git commit --amend`: Modifica o corrige el último commit realizado (antes de haberlo subido con push).
* Alias de Git: Atajos personalizados definidos mediante `git config --global alias.<nombre> "<comando>"`.
