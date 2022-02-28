# ESTADISTICA MULTIVARIANTE CON R


En la primera parte de analisis se estudiaran la tasa de enfermedades transmitidas por los alimentos causadas por
el consumo de hortalizas y frutas en la Unión Europea y Estados Unidos con los datos del trabajo de
Callejón et al.[1] (2015).

Las enfermedades del análisis fueron Norovirus, Salmonella spp, Escherichia coli, Campylobacter spp,
Shigella spp, Clostridium spp, Staphylococcus spp, Yersinia spp, Bacillus spp, otros virus y otros microorganismos.
Las verduras eran Ensalada (todos los productos relacionados con la ensalada), Hojas (todos
los productos relacionados con las hojas), Tomate y Otras verduras. Las frutas fueron Germinados (todos
los productos relacionados con los germinados), Bayas, Melón, Zumos y Otras frutas.

En la segunda parte analisis basado en Corradino[2] quien utilizó el MDS para estudiar la estructura de proximidades en una colonia de monos japoneses.
Las observaciones se realizaron en un grupo social de 14 monos japoneses durante un período de
un año. Los catorce monos se nombran y describen en la Tabla 1.
Se observaron las relaciones de proximidad cada 60 segundos. Si dos monos se encontraban a menos de
1.5 metros de distancia y se toleraban, se decía que estaban “cerca”. Se calcularon las disimilaridades para
cada par de monos en función del tiempo que la pareja estuvo cerca la una de la otra. Las disimilaridades
se estudiaron por separado en la temporada de cría (monk_85.dis) y fuera de ésta (monk_84.dis).

En la tercera parte, el análisis de componentes principales se lleva a cabo calculando los valores propios y los
vectores propios de la matriz de correlaciones. Con n casos y p variables, si escribimos X para la matriz
n×p estandarizada para que las columnas tengan media cero y desviación estándar unitaria, encontramos
los valores propios y los vectores propios de la matriz p × p X'X (que es n o n − 1 veces la matriz de
correlaciones dependiendo de qué denominador se haya utilizado al calcular las desviaciones estándar).
Con los datos de los gorriones del ejercicio 3 de los ejercicios propuestos para PCA.

Segundo análisis que consiste en un estudio contiene dos medidas de los anillos de crecimiento en las escamas de salmones de Alaska y de Canadá. Los datos se pueden obtener del archivo salmon.txt. Guardar este archivo en R como un data.frame de nombre salmon con la función read.table. Estos datos también se pueden hallar en el data.frame salmon del paquete rrcov.

En segundo lugar, Vamos a utilizar unos datos del Old Faithful, uno de los géiseres más conocidos del Parque nacional de Yellowstone, en el estado de Wyoming de los Estados Unidos.

Para obtener este conjunto de datos en R simplemente hay que ejecutar la instrucción faithful. También hay un archivo de ayuda que se ve con la instrucción ?faithful.
