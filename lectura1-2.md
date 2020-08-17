Nombre: Yesenia Helem Salinas

Comentarios: Post original FunkSVD

Debo admitir que la lectura fue un poco densa. Un punto que destacar es: se le da bastante énfasis es al ajuste excesivo, donde habla y toma en cuenta los antecedentes de penalizar la magnitud de las características, eso en un entorno de regularización. Esto, introduciendo a una función no lineal, como la sigmoide (espero haber entendido bien esa parte), además de trabajar bajo la penalización de la suma de diferencias al cuadrado. Al calcular sobre toda la matriz, entendí que esta penalizando de igual manera tanto las diferencias de sus raitings conocidos como las diferencias de sus predicciones de los raitings desconocidos. Sin embargo, no logré comprender como realiza la aproximación de la matriz resultante a la matriz original, es decir, ¿cómo termina de ajustr el modelo al original, a pesar de que pretende ajustar el modelo solo a sus raitings observados?. y ¿cómo es obligado a tener combinaciones lineales de los vectores?.

La idea que cuenta Simon, sobre minimizar la suma de los errores al cuadrado frente solo a las raitings conocidos es bastante acertado (mediante el descenso de gradiente), ya que el hecho de que únicamente considere un número pequeño de raitings en lugar de toda la matriz de elementos del usuario, hace sentido a que es rápido.

Necesito leer más artículos al respecto, ya que no logré comprenderlo del todo, quizá porque es un post, y no tiene un outline y estoy acostumbrada a ello, no lo sé, pero fue una idea que me sorprendió y me gustó.
