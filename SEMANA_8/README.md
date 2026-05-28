# Segmentación de clientes con K-Means

Este trabajo aplica aprendizaje no supervisado para identificar segmentos de clientes a partir de variables de comportamiento de compra y uso del sitio. Se utilizó el algoritmo K-Means sobre un dataset provisto en el campus, considerando frecuencia de compra mensual, ticket promedio, tiempo de permanencia en el sitio, sensibilidad a descuentos y tasa de devoluciones.

Antes de aplicar el modelo, las variables fueron escaladas para evitar que las diferencias de magnitud afecten el cálculo de distancias. Luego se compararon distintos valores de k entre 2 y 6 mediante el método del codo, seleccionando k igual a 3 como una opción razonable para la segmentación.

Finalmente, se analizaron los centroides de cada cluster para describir perfiles de clientes y proponer posibles estrategias comerciales diferenciadas.

