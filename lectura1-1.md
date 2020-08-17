Nombre: Yesenia Helem Salinas
Comentarios:  Item-based collaborative filtering recommendation algorithms


El planteamiento del los problemas y las soluciones fueron bien acertadas, el cómputo es un problema que en grandes datasets es bastante frecuente, y abordar esos desafíos sin duda trae bueos aportes. 

Pengo algunas observaciones y dudas que no las he podido aclarar:

Entiendo que describen como encontrar los items más similares, para luego calcular la predicción sobre raitings de los items similares. En ese sentido tengo una duda sobre una de las técnicas para Cálculo de predicción, que no se detalla en el trabajo, que es el de Regresión:
- Calculan una aproximación R_uN de los raitings basados en un modelo de regresión lineal R´_N, pero en ese punto no detalla si el modelo obtuviera complejidad. Ya que en el punto 3.3 garantizan que su enfoque proporcionará una predicción de buena calidad, sin embargo, no me queda claro cómo acota los parámetros óptimos en la regresión, o de alguna manera tampoco se refiere a quitarle la complejidad al modelo con algún tipo de penalización al momento de la predicción. Esa duda ya que el modelo basado en regresión muestra buenos resultados con valores pequeños de x, pero a medida que se incrementa x el modelo de predicción tiende a fallar, entonces no explica cual es el problema ahí, ¿será la complejidad del modelo?, ¿los parámetros óptimos tendrán implicancia si no son acotados?, o existirá un sobre ajuste (a causa de los parámetros).

Ahora, en base a los experimentos con el tamaño de vecinos, el planteamiento es bueno, pero al igual que con el modelo de regresión no me queda claro el por qué con más de 30 vecinos el rendimiento no mejora (al contrario), claro que se comprende la sensibilidad del tamaño de x, pero no me quedó claro con esa explicación, quizá revisando más literatura me queda más claro. 

Quise conocer las mejoras al modelo (trabajo futuro), pero a pesar que en 1.3 hace referencia a observaciones para futuras investigaciones, en las Conclusiones solo da énfasis a los Sistemas Recomendadores como nueva tecnología, pero no se comenta ningún desafío posterior sobre la técnica presentada.

Finalmente, me gustó la sección de experimentación y sensibilidad del tamaño del modelo, en general toda variación con diferentes técnicas.
