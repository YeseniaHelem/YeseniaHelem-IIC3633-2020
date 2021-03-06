**Bayesian Personalized Ranking from Implicit Feedback**

El trabajo propuesto por Rendle, S., Freudenthaler, C., Gantner, Z., & Schmidt-Thieme, L. (2009)[1] es un modelo del algoritmo de aprendizaje LearnBPR, donde también abordan y la optimización para bayesian personalized ranking. Detallaron los problemas de los modelos de feedback implícito, y es que solo se observan las clases positivas, ya que es la única información que puede estar disponible. El artículo aborda estos desafíos, los autores consideran ambos pares de positivos y negativos, incluso las variables latentes. Además, como lo mencioné anteriormente, detallaron muy bien el algoritmo de aprendizaje BPR, partiendo de la definición de la función de la likelihoood, y el prior, incluyendo el criterio de optimización, para luego, mostrar cómo aplicaron el criterio a la matriz de factorización y KNN.

Algo que me llamó la atención fue el proceso de construcción del modelo LeanrBPR, cuando hacen mención de cómo maximizar la posterior, y lo detallaron muy bien, al igual que la likelihood (p> u | Θ) , además definen a la densidad del prior. El trabajo no detalla si las variables y funciones que calcula para la predicción son normalizadas, pero cuando menciona que el AUC(area under the roc curve) trabaja con una constante de normalización, entonces, asumo que las todas las variables estan normalizadas. En cuanto a al criterio de optimización, y escribiendo sobre AUC, algo interesante fue que el trabajó mostró su analogía de optimización en base a la maximización del área bajo la curva ROC. El detalle del trabajo de alguna da una noción de desarrollar el algoritmo, únicamente con el paper, me refiero a que los pasos que siguieron fueron muy bien detallados.


Finalmente, un punto a rescatar y tomar en cuenta, fue que hicieron mención a Multi-class, el paper lo menciona en trabajos realizados hasta ese momento,  pero no lo abarcó en en paper, me hubiera gustado que explorara un poco vectores mas variados, multi-class (L. Shimidt-Thieme, 2005)[2]  ó  diferentes "canales" (Babak Loni et al. 2016)[3], en los que los usuarios interactúan con los elementos en lugar de trabajar con valores binarios (aunque en trabajos futuros), pero fue un trabajo del 2009, y para ello fue suficiente con el aporte que dieron. 




Bibliografía

[1] Rendle, S., Freudenthaler, C., Gantner, Z., & Schmidt-Thieme, L. (2009). BPR: Bayesian personalized ranking from implicit feedback. In Proceedings of the Twenty-Fifth Conference on Uncertainty in Artificial Intelligence (pp. 452-461). AUAI Press.

[2] L. Schmidt-Thieme. Compound classification models for recommender systems. In IEEE In- ternational Conference on Data Mining (ICDM 2005), pages 378–385, 2005

[3] Babak Loni, Roberto Pagano, Martha Larson, and Alan Hanjalic. Bayesian personalized ranking with multi- channel user feedback. In RecSys, pages 361–364, 2016
