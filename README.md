# Tarea1-modulo2-Veru
Tarea: Investigación y Desarrollo de un Análisis Exploratorio de Datos (EDA)

## 1. ¿Qué es el EDA y cuál es su propósito en el análisis de datos?

El análisis exploratorio de datos (EDA) es utilizado por los científicos de datos para analizar e investigar conjuntos de datos y resumir sus características principales, a menudo empleando métodos de visualización de datos.

EDA ayuda a determinar la mejor manera de manipular las fuentes de datos para obtener las respuestas que necesita, lo que facilita a los científicos de datos descubrir patrones, detectar anomalías, probar una hipótesis o verificar suposiciones.

EDA se utiliza principalmente para ver lo que los datos pueden revelar más allá del modelado formal o la tarea de prueba de hipótesis y proporciona una mejor comprensión de las variables del conjunto de datos y las relaciones entre ellas. También puede ayudar a determinar si las técnicas estadísticas que está considerando para el análisis de datos son adecuadas. Desarrolladas originalmente por el matemático estadounidense John Tukey en la década de 1970, las técnicas EDA siguen siendo un método ampliamentecode utilizado en el proceso de descubrimiento de datos en la actualidad.

El objetivo principal de EDA es ayudar a analizar los datos antes de hacer suposiciones. Puede ayudar a identificar errores obvios, así como a comprender mejor los patrones dentro de los datos, detectar valores atípicos o eventos anómalos y encontrar relaciones interesantes entre las variables.

Los científicos de datos pueden utilizar el análisis exploratorio para garantizar que los resultados que producen sean válidos y aplicables a los resultados y objetivos empresariales deseados. EDA también ayuda a las partes interesadas al confirmar que están haciendo las preguntas correctas. EDA puede ayudar a responder preguntas sobre las desviaciones estándar, las variables categóricas y los intervalos de confianza. Una vez que se complete el EDA y se extraigan los conocimientos, sus características se pueden utilizar para un análisis o modelado de datos más sofisticados, incluido el machine learning.

Entre las funciones y técnicas estadísticas específicas que puede realizar con las herramientas EDA se incluyen las siguientes:

Técnicas de clustering y reducción de dimensiones, que ayudan a crear visualizaciones gráficas de datos de alta dimensión que contienen muchas variables.

Visualización univariante de cada campo del conjunto de datos sin procesar, con estadísticas de resumen.

Visualizaciones bivariantes y estadísticas de resumen que le permiten evaluar la relación entre cada variable del conjunto de datos y la variable de destino que está viendo.

Visualizaciones multivariantes, para mapear y comprender las interacciones entre los diferentes campos de los datos.

K-medias es un método de clustering en el aprendizaje no supervisado donde los puntos de datos se asignan a grupos K, es decir, el número de clústeres, basado en la distancia desde el centroide de cada grupo. Los puntos de datos más cercanos a un centroide determinado se agruparán en la misma categoría. El clustering K-medias se utiliza comúnmente en la segmentación de mercados, el reconocimiento de patrones y la compresión de imágenes.

Los modelos predictivos, como la regresión lineal, utilizan estadísticas y datos para predecir resultados.

## 2. ¿Qué tipos de datos existen (categóricos, numéricos, ordinales, etc.) en un EDA?

Datos cualitativos
En estadística, los datos cualitativos, también llamados datos categóricos, son un tipo de datos que representan cualidades, características o categorías. Es decir, los datos cualitativos solo pueden tomar valores no numéricos.

Asimismo, dentro de los datos cualitativos se distinguen dos subtipos de datos: los datos cualitativos ordinales, los cuales se pueden ordenar jerárquicamente, y los datos cualitativos nominales, los cuales no se pueden ordenar.

Datos cuantitativos
En estadística, los datos cuantitativos, también conocidos como datos numéricos, son datos que representan números. Es decir, los datos cuantitativos son un tipo de datos que solo pueden tomar valores numéricos.

Además, los datos cuantitativos se clasifican en dos subtipos de datos estadísticos: los datos cuantitativos discretos, que no pueden tomar algunos valores, y los datos cuantitativos continuos, que pueden tomar cualquier valor dentro de un intervalo.

## 3. ¿Cuál es la diferencia entre análisis univariado, bivariado y multivariado?

Hay cuatro tipos principales de EDA:

