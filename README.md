# Morphing
La transformación de la forma de un objeto a otra forma es llamada **MORPHING**, que es la  contracción de **METAMORPHOSING**, o la metamorfosis de formas.

# Técnica de Morphing
Un animador puede modelar una metamorfosis por medio de una transición de formas poligonales a 
través de polígonos intermedios, de un frame a otro frame.
Dados dos frames, cada uno con diferente número de segmentos de línea, podemos primero ajustar 
la especificación de un objeto en uno de los frames, de tal modo que el número de ejes o aristas 
(vértices) del polígono sea el mismo en los dos frames.
El segmento de línea del frame 1 tiene dos puntos, será transformado en el segundo frame en dos 
segmentos. Como el frame 2 tiene dos segmentos de línea, adicionaremos un punto en el segmento 
del frame 1, para balancear el número de segmentos como se muestra a continuación:

![image](https://github.com/Monserrath1/Tecnica_de_Morphing/assets/130505601/d9785221-c813-4e41-ae81-15c9d80f2e33)

De este modo se balancea el número de segmento y vértices.



