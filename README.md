# predicciones-de-ventas-alimenticias

### Predicción de ventas para productos alimenticios vendidos en diversas tiendas.

#### Erwin Barriga

## Proyecto 1 - Parte 1 (base)

1. Crea un repositorio GitHub que albergará el primer proyecto de portafolio. Sigan las instrucciones en el video de abajo para ayudarlos a completar esta tarea.

2. Usen Pandas para leer el conjunto de datos de predicción de ventas en un cuaderno de Google Colab y verifiquen los datos utilizando el comando `df.head()`.  
    * Descarguen los datos con este enlace: __[descarguen los datos](https://drive.google.com/file/d/1syH81TVrbBsdymLT_jl2JIf6IjPXtSQw/view?usp=sharing)__. (Nota: Fuente original de datos)

3. Agreguen el cuaderno de Google Colab al repositorio de GitHub.  Abran la pestaña de “archivo” y hagan clic en “Guardar copia en Github”.


## Proyecto 1 - Parte 2 (base)

Para la parte 2, la tarea es usar Pandas para empezar a limpiar y explorar los datos. Al ser científicos de datos, alrededor del 80% de nuestro tiempo se dedica a la preparación de datos, así que este es un paso muy importante. 

* Sus datos ya deberían estar cargados en el cuaderno de la parte 1 del proyecto.
* Exploren los datos - ¿Qué necesitan para limpiar estos datos? ¡Límpienlos!  
* Asegúrense de abordar cada una de las siguientes tareas:

  1. ¿Cuántas filas y columnas?

  2. ¿Cuáles son los tipos de datos en cada variable?

  3. ¿Hay duplicados? Si es el caso, eliminen algunos duplicados.

  4. Identifiquen los valores faltantes.

  5. Decidan cómo abordar los valores faltantes y cómo hacerlo. (Esto requiere sus criterios, así que expliquen su elección).

  6. Confirmen que no hay valores faltantes después de abordarlos.

  7. Encuentren y arreglen alguna categoría inconsistente de datos (example: fix cat, Cat, and cats so that they are consistent) 

  8. Para cualquier columna numérica, obtengan las estadísticas resumidas para cada uno (mínimo, máximo y media)

**Diccionario de datos para este conjunto de datos:**

| Nombre de la variable      | Descripción                                                                                           |
|----------------------------|-------------------------------------------------------------------------------------------------------|
| Item_Identifier            | Identificación única del producto                                                                     |
| Item_Weight                | Peso del producto                                                                                     |
| Item_Fat_Content           | Si el producto es bajo en grasa o regular                                                              |
| Item_Visibility            | Porcentaje de la superficie total de exposición de todos los productos de una tienda asignada al producto concreto |
| Item_Type                  | Categoría a la que el producto pertenece                                                               |
| Item_MRP                   | Precio máximo de venta al público (precio de catálogo) del producto                                   |
| Outlet_Identifier          | Identificación única de la tienda                                                                     |
| Outlet_Establishment_Year  | El año en que se estableció la tienda                                                                 |
| Outlet_Size                | El tamaño de la tienda en cuanto al área total                                                         |
| Outlet_Location_Type       | El tipo de área donde se encuentra la tienda                                                           |
| Outlet_Type                | Si el punto de venta es una tienda de comestibles o algún tipo de supermercado                         |
| Item_Outlet_Sales          | Ventas del producto en una tienda particular. Es la variable objetivo a predecir.                    |


## Proyecto 1 - Parte 3 (base)

Para la tercera parte, la tarea es completar cualquier análisis estadístico que los puedan a ayudar a comprender, explicar o moldear sus datos. Esto debe incluir al menos uno de cada:

* Histograma para ver las distribuciones de diversas características en el conjunto de datos.
* Boxplot para ver resúmenes estadísticos de diversas características en el conjunto de datos.
* Mapa de calor de la correlación entre las características.

No duden en agregar más del mínimo. ¡Recuerden que esta es su oportunidad para mostrar sus habilidades!

## Proyecto 1 - Parte 4 (base)

El objetivo de esto es ayudar al minorista a comprender las propiedades de los productos y los puntos de venta que desempeñan un papel crucial en el aumento de las ventas.

Para la cuarta parte, la tarea es crear numerosas visualizaciones de datos para ayudar a las partes interesadas a comprender mejor las tendencias de los datos. No duden en ser creativos esta semana.

* Aprovechen sus limpiezas, exploraciones y análisis anteriores.
* Creen un mínimo de dos visualizaciones de datos para ayudar a otros comprender las tendencias en los datos (análisis de datos explicativos).
* Puesto que estos gráficos son para la elaboración de informes, asegúrense de que tengan un buen aspecto incluyendo títulos, leyendas, etc.