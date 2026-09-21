# Perro

**Autor:** Sebastián San Martín

---

## Comandos Básicos de Git

A continuación se detallan los comandos esenciales para la configuración, clonación y envío de cambios en un repositorio Git:

### `git clone url_repo .`
Clona el repositorio situado en la `url_repo` dentro del directorio actual en el que te encuentras (el punto `.` indica la carpeta local actual).

### `git config --global user.name Servirion`
Configura tu nombre de usuario de Git a nivel global (`Servirion`). Este nombre firmará todos los commits que realices en el equipo.

### `git config --global user.email sebastian.sanmartin36@inacapmail.cl`
Establece tu correo electrónico global en Git. Se utiliza para asociar tus commits con tu cuenta personal o institucional.

### `git config --global --list`
Muestra una lista con todas las configuraciones globales que tienes aplicadas en Git (como el nombre, correo, editor por defecto, etc.).

### `git add .`
Añade todos los archivos modificados, creados o eliminados del directorio actual al área de preparación (*Staging Area*), listos para incluirse en el próximo commit.

### `git commit -m "comentario"`
Guarda una captura de los cambios que estaban en el área de preparación en el historial local, incluyendo un mensaje breve que describe lo que se realizó.

### `git push origin main`
Sube (envía) los commits guardados en tu repositorio local hacia la rama principal (`main`) del repositorio remoto configurado como `origin` (por ejemplo, en GitHub, GitLab o Bitbucket).