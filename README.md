<h1 align = "center">
  Módulo 2: Portafolio de Implementacion con Framework
</h1>

<h3 align = "center">
 Ariadna Jocelyn Guzmán Jiménez A01749373
</h3>

<h3 align = "center">
 09-09-2022
</h3>
 
#### Nombre del archivo a revisar:
portafolioimplementacionm2_framework.py

#### Librerías utilizadas:
* **numpy** : Para la creación de vectores y matrices.
* **pandas** : Para la creación y operaciones de dataframes.
* **seaborn** : Basada en matplotlib para la graficación de datos estadísticos.
* **matplotlib.pyplot** : Para la generación de gráficos.
* **sklearn.model_selection - train_test_split** : Para la división de los datos en subconjuntos de entrenamiento y prueba.
* **sklearn.preprocessing - StandardScaler** : Para el escalamiento de datos.
* **sklearn.ensemble - RandomForestClassifier** : Para la implementación del algoritmo de bosques aleatorios.
* **sklearn.metrics - confusion_matrix** : Para la visualización de desempeño del algoritmo.
* **sklearn - metrics** : Para el cálculo de errores medios (cuadrático o absoluto).

#### Dataset utilizado: 
  	
Breast Cancer Wisconsin (Original), obtenido de la página https://archive.ics.uci.edu/ml/datasets.php

*Set de datos de agrupaciones cronológicas sobre la información de tumores de cáncer de mama*

Atributos:
1. Sample code number: Id del tumor
2. Clump Thickness: 1 - 10
3. Uniformity of Cell Size: 1 - 10
4. Uniformity of Cell Shape: 1 - 10
5. Marginal Adhesion: 1 - 10
6. Single Epithelial Cell Size: 1 - 10
7. Bare Nuclei: 1 - 10
8. Bland Chromatin: 1 - 10
9. Normal Nucleoli: 1 - 10
10. Mitoses: 1 - 10
11. Class: (2 para benigno, 4 para maligno)

#### Métrica de desempeño:
Se utilizó un modelo prueba de 20% y entrenamiento 80%.

Posteriormente, se realizó una variación de estimaciones (2,4,6,8,10) para visualizar cual era el mejor y más preciso y así, calcular las predicciones.

![image](https://user-images.githubusercontent.com/58440787/189464550-1abea728-55eb-4642-850e-ce575b163590.png)

#### Predicciones de prueba: 
Visualizamos que el modelo fue casi totalmente preciso, al no haber tanta diferencia entre las predicciones y los valores estimados. Esto lo reflejamos en la matriz de confusión.

![image](https://user-images.githubusercontent.com/58440787/189464563-1ae40554-17d4-4b46-a4e8-8513cd22936e.png)

![image](https://user-images.githubusercontent.com/58440787/189464574-2a1576ae-d558-4d94-8ac3-46f1b3236d19.png)



