# Proyecto Final Multiprocesadores
### Martín Octavia García García - A01328971
### Víctor Darío Alor López - A01731643
Se probarán 3 diferentes algoritmos en la computadora virtual que ocupen en sus servicios. Deberán de encontrar el número óptimo de threads para su ejecución y comparar los resultados con los tiempos obtenidos en cada uno de los equipos de los miembros del equipo.
## Resultados
Para la realización de este proyecto de utilizaron 3 máquinas virtuales: Amazon, Google e IBM, así como 3 equipos personales: HP OMEN, MSI Raider y Surface Pro 7.

Teniendo como resultados la siguiente tabla.
![imagen](https://user-images.githubusercontent.com/83479688/143066435-2ef08ab9-c27b-4789-90c9-73e47b18572a.png)

Para ver todos los gráficos así como algunas imágenes de los resultados de las pruebas puede ver el [documento](https://docs.google.com/document/d/1BuCEfgQMn0Djsf8-Sb4xyqLAucGC-UfEAUhB6UZVLeE/edit?usp=sharing) que se realizó para este proyecto.
## Conclusiones
Después de discutir y analizar los resultados nos dimos cuenta que para el caso del cálculo del área bajo la curva, los mejores resultados fueron por parte de las computadoras físicas, y en el caso del procesamiento de imágenes fue al contrario los servicios de cloud computing fueron más eficientes.

Otra cosa que pudimos analizar es que los resultados de los servicios de cloud computing son en general más estables en los resultados, es decir que no vemos que los tiempos fluctúan demasiado, o en el caso de volver a ejecutar el programa los resultados son casi iguales, cosa que no pasa con los equipos físicos. Esto  es debido a que los servicios de cloud computing solo están enfocando su poder de procesamiento en la tarea asignada y no en muchas tareas en segundo plano,como es el caso de las laptops.

Algo que pudimos detectar en el procesamiento de imágenes es que la mejor forma de aprovechar el uso de threads es usarlos para procesar diferentes imágenes a la vez, ya que si enfocamos muchos threads en una sola imagen, estos van generando un error o perdiendo pixeles.

En conclusión podemos afirmar que los servicios de cloud computing son muy versátiles, configurables y además confiables (mientras tengamos una buena conexión a internet). Por lo que son una gran opción a considerar si necesitamos hacer uso de gran poder de procesamiento y no queremos saturar nuestro equipo de uso diario.
