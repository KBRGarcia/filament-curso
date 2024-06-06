# FILAMENTPHP : DE CERO A EXPERTO
## El Rincon de Isma
## YouTube

## Repositorio del curso: https://github.com/elrincondeisma/curso-filamentphp-intranet
## Repositorio personal del proyecto: https://github.com/KBRGarcia/Curso-Filament.git

_____________________________________________________________________________________________________________________________________________________________________
# 2 - Curso de FILAMENTPHP de CERO a EXPERTO | INSTALACIÓN Y CONFIGURACIÓN DE FILAMENTPHP
_____________________________________________________________________________________________________________________________________________________________________

Creamos nuestro royecto de laravel usando el comando:

 - composer create-project laravel/laravel example-app
 - cd example-app

Luego se añade el proyecto a GitHub (el proyecto ya tiene que estar creado) mediante el comando:

 - git init
 - git add .
 - git commit -m "primer commit del repositorio"
 - git branch -M main

Para el repositorio remoto
 - git remote add origin ruta_del_repositorio_remoto
 - git push -u origin main
 - git remote add origin ruta-del-repositorio
 - git push -u origin main

(Opcional) Se modifica el archivo README.md para que contenga toda la información que yo desee

Para instalar filamentphp se hace lo siguiente:
 - composer update
 - composer require filament/filament:"^3.2" -W
 - php artisan filament:install --panels

Nos va a preguntar sobre el ID y por lo general se coloca admin o dashboard, vamos a utilizar dashboard

Luego ejecutamos el comando

 - php artisan migrate

Creamos nuestro usuario con el comando

 - php artisan make:filament-user

user: KBRGarcia
email: kbrgarcia@gmail.com
password: 123456789

