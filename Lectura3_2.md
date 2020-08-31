**Evaluating Recommendation Systems**

El elegir el tipo de modelo del sistema de recomendación que se usará para una determinada tarea suele ser uno de los pasos más importantes, y para ello es necesario analizar una serie de variables(propiedades) sobre el entorno/contexto. El trabajo [1] describen los entornos apropiados al momento de elegir un modelo.  El trabajo se basa en tres aspectos en cuanto a las configuraciones de evaluación;  offline, estudios basados en el usuario, algo así como user testing o user experience, y finalmente el aspecto online. Describen las ventajas y contras de usar cada aspecto al momento de evaluar el rendimiento de un modelo, además de ejemplos en la práctica. Cada sistema de recomendación tiene una serie de propiedades, y Shani y Gunawardana  proponen los diferentes métodos que podrían ser usados para medir dichas propiedades. Entre las evaluaciones de rendimiento, sugieren  a la precision como una métrica estándar, además de presentar diferentes métricas para medir dicha precision.

Es interesante cómo el artículo da profundidad es la definición coverage, describen los ítems que deben ser medidos al momento de elaborar un método o modelo propio. Además lo mencionan que las recomendaciones deben evaluarse equilibradamente entre coverage y precision. Otro punto paralelo e interesante es cómo abarcó la confianza en temas de recomendación, y hecho de cómo el sistema confía en sus scores, cómo los usuarios confían en los scores del sistema. El tema de dar falsos positivos también lo abarcó, y cómo reducir el riesgo en ese entorno. 


Si bien el trabajo explora diferentes propiedades, algunas no son lo suficientemente descritas, en comparación de las demás, entonces, esto podría indicarme que no es tan importante, pero en la práctica si lo es, ya que podría estár sesgando un modelo. Un ejemplo es cuando refieren a la adaptabilidad,  ya que es un aspecto muy importante, y el tiempo podría ser un factor que tengamos que analizar a la hora de elaborar el algoritmo. En ese sentido, se debe tomar en cuenta que la precision podría fallar un poco en ese aspecto, el trabajo lo mencionó pero no tuvo gran relevancia. Otro aspecto fue la diversidad, el hecho de tener un rango de valores para los parámetros de diversidad, tal como lo mencionaron en el trabajo, acaso: ¿estaría sesgando el modelo de alguna manera?, ya que en general los usuarios no siempre esperan recomendaciones bajo un mismo entorno. Entonces, creo que esta propiedad podría ser mayor explorada, quizá trabajos recientes lo exploraron y fueron específicos, es tema de una pequeña revisión.

Finalmente, el trabajo es bastante sólido y concreto, ayuda como una guía al momento de elegir un algoritmo, y te da una vista más amplia del entorno, eso ayuda a tomar decisiones en base a una serie de variables bien sustentadas.




[2] Guy, S., & Gunawardana, A.. (2011) “Evaluating recommendation systems.” In Recommender systems handbook, pp. 257-297. Springer US, 2011.