No gráfico univariante
gráfico univariante
No gráfico multivariante
Gráfico multivariante
No gráfico univariante
Es la forma más simple de análisis de datos, donde los datos que se analizan consisten en una sola variable. Dado que es una sola variable, no se ocupa de causas o relaciones. El objetivo principal del análisis univariado es describir los datos y encontrar patrones dentro de ellos.

gráfico univariante
Los métodos no gráficos no proporcionan una imagen completa de los datos. Por lo tanto, se requieren métodos gráficos. Entre los tipos comunes de gráficos univariantes se incluyen los siguientes:

Diagramas de tallos y hojas, que muestran todos los valores de los datos y la forma de la distribución.

Histogramas, un gráfico de barras en el que cada barra representa la frecuencia (recuento) o proporción (recuento/recuento total) de casos para un rango de valores.

Diagramas de caja, que representan gráficamente el resumen de cinco números, que son el mínimo, el primer cuartil, la mediana, el tercer cuartil y el máximo.
No gráfico multivariante
Los datos multivariantes surgen de más de una variable. Las técnicas de EDA multivariante no gráfico generalmente muestran la relación entre dos o más variables de los datos a través de tabulación cruzada o estadística.

Gráfico multivariante
Los datos multivariantes utilizan gráficos para mostrar las relaciones entre dos o más conjuntos de datos. El gráfico más utilizado es un diagrama de barras agrupado o un gráfico de barras en el que cada grupo representa un nivel de una de las variables y cada barra dentro de un grupo representa los niveles de la otra variable.

Otros tipos comunes de gráficos multivariante incluyen:

Diagrama de dispersión, que se utiliza para trazar puntos de datos en un eje horizontal y vertical para mostrar cuánto se ve afectada una variable por otra.

Gráfico multivariante, que es una representación gráfica de las relaciones entre los factores y una respuesta.

Gráfico de ejecución, que es un gráfico lineal de datos trazados a lo largo del tiempo.

Gráfico de burbujas, que es una visualización de datos que muestra múltiples círculos (burbujas) en un gráfico bidimensional.

Mapa de calor, que es una representación gráfica de los datos en la que los valores se representan por color.

## 4. ¿Qué es la estadística descriptiva?

La estadística descriptiva es la rama de la estadística que se encarga de describir los datos recopilados para ayudar a analizarlos. Es decir, la estadística descriptiva sirve para resumir un conjunto de datos mediante medidas estadísticas, gráficos o tablas.

Es la parte de la estadística que se usa para resumir una muestra de datos estadísticos, a diferencia de la estadística inferencial cuyo objetivo es determinar los parámetros de la población. 

Medidas estadísticas descriptivas
Las medidas estadísticas descriptivas son parámetros estadísticos que sirven para describir un conjunto de datos. Es decir, las medidas descriptivas son cálculos que se hacen sobre una muestra de datos para resumir dichos datos.

Ezoic
En estadística, las medidas descriptivas se clasifican en:

Medidas de tendencia central: son valores representativos del centro de un conjunto de datos.
Medidas de dispersión: sirven para evaluar cuánto de dispersos o juntos están los datos de una muestra.
Medidas de posición: informan de la estructura de un conjunto de datos, es decir, ayudan a saber cómo es un conjunto de datos.
Medidas de forma: permiten describir una distribución de probabilidad según la forma que tiene sin necesidad de representarla gráficamente.

Gráficos estadísticos descriptivos
Un gráfico estadístico descriptivo es una representación gráfica de un conjunto de datos, de modo que un gráfico estadístico permite resumir una muestra de datos de manera visual.

Por lo tanto, una gráfico estadístico sirve para analizar una muestra de datos visualmente. En estadística descriptiva, los gráficos o diagrama son muy útiles porque ayudan extraer conclusiones de un conjunto de datos sin necesidad de hacer cálculos.

## 5. ¿Qué es la limpieza de datos y qué tareas suelen incluirse en este paso?

La limpieza de datos, también llamada depuración de datos, es el proceso de identificar y corregir errores e incongruencias en conjuntos de datos sin procesar para mejorar la calidad de los datos.

El objetivo de la limpieza de datos es ayudar a garantizar que los datos sean precisos, completos, coherentes y utilizables para el análisis o la toma de decisiones. Los procesos de limpieza de datos funcionan para abordar problemas comunes de calidad de datos, como duplicados, valores faltantes, incongruencias, errores de sintaxis, datos irrelevantes y errores estructurales.

