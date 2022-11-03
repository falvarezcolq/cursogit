# Curso de git

1. DESCARGAR GIT https://git-scm.com/
2. Tener un editor o instalar Visual Studio Code  https://code.visualstudio.com/
3. Crear cuenta en github https://github.com/ requiere activacion por correo


## Configurar git por primera vez

https://git-scm.com/book/es/v2/Inicio---Sobre-el-Control-de-Versiones-Configurando-Git-por-primera-vez



Tu Identidad
Lo primero que deberás hacer cuando instales Git es establecer tu nombre de usuario y dirección de correo electrónico. Esto es importante porque los "commits" de Git usan esta información, y es introducida de manera inmutable en los commits que envías:

```
$ git config --global user.name "Juan perez"
$ git config --global user.email juanperez@example.com
```


### Comprobando tu Configuración
Si quieres comprobar tu configuración, puedes usar el comando git config --list para mostrar todas las propiedades que Git ha configurado:

```
$ git config --list
```





## Primeros comandos


mkdir cursogit

crear el archivo.txt

```
git init
git status
git add .
git commit -m "primer commit"
git diff


git add .
git commit -m "segundo commit"

git add .
git commit -m "tercer commit commit"


git log

```