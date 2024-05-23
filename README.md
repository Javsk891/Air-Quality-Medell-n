# Air-Quality-Medell-n
Repositorio que contiene diferentes modelos de Machine Learning, donde se trabaja la predicción de variables de calidad del aire de la ciudad de Medellín utilizando diferentes modelos de ML.

El dataset utilizado se encuentra en el repositorio. "data_volador2"

PM2.5 LSTM model.

A través del Notebook llamado PM2.5 LSTM model se ha desarrollado un modelo de machine learning con las librerías TensorFlow y Keras en donde se busca realizar un pronostico de la variable de calidad del aire PM2.5, se hace el desarrollo del modelo con la finalidad de observar el comportamiento del modelo en este tipo de predicciones de contaminacion ambiental. Los resultados obtenidos han sido aceptables, pues se ha tenido predicciones cercanas a los valores reales para los sets de entrenamiento, validación y prueba. La gráficas muestras que las predicciones siguen las tendencias de los datos reales. 

PREDICCIONES DEL SET DE ENTRENAMIENTO COMPARADO A LOS DATOS REALES DEL SET DE DATOS 

![image](https://github.com/Javsk891/Air-Quality-Medell-n/assets/96545411/6b908b53-72c7-4306-8167-4bdb81eba39c)

PREDICCIONES DEL SET DE VALIDACION COMPARADO A LOS DATOS REALES DEL SET DE DATOS 

![image](https://github.com/Javsk891/Air-Quality-Medell-n/assets/96545411/3ff8f3dd-f171-4aee-ab20-c1da4e3490e6)

PREDICCIONES DEL SET DE PRUEBA COMPARADO A LOS DATOS REALES DEL SET DE DATOS 

![image](https://github.com/Javsk891/Air-Quality-Medell-n/assets/96545411/4ea07a79-243f-4d9e-b37c-c4fec7e86ecd)

Los errores cuadraticos medios (RSME) han dado valores aceptables, sin embargo este modelo es apenas una prueba, y el objetivo es seguir construyendo y expreimentando con sus diferentes hiperparámetros para mejorar los resultados de las predicciones

![image](https://github.com/Javsk891/Air-Quality-Medell-n/assets/96545411/905bc2d8-7049-4e1d-af8b-1e015709294e)

También se considera el análisis en los diferentes metodos de imputación de datos faltantes en el set de datos de entrada, ya que se considera que este puede ser un factor que pudo disminuir la capacidad de predicción del modelo 
