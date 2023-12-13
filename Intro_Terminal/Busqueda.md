# Búsqueda de Archivos

La búsqueda de archivos en sistemas Unix/Linux se simplifica enormemente con el comando find. Este comando permite localizar archivos en una ruta específica, filtrar por tipos de archivo y establecer condiciones basadas en el tamaño. A continuación, se presentan algunos ejemplos básicos para comprender cómo utilizar eficazmente el comando find.

```bash
find # Busca el archivo en la ruta que indiques y el tipo de archivo que necesites. 
find ruta -name *.png
find ./ -name *.png # Busca los archivos que se encuentren el directorio con la terminación en png. 
find ./ -type # Búsqueda por tipo de archivos f para archivos, d para directorios y I para enlaces simbólicos. 
find ./ -size 4k # Busca archivos que pesen exactamente 4kb añadiendo + buscara 4 o mas kb y - con la operación contraria. 
```

## GREP - Coincidencias de Búsqueda

Cuando se trata de la búsqueda de patrones dentro de archivos, el comando grep (Global Regular Expression Print) es esencial. Permite realizar búsquedas en archivos basadas en expresiones regulares, facilitando la identificación de líneas que contienen información específica. A continuación, se presentan algunos usos comunes de grep para realizar búsquedas efectivas.

```bash
grep [ExpresiónRegular] [archivoDondeBuscar]
grep the movies.csv # Busca la palabra the en el archivo. 
grep -i action movies.csv # Búsqueda de la palabra action en mayúscula y en minúscula en el archivo. 
grep -c drama movies.csv # Cuenta cuantas veces se repite una palabra en el archivo. 
grep -v drama movies.csv # Evita todas las selecciones que tengan la palabra en el archivo. 
grep -m 10 Fan movies.csv # Devuelve las primeras 10 Coincidencias del archivo. 
```

[Inicio](./README.md)
