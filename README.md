# Ridge-Lasso
Analisis de regresion Ridge y Lasso que permita construir un modelo predictivo a una base de datos real de manera que puedas generar pronósticos adecuados.

Considerando datos de consumo de combustible y emisiones de CO2, limpiamos los valores a utilizar con los modelos
<br>![image](https://github.com/user-attachments/assets/0a3b3530-a1e6-4b64-bc16-cc5ec9a035ba)

Definimos el área de entrenamiento y área de prueba para utilizar el modelo de regresión múltiple, donde observando la comparación de resultados reales contra predichos y los indicadores de bondad y ajuste, podemos determinar que es aunque se puedan mejorar estos valores, nos provee con información útil y utilizable.
<br>![image](https://github.com/user-attachments/assets/d0c34821-682b-425d-abf9-874249687dcd)

Continuando con el modelo Ridge podemos observar una mejoría en los indicadores de bondad y ajuste lo que lo convierte en el modelo óptimo para este caso, observando los resultados reales contra los predichos podemos ver que son bastante confiables.
<br>![image](https://github.com/user-attachments/assets/9729bb0a-b039-4f61-b6b7-2c0e4a161211)

Teniendo en cuenta también que la gráfica de residuos nos da el mejor ajuste comparado con los otros modelos
<br>![image](https://github.com/user-attachments/assets/8bcabe5d-443f-4f9c-a4d8-707dd593ccb8)

Utilizando el modelo Lasso vemos que también obtenemos buenos resultados pero más cercanos a los obtenidos en la regresión lineal múltiple, que aunque pueden ser valores confiables, no superan a los del modelo Ridge
<br>![image](https://github.com/user-attachments/assets/efd5cfe7-9a21-420c-9653-d5877cd4c21f)

***Conclusion***

A pesar de que los tres modelos obtuvieron valores muy cercanos a los reales, el mejor modelo en este caso fue el modelo Ridge debido a su alto valor de R^2 (0.9934) y el valor más bajo de los tres modelos de Raíz del Error cuadrático medio, que aunque los resultados no son exactos, la comparación entre los valores reales y predichos son muy cercanos y donde la gráfica de residuos es la que mas se alinea con la predicción, podemos utilizar estos datos como valores confiables. 