La limpieza de datos también es un componente fundamental de la gestión eficaz de datos, que ayuda a garantizar que los datos sigan siendo precisos, seguros y accesibles en cada etapa de su ciclo de vida.

Los datos de alta calidad o “limpios” son cruciales para adoptar eficazmente la inteligencia artificial (IA) y las herramientas de automatización. Las organizaciones también pueden utilizar la IA para ayudar a agilizar el proceso de limpieza de datos.

¿Por qué es importante la limpieza de datos?
Las organizaciones con datos limpios y bien gestionados están mejor equipadas para tomar decisiones confiables basadas en datos, responder rápidamente a los cambios del mercado y optimizar las operaciones del flujo de trabajo.

La limpieza de datos es un componente integral de la ciencia de datos, ya que es un primer paso esencial para la transformación de datos: la limpieza de datos mejora la calidad de los datos, y la transformación de datos convierte esos datos sin procesar de calidad en un formato utilizable para el análisis.

La transformación de datos permite a las organizaciones desbloquear todo el potencial de los datos para utilizar business intelligence (BI), depósitos de datos y analytics de big data. Si los datos de origen no están limpios, los resultados de estas herramientas y tecnologías podrían ser poco confiables o inexactos, lo que daría lugar a malas decisiones e ineficiencias.

De manera similar, los datos limpios también sustentan el éxito de la IA y machine learning (ML) en una organización. Por ejemplo, la limpieza de datos ayuda a garantizar que los algoritmos de ML se entrenen con conjuntos de datos precisos, coherentes y sin sesgo. Sin esta base de datos limpios, los algoritmos podrían producir predicciones inexactas, incongruentes o con sesgo, lo que reduce la eficacia y confiabilidad de la toma de decisiones.

¿Cuáles son los beneficios de la limpieza de datos?
Los beneficios clave de la limpieza de datos incluyen:

Toma de decisiones fundamentada
Productividad mejorada
Eficiencia de costos
Cumplimiento y seguridad de los datos
Rendimiento mejorado del modelo
Mejora de la congruencia de los datos
Toma de decisiones fundamentada
Las decisiones basadas en datos limpios y de alta calidad tienen más probabilidades de ser efectivas y estar alineadas con los objetivos comerciales. Por el contrario, las decisiones empresariales basadas en datos sucios (con información duplicada, errores tipográficos o incoherencias) pueden dar lugar a recursos desperdiciados, oportunidades perdidas o errores estratégicos.

Productividad mejorada
Los datos limpios permiten a los empleados dedicar menos tiempo a corregir errores e incongruencias, acelerando el procesamiento de datos. Así, los equipos tienen más tiempo para enfocarse en el análisis de datos y los insights.

Eficiencia de costos
La mala calidad de los datos puede dar lugar a errores costosos, como un exceso de inventario debido a registros duplicados o una interpretación errónea del comportamiento de los clientes a causa de datos incompletos. La limpieza de datos ayuda a prevenir estos errores, ahorrando dinero y reduciendo los riesgos operativos.

Cumplimiento y seguridad de los datos
Los datos limpios pueden ayudar a las organizaciones a cumplir con las regulaciones de protección de datos, como el Reglamento General de Protección de Datos (RGPD) de la Unión Europea, manteniendo los datos precisos y actualizados. También evita la retención accidental de información redundante o sensible, reduciendo los riesgos de seguridad.

Rendimiento mejorado del modelo
La limpieza de datos es esencial para entrenar modelos de machine learning eficaces. Los datos limpios mejoran la precisión de los resultados y ayudan a garantizar que los modelos se generalicen bien a nuevos datos, lo que lleva a predicciones más sólidas.

Mejora de la coherencia de los datos
La limpieza de datos ayuda a garantizar que los datos combinados sean coherentes y utilizables en todos los sistemas, evitando problemas que puedan surgir de formatos o estándares de datos en conflicto. Esto es importante para la integración de datos, donde los datos limpios y estandarizados ayudan a garantizar que los sistemas dispares puedan compartir y comunicarse de manera efectiva.

Técnicas de limpieza de datos
La limpieza de datos suele comenzar con la evaluación de datos. También conocida como perfilado de datos, esta evaluación implica revisar un conjunto de datos para identificar problemas de calidad que requieran corrección. Cuando se identifican, las organizaciones pueden emplear varias técnicas de limpieza de datos, que incluyen:

