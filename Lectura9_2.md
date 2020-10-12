**Carousel Personalization in Music Streaming Apps with Contextual Bandits**


El artículo de [] se enfoca en aplicaciones de transmisión de música, modelando una personalización de ‘carrusel’ como un problema contextual de multi-armed bandit. Consideran a los ‘destiladores’ como las listas clasificadas de items, o cartas (álbumes artistas, listas de reproducción, etc). En ese sentido, ellos toman en cuenta la información contextual que se tiene sobre las preferencias de los usuarios, y muestran la eficacia del modelo bajo la aplicación Deezer. Así, el trabajo considera 862 listas de reproducción, y realizaron experimentos fuera de línea en las que simularon las respuestas/reacciones de los usuarios a las recomendaciones brindadas.  Evalúan sus experimentos de manera secuencial, comparando versiones semi personalizadas de varios algoritmos con algoritmos totalmente personalizados.  

Ahora, su modelo consideran dentro del contexto que los usuarios vean las cartas o items seleccionados. Esa asunción es bastante acertada, ya que en la realidad los usuarios muy pocas veces hacen click sobre los ítems para explorar más items, sino que deslizan hacia la izquierda o derecha. El artículo aborda este desafío y lo menciona bastante bien,  cuando evalúan un modelo de ítems estocásticos, a consecuencia de la ambigüedad de las cartas. Sin embargo, no detalla sobre el sesgo que estaría generando, al asumir dicha asunsión, es cierto que es realista, pero a la hora de modelar los datos, es importante conocer bien los parámetros de la esa distribución.  

Un gran aporte que realizan es brindar un dataset con las simulaciones que hicieron, el cual apoyará de manera significativa para futuras investigaciones.  El trabajo mismo concluye sobre la independencia de cada variable al modelar los datos, lo cual podría ser poco realista. Así, en investigaciones futuras, es posible explorar más a fondo sobre la base de sus experimentos, y llegar a mejorar el modelo planteado.



[1] Bendada, W., Salha, G., & Bontempelli, T. (2020). Carousel Personalization in Music Streaming Apps with Contextual Bandits. In Fourteenth ACM Conference on Recommender Systems (pp. 420-425).
