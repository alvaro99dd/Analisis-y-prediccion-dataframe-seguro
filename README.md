# Analisis y prediccion dataframe seguro
![Alt text](https://d31dn7nfpuwjnm.cloudfront.net/images/valoraciones/0049/7296/seguros_que_debemos_tener_500_foro.jpg?1655183944 "cloudfront.net")

Usando un conjunto de datos ficticio sobre los clientes de una aseguradora, realizamos un análisis exploratorio del mismo y entrenamos a un modelo predictivo.
Nuestro objetivo será ver si los datos son suficientes para predecir el estado de las pólizas de clientes nuevos.

## Objetivo
Como comentábamos antes, queremos comprobar si podremos predecir lo "fiable" que es un cliente nuevo, en base a datos como su salario anual, el tamaño del núcleo familiar o su sector de trabajo.
Para ello, primero realizamos un preprocesamiento general de los datos para ir conociendo el dataset y limpiarlo de outliers, valores nulos... etc.

Tras esto, hacemos un EDA para terminar de conocer todos los datos, ver sus distribuciones, compararlas visualmente y realizar algunos test de hipótesis. Con esto queremos asegurarnos de la relación que existe entre variables importantes.

Por último, entrenamos un modelo de machine learning, en concreto hemos usado un Random Forest Classifier. Hemos llegado a la conclusión de usar este modelo gracias a realizar pruebas en pycaret, donde hemos podido comprobar entre varios modelos cuál sería el mejor para nuestro conjunto de datos.

## Resultado
Esta prueba me ha resultado muy útil para aprender a reparar conjuntos de datos y poder usarlos en modelos predictivos, he experimentado además con algunos tests de hipótesis distintos a los que suelo usar y me he encontrado con varios problemas de los que he aprendido mucho.

Con respecto al objetivo de la prueba, el modelo final sólo tenía un accuracy de 0.6, por lo que no parece fiable para predecir el estado de la cuenta.