Normalización
Abordar los valores atípicos
Deduplicación
Abordar los valores faltantes
Validación
Normalización
Las incongruencias surgen cuando los datos se representan en diferentes formatos o estructuras dentro del mismo conjunto de datos. Por ejemplo, una discrepancia común es el formato de fecha, como “MM-DD-AAAA” frente a “DD-MM-AAAA”. La estandarización de formatos y estructuras puede ayudar a garantizar la uniformidad y compatibilidad para un análisis preciso.

Abordar los valores atípicos
Los valores atípicos son puntos de datos que se desvían significativamente de otros en un conjunto de datos, causados por errores, eventos raros o anomalías verdaderas. Estos valores extremos pueden distorsionar el análisis y la precisión del modelo al sesgar los promedios o las tendencias. Los profesionales de la gestión de datos pueden abordar los valores atípicos evaluando si son errores de datos o valores significativos. Luego, pueden decidir retener, ajustar o eliminar esos valores atípicos en función de la relevancia para el análisis.

Deduplicación
La deduplicación de datos es un proceso de racionalización en el que los datos redundantes se reducen eliminando copias adicionales de la misma información. Los registros duplicados ocurren cuando se repite el mismo punto de datos debido a problemas de integración, errores de entrada manual de datos o fallas del sistema. Los duplicados pueden inflar los conjuntos de datos o distorsionar el análisis, lo que lleva a conclusiones inexactas.

Abordar los valores faltantes
Los valores faltantes surgen cuando los puntos de datos están ausentes debido a una recopilación de datos incompleta, errores de entrada o fallas del sistema. Estas deficiencias pueden distorsionar el análisis, reducir la precisión del modelo y limitar la utilidad del conjunto de datos. Para solucionar este problema, los profesionales de datos pueden reemplazar los datos que faltan por datos estimados, eliminar entradas incompletas o marcar los valores faltantes para una investigación más profunda.

Validación
Una revisión final al término del proceso de limpieza de datos es crucial para verificar que los datos están limpios y listos para el análisis o visualización y sean precisos. La validación de datos a menudo implica el uso de inspección manual o herramientas automatizadas de limpieza de datos para verificar cualquier error restante, datos inconsistentes o anomalías.

Uso de IA para la limpieza de datos
Los científicos de datos, analistas de datos, ingenieros de datos y otros profesionales de la gestión de datos pueden realizar técnicas de limpieza de datos a través de métodos manuales, como inspección visual, referencias cruzadas o tablas dinámicas en hojas de cálculo de Microsoft Excel.

También pueden usar lenguajes de programación, como Python, SQL y R para ejecutar scripts y automatizar el proceso de limpieza de datos. Muchos de estos enfoques están respaldados por herramientas de código abierto, que brindan flexibilidad y soluciones rentables para organizaciones de todos los tamaños.

Sin embargo, la IA también se puede utilizar para ayudar a automatizar y optimizar varios pasos de limpieza de datos, que incluyen:

Análisis de datos de origen: las herramientas de limpieza de datos impulsadas por IA pueden identificar automáticamente patrones, anomalías e incongruencias en los datos de origen. La IA también puede sugerir reglas de negocio relevantes mediante el análisis de tendencias y relaciones de datos, lo que reduce los esfuerzos manuales para definir estas reglas. Por ejemplo, la IA puede identificar que una columna de números de teléfono a menudo tiene códigos de área faltantes y luego sugerir una regla para la estandarización.
Estandarización de datos: el procesamiento de lenguaje natural (PLN) puede estandarizar texto no estructurado, como el formato de direcciones o descripciones de productos. Los modelos de machine learning también pueden identificar y recomendar formatos coherentes para datos, como fechas o monedas. Los generadores de expresiones regulares impulsados por IA pueden automatizar la detección y normalización de formatos incoherentes.
Consolidación de duplicados: los modelos de IA basados en reglas o aprendidos pueden decidir cuál es el mejor registro para “sobrevivir” al eliminar duplicados, teniendo en cuenta la precisión, la actualidad o la confiabilidad. Por ejemplo, los modelos pueden priorizar campos específicos en función del contexto, como mantener la dirección de correo electrónico más reciente en el registro consolidado.
Aplicación de reglas: Los modelos de IA pueden automatizar la creación y aplicación de reglas de limpieza de datos aprendiendo de las correcciones históricas y del feedback del usuario. Pueden aplicar estas reglas de forma dinámica a múltiples conjuntos de datos, ayudando a garantizar la coherencia entre los sistemas. Los sistemas de IA también pueden generar reglas personalizadas para industrias o ámbitos específicos, como los números de identificación del impuesto sobre el valor agregado (IVA) en la Unión Europea.


