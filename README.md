# Actividad Práctica 1
## Promedio General de un alumno.

Se requiere obtener el promedio general de un alumno. Para lo cual se tienen 3 archivos que corresponden a la lista de calificaciones de 3 Materias diferentes. Cada archivo contiene la lista de alumnos con sus respectivas calificaciones de cada unidad junto con la información del alumno (nombre completo y matrícula). Cabe resaltar que cada materia tiene un número determinado de unidades. A continuación se muestra un ejemplo del contenido de los archivos.

```
Matrícula,Nombre,U1,U2,U3
1930258,Basilio Amo Moreno,60.3,60.5,85
1930168,Yago Avilés,80.3,85.2,95
1930548,Gilberto Agapito Viña Cabrero,75.2,96,65
1930698,Mercedes del Mayoral,90.3,95,70
1930659,Laura Carla Guardiola Osuna,95,93,90
1930268,Alejo Campoy Gomis,100,95,85
1930784,Gracia Ordóñez Egea,65.3,75,95
1930854,Ana Hoyos Reig,85,80,96
1930946,Sosimo Pastor Doménech,96,90,95
1930258,Trinidad Angulo,78.2,80,90
```

Se deberá poder realizar la consulta de dos formas distintas

  1. Mediante la introducción de la matrícula en la linea de comandos al invocar al programa.

     > ```bash
     > $java App 1930125
     > Matrícula: 1930125   Alumno: Juan Escutia
     > 
     > Materia: Matemáticas para la computación
     > Calificaciones: 95, 95, 95   Promedio Parcial: 95
     > 
     > Materia: Valores del Ser
     > Calificaciones: 100, 100, 100 Promedio Parcial: 100
     > 
     > Materia: Programación Orientada a Objetos
     > Calificaciones: 70, 70, 75   Promedio Parcial: 71.6
     > 
     > Promedio General: 88.8
     > ```
  2. Mediante un menú
     >```bash
     >$java App
     >*** Promediado general de un alumno ***
     >******************* MENU *************************
     >
     >1.- Búsqueda del promedio general de un alumno
     >2.- Salir
     >1
     >Digite la matrícula del alumno: 1930125
     >Matrícula: 1930125   Alumno: Juan Escutia
     > 
     > Materia: Matemáticas para la computación
     > Calificaciones: 95, 95, 95   Promedio Parcial: 95
     > 
     > Materia: Valores del Ser
     > Calificaciones: 100, 100, 100 Promedio Parcial: 100
     > 
     > Materia: Programación Orientada a Objetos
     > Calificaciones: 70, 70, 75   Promedio Parcial: 71.6
     > 
     > Promedio General: 88.8
     >
     >¿Desea buscar a otro alumno s/n?
     >n
     >```


  > **Puntos Extra (15)**
  > 
  > Se podrá incluir una opción en el menú que permtia calcular los promedios generales de todos los alumnos.
  > 
  > ```bash
  >$java App
  > *** Promediado general de un alumno ***
  >******************* MENU *************************
  >
  >  1.- Búsqueda del promedio general de un alumno
  >  2.- Calcular el promedio general de todos los alumnos
  >  3.- Salir
  > 
  > 1930258 Basilio Amo Moreno 95
  > 1930168 Yago Avilés 86
  > 1930548 Gilberto Agapito Viña Cabrero 92
  > 1930698 Mercedes del Mayoral 78
  > 1930659 Laura Carla Guardiola Osuna 79
  > 1930268 Alejo Campoy Gomis 86
  > 1930784 Gracia Ordóñez Egea 79
  > 1930854 Ana Hoyos Reig 91
  > 1930946 Sosimo Pastor Doménech 74
  > 1930258 Trinidad Angulo 67
  >``` 