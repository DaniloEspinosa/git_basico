# GIT bàsico

1 - Crear .gitignore y README.md

2 - Iniciar el proyecto:
git init

3 - Configuración
git config [--global] user.name "nombre"
git config [--global] user.email mi.email@ejemplo.com
git config --global core.autocrlf true (Win) o input(Mac - Linux)
git config --global core.editor "code --wait"

4 - Información del estado
git status

5 - Pasar al stage
git add .gitignore README.md

6 - Pasar al commit (versión 1)
git commit -m "README hasta el punto 5"
git commit -a -m "README hasta el punto 6"