## 6. ¿Qué papel juegan las librerías pandas, matplotlib y seaborn en un EDA?
Las librerías python data science son el núcleo del ecosistema analítico y permiten realizar cálculos numéricos, transformar datos, representarlos visualmente y obtener conclusiones fiables.

Portales como Kaggle muestran en sus encuestas anuales cómo estas librerías son las más utilizadas por analistas, científicos de datos y perfiles técnicos que trabajan con información de distintas fuentes. Cada una cumple una función distinta dentro del análisis.

Numpy: la base numéerica del análisis
Numpy es la librería que proporciona estructuras de datos optimizadas para trabajar con grandes volúmenes de información numérica. Está construida para manejar operaciones vectoriales y matriciales de forma rápida, algo esencial en cualquier análisis complejo.

Algunas de sus funciones habituales son:

- Trabajar con arrays multidimensionales.
- Ejecutar operaciones matemáticas de forma eficiente.
- Manipular estructuras numéricas de gran tamaño.

Sin Numpy, gran parte del ecosistema analítico de Python no existiría, ya que ofrece el rendimiento necesario para manejar cálculos de alto volumen.

Pandas: importación, limpieza y transformación de datos
Si hay una librería central dentro de las librerías python data science, esa es Pandas. Todo proyecto analítico comienza por importar, revisar, limpiar y preparar los datos, y Pandas proporciona métodos claros y directos para hacerlo.

Se suele utilizar para:

- Importar datos desde CSV, Excel, SQL o fuentes web.
- Limpiar inconsistencias y corregir formatos erróneos.
- Detectar valores fuera de rango mediante análisis estadístico.
- Interpolar valores ausentes.
- Crear nuevas columnas basadas en cálculos o condiciones.
- Agrupar datos y generar resúmenes.
- Combinar varias fuentes en una sola estructura.

Pandas es la herramienta que convierte datos brutos en información trabajable. Sin ella, las fases posteriores del análisis serían mucho más difíciles.

Matplotlib: la base de la visualización
Una parte importante del análisis consiste en representar los datos para identificar patrones, tendencias o comportamientos. Matplotlib es la librería que permite construir todo tipo de visualizaciones desde cero, con control total sobre el formato y la estructura del gráfico.

Se suelen desarrollar gráficos como:

- Líneas para estudiar evoluciones temporales.
- Barras para comparaciones entre categorías.
- Histogramas para analizar distribuciones.
- Diagramas de dispersión para estudiar relaciones entre variables.

Matplotlib proporciona la flexibilidad necesaria para crear visualizaciones personalizadas y adaptar cada gráfico a las necesidades del análisis.

Seaborn: visualización estadística avanzada
Seaborn está construida sobre Matplotlib, pero incorpora una capa estadística que facilita visualizar patrones de forma más directa. Permite crear gráficos complejos con pocas instrucciones y está orientada a representar distribuciones y relaciones.

Algunas visualizaciones centradas en el análisis son:

- Heatmaps para mostrar correlaciones.
- Regresiones lineales.
- Joint plots para combinar varias distribuciones.
- Gráficos avanzados ideales para análisis exploratorio.
Seaborn es fundamental cuando se quiere profundizar en el comportamiento de las variables, especialmente cuando se analizan relaciones entre ellas.

La combinación de librerías en un flujo de trabajo real
Una de las claves del ecosistema de Data Science es que estas librerías se complementan entre sí. Un flujo de trabajo habitual sigue una estructura como esta:

Numpy para cálculos numéricos.
Pandas para estructurar, limpiar y transformar.
Matplotlib para construir visualizaciones detalladas.
Seaborn para gráficos estadísticos más avanzados.
De esta forma, todo el proyecto se desarrolla dentro de Python, sin necesidad de dividir el trabajo entre distintas plataformas.

Conclusión
Las librerías python data science son el corazón de cualquier proyecto de análisis. Numpy aporta la base numérica, Pandas organiza y transforma los datos, Matplotlib representa información con detalle y Seaborn permite ir un paso más allá en el análisis visual. Juntas, forman un conjunto sólido que permite trabajar de forma profesional con datos procedentes de cualquier fuente.

