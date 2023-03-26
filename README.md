# **Ejemplo de Predicciones de Ventas Alimenticias**

## Predicción de ventas para productos alimenticios vendidos en diversas tiendas.

### Erwin Barriga

Ejercicio usando Pandas para leer el conjunto de datos de predicción de ventas y limpiar y explorar los datos. Se han realizado histogramas y boxplots para ver las distribuciones  y resúmenes estadísticos de diversas características en el conjunto de datos. Se han creado visualizaciones de datos para ayudar a las partes interesadas a comprender mejor las tendencias de los datos.

Finalmente se ha creado un pipeline de preprocesamiento para preparar el conjunto de datos para el aprendizaje automático, identificando la matriz objetivo ($X$) y las características ($y$). Luego, mediante un `train test split` se ha comparado el desempeño de en la predicción de un modelo de regresión lineal y un modelo de árbol de regresión.

Fuente original de datos: __[enlace](https://drive.google.com/file/d/1syH81TVrbBsdymLT_jl2JIf6IjPXtSQw/view?usp=sharing)__.

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
