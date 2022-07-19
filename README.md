# DESCARGAR PROYECTO

Tener instalado GIT en la computadora

## Ejecutar los siguientes comandos 

Este comando bajara los archivos del repositorio a la computadora en la ruta que se especifique.

```bash
git clone https://github.com/DevForAll/audit_website.git
```

Una vez descargado se descargara una carpeta llamada 'audit_website' que contendra todo el codigo del proyecto.

Entrar a la carpeta 'audit_website' y abrir el archivo index.html con el navegador que se tenga. Al hacer esto se podra levantar la pagina.

Si se va a editar codigo, se recomienda usar un editor de codigo como Visual Studio Code, a la vez tener la extension 'Live Server' 
para levantar la pagina en local

## Subir los cambios al repositorio

Luego de haber se clonado o descargado el repositorio, siempre bajar los cambios con el siguiente comando

```bash
git pull
```

Muestra el detalle del estado de nuestro repositorio y el area de preparacion

```bash
git status
```

Agregar todos los archivos modificados en nuestra maquina local

```bash
git add .
```

Agregar un comentario del cambio que se realiza en el archivo

```bash
git commit -m "Se modifico el texto del menu"
```

Enviar los cambios al repositorio. En nuestro caso la rama principal se llama "main"

```bash
git push origin main
```


Verificamos la rama que estamos utilizando

```bash
git branch
```

Visualizamos todas las ramas que tenemos en nuestra maquina local

```bash
git branch --all
```


Thanks for downloading this template!

Template Name: Mamba
Template URL: https://bootstrapmade.com/mamba-one-page-bootstrap-template-free/
Author: BootstrapMade.com
License: https://bootstrapmade.com/license/