## 7. ¿Qué es una matriz de correlación y para qué sirve en el EDA?
Una matriz de correlación ayuda a visualizar las relaciones entre múltiples variables simultáneamente. Es una herramienta esencial para identificar patrones y correlaciones entre diferentes métricas, lo que la hace valiosa para la exploración y predicción de datos.

Cómo leer la visualización:
Una matriz de correlación muestra los coeficientes de correlación entre pares de variables en un formato matricial. Cada celda de la matriz representa la correlación entre dos variables, normalmente codificada por colores para indicar la fuerza y la dirección de la relación (positiva o negativa).

Estructura de datos:
Medidas: Múltiples
Dimensiones: Múltiples

Buenas prácticas / Limitaciones:
Puntos de datos: Utilizar con un número manejable de variables para mantener la claridad.
Claridad: Evitar sobrecargar la matriz con demasiadas variables, ya que puede dificultar su interpretación.
Contexto: Proporcionar contexto o anotaciones para resaltar las correlaciones significativas.

Ejemplos de cuándo utilizarlo:
- Analizar la relación entre distintos indicadores financieros.
- Comprender el comportamiento de los clientes a través de diversas métricas.
- Exploración de correlaciones en datos sobre salud y bienestar.
- Usos comunes en la industria:
- Finanzas
- Marketing
- Sanidad
- Investigación
- 
## 8. ¿Qué son los outliers y qué métodos existen para detectarlos y tratarlos en un análisis exploratorio?
Los valores atípicos, también conocidos como outliers, son observaciones que se desvían significativamente del resto de los datos en un conjunto. En el contexto de la programación y el análisis de datos, entender qué son los valores atípicos y cómo manejarlos es fundamental para garantizar la calidad de los resultados estadísticos. Estos puntos de datos pueden surgir por errores en la recolección, variaciones naturales o eventos inusuales, y su identificación es clave para tomar decisiones informadas en proyectos tecnológicos. 

Un valor atípico se define como una observación que se encuentra a una distancia inusual de otros valores en un conjunto de datos. Por ejemplo, en un dataset de temperaturas diarias que oscilan entre 20°C y 30°C, un valor de 50°C sería un outlier. Estos valores pueden distorsionar los análisis estadísticos, como el cálculo de la media o la varianza, y afectar modelos de machine learning.

Tipos de Valores Atípicos
Los valores atípicos pueden clasificarse en tres categorías principales: puntuales, contextuales y colectivos. Los valores atípicos puntuales son observaciones individuales que se desvían del resto del conjunto, como el valor 50 en el ejemplo anterior. Los valores atípicos contextuales dependen del contexto, como un pico de tráfico web durante un evento específico. Por último, los valores atípicos colectivos son grupos de datos que, en conjunto, se desvían de la norma, como un clúster de transacciones sospechosas en un sistema financiero.

Identificar el tipo de outlier es crucial para decidir cómo manejarlo. Por ejemplo, en un sistema de detección de fraudes, un valor atípico contextual podría ser una señal importante, mientras que un valor atípico puntual podría ser un error de entrada.

Causas de los Valores Atípicos
Los valores atípicos pueden originarse por diversas razones. Los errores de medición son comunes, como un sensor que registra incorrectamente una temperatura. Las variaciones naturales también pueden generar outliers, como un día excepcionalmente cálido en un registro climático. Además, los eventos anómalos, como un ciberataque, pueden producir valores atípicos en datasets de ciberseguridad. En el desarrollo de software, los errores humanos, como ingresar un valor incorrecto en una base de datos, también son una causa frecuente.

Entender la causa de un outlier ayuda a determinar si debe eliminarse, ajustarse o analizarse más a fondo. Por ejemplo, en un sistema de monitoreo, un valor atípico causado por un error de hardware debería corregirse, mientras que uno causado por un evento real podría requerir un análisis adicional.

Métodos para Identificar Valores Atípicos
Existen varios métodos para detectar valores atípicos, desde enfoques visuales hasta técnicas estadísticas avanzadas. A continuación, se presentan los más comunes, con ejemplos prácticos en Python.

