# legalbot-desafio-objetos-JP
Desafío propuesto por legalbot

El objetivo de este desafío es construir un clasificador que categorice los 3.500 Objetos de sociedades en un número N de categorías, dejando el número N a criterio tuyo. La idea es poder entender rápidamente a que se dedica una empresa con la categoría a la cual pertenece el objeto.

La estructura del repositorio consta de la carpeta Notebook, la cual contiene un archivo jupyter que contiene el core del modelo. Además se incluyen dos archivos .html, los cuales contienen los resultados de los modelos LDA con datos transformados a un espacio numérico BOW y TF-IDF. Además, contiene una carpeta llamda embedding, la que almacena los modelos generativos para ambos datos de entrenamiento, con la finalidad que no se deba ejecutar el modelo nuevamente, sino, cargar los archivos directamente y poder realizar predicciones directamente.
La carpeta resources, contiene diccionarios, pero éstos se encuentran en inglés, por lo tanto no se utilizan en este desafio.

