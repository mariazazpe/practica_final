________________________________________________________________________________________________________________________

Esta es la última práctica para la asignatura de Machine Learning, del máster en ciencia de datos, con el título:
ANÁLISIS DE PUNTUACIÓN DE COMERCIOS. La hemos realizado Alba Rodríguez Berenguel y María Zazpe Quintana.
________________________________________________________________________________________________________________________

Correos electrónicos:
alba.rberenguel@cunef.edu
maria.zazpe@cunef.edu

Github:
Alba: https://github.com/albarodber/prediccion_puntuacion
Maria: https://github.com/mariazazpe/practica_final
________________________________________________________________________________________________________________________

Los datos que empleamos los hemos obtenidos de la web de datos abiertos www.yelp.com/dataset y contiene información sobre
usuarios, negocios y reseñas de estos usuarios sobre los negocios. A partir de ellos, hemos planteado el caso de uso:

PROBABILIDAD DE QUE UN RESTAURANTE OBTENGA UNA PUNTUACIÓN ALTA POR PARTE DE UN USUARIO EXPERIMENTADO, DADOS LOS ATRIBUTOS
DEL RESTAURANTE. Considerando que una puntuación alta es entre 4 - 5 estrellas y los usuarios experimentados son aquellos
que han publicado más de 100 reseñas.

Para ello hemos llevado a cabo practicamente todas las fases de un proyecto de Machine Learning: Recolección, preparación,
análisis de los datos, construcción de modelos, entrenamiento y elección de modelo.
________________________________________________________________________________________________________________________

Las carpetas que se encuentran en el proyecto son las siguientes:

    - Data: Se encuentran los datos utilizados. En la carpeta raw están los datos brutos sin modificar y en la carpeta 
	    processed están los datos ya transformados, con los que hemos trabajado. Hay una carpeta extra, "geoespacial"
	    con los archivos que hemos empleado para realizar las visualizaciones geoespaciales.
    - Env: Archivo requirements.txt
    - Html: Notebooks guardados en formato html.
    - Models: Modelos construidos guardados en formato pickle.
    - Notebooks: Notebooks con los que hemos trabajado, enumerados según el orden que hemos seguido en el proyecto.

También se puede encontrar un archivo formato excel, llamado "data_dictionary" que es el diccionario de datos, donde se 
explica cada una de las variables de nuestros datos.
	