Visualización con Boxplots
Los diagramas de caja (boxplots) son una forma visual de identificar valores atípicos. Un boxplot muestra la mediana, los cuartiles y los valores que caen fuera de un rango definido, conocidos como límites de los bigotes. Los puntos fuera de estos límites se consideran outliers.

Regla del Rango Intercuartílico (IQR)
El método del rango intercuartílico (IQR) es un enfoque estadístico para detectar outliers. El IQR se calcula como la diferencia entre el tercer cuartil (Q3) y el primer cuartil (Q1). Los valores que caen fuera de los límites [Q1 - 1.5IQR, Q3 + 1.5IQR] se consideran atípicos.

Z-Score para Datos Normales
El Z-score mide cuántas desviaciones estándar está un valor respecto a la media. Un valor con un Z-score mayor a 3 (o menor a -3) suele considerarse un outlier en una distribución normal.

Métodos Avanzados: DBSCAN
En datasets multidimensionales, los métodos de clustering como DBSCAN pueden identificar valores atípicos como puntos que no pertenecen a ningún clúster. Este enfoque es útil en aplicaciones de machine learning.

Cómo Manejar Valores Atípicos
Una vez identificados, los valores atípicos pueden manejarse de varias formas, dependiendo del contexto. Las opciones incluyen eliminarlos, transformarlos o analizarlos por separado.

Eliminación de Outliers
Eliminar valores atípicos es común cuando se deben a errores. Sin embargo, esto debe hacerse con cuidado para no perder información valiosa.

Transformación de Datos
Transformar los datos, como aplicar una escala logarítmica, puede reducir el impacto de los outliers sin eliminarlos.

Análisis Separado
En algunos casos, los outliers son de interés y deben analizarse por separado, como en la detección de fraudes.

Consideraciones al Trabajar con Outliers
Al manejar valores atípicos, es importante considerar el contexto del dataset y los objetivos del análisis. Los métodos detección outliers no son universales, y lo que funciona para un dataset puede no ser adecuado para otro.

Conclusiones
Los valores atípicos son una parte inevitable del análisis de datos, y su manejo adecuado es esencial para obtener resultados precisos en proyectos de programación y tecnología. Desde la visualización con boxplots hasta métodos avanzados como DBSCAN, existen múltiples herramientas para identificar y tratar outliers. Los ejemplos de código en Python proporcionados en este tutorial permiten a los programadores implementar estas técnicas de manera práctica. Al trabajar con valores atípicos, es crucial entender su origen, elegir el método de detección adecuado y tomar decisiones informadas sobre cómo manejarlos. Con estas habilidades, podrás mejorar la calidad de tus análisis y construir sistemas más robustos en el mundo de la tecnología.

## 9. ¿Qué es hipótesis testing y para qué sirve en el EDA?
La comprobación de hipótesis es un procedimiento estadístico utilizado para comprobar supuestos o hipótesis sobre un parámetro de la población. Implica formular una hipótesis nula (H0) y una hipótesis alternativa (Ha), recopilar datos y determinar si las pruebas son lo suficientemente sólidas como para rechazar la hipótesis nula.

El objetivo principal de la comprobación de hipótesis es hacer inferencias sobre una población a partir de una muestra de datos. Permite a los investigadores y analistas cuantificar la probabilidad de que las diferencias o relaciones observadas en los datos se hayan producido por casualidad en lugar de reflejar un efecto verdadero en la población.

John W. Tukey escribió el libro Análisis de datos exploratorios en 1977. Tukey sostuvo que en estadística se ponía demasiado énfasis en las pruebas de hipótesis estadísticas (análisis de datos confirmatorios); era necesario poner más énfasis en el uso de datos para sugerir hipótesis a probar. En particular, sostuvo que confundir los dos tipos de análisis y emplearlos en el mismo conjunto de datos puede conducir a un sesgo sistemático debido a los problemas inherentes a la prueba de hipótesis sugeridas por los datos.

Los objetivos de EDA son:

Permitir descubrimientos inesperados en los datos
Sugerir hipótesis sobre las causas de los fenómenos observados
Evaluar los supuestos en que se basará la inferencia estadística
Apoyar la selección de instrumentos y técnicas estadísticos apropiados
Proporcionar una base para una mayor recopilación de datos mediante encuestas o experimentos
Se han adoptado muchas técnicas EDA en la minería de datos. También se están enseñando a estudiantes jóvenes como una forma de introducirlos en el pensamiento estadístico.