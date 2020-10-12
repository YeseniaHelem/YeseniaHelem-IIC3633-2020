**Multi-Armed Recommender System Bandit Ensembles**

El trabajo de [1] explora la adaptación de una perspectiva más realista para el diseño de conjuntos de recomendadores dinámicos, donde consideran la incorporación de un técnica multi-armed bandit. [1] considera la naturaleza cíclica un proceso de recomendación, donde el input se crea a partir de la reacción de los usuarios a las recomendaciones.  El proceso  optimiza dinámicamente los conjuntos de recomendadores. En ese sentido, ellos experimentan con combinaciones de tres diferentes algoritmos, que son KNN, factorización matricial y non-personalized most-popular recommendation. La evaluación para cada algoritmo tiene sus propios conjuntos de training y testing, esto debido a son construidas a partir de las reacciones de los usuarios y sus propias recomendaciones. 

Es interesante cómo evalúan esta adaptación, pero a pesar que el artículo menciona que no presenta ningún sesgo sobre la estructura iterativa de retroalimentación, sería mostrar alguna tabla comparativa sobre los márgenes de error. Así, también sería interesante ver el proceso de recomendación de manera iterativa, y mostrar más a fondo cómo un conjunto depende de la iteración previa. 

El enfoque presenta un proceso de iteración interesante, y que tener bajo costo computacional también es bueno, sobretodo al tratarse de iteraciones. Además, incluir el rendimiento para ajustar cada output, en la práctica habría que revisar cómo funciona. 



[1] Cañamares, R., Redondo, M., & Castells, P. (2019). Multi-armed recommender system bandit ensembles. In Proceedings of the 13th ACM Conference on Recommender Systems (pp. 432-436).
