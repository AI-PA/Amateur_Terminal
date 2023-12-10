# Que hace un comando en Linux ? y que son los alias?

## Que es un comando ?

Un **comando** es un mensaje enviado al ordenador que provoca una respuesta en este sistema y se comporta como una orden, pues informa al dispositivo informático que debe ejecutar una acción según la indicación que pueda enviarse.

Cada sistema operativo incorpora un determinado número de comandos básicos, que permiten ejecutar las tareas más simples con órdenes directas.

**Un comando pueden significar cuatro cosas:**

1. Un programa ejecutable
2. Un comando de utilidad de la *shell*. Esto es un programa en sí mismo, que puede tener funciones. Ejemplo `cd`
3. Una función de shell. Son funciones de shell externas al comando de utilidad. Ejemplo `mkdir`
4. Un alias. Un ejemplo es `ls`

## Qué son las entradas y salidas de la terminal

En la consola nosotros generamos una entrada cuando escribimos y una salida casi siempre que ejecutamos un comando.

A las entradas típicamente se les suele llamar **Standard Input** y a las salidas **Standard Output**, además se les suele abreviar como **stdin** y **stdout** respectivamente.

## Cómo usar el operador de redirection (>)

A veces queremos guardar la información de una salida porque nos puede interesar almacenar.

```bash
#Retiración 
## Standar Ouputs
ls -l > output.txt # El resultado se guarda en el archivo.
ls -l ./Secretos >> output # Concatena el resultado con lo que halla en el archivo. 

##Redición de Standar ERORRS!. 
ls -lls 2> error.txt # En caso de error se guarda en error.txt

##Redireccion Standar Errors y Outputs
ls -l output.txt 2>&1 # redirige el file description 2 y el file description 1. 
 
```

---

## Alias

En Linux, un alias es un nombre alternativo o abreviado que se asigna a un comando o conjunto de comandos. Los aliases se utilizan para crear atajos o simplificar la ejecución de comandos largos y frecuentemente utilizados.

```bash
Type Comando 
# Muestra el tipo de comando que es donde esta ubicado, 
# si es un alias.

alias rutas. # Crear un alias, si no se guarda solo se aplica cuando esta activo. 
help comando # Explica que hace el comando y las opciones que tiene. 
man comando # Explica como se usa y da ejemplos. 
info comando # Otra forma de explicar su uso. 
whatis comando # Explica de manera resumida que hace el comando. 
```
