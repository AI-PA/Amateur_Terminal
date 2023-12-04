# Comandos Básicos

## Saber donde estamos 📍

Para empezar con este mundo de las terminales donde nuestra única herramienta es el teclado los y los comandos que logremos aprender lo primero que hay que hacer es saber donde estamos.

A la hora de iniciar una terminal aparecerá el símbolo " ~ " que nos indica que estamos en la carpeta home de nuestro sistema, para comprobarlo podemos poner el comando pwd que nos muestra la ruta donde estamos ubicados.

![imagen](../Pictures/Home.png)

``` Bash

pwd # Muestra la carpeta donde te encuentras. 
cd ./NombreDeCarpeta  # Te permite moverte a otra carpeta u ubicación
cd ./.. #Regresa a una carpeta hacia atrás.  
cd  ~ # Te mueve a Home. ~
file ./Ruta/Archivo # Muestra la información del archivo.
clear # Limpia la terminal.

```

## Mostrando los archivos 🕵️

Cuando intentamos movernos entre directorios debemos saber a que carpeta muy bien su nombre para no equivocarnos lo importante aquí es que pasa si no nos sabemos el nombre de la carpeta (。﹏。*)?

Para eso tenemos el comando ls y tree que nos muestran las carpetas que tenemos.

![Ls en Directorio](../Pictures/Directory%20ls.png)
a qui podemos ver como el comando ls entra en acción mostrando las carpetas que tenemos en la ruta.

mientras que el comando tree nos muestra mas a detalle el contenido de cada directorio de la siguiente manera.

![Tree en Directorio](./../Pictures/Tree.png)

Algunos de los comando que podemos usar para mostrar archivos tenemos:

```Bash

ls # mostrar archivos
ls -la  # mostrar todos los archivos incluso los ocultos
ls -lSH # muestra los archivos y el peso y edición.
ls -lr # muestra los archivos al revés de "Z a A"
tree # muestra los archivos por ramitas
tree -L 2 # muestra los archivos por 2 niveles.

```

En el caso de tree se necesita instalar.

```Bash
sudo snap install tree
```

## Las 3 Acciones Básicas : Crear, Copiar y Eliminar Archivos

Ahora que ya sabemos crear carpetas y movernos por ellas, es hora de aumentar la dificultad creando archivos, renombrarlos, copiarlos y eliminarlos.

Empecemos con el comando para crear archivos el cual es "Touch" el cual nos permite crear archivos con su nombre y extension.

```Bash
 touch NombreArchivo.Extension
```
