# Image_analysis_with_NN
Análisis de fotos de abejas y clasificación por especie y estado de salud, mediante redes neuronales convolucionales. Trabajo realizado en Posgrado de Big Data en Universidad ORT. 

En primera instancia, se construyen dos clasificadores; uno para la predicción de la sub-especie y otro para la predicción del estado de salud. Se cuenta con las imágenes en formato png y diferentes tamaños, el dataset con las etiquetas correspondientes a la sub-especie y estado de salud de cada abeja, y el dataset con la información a predecir.
En primer lugar, se realiza un análisis exploratorio de datos, luego una partición en train, validation y test. Se eligen los parámetros adecuados para mejorar la arquitectura de la red, en cuanto a capas convolucionales y regularización.
Primero se crearon modelos personalizados individuales, luego éstos se ensayaron por Transfer learning y por último por Multitasking Learning.
Para la mejora del modelo, siempre teniendo como objetivo lograr una macro average accuray superior al 85% en test, se ensayaron diferentes alternativas.
La macro average recall es una métrica usada en problemas muti-clase como es nuestro caso, y mide el recall promedio por clase. 
