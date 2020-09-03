# Practica1
# Ingrid Lorena Garcia Yantuche, Carné: 201700399
# Manual De Usuario
#### La aplicación consta en que el usuario podrá cargar varios archivos a memoria y podra obtener datos generales a traves de comandos.
Comando
------------------
1. CARGAR
2. SELECCIONAR
3. MAXIMO
4. MINIMO
5. SUMA
6. CUENTA
7. REPORTAR

> Los comandos serán ejecutados en consola, uno por uno.
**************************************************************************************************************************************************

## Comando CARGAR
#### El usuario podrá cargar N cantidad de archivos con extensión Json
#### Entrada correcta---> CARGAR archivo1.json, archivo2.json, archivoN.json
> Para el ingreso de la entrada después de la coma dejar un espacio, en caso de no dejar un espacio no lo tomara como una entrada correcta.

**************************************************************************************************************************************************

## Comando SELECCIONAR
#### El usuario podra ver ciertos registros para algunas condiciones, la entrada despues de la coma se deja un espacio, de lo contrario no es valida, a continuación de muestra la entrada correcta.
####-----> SELECCIONAR nombre, edad DONDE nombre= "registro 3"

> No es permitido la entrada donde tengan dos condiciones ni tampoco es permitido la llamada de atributos que no existe.

*************************************************************************************************************************************************

## Comando MAXIMO
#### Permite encontrar el valor máximo que se encuentre en el atributo de uno de los registros del conjunto en memoria.
> MAXIMO edad
--
> MAXIMO promedio

*************************************************************************************************************************************************

## Comando MINIMO
#### Permite encontrar el valor mínimo que se encuentre en el atributo de uno de los registros del conjunto en memoria.
> MINIMO edad
--
> MINIMO promedio

*************************************************************************************************************************************************

## Comando SUMA
#### El usuario podrá obtener la suma de todos los valores de un atributo especificado en el comando. El comando solo permitira entrada para los atributos de edad y promedio
> SUMA edad
--
> SUMA promedio

*************************************************************************************************************************************************

## Comando CUENTA
#### Permite contar el número de registros que se han cargado a memoria.

*************************************************************************************************************************************************

## Comando REPORTAR
#### Se mostrara un reporte en html de todos los registros. 
