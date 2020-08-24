
**Collaborative Filtering for Implicit Feedback Datasets**

El trabajo de Hu, Y., Koren, Y., & Volinsky, C. (2008)[1] describe la construcción de un modelo de sistema de recomendación utilizando feedback implícito, describieron los tipos de modelos (User Based CF), y los compara con el modelo planteado, además mencionó los problemas de cómputo, y detallaron cómo se hizo la reducción de complejidad. Me llamó la atención cómo presentaron los problemas y/o carencias de obtener las ‘acciones negativas’ por parte de los usuarios, ya que es difícil saber si a una persona no le gusta un ítem dado que podría no saber de su existencia, a diferencia de los feedbacks positivos, en general el autor detalla varias maneras de interpretar algo así como un raiting positivo. 

EL trabajo mencionó varios trabajos anteriores, como por ejemplo modelos de factores latentes, en sí, este trabajo también presenta una noción parecida (factores latentes). En ese sentido, basándome en algunos puntos que el trabajó abarcó, por ejemplo, el modelo utiliza factores del usuario, pero no hace referencia a problemas que tienen los modelos generativos, me hubiera gustado que se comentara aunque en un par de líneas. Tampoco mencionó cómo forman la función de densidad para calcular la probabilidad (condicional en este caso) o cómo lo optimizan. Otro aspecto que me llamó la atención es sobre la regularización, puesto que es un parámetro dependiente, ya que el paper indica que es determinado por cross validations, pero a posterior no detallan: ¿por qué de esas acotaciones?. Sin embargo, en los resultados si detallaron que tener una regularización de 0 era indicio de un mal resultado, y que es mejor tener una regularización más alta, pero me hubiera gustado ver la sensibilidad del modelo para entender mejor el por qué de esas acotaciones(algún dibujito :) ).

En el caso de explicit feedback existen problemas con la medición de la similitud (el artículo los detalló muy bien). Para el caso de implicit feedback también mencionaron que existen problemas para las ‘preferencias negativas’, y por ello el paper trabajó muy bien sobre las preferencias positivas (valga la redundancia), pero no hubo un detalla a fondo con las negativas (a pesar de haberlas mencionado).

Algo que se notó bastante en en todo el trabajo fue que: la presentación que los autores hacen sobre implicit feedback, pienso que no necesariamente es ‘otra manera’ de trabajar con las variables latentes, así como ellos lo mencionaron, ya que en reiteradas ocaciones hace mención de: ‘a diferencia de…(explicit feedback)’. En ese sentido, quizá esperaría que la hipótesis haya sido complementaria a explicit feedback, me explico: alguna manera de integrar los datos producidos por el feedback implícito hacia el feedback explicito. 

Los autores al final del artículo escribieron sobre una posible extensión del trabajo, en donde proponen una noción de cómo integrar contenido dinámico relacionado al tiempo, y dado el contexto (implicit feedback) remarcaría bastante este aporte para este tipo de modelos, fue algo que me llamó la atención, muy acertado ese criterio. En ese sentido, un área que se está investigando a cerca de introducir este criterio del tiempo es en recomendaciones musicales [2], donde proponen incorporar la dinámica del tiempo, tal como lo mencionaron en el paper [1].

Finalmente, un último punto que rescatar es que el autor detalló muy bien los pasos que siguieron para reducir la complejidad del modelo, fue muy interesante el ajuste de los cálculos, no únicamente aplicada a este tipo de modelos, sino a una gran variedad donde puede ser aplicada.

 


Bibliografía
[1] Hu, Y., Koren, Y., & Volinsky, C. (2008). Collaborative filtering for implicit feedback datasets. In Data Mining, 2008. ICDM’08. Eighth IEEE International Conference on (pp. 263-272). IEEE.
[2] D.Sánchez-Moreno,Y.Zheng,andM.N.Moreno-García,‘‘Incorporating time dynamics and implicit feedback into music recommender systems,’’ in Proc. IEEE/WIC/ACM Int. Conf. Web Intell. (WI), Dec. 2018, pp. 580–585
