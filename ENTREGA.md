# Entrega del Trabajo Práctico Integrador

## Datos del participante
- Nombre y apellido: Débora Torres
- Curso: Introducción a Git y GitHub para la Gestión de Proyectos Digitales
- Fecha de entrega:
05/11/2026
## Enlaces
- Repositorio de GitHub:https://github.com/deboralujan/-tp-integrador-git-torres-debora
- Issue:https://github.com/deboralujan/-tp-integrador-git-torres-debora/issues/1
- Pull request:https://github.com/deboralujan/-tp-integrador-git-torres-debora/pull/2

## Comandos principales utilizados
- git init
- git status
- git add
- git commit
- git log --oneline
- git remote add origin
- git remote -v
- git push
- git branch
- git switch
- git merge
- git pull
Aclaraciones:
- Se utilizó `git switch` (no `git checkout`) para cambiar de rama.
- La rama principal se llama `main`.
## Descripción del proceso
Primero instalé Git, configuré mi nombre y correo, y creé la carpeta del proyecto con `mkdir`. Inicialicé el repositorio con `git init` y armé la estructura: README.md, ENTREGA.md y la carpeta proyecto con index.html y styles.css. Registré los cambios con `git add` y `git commit`, y consulté el historial con `git log --oneline`. Luego creé un repositorio público en GitHub, lo conecté con `git remote add origin` y subí el trabajo con `git push`. Creé una issue para mejorar el README, trabajé en la rama `mejora-readme` y abrí una pull request que fusioné en GitHub. Después actualicé `main` con `git pull` y practiqué `git merge` desde la terminal con una segunda rama.

## Dificultades encontradas
- Al crear la carpeta escribí el nombre sin el comando `mkdir`, y la terminal dijo "command not found". Lo resolví usando `mkdir` antes del nombre.
- El archivo styles.css se creó en la raíz y no dentro de la carpeta proyecto. Lo moví con `mv styles.css proyecto/`.
- Al reemplazar la URL del remoto dejé el texto de ejemplo "TU-USUARIO" y falló el push. Lo corregí con `git remote set-url origin`.
- GitHub no aceptó mi contraseña en el `git push`. Creé un token de acceso personal y lo usé como contraseña.
- El repositorio quedó con un guion al inicio del nombre, pero no afectó el funcionamiento.

## Reflexión final
Aprendí que Git permite registrar la evolución de un proyecto con commits claros y volver a entender qué se hizo y por qué. También entendí la diferencia entre Git, que versiona en mi computadora, y GitHub, que permite publicar y colaborar. Trabajar con ramas, issues y pull requests me mostró cómo se organiza un cambio antes de integrarlo a la versión principal.