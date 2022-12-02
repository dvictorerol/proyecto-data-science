# Proyecto: Análisis sobre la insuficiencia del desarrollo educacional con relación al rendimiento académico y otras variables

## Consideraciones generales :octocat:

- https://datosabiertos.mineduc.cl/directorio-de-establecimientos-educacionales/

- https://datosabiertos.mineduc.cl/subvenciones-a-establecimientos-educacionales/

- https://datosabiertos.mineduc.cl/resumen-de-docentes-por-establecimiento/

- https://www.ine.gob.cl/docs/default-source/encuesta-suplementaria-de-ingresos/cuadros-estadisticos/2021/ingreso-medio-mensual-por-regi%C3%B3n-2010---2021.xlsx?sfvrsn=30ed8da9_6

- https://datosabiertos.mineduc.cl/matricula-en-educacion-superior/

- https://datosabiertos.mineduc.cl/matricula-por-estudiante-2/

- https://www.ide.cl/index.php/limites-y-fronteras/item/1528-division-politica-administrativa-2020

- https://www.mifuturo.cl/mi-futuro-buscadores/

- https://datosabiertos.mineduc.cl/rendimiento-por-estudiante-2/


## Cosas implementadas

##### ✅ Clusters
##### ✅ Graficos

## Ejecución :computer:
El módulo principal de la tarea a ejecutar es  ```menu.py```. Además se debe crear/clonar los siguientes archivos y directorios adicionales:
directorio: Carpeta llamada ```partidas``` donde se guardaran las partidas
archivo: ```puntajes``` donde estarán guardados los ranking.
Por otro lado, tambien deben estar clonados los modulos ```tablero``` y ```parametros``` para que funcione correctamente todo

## Librerías :books:
### Librerías externas utilizadas
La lista de librerías externas que utilicé fue la siguiente:

1. ```random```: ```randint()```
2. ```math```: ```ceil()``` 
3. ```os```: ```modulo```

### Librerías propias
Por otro lado, los módulos que fueron creados fueron los siguientes:

1. ```verificaciones```: Contiene las funciones necesarias para comprobar las opciones entregadas por el usuario en el ```menu``` y ```menu_juego```.
2. ```bestias```: Hecha para verificar las bestias y el backtracking para el flujo del juego de ```menu_juego```
3. ```menu_juego```: Este módulo contiene el flujo del juego
4. ```tablero``` modulo entregado para la tarea
## Supuestos y consideraciones adicionales :thinking:
Los supuestos que realicé durante la tarea son los siguientes:

1. El mecanismo usado para ```guardar``` las partidas fue, en el archivo ```nombre.txt``` guardar los tableros que son una lista de lista, guardo las lineas que estan dentro de la lista mayor en el mismo formato que uno ve el tablero al ejecutar el juego. Como utilizo 2 tableros uno es el que ve el jugador y otro en el cual se hace las modificaciones, para saber que linea es de que tablero coloque un "END" para identificar que finalizo las lineas de la lista del primer tablero para asi las siguientes incluirlas en el tablero no visible.

2. El archivo de ```puntajes.txt``` esta en el formato ```nombre,puntaje```  a medida que se va agregando puntejes se va ordenando, ya que el orden lo especifico en el codigo y no es necesario que este ordenado en el archivo mismo.

3. El codigo no incluye ```Programación Orientada a Objetos``` ya que no era necesario según lo especificado.

4. el archivo ```codigo tarea 0``` ```no tomar en cuenta```, contiene el codigo bruto y no esta completo 

## Referencias de código externo :book:

Para realizar mi tarea saqué código de:

## Descuentos
La guía de descuentos se encuentra [link](https://github.com/IIC2233/Syllabus/blob/master/Tareas/Descuentos.md).
