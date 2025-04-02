# Repositorio-informacion-git
Pruebas de git
## Comandos de git
- Para clonar el repositorio de git, puedes usar el siguiente comando:
git clone https://github.com/AidaBS86/Nuevo-repositorio-git.git
- Para subir ficheros a un repositorio:
#### 1o git add -A (añade TODOS los ficheros a git)
#### 2o git commit -m "actualizar el readme" (añadimos un mensaje de lo que estamos subiendo, entre comillas)
#### 3o git push
IMPORTANTE ABRIR LA TERMINAL EN DOCUMENTO DEL REPOSITORIO (abrir en terminal integrado u open in integrated terminal, boton derecho sobre la carpeta)
- Para bajar cambios de la nube (cambios en github, y darle a confirmar cambios, pero para bajarlo, tienes que asegurar que los cambios del vscode estan subidos. Las bajadas son con merge)
#### git pull










Información extra:
-En github, se puede dar click al botón Commits (Historia) y se ve el historial de quien a subido y la descripcion de lo que ha subido (cuando nosotras ponemos el git commit -m "texto").
-Es posible que dos personas cambien la misma linea de codigo a la vez (ej: título), entonces al hacer el git push te dara error y te pide que 1o hagas un git pull y te dara el error de que se ha escrito en la misma linea, y somos nosotras las que hemos de decidir cual escogemos, te aparecen las opciones en vscode; "aceptar cambio actual", "actual cambio entrante" o "aceptar ambos cambios". Despues  hay que volver a subir y luego bajar.
-Hay tipos de documentos que no se pueden abrir en github, ej: jupyter notebook.
-La unica manera de que otros puedan editar tu repo en github, tenemos que dar permiso a la persona, aunque sea publico.

