# Prueba DataScience - Whale & Jaguar

Esta prueba contempla una dedicación máxima de 5 días. Lea muy bien las instrucciones de cada punto y enfóquese en entregar únicamente lo que aparece en la sección de "entregables".

**El entregable debe hacerse como un pull request a este repositorio**

## I - Clasificador de textos
**PROBLEMA** - Utilice el conjunto de datos que se encuentra en la ubicación _data/clasificador/clasificador.json_ para crear un **modelo baseline** que, a partir de la columna _text_ prediga la edad de la persona que escribió dicho texto. El modelo debe estar creado en Python, utilice el framework que mejor le parezca (tenga en cuentael tiempo ya que es un **modelo baseline**).

**ENTREGABLE** - Pull request a este repositorio que contenga una carpeta con los scripts o notebooks de jupyter utilizados para resolver el problema, recuerde incluir métricas de desempeño del modelo en el conjunto de datos brindado. Por favor nombre su carpeta "prueba_{_su nombre_}".

**ENTREVISTA** - Para la entrevista prepare una presentación corta (5min) en la que muestre 
- La estrategia utilizada para resolver el problema
- Los resultados y desempeño del modelo

_Recuerde que debe presentarla como si fuéramos su cliente que lo ha contratado para resolver este problema específico_.

## II - Proyecto abierto

**PROBLEMA** - Dado un conjunto de tweets, se requiere crear una solución que permita derivar diversas variables de tipo demográfico de los usuarios que escriben dichos tweets. Considere que se tiene una tabla como la que está en la ubicación  _data/proyecto/proyecto.json_, tenga en cuenta la estructura de datos que tiene a disposición. En el mismo directorio encontrará un archivo con explicación de las columnas.

Plantee una **estrategia de soluición** al problema de inferir las variables demográficas
- Rango de edad (de la cuenta que escribe el tweet)
- Sexo (de la cuenta que escribe el tweet)
- Ubicación (de la cuenta que escribe el tweet)

**Sólo debe trabajar la estrategia de solución en un documento estructurado, no se espera que escriba nada de código**.

Tenga en cuenta que en la fuente original pueden aparecer múltiples tweets de un mismo usuario. Recuerde que el objetivo es derivar las variables demográficas a nivel de usuario, mas no de tweet.

**ENTREGABLE** - Incluir documento con estrategia de solución en la carpeta para el pull request mencionada anteriormente. Contemple modelos base a partir de los cuales iterar y detalle qué estrategias o modelos utilizaría en cada etapa de la solución.

**ENTREVISTA** - Para la entrevista prepare una presentación corta (5min) en la que exponga la estrategia de solución.

_Recuerde que debe presentarla como si fuéramos su cliente que lo ha contratado para resolver este problema específico_.
