** Context-Aware Recommender Systems**


El trabajo de [1] cómo es posible tomar en cuenta las diferentes acciones e información contextual para la incorporarlas en el proceso de un sistema recomendador. En el cual analiza varios  conceptos sobre contextos, y factores además de cómo estos factores van cambiando a través del tiempo. Normalmente, los sistemas recomendadores no incorporan en sus procesos una base en cuanto a  conocimiento del contexto, por lo que esto se traduce en una pérdida de información. En ese sentido, el autor menciona que la diferencia entre ambos tipos de proceso es ser o no independiente de la acción. El trabajo también explica y analiza las diferencias que existen entre un sistema recomendador que incorpora el contexto de forma implícita e explícita. Para poder definir cómo es posible incorporar el contexto en sistemas de recomendación, detallaron los paradigmas para el uso de información contextual; los cuales son i) prefiltrado contextual, ii) postfiltrado contextual y iii) modelado contextual. Para cada paradigma mostraron los rendimientos dependiendo del problema. 


Es interesante cómo poder incluir el contexto en el proceso de recomendación, en ese punto los autores resaltaron 3 tipos de conocimientos para un sistema, los cuales son totalmente observable, parcialmente observable y no observable. En los cuales escribieron acerca un factor importante, el cual es el tiempo, pero no lo denotaron como importante, y fue clasificado como parcialmente observable. En ese sentido, no detallan bien la estructura de este factor, o quizá se toman en cuenta todos los conceptos relacionados con el tiempo para un usuario, es decir, tiempo de vista de un artículo, tiempo de búsqueda, tiempo de compra, tiempo de navegación, etc. Quizá es un factor bastante complejo, y es explorado en otros trabajos, y precisamente fue explorado y detallado en otro trabajo [2], del mismo autor. En el trabajo de [2]  desarrolló un enfoque basado en la reducción para el modelo de recomendación multidimensional que incorpora información contextual, como lugar y tiempo, para un el desarrollo de un proceso de recomendación. Trabajo muy bien detallado, el cual me permitió tener un enfoque más claro de incorporación de información del contexto en un sistema recomendador.  

Finalmente, es importante resaltar lo compleja que es esta tarea (incorporar información del contexto), tanto para sistemas estáticos como dinámicos. Además, el trabajo menciona que son trabajos con bastantes desafíos todavía, además de investigación a la hora de trabajar con estos factores, ya que la sensibilidad del cambio de un factor es bastante alta, lo que se vuelve una tarea delicada. 


[1] Adomavicius, G., Mobasher, B., Ricci, F. and Tuzhilin, A. (2011). Context-Aware Recommender Systems. AI Magazine, 32(3), 67-80.


[2] G. Adomavicius, R. Sankaranarayanan, S. Sen, A. Tuzhilin
Incorporating contextual information in recommender systems using a multidimensional approach ACM Transactions on Information Systems (TOIS), 23 (2005), pp. 103-145
