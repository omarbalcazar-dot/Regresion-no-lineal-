# Regresion-no-lineal-

El proposito de este trabajo es comprobar la hipótesis de "Entre más cerca de la hora de cierre de la bandeja se entrega la tarea, peor es la calificación obtenida."
Para esto, trabajamos con el archivo TiempoDeEntrega.csv, el cual contiene:

Tiempo: horas restantes antes del cierre de la bandeja

Calificación: nota obtenida en escala de 0 a 110.

Intrucciones:

1. Importación y visualización inicial

  • Se importan los datos y se grafica un scatter plot para observar la relación entre el tiempo de entrega y la calificación
  
  • Hacer una predicción inicial sobre que modelo sería más adecuado


2. División de datos
   
  • Los datos se separaron en 70% entrenamiento y 30% prueba.
  
  • Se calcula los promedios de tiempo y calificación en cada conjunto, comparando sus diferencias.


3. Regresión polinomial
   
  • Se hace un modelo de regresión polinomial con el conjunto de entrenamiento.
  
  • Se interpreta el coeficiente lineal para analizar la relación entre tiempo de entrega y calificación.
   

4. Regresión segmentada
   
  • Se implementa un modelo segmentado con funciones cuadráticas en cada tramo, siguiendo la estrategia de la lectura interactiva.
  
  • Se genera predicciones para el conjunto de prueba.

   
5. Modelo KNN
    
  • Se implementa un modelo de regresión KNN con diferentes valores de k.
  
  • Se genera predicciones para comparar con los otros modelos.


6. Comparación de modelos con RSE
    
  • Se calcula RSE para los tres modelos en el conjunto de prueba.
  
  • Se discutieron las diferencias no solo en términos de error, sino también en interpretabilidad


7. Visualización comparativa
    
  • Se genera una grafica mostrando las calificaciones reales junto con las predichas por los tres modelos en un mismo plot.

  La actividad va de 3 documentos:
