## CONFIGURACIÓN BÁSICA GIT

En este archivo de texto expondremos todos los **comandos básicos y útiles** para Git.

A continuación os mostramos una *tabla de comandos de configuración*


| Comando | Descripción |
| -- | -- | 
| git config --global user.name *'nombre'* | Establecer nuestro nombre de usuario |
| git config --global user.email *'email'* | Establecer nuestra dirección de correo |
| git config --system core.editor *'editor'* | Establecer el editor de texto |
| git config --global color.ui true | Habilitar el uso de color |
| git config --list | Ver la configuración |

### Comandos más útiles

| Comando | Descripción |
| -- | -- | 
| git init {nombre} | Crear un repositorio |
| git clone {url} | Descargar un repositorio |
| git status | Lista de archivos nuevos o modificados |
| git diff | Muestra diferencias entre archivos o ramas |
| git add {archivo} | Añade un cambio del directorio de trabajo en el entorno de ensayo |
| git log | Ver historial de la rama actual |
| git commit -m "mensaje" | Crear un commit |
| git branch {nombre} | Crear una nueva rama |
| git checkout {rama} | Cambia a la rama indicada |
| git merge {rama} | Combina la rama actual y la indicada |
| git fetch {nombre} | Descarga cambios del repositorio remoto |
| git pull | Descarga e integra los cambios del repositorio remoto |
| git push {rama} | Sincroniza los commits en el repositorio remoto